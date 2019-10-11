# blockchain-demo

Implementation of a cryptocurrency in Kotlin

To run this project you will need to install Kotlin and run the following commands.

First use kotlinc to create a self-contained and runnable jar file.

```bash
kotlinc src/Main.kt -include-runtime -d kCoin.jar
```

Next use java to run the jar file.

```bash
java -jar kCoin.jar
```

_Inspired by Vasily Fomin's [blog post](https://medium.com/@vasilyf/lets-implement-a-cryptocurrency-in-kotlin-part-1-blockchain-8704069f8580)_
