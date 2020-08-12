
# Kotlin

## What is Kotlin?

[Kotlin](https://kotlinlang.org/) is a general-purpose programming language that is
 
 * cross-platform,
 * statically typed
 * concise (using type inference)


## What is it good for?

* Android native development
    * 2019: Google endorsed as preferred language for Android app development
* Cross-platform mobile development
    * "Write the business logic for your iOS and Android apps with less time and effort – using nothing but Kotlin" [Jetbrains](https://www.jetbrains.com/lp/mobilecrossplatform/)
* Cross-platform library development
    * [Kotlin/Native](https://kotlinlang.org/docs/reference/native-overview.html) uses LLVM to compile Kotlin to static or dynamic native libraries for many platforms.
    * iOS, macOS, Android, Windows, Linux, WebAssembly
* Server-side development
    * Kotlin is JVM compatible so it can be used on top of Java web service frameworks like Spring
* Javascript front-end development
    * [Kotlin/JS](https://kotlinlang.org/docs/reference/js-overview.html) transpiles to optimally-sized, readable Javascript.
    * Statically-typed interfaces to reference DOM elements and WebGL
    * Server-side interfaces to integrate with Node.js
    * [Dukat](https://github.com/kotlin/dukat) assists with conversion of TypeScript definitions to Kotlin/JS
    * [Writing for React with Kotlin](https://play.kotlinlang.org/hands-on/Building%20Web%20Applications%20with%20React%20and%20Kotlin%20JS/01_Introduction?_ga=2.48013543.130858947.1597256917-436358688.1584403503)
* Declarative UI for Android apps: [Jetpack Compose](https://developer.android.com/jetpack/compose)
	* as of this writing,latest version is [0.1.0-dev16](https://developer.android.com/jetpack/androidx/releases/compose) self-described as evolving with API breaking changes expected

	
## What does it look like?

```
fun main() {
    println("Hello, world!!!")
    print(factorial(10))
}

fun factorial(i: Int): Int {
    return if (i == 0 || i == 1) { i } else { i * factorial(i-1) }
}
```
```
Hello, world!!!
3628800
```

Some important things to know:
* [The Elvis operator](https://kotlinlang.org/docs/reference/null-safety.html#elvis-operator)
* [Smart Casts](https://kotlinlang.org/docs/reference/typecasts.html)

## Where do I go to learn it?

* [Kotlin Playground](https://play.kotlinlang.org/hands-on/overview)
* Interactive Exercises: [Kotlin Koans](https://play.kotlinlang.org/koans)
* Kotlin Evolution Proposals [KEEP](https://github.com/Kotlin/KEEP)