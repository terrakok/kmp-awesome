# <img src="https://github.com/terrakok/kmm-awesome/raw/master/img/pluginIcon.svg" width="30"/> Awesome KMM

<img src="https://github.com/terrakok/kmm-awesome/raw/master/img/kmm.svg" align="center" width="650"/>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub Repo stars](https://img.shields.io/github/stars/terrakok/kmm-awesome)](https://github.com/terrakok/kmm-awesome)
[![Maven Central](https://img.shields.io/maven-central/v/org.jetbrains.kotlin/kotlin-maven-plugin.svg)](https://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.jetbrains.kotlin%22)

Kotlin Multiplatform Mobile (KMM) is an SDK designed to simplify creating cross-platform mobile applications. With the
help of KMM, you can share common code between iOS and Android apps and write platform-specific code only where it’s
necessary. For example, to implement a native UI or when working with platform-specific APIs.

## Resources
🖼 [KMM website](https://kotlinlang.org/lp/mobile/)  
📜 [KMM blog](https://blog.jetbrains.com/kotlin/category/mobile/)  
📺 [KMM YouTube](https://www.youtube.com/playlist?list=PLlFc5cFwUnmy_oVc9YQzjasSNoAk4hk_C)  
📋 [KMM Documentation](https://kotlinlang.org/docs/kmm-overview.html)

## Tooling

#### 🛠 [Kotlin Multiplatform Mobile plugin](https://plugins.jetbrains.com/plugin/14936-kotlin-multiplatform-mobile) for Android Studio
> The Kotlin Multiplatform Mobile (KMM) plugin helps you develop applications that work on both Android and iOS.

#### 🛠 [Kotlin Multiplatform Mobile plugin](https://plugins.jetbrains.com/plugin/17098-kotlin-multiplatform-mobile-for-appcode/) for AppCode
> The Kotlin Multiplatform Mobile (KMM) plugin for AppCode helps you develop applications for Android and iOS using the unified Gradle project model.

#### 🛠 [CocoaPods](https://kotlinlang.org/docs/native-cocoapods.html) integration
> Kotlin/Native provides integration with the CocoaPods dependency manager. You can add dependencies on Pod libraries as well as use a multiplatform project with native targets as a CocoaPods dependency (Kotlin Pod).

#### 🛠 [MOKO KSwift](https://github.com/icerockdev/moko-kswift) gradle plugin
> KSwift it's gradle plugin for generation Swift-friendly API for Kotlin/Native framework.

#### 🛠 [CompleteKotlin](https://github.com/LouisCAD/CompleteKotlin) gradle plugin
> Gradle Plugin to enable auto-completion and symbol resolution for all Kotlin/Native platforms.

## Libraries

### 📋 Log
[Napier](https://github.com/AAkira/Napier) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/AAkira/Napier)](https://github.com/AAkira/Napier)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.aakira/napier/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.aakira/napier)
> Napier is a logger library for Kotlin Multiplatform. It supports for the Android, Darwin(iOS, macOS, watchOS, tvOS), JVM, JavaScript. Logs written in common module are displayed on logger viewer of each platform.

[Kermit](https://github.com/touchlab/Kermit) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/Kermit)](https://github.com/touchlab/Kermit)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/co.touchlab/kermit/badge.svg)](https://maven-badges.herokuapp.com/maven-central/co.touchlab/kermit)
> Kermit is a Kotlin Multiplatform logging utility with composable log outputs. The library provides prebuilt loggers for outputting to platform logging tools such as Logcat and NSLog.

### 🌎 Network
[Ktor](https://github.com/ktorio/ktor) - http client
[![GitHub Repo stars](https://img.shields.io/github/stars/ktorio/ktor)](https://github.com/ktorio/ktor)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.ktor/ktor/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.ktor)
> Ktor includes a multiplatform asynchronous HTTP client, which allows you to make requests and handle responses, extend its functionality with plugins (formerly known as features), such as authentication, JSON serialization, and so on. In this tutorial, we'll create a simple client application for sending a request and receiving a response.

[Apollo GraphQL](https://github.com/apollographql/apollo-android) - GraphQL client
[![GitHub Repo stars](https://img.shields.io/github/stars/apollographql/apollo-android)](https://github.com/apollographql/apollo-android)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.apollographql.apollo3/apollo-runtime/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.apollographql.apollo3)
> A strongly-typed, caching GraphQL client for the JVM, Android, and Kotlin multiplatform.

[WebRTC KMP](https://github.com/shepeliev/webrtc-kmp) - WebRTC client
[![GitHub Repo stars](https://img.shields.io/github/stars/shepeliev/webrtc-kmp)](https://github.com/shepeliev/webrtc-kmp)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shepeliev/webrtc-kmp/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.shepeliev/webrtc-kmp)
> WebRTC Kotlin Multiplatform SDK

[Krossbow](https://github.com/joffrey-bion/krossbow) - WebSocket client
[![GitHub Repo stars](https://img.shields.io/github/stars/joffrey-bion/krossbow)](https://github.com/joffrey-bion/krossbow)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.hildan.krossbow/krossbow-stomp-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.hildan.krossbow/krossbow-stomp-core)
> A coroutine-based Kotlin multi-platform WebSocket client and STOMP 1.2 client over web sockets.

[MOKO SocketIo](https://github.com/icerockdev/moko-socket-io) - Socket.IO implementation
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-socket-io)](https://github.com/icerockdev/moko-socket-io)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/socket-io/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/socket-io)
> This is a Kotlin MultiPlatform library that provides real-time, event-based communication for iOS and Android.

### 📦 Storage
[Multiplatform-Settings](https://github.com/russhwolf/multiplatform-settings) - Key-Value preferences
[![GitHub Repo stars](https://img.shields.io/github/stars/russhwolf/multiplatform-settings)](https://github.com/russhwolf/multiplatform-settings)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.russhwolf/multiplatform-settings/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.russhwolf/multiplatform-settings)
> This is a Kotlin library for Multiplatform apps, so that common code can persist key-value data

[SQLDelight](https://github.com/cashapp/sqldelight) - SQLite database
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/sqldelight)](https://github.com/cashapp/sqldelight)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.squareup.sqldelight/com.squareup.sqldelight.gradle.plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.squareup.sqldelight/com.squareup.sqldelight.gradle.plugin)
> SQLDelight generates typesafe kotlin APIs from your SQL statements. It verifies your schema, statements, and migrations at compile-time and provides IDE features like autocomplete and refactoring which make writing and maintaining SQL simple.

[Realm](https://github.com/realm/realm-kotlin) - NoSQL database
[![GitHub Repo stars](https://img.shields.io/github/stars/realm/realm-kotlin)](https://github.com/realm/realm-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.realm.kotlin/gradle-plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.realm.kotlin/gradle-plugin)
> Realm is a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the Kotlin SDK for Realm, which runs on Kotlin Multiplatform and Android.

[SQLiter](https://github.com/touchlab/SQLiter) - SQLite driver
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/SQLiter)](https://github.com/touchlab/SQLiter)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/co.touchlab/sqliter/badge.svg)](https://maven-badges.herokuapp.com/maven-central/co.touchlab/sqliter)
> SQLiter is a SQLite driver for Kotlin Native, currently Apple and Windows variants. It is designed to serve as a driver to power user-friendly libraries rather than something to use directly. Currently SQLiter powers the SQLDelight library on native clients.

[Kodein-DB](https://github.com/Kodein-Framework/Kodein-DB) - NoSQL database
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/Kodein-DB)](https://github.com/Kodein-Framework/Kodein-DB)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.kodein.db/kodein-db/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.kodein.db/kodein-db)
> Kodein-DB is a Kotlin/Multiplatform embedded NoSQL database that works on JVM, Android, Kotlin/Native and iOS. It is suited for client or mobile applications.

### 📱 Device
[MOKO Permissions](https://github.com/icerockdev/moko-permissions) - System permissions manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-permissions)](https://github.com/icerockdev/moko-permissions)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/permissions/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/permissions)
> Kotlin MultiPlatform library for providing runtime permissions on iOS & Android

[MOKO Geo](https://github.com/icerockdev/moko-geo) - Location manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-geo)](https://github.com/icerockdev/moko-geo)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/geo/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/geo)
> Geolocation access for mobile (android & ios) Kotlin Multiplatform development

[MOKO Biometry](https://github.com/icerockdev/moko-biometry) - System biometry manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-biometry)](https://github.com/icerockdev/moko-biometry)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/biometry/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/biometry)
> This is a Kotlin Multiplatform library that provides authentication by FaceId and TouchId (Fingerprint)

[MOKO Media](https://github.com/icerockdev/moko-media) - System media manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-media)](https://github.com/icerockdev/moko-media)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/media/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/media)
> This is a Kotlin MultiPlatform library that provides media picking in common code (photo/video) and video player controls.

[MOKO Maps](https://github.com/icerockdev/moko-maps) - Google maps manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-maps)](https://github.com/icerockdev/moko-maps)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/maps/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/maps)
> This is a Kotlin Multiplatform library that provides controls of maps to common code.

### 💉 Dependency Injection
[Koin](https://github.com/InsertKoinIO/koin) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/InsertKoinIO/koin)](https://github.com/InsertKoinIO/koin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.insert-koin/koin-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.insert-koin/koin-core)
> A pragmatic lightweight dependency injection framework for Kotlin developers. Koin is a DSL, a light container and a pragmatic API

[Kodein](https://github.com/Kodein-Framework/Kodein-DI) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/Kodein-DI)](https://github.com/Kodein-Framework/Kodein-DI)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.kodein.di/kodein-di/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.kodein.di/kodein-di)
> Kodein-DI is a very simple and yet very useful dependency retrieval container.

[PopKorn](https://github.com/corbella83/PopKorn) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/corbella83/PopKorn)](https://github.com/corbella83/PopKorn)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/cc.popkorn/popkorn/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cc.popkorn/popkorn)
> PopKorn is a simple, powerful and lightweight Kotlin Multiplatform Dependency Injector. It doesn't need any modules or components, just use it without writing a single extra file! It supports AND, IOS, JVM, JS and NATIVE.

### 🏗 Architecture
[MVI Kotlin](https://github.com/arkivanov/MVIKotlin) - MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/MVIKotlin)](https://github.com/arkivanov/MVIKotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.mvikotlin/mvikotlin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.mvikotlin/mvikotlin)
> MVIKotlin is a Kotlin Multiplatform framework that provides a way of (not only) writing shared code using MVI pattern. It also includes powerful debug tools like logging and time travel.

[Redux Kotlin](https://github.com/reduxkotlin/redux-kotlin) - Redux framework
[![GitHub Repo stars](https://img.shields.io/github/stars/reduxkotlin/redux-kotlin)](https://github.com/reduxkotlin/redux-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.reduxkotlin/redux-kotlin-threadsafe/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.reduxkotlin/redux-kotlin-threadsafe)
> Redux implementation for Kotlin (supports multiplatform JVM, native, JS, WASM)

[MOKO MVVM](https://github.com/icerockdev/moko-mvvm) - Redux framework
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-mvvm)](https://github.com/icerockdev/moko-mvvm)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/mvvm/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/mvvm)
> This is a Kotlin Multiplatform library that provides architecture components of Model-View-ViewModel for UI applications. Components are lifecycle-aware on Android.

### 🔍 Analytics
[MOKO Crash Reporting](https://github.com/icerockdev/moko-crash-reporting) - reporting to Crashlytics
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-crash-reporting)](https://github.com/icerockdev/moko-crash-reporting)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/crash-reporting-crashlytics/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/crash-reporting-crashlytics)
> Fatal and Non-Fatal reporting to Crashlytics for Kotlin Multiplatform Mobile

### 🩺 Test
[Kotest](https://github.com/kotest/kotest) - test framework

### 📁 File
[Okio](https://github.com/square/okio) - access, store, and process your data
[![GitHub Repo stars](https://img.shields.io/github/stars/square/okio)](https://github.com/square/okio)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.squareup.okio/okio/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.squareup.okio/okio)
> Okio is a library that complements java.io and java.nio to make it much easier to access, store, and process your data.

[Suparnatural FS](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/fs) - file system i/o
[![GitHub Repo stars](https://img.shields.io/github/stars/suparngp/kotlin-multiplatform-projects)](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/fs)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.suparnatural.kotlin/fs/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.suparnatural.kotlin/fs)
> Kotlin multiplatform file system i/o for android, iOS, Java and NodeJS


### 🗃 Serializer
[kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - JSON serialization

### ⏰ Date-Time

### ➿ Asynchronous

### 🔧 Utils
[MOKO Resources](https://github.com/icerockdev/moko-resources) - System resources manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-resources)](https://github.com/icerockdev/moko-resources)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/resources/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/resources)
> This is a Kotlin MultiPlatform library that provides access to the resources on iOS & Android with the support of the default system localization.

[MOKO Graphics](https://github.com/icerockdev/moko-graphics) - Graphics primitives
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-graphics)](https://github.com/icerockdev/moko-graphics)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/graphics/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/graphics)
> This is a Kotlin Multiplatform library that provides graphics primitives to common code.

[MOKO Parcelize](https://github.com/icerockdev/moko-parcelize) - Parcelize in common code
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-parcelize)](https://github.com/icerockdev/moko-parcelize)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/parcelize/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/parcelize)
> This is a Kotlin Multiplatform library that supports Parcelize in common code.

## Sample apps

## Authors

## Contribution guide
