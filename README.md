# Coroutines-Basics 🧵

![Coroutines-Basics](https://miro.medium.com/max/800/1*1tDZwUd3NMQuIjZVkv-r0w.png)

A coroutine is a concurrency design pattern that you can use on Android to simplify code that executes asynchronously. Coroutines were added to Kotlin in version 1.3 and are based on established concepts from other languages.

On Android, coroutines help to manage long-running tasks that might otherwise block the main thread and cause your app to become unresponsive. Over 50% of professional developers who use coroutines have reported seeing increased productivity. This topic describes how you can use Kotlin coroutines to address these problems, enabling you to write cleaner and more concise app code.


## Features 👀

![Coroutines-Basics](https://www.chaddha.me/content/images/2020/12/Kotlin-Coroutises-Fundamentals_o-2.jpg)

Coroutines is our recommended solution for asynchronous programming on Android. Noteworthy features include the following:

1. **Lightweight**: You can run many coroutines on a single thread due to support for suspension, which doesn't block the thread where the coroutine is running. Suspending saves memory over blocking while supporting many concurrent operations.
2. **Fewer memory leaks**: Use structured concurrency to run operations within a scope.  
3. **Built-in cancellation support**: Cancellation is propagated automatically through the running coroutine hierarchy.
4. **Jetpack integration**: Many Jetpack libraries include extensions that provide full coroutines support. Some libraries also provide their own coroutine scope that you can use for structured concurrency.

## Project Contents 📜

- [CoroutineScope](https://github.com/ZeynelErdiKarabulut/CoroutineBasics/blob/master/app/src/main/java/com/zeynelerdi/CoroutineBasics/CoroutineScopeClass.kt)
- [Dispatchers Coroutines](https://github.com/ZeynelErdiKarabulut/CoroutineBasics/blob/master/app/src/main/java/com/zeynelerdi/CoroutineBasics/DispatchersCoroutines.kt)
- [GlobalScope](https://github.com/ZeynelErdiKarabulut/CoroutineBasics/blob/master/app/src/main/java/com/zeynelerdi/CoroutineBasics/GlobalScopeClass.kt)
- [Nested Coroutines](https://github.com/ZeynelErdiKarabulut/CoroutineBasics/blob/master/app/src/main/java/com/zeynelerdi/CoroutineBasics/NestedCoroutines.kt)
- [RunBlocking](https://github.com/ZeynelErdiKarabulut/CoroutineBasics/blob/master/app/src/main/java/com/zeynelerdi/CoroutineBasics/RunBlockingClass.kt)
- [Suspend Coroutines](https://github.com/ZeynelErdiKarabulut/CoroutineBasics/blob/master/app/src/main/java/com/zeynelerdi/CoroutineBasics/SuspendCoroutines.kt)
- [Coroutines Async](https://github.com/ZeynelErdiKarabulut/CoroutineBasics/blob/master/app/src/main/java/com/zeynelerdi/CoroutineBasics/CoroutinesAsync.kt)
