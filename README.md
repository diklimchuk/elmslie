![Elmslie](https://user-images.githubusercontent.com/16104123/104534649-b5defa80-5625-11eb-98b6-d761623f8964.jpeg)
[![](https://jitpack.io/v/diklimchuk/test.svg)](https://jitpack.io/#diklimchuk/test)

Elmslie is a minimalistic reactive implementation of TEA/ELM written in kotlin.

## Why?
- **Scalable and Reusable**: Built-in support for nesting components
- **Reactive**: Written with RxJava2
- **Single immutable state**: Simplify state management
- **UDF**: Say no to spaghetti code with Unidirectional Data Flow

## Documentation
To get help head to the [wiki](https://github.com/vivid-money/elmslie/wiki)

## Download
Library is distributed through JitPack

#### Add repository in the root build.gradle
```
allprojects {
 repositories {
    maven { url "https://jitpack.io" }
 }
}
```

#### Add required modules:
- Core - for pure kotlin ELM implementation

`implementation 'vivid.money.elmslie:elmslie-core:{latest-version}'`

- Android - for android apps only, simplifies lifecycle handling  

`implementation 'vivid.money.elmslie:elmslie-android:{latest-version}'`

## Related articles
- [Why did we select ELM? (Russian)](https://habr.com/ru/company/vivid_money/blog/534386/)
- [ELM. Pt1 (English)](https://proandroiddev.com/taming-state-in-android-with-elm-architecture-and-kotlin-part-1-566caae0f706)
- [ELM. Pt2 (English)](https://proandroiddev.com/taming-state-in-android-with-elm-architecture-and-kotlin-part-2-c709f75f7596)
- [ELM. Pt3 (English)](https://proandroiddev.com/taming-state-in-android-with-elm-architecture-and-kotlin-part-2-c709f75f7596)

