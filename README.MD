# <img src="https://github.com/terrakok/kmm-awesome/raw/master/img/pluginIcon.svg" width="30"/> Awesome KMM

<img src="https://github.com/terrakok/kmm-awesome/raw/master/img/kmm.svg" align="center" width="650"/>

[![Pull request](https://img.shields.io/badge/PRs-welcome-success)](https://github.com/terrakok/kmm-awesome/pulls)
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
🤩 [KMM Samples](https://kotlinlang.org/docs/kmm-samples.html)

## Contents
<table>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#tooling">🛠 Tooling</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Log">📋 Log</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Network">🌎 Network</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Storage">📦 Storage</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Device">📱 Device</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Dependency-Injection">💉 Dependency Injection</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Architecture">🏗 Architecture</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Analytics">🔍 Analytics</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Test">🩺 Test</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Crypto">🔑 Crypto</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-File">📁 File</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Language-extentions">🚀 Language extentions</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Serializer">🗃 Serializer</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Date-Time">⏰ Date-Time</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Asynchronous">➿ Asynchronous</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Audio">🎵 Audio</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Graphics">🎨 Graphics</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Service-SDK">🧩 Service SDK</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Arithmetic">🧮 Arithmetic</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Utils">🔧 Utils</a></td>
    <td></td>
  </tr>
</table>

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

#### 🛠 [BuildKonfig](https://github.com/yshrsmz/BuildKonfig) gradle plugin
> BuildConfig for Kotlin Multiplatform Project

#### 🛠 [Kotlin Native Xcode Support](https://github.com/touchlab/xcode-kotlin)
> Plugin to facilitate debugging iOS applications using Kotlin Native in Xcode. Defines Kotlin files as source code, with basic highlighting. Allows you to set breakpoints and includes llvm support to view data in the debug window. Xcode does not officially support custom language definitions, but they also don't explicitly block them.

#### 🛠 [Dokka](https://github.com/Kotlin/dokka) documentation generation tool
> Dokka is a documentation engine for Kotlin, performing the same function as javadoc for Java. Just like Kotlin itself, Dokka fully supports mixed-language Java/Kotlin projects. It understands standard Javadoc comments in Java files and KDoc comments in Kotlin files, and can generate documentation in multiple formats including standard Javadoc, HTML and Markdown.

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

[Kodein-Log](https://github.com/Kodein-Framework/Kodein-Log) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/Kodein-Log)](https://github.com/Kodein-Framework/Kodein-Log)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.kodein.log/kodein-log/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.kodein.log/kodein-log)
> Kodein-Log is a lightweight Kotlin/Multiplatform logging library with a simple API, that works on JVM, Android, JavaScript, iOS, as well as for all Kotlin/Native targets.

[Klogger](https://github.com/korlibs/klogger) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/klogger)](https://github.com/korlibs/klogger)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.klogger/klogger/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.klogger/klogger)
> Klogger is a logger library for multiplatform Kotlin. This library provides a simple interface to do logging into suitable outputs like javascript’s console, or stdout/stderr.

[Cabret](https://github.com/Foso/Cabret-Log) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/Foso/Cabret-Log)](https://github.com/Foso/Cabret-Log)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/de.jensklingenberg.cabret/cabret-compiler-runtime/badge.svg)](https://maven-badges.herokuapp.com/maven-central/de.jensklingenberg.cabret/cabret-compiler-runtime)
> This is an Kotlin Library that enables Annotation-triggered method call logging for Kotlin Multiplatform.

[KmLogging](https://github.com/LighthouseGames/KmLogging) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/LighthouseGames/KmLogging)](https://github.com/LighthouseGames/KmLogging)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.lighthousegames/logging/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.lighthousegames/logging)
> Kotlin multiplatform logging. High performance, composable and simple to use. 

[Kydra Log](https://github.com/PocketByte/kotlin-kydra-log) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/PocketByte/kotlin-kydra-log)](https://github.com/PocketByte/kotlin-kydra-log)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/ru.pocketbyte.kydra/kydra-log/badge.svg)](https://maven-badges.herokuapp.com/maven-central/ru.pocketbyte.kydra/kydra-log)
> Kotlin Multiplatform Library that allows to write logs in common module.

### 🌎 Network
[Ktor](https://github.com/ktorio/ktor) - http client
[![GitHub Repo stars](https://img.shields.io/github/stars/ktorio/ktor)](https://github.com/ktorio/ktor)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.ktor/ktor/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.ktor)
> Ktor includes a multiplatform asynchronous HTTP client, which allows you to make requests and handle responses, extend its functionality with plugins (formerly known as features), such as authentication, JSON serialization, and so on. 

[Apollo GraphQL](https://github.com/apollographql/apollo-android) - GraphQL client
[![GitHub Repo stars](https://img.shields.io/github/stars/apollographql/apollo-android)](https://github.com/apollographql/apollo-android)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.apollographql.apollo3/apollo-runtime/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.apollographql.apollo3/apollo-runtime)
> A strongly-typed, caching GraphQL client for the JVM, Android, and Kotlin multiplatform.

[kgql](https://github.com/yshrsmz/kgql) - GraphQL Document wrapper generator
[![GitHub Repo stars](https://img.shields.io/github/stars/yshrsmz/kgql)](https://github.com/yshrsmz/kgql)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.codingfeline.kgql/core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.codingfeline.kgql/core)
> GraphQL Document wrapper generator for Kotlin Multiplatform Project. Currently, available for JVM/Android/iOS

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
> This is a Kotlin Multiplatform library that provides real-time, event-based communication for iOS and Android.

[rsocket](https://github.com/rsocket/rsocket-kotlin) - RSocket Kotlin multi-platform implementation
[![GitHub Repo stars](https://img.shields.io/github/stars/rsocket/rsocket-kotlin)](https://github.com/rsocket/rsocket-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.rsocket.kotlin/rsocket-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.rsocket.kotlin/rsocket-core)
> RSocket is a binary protocol for use on byte stream transports such as TCP, WebSockets and Aeron.

### 📦 Storage
[Multiplatform-Settings](https://github.com/russhwolf/multiplatform-settings) - Key-Value preferences
[![GitHub Repo stars](https://img.shields.io/github/stars/russhwolf/multiplatform-settings)](https://github.com/russhwolf/multiplatform-settings)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.russhwolf/multiplatform-settings/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.russhwolf/multiplatform-settings)
> This is a Kotlin library for Multiplatform apps, so that common code can persist key-value data

[KVault](https://github.com/Liftric/KVault) - secure key-value storage
[![GitHub Repo stars](https://img.shields.io/github/stars/Liftric/KVault)](https://github.com/Liftric/KVault)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.liftric/kvault/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.liftric/kvault)
> It acts as an iOS Keychain wrapper and implements encrypted SharedPreferences for Android.

[SQLDelight](https://github.com/cashapp/sqldelight) - SQLite database
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/sqldelight)](https://github.com/cashapp/sqldelight)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.squareup.sqldelight/com.squareup.sqldelight.gradle.plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.squareup.sqldelight/com.squareup.sqldelight.gradle.plugin)
> SQLDelight generates typesafe kotlin APIs from your SQL statements. It verifies your schema, statements, and migrations at compile-time and provides IDE features like autocomplete and refactoring which make writing and maintaining SQL simple.

[Realm](https://github.com/realm/realm-kotlin) - NoSQL database
[![GitHub Repo stars](https://img.shields.io/github/stars/realm/realm-kotlin)](https://github.com/realm/realm-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.realm.kotlin/gradle-plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.realm.kotlin/gradle-plugin)
> Realm is a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the Kotlin SDK for Realm, which runs on Kotlin Multiplatform and Android.

[cache4k](https://github.com/ReactiveCircus/cache4k) - In-memory Cache
[![GitHub Repo stars](https://img.shields.io/github/stars/ReactiveCircus/cache4k)](https://github.com/ReactiveCircus/cache4k)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.reactivecircus.cache4k/cache4k/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.reactivecircus.cache4k/cache4k)
> Provides a simple in-memory key-value cache for Kotlin Multiplatform, with support for time-based (expiration) and size-based evictions.

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
> Kotlin Multiplatform library for providing runtime permissions on iOS & Android

[MOKO Resources](https://github.com/icerockdev/moko-resources) - System resources manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-resources)](https://github.com/icerockdev/moko-resources)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/resources/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/resources)
> This is a Kotlin Multiplatform library that provides access to the resources on iOS & Android with the support of the default system localization.

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
> This is a Kotlin Multiplatform library that provides media picking in common code (photo/video) and video player controls.

[MOKO Maps](https://github.com/icerockdev/moko-maps) - Google/Mapbox maps manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-maps)](https://github.com/icerockdev/moko-maps)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/maps/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/maps)
> This is a Kotlin Multiplatform library that provides controls of maps to common code.

[Kable](https://github.com/juullabs/kable) - Coroutines-powered API for interacting with Bluetooth Low Energy devices.
[![GitHub Repo stars](https://img.shields.io/github/stars/juullabs/kable)](https://github.com/juullabs/kable)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.juul.kable/core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.juul.kable/core/)
>Kotlin Asynchronous Bluetooth Low Energy provides a simple Coroutines-powered API for interacting with Bluetooth Low Energy devices.

[Blue-Falcon](https://github.com/Reedyuk/blue-falcon) - A Bluetooth kotlin multiplatform library for iOS and Android
[![GitHub Repo stars](https://img.shields.io/github/stars/Reedyuk/blue-falcon)](https://github.com/Reedyuk/blue-falcon)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.bluefalcon/blue-falcon-rpi/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.bluefalcon/blue-falcon-rpi)
>A Bluetooth "Cross Platform" Kotlin Multiplatform library for iOS, Android, MacOS, Raspberry Pi and Javascript.
Bluetooth in general has the same functionality for all platforms, e.g. connect to device, fetch services, fetch characteristics.

[Connectivity status](https://github.com/ln-12/multiplatform-connectivity-status) - Multiplatform connectivity status
[![GitHub Repo stars](https://img.shields.io/github/stars/ln-12/multiplatform-connectivity-status)](https://github.com/rsocket/rsocket-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.ln-12/multiplatform-connectivity-status/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.ln-12/multiplatform-connectivity-status)
> This Kotlin multiplatform mobile utility library allows monitoring the internet connection status of the device. You can use it from shared code as well as directly from Android or iOS code.

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

[FlowRedux](https://github.com/freeletics/FlowRedux) - Statemachine library with nice DSL
[![GitHub Repo stars](https://img.shields.io/github/stars/freeletics/FlowRedux)](https://github.com/freeletics/FlowRedux)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.freeletics.flowredux/flowredux/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.freeletics.flowredux/flowredux)
> Building async. running Kotlin Multiplatform state machine made easy with a DSL and coroutines.

[Mobius.kt](https://github.com/DrewCarlson/mobius.kt) - Mobius Framework
[![GitHub Repo stars](https://img.shields.io/github/stars/DrewCarlson/mobius.kt)](https://github.com/DrewCarlson/mobius.kt)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.drewcarlson/mobiuskt-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.drewcarlson/mobiuskt-core)
> Kotlin Multiplatform [Mobius](https://github.com/spotify/mobius) implementation.

[MOKO MVVM](https://github.com/icerockdev/moko-mvvm) - MVVM framework
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-mvvm)](https://github.com/icerockdev/moko-mvvm)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/mvvm/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/mvvm)
> This is a Kotlin Multiplatform library that provides architecture components of Model-View-ViewModel for UI applications. Components are lifecycle-aware on Android.

[Oolong](https://github.com/oolong-kt/oolong) - MVU for Kotlin Multiplatform 
[![GitHub Repo stars](https://img.shields.io/github/stars/oolong-kt/oolong)](https://github.com/oolong-kt/oolong)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.oolong-kt/oolong/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.oolong-kt/oolong)
> Oolong is an [Elm](https://guide.elm-lang.org/architecture) inspired Model-View-Update (MVU) implementation for Kotlin multiplatform.

[Summer](https://github.com/adevone/summer) - Share ViewModels between iOS, Android and Web apps
[![GitHub Repo stars](https://img.shields.io/github/stars/adevone/summer)](https://github.com/adevone/summer)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.adevone.summer/summer/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.adevone.summer/summer)
> Summer is a presentation level library with kotlin-multiplatform support. It can be used to share viewModels between iOS, Android and Web apps.  Summer does not use code generation and thus have not significant effort on compilation time and odd build-time errors.  Project aims to have out-of-box support of Android Framework, Jetpack Compose, UIKit and SwiftUI without any adapters and platform-specific limitations.

[Decompose](https://github.com/arkivanov/Decompose) - componentization and navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/Decompose)](https://github.com/arkivanov/Decompose)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.decompose/decompose/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.decompose/decompose)
> Decompose is a Kotlin Multiplatform library for breaking down your code into lifecycle-aware business logic components (aka BLoC), with routing functionality and pluggable UI (Jetpack Compose, Android Views, SwiftUI, JS React, etc.)

[multiplatform-paging](https://github.com/kuuuurt/multiplatform-paging) - Pagination library for KMM
[![GitHub Repo stars](https://img.shields.io/github/stars/kuuuurt/multiplatform-paging)](https://github.com/kuuuurt/multiplatform-paging)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.kuuuurt/multiplatform-paging/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.kuuuurt/multiplatform-paging)
> A Kotlin Multiplatform library for pagination.

### 🔍 Analytics
[MOKO Crash Reporting](https://github.com/icerockdev/moko-crash-reporting) - reporting to Crashlytics
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-crash-reporting)](https://github.com/icerockdev/moko-crash-reporting)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/crash-reporting-crashlytics/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/crash-reporting-crashlytics)
> Fatal and Non-Fatal reporting to Crashlytics for Kotlin Multiplatform Mobile

[CrashKiOS](https://github.com/touchlab/CrashKiOS) - Crash reporting for Kotlin/Native iOS applications 
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/CrashKiOS)](https://github.com/touchlab/CrashKiOS)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/co.touchlab/crashkios/badge.svg)](https://maven-badges.herokuapp.com/maven-central/co.touchlab/crashkios)
> Thin library that provides symbolicated crash reports for Kotlin code on iOS.

### 🩺 Test
[Kotest](https://github.com/kotest/kotest) - test framework
[![GitHub Repo stars](https://img.shields.io/github/stars/kotest/kotest)](https://github.com/kotest/kotest)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.kotest/kotest-mpp/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.kotest/kotest-mpp)
> Powerful, elegant and flexible test framework for Kotlin with additional assertions, property testing and data driven testing 

### 🔑 Crypto
[Libsodium](https://github.com/ionspin/kotlin-multiplatform-libsodium) - Libsodium bindings for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/ionspin/kotlin-multiplatform-libsodium)](https://github.com/ionspin/kotlin-multiplatform-libsodium)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.ionspin.kotlin/multiplatform-crypto-libsodium-bindings/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.ionspin.kotlin/multiplatform-crypto-libsodium-bindings)
> Libsodium bindings project uses libsodium c sources and libsodium.js to provide a kotlin multiplatform wrapper library for libsodium.

[Krypto](https://github.com/korlibs/krypto) - Pure Kotlin cryptography library
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/krypto)](https://github.com/korlibs/krypto)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.krypto/krypto/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.krypto/krypto)
> SecureRandom, Hash (MD5/SHA1/SHA256), AES

[cryptohash](https://github.com/appmattus/crypto/tree/main/cryptohash) - A set of cryptographic (and not so cryptographic) hashing functions
[![GitHub Repo stars](https://img.shields.io/github/stars/appmattus/crypto)](https://github.com/appmattus/crypto)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.appmattus.crypto/cryptohash/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.appmattus.crypto/cryptohash)
> xxHash, Blake, HMAC, Keccak, MD5, SHA, etc

### 📁 File
[Okio](https://github.com/square/okio) - access, store, and process your data
[![GitHub Repo stars](https://img.shields.io/github/stars/square/okio)](https://github.com/square/okio)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.squareup.okio/okio/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.squareup.okio/okio)
> Okio is a library that complements java.io and java.nio to make it much easier to access, store, and process your data.

[KorIO](https://github.com/korlibs/korio) - access, store, and process your data
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korio)](https://github.com/korlibs/korio)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.korio/korio/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.korio/korio)
> KorIO is a library for Charsets, Encodings, Checksums, Compression, I/O, Streams, Virtual File System, Networking, Http, WebSockets, Serialization…

[Suparnatural FS](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/fs) - file system i/o
[![GitHub Repo stars](https://img.shields.io/github/stars/suparngp/kotlin-multiplatform-projects)](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/fs)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.suparnatural.kotlin/fs/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.suparnatural.kotlin/fs)
> Kotlin multiplatform file system i/o for android, iOS, Java and NodeJS

### 🚀 Language extentions

[Arrow](https://github.com/arrow-kt/arrow) - Functional companion to Kotlin's Standard Library 
[![GitHub Repo stars](https://img.shields.io/github/stars/arrow-kt/arrow)](https://github.com/arrow-kt/arrow)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.arrow-kt/arrow-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.arrow-kt/arrow-core)
> Arrow aims to provide a lingua franca of interfaces and abstractions across Kotlin libraries. For this, it includes the most popular data types such as Option, Either, Validated etc and functional operators such as traverse and computation blocks to empower users to write pure FP apps and libraries built atop higher order abstractions.

[Result](https://github.com/kittinunf/Result) - success/failure result
[![GitHub Repo stars](https://img.shields.io/github/stars/kittinunf/Result)](https://github.com/kittinunf/Result)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.kittinunf.result/result/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.kittinunf.result/result)
> This is a tiny framework for modelling success/failure of operations in Kotlin. In short, it is a model in type of Result<V: Any?, E : Throwable>.

### 🗃 Serializer
[kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - JSON serialization
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx.serialization)](https://github.com/Kotlin/kotlinx.serialization)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.jetbrains.kotlinx/kotlinx-serialization-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.jetbrains.kotlinx/kotlinx-serialization-core)
> Kotlin serialization consists of a compiler plugin, that generates visitor code for serializable classes, runtime library with core serialization API and support libraries with various serialization formats.

[MOKO Parcelize](https://github.com/icerockdev/moko-parcelize) - Parcelize in common code
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-parcelize)](https://github.com/icerockdev/moko-parcelize)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/parcelize/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/parcelize)
> This is a Kotlin Multiplatform library that supports Parcelize in common code.

[Pbandk](https://github.com/streem/pbandk) - Kotlin code generator and runtime for Protocol Buffers.
[![GitHub Repo stars](https://img.shields.io/github/stars/streem/pbandk)](https://github.com/streem/pbandk)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/pro.streem.pbandk/protoc-gen-pbandk-jvm/badge.svg)](https://maven-badges.herokuapp.com/maven-central/pro.streem.pbandk/protoc-gen-pbandk-jvm)
>It has the core set of protobuf features implemented and is being used in production.

### ⏰ Date-Time
[Kotlinx DateTime](https://github.com/Kotlin/kotlinx-datetime) - Date & Time library
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx-datetime)](https://github.com/Kotlin/kotlinx-datetime)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.jetbrains.kotlinx/kotlinx-datetime/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.jetbrains.kotlinx/kotlinx-datetime)
> A multiplatform Kotlin library for working with date and time.

[Klock](https://github.com/korlibs/klock) - Date & Time library
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/klock)](https://github.com/korlibs/klock)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.soywiz/klock/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.soywiz/klock)
> Klock is a Date & Time library for Multiplatform Kotlin. It is designed to be as allocation-free as possible using Kotlin inline classes, to be consistent and portable across targets since all the code is written in Common Kotlin, and to provide an API that is powerful, fun and easy to use.

[Island Time](https://github.com/erikc5000/island-time) - Date & Time library
[![GitHub Repo stars](https://img.shields.io/github/stars/erikc5000/island-time)](https://github.com/erikc5000/island-time)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.islandtime/core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.islandtime/core)
> A Kotlin Multiplatform library for working with dates and times, heavily inspired by the java.time library.

### ➿ Asynchronous

[Kotlinx Coroutines](https://github.com/Kotlin/kotlinx.coroutines) - Kotlin coroutines
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx.coroutines)](https://github.com/Kotlin/kotlinx.coroutines)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.jetbrains.kotlinx/kotlinx-coroutines-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.jetbrains.kotlinx/kotlinx-coroutines-core)
> Library support for Kotlin coroutines

[Reaktive](https://github.com/badoo/Reaktive) - Reactive Extensions
[![GitHub Repo stars](https://img.shields.io/github/stars/badoo/Reaktive)](https://github.com/badoo/Reaktive)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.badoo.reaktive/reaktive/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.badoo.reaktive/reaktive)
> Kotlin multiplatform implementation of Reactive Extensions.

[Kotlinx Atomicfu](https://github.com/Kotlin/kotlinx.atomicfu) - atomic operations
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx.atomicfu)](https://github.com/Kotlin/kotlinx.atomicfu)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.jetbrains.kotlinx/atomicfu/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.jetbrains.kotlinx/atomicfu)
> The idiomatic way to use atomic operations in Kotlin.

[Stately](https://github.com/Autodesk/coroutineworker) - Kotlin Multiplatform State Library 
[![GitHub Repo stars](https://img.shields.io/github/stars/Autodesk/coroutineworker)](https://github.com/Autodesk/coroutineworker)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/co.touchlab/stately/badge.svg)](https://maven-badges.herokuapp.com/maven-central/co.touchlab/stately)
> Stately is a state utility library to facilitate state management in Kotlin Multiplatform.

[CoroutineWorker](https://github.com/touchlab/Stately) - Workers for Kotlin Native
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/Stately)](https://github.com/touchlab/Stately)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.autodesk/CoroutineWorker/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.autodesk/CoroutineWorker)
> Kotlin Coroutine-based workers for native

[Koru](https://github.com/FutureMind/koru) - Coroutine wrappers for Kotlin Native 
[![GitHub Repo stars](https://img.shields.io/github/stars/FutureMind/koru)](https://github.com/FutureMind/koru)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.futuremind/koru/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.futuremind/koru)
> Automatically generates wrappers for suspend functions and Flow for easy access from Swift code in Kotlin Multiplatform projects.

[KMP-NativeCoroutines](https://github.com/rickclephas/KMP-NativeCoroutines) - Swift wrapper for Kotlin Coroutines 
[![GitHub Repo stars](https://img.shields.io/github/stars/rickclephas/KMP-NativeCoroutines)](https://github.com/rickclephas/KMP-NativeCoroutines)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.rickclephas.kmp/kmp-nativecoroutines-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.rickclephas.kmp/kmp-nativecoroutines-core)
> Library to use Kotlin Coroutines from Swift code in KMP apps

### 🎵 Audio
[Korau](https://github.com/korlibs/korau) - Kotlin cORoutines AUdio
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korau)](https://github.com/korlibs/korau)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.korau/korau/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.korau/korau)
> Pure Kotlin WAV, MP3 and OGG vorbis decoders

### 🎨 Graphics
[MOKO Graphics](https://github.com/icerockdev/moko-graphics) - Graphics primitives
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-graphics)](https://github.com/icerockdev/moko-graphics)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/graphics/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/graphics)
> This is a Kotlin Multiplatform library that provides graphics primitives to common code.

[Korim](https://github.com/korlibs/korim) - Imaging utilities
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korim)](https://github.com/korlibs/korim)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.korim/korim/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.korim/korim)
> Kotlin cORoutines IMaging, Bitmap and Vector graphics for Multiplatform Kotlin

### 🧩 Service SDK
[Firebase Kotlin SDK](https://github.com/GitLiveApp/firebase-kotlin-sdk) - A Kotlin-first SDK for Firebase 
[![GitHub Repo stars](https://img.shields.io/github/stars/GitLiveApp/firebase-kotlin-sdk)](https://github.com/GitLiveApp/firebase-kotlin-sdk)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.gitlive/firebase-auth/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.gitlive/firebase-auth)
> The Firebase Kotlin SDK is a Kotlin-first SDK for Firebase. It's API is similar to the Firebase Android SDK Kotlin Extensions but also supports multiplatform projects, enabling you to use Firebase directly from your common source targeting iOS, Android or JS.

[VK SDK Kotlin](https://github.com/vksdk/vk-sdk-kotlin) - Unofficial VK SDK 
[![GitHub Repo stars](https://img.shields.io/github/stars/vksdk/vk-sdk-kotlin)](https://github.com/vksdk/vk-sdk-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.petersamokhin.vksdk/core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.petersamokhin.vksdk/core)
> Create a chat-bot for VK.com in a few lines of code, use the API and forget about the limitations

[bitcoin-kmp](https://github.com/ACINQ/bitcoin-kmp) - Kotlin Multiplatform Bitcoin Library
[![GitHub Repo stars](https://img.shields.io/github/stars/ACINQ/bitcoin-kmp)](https://github.com/ACINQ/bitcoin-kmp)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/fr.acinq.bitcoin/bitcoin-kmp/badge.svg)](https://maven-badges.herokuapp.com/maven-central/fr.acinq.bitcoin/bitcoin-kmp)
> This is a simple Kotlin Multiplatform library which implements most of the bitcoin protocol

[MOKO Tensorflow](https://github.com/icerockdev/moko-tensorflow) - Mobile Kotlin TensorFlow
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-tensorflow)](https://github.com/icerockdev/moko-tensorflow)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/tensorflow/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/tensorflow)
> This is a Kotlin MultiPlatform library that provides access to TensorFlow-Lite functionality from common source set.

[qBittorrent](https://github.com/DrewCarlson/qBittorrent-Kotlin) - wrapper for the qBittorrent Web API
[![GitHub Repo stars](https://img.shields.io/github/stars/DrewCarlson/qBittorrent-Kotlin)](https://github.com/DrewCarlson/qBittorrent-Kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.drewcarlson/qbittorrent-client/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.drewcarlson/qbittorrent-client)
> Multiplatform Kotlin wrapper for the qBittorrent Web API using Ktor.

[Cognito-idp](https://github.com/Liftric/cognito-idp) - AWS Cognito Identity Provider
[![GitHub Repo stars](https://img.shields.io/github/stars/Liftric/cognito-idp)](https://github.com/Liftric/cognito-idp)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.liftric/cognito-idp/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.liftric/cognito-idp)
> Lightweight AWS Cognito Identity Provider client for Kotlin Multiplatform and Typescript projects.

[TMDb API](https://github.com/MoviebaseApp/tmdb-api) - access to TMDb API 
[![GitHub Repo stars](https://img.shields.io/github/stars/MoviebaseApp/tmdb-api)](https://github.com/MoviebaseApp/tmdb-api)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/app.moviebase/tmdb-api/badge.svg)](https://maven-badges.herokuapp.com/maven-central/app.moviebase/tmdb-api)
> This library gives access to TMDb API version 3 and 4 for mobile, desktop, and web applications. It supports Swift, Kotlin, and JavaScript by setting up as a Kotlin Multiplatform project.

[tgbotapi](https://github.com/InsanusMokrassar/TelegramBotAPI) - Wrapper and different tools for [Telegram Bots API](https://core.telegram.org/bots/api)
[![GitHub Repo stars](https://img.shields.io/github/stars/InsanusMokrassar/TelegramBotAPI)](https://github.com/InsanusMokrassar/TelegramBotAPI)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.inmo/tgbotapi/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.inmo/tgbotapi)
> (JS, JVM) This library will give you a lot of tools for work with [Telegram Bots API](https://core.telegram.org/bots/api) including live location dsl, keyboards dsl, FSM Behaviour Builder and a lot of others

### 🧮 Arithmetic

[KBigNum](https://github.com/korlibs/kbignum) - Big Numbers
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/kbignum)](https://github.com/korlibs/kbignum)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.kbignum/kbignum/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.kbignum/kbignum)
> Library for Big Numbers

[BigNum](https://github.com/ionspin/kotlin-multiplatform-bignum) - Big Numbers
[![GitHub Repo stars](https://img.shields.io/github/stars/ionspin/kotlin-multiplatform-bignum)](https://github.com/ionspin/kotlin-multiplatform-bignum)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.ionspin.kotlin/bignum/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.ionspin.kotlin/bignum)
> Kotlin Multiplatform BigNum library is a pure kotlin implementation of arbitrary precision arithmetic operations. It follows the same approach as Kotlin does on JVM to keep the interface familiar.

### 🔧 Utils
[UUID](https://github.com/benasher44/uuid) - UUID generator
[![GitHub Repo stars](https://img.shields.io/github/stars/benasher44/uuid)](https://github.com/benasher44/uuid)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.benasher44/uuid/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.benasher44/uuid)
> Kotlin Multiplatform UUID generator

[Colormath](https://github.com/ajalt/colormath) - Multiplatform Kotlin color conversion and manipulation 
[![GitHub Repo stars](https://img.shields.io/github/stars/ajalt/colormath)](https://github.com/ajalt/colormath)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.ajalt/colormath/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.ajalt/colormath)
> Colormath is a Kotlin Multiplatform library for color manipulation and conversion.

[GEOK](https://github.com/piruin/geok) - Kotlin geometry library 
[![GitHub Repo stars](https://img.shields.io/github/stars/piruin/geok)](https://github.com/piruin/geok)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.piruin/geok/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.piruin/geok)
> Small geometry library for Java and Kotlin. Contains useful basic utilities that require on most application.

[fluid-currency](https://github.com/fluidsonic/fluid-currency) - currency library
[![GitHub Repo stars](https://img.shields.io/github/stars/fluidsonic/fluid-currency)](https://github.com/fluidsonic/fluid-currency)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fluidsonic.currency/fluid-currency/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.fluidsonic.currency/fluid-currency)
> Kotlin multiplatform currency library.

[fluid-country](https://github.com/fluidsonic/fluid-country) - country library
[![GitHub Repo stars](https://img.shields.io/github/stars/fluidsonic/fluid-country)](https://github.com/fluidsonic/fluid-country)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.fluidsonic.country/fluid-country/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.fluidsonic.country/fluid-country)
> Kotlin multiplatform country library.

[Kmem](https://github.com/korlibs/kmem) - Data primitives
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/kmem)](https://github.com/korlibs/kmem)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.kmem/kmem/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.kmem/kmem)
> Kmem is bit, array and fast memory utilities library for multiplatform Kotlin

[KaseChange](https://github.com/pearxteam/kasechange) - convert strings between various case formats
[![GitHub Repo stars](https://img.shields.io/github/stars/pearxteam/kasechange)](https://github.com/pearxteam/kasechange)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/net.pearx.kasechange/kasechange/badge.svg)](https://maven-badges.herokuapp.com/maven-central/net.pearx.kasechange/kasechange)
> Multiplatform Kotlin library to convert strings between various case formats including Camel Case, Snake Case, Pascal Case and Kebab Case

[FuzzyWuzzy-Kotlin](https://github.com/willowtreeapps/fuzzywuzzy-kotlin) - Fuzzy string matching for Kotlin
[![GitHub Repo stars](https://img.shields.io/github/stars/willowtreeapps/fuzzywuzzy-kotlin)](https://github.com/willowtreeapps/fuzzywuzzy-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.willowtreeapps/fuzzywuzzy-kotlin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.willowtreeapps/fuzzywuzzy-kotlin)
> Useful for selecting the closest matching string from a collection of strings. Various algorithms are available.

## Suggest your an idea
[What libraries are you missing?](https://github.com/terrakok/kmm-awesome/discussions/7)

## Authors
https://github.com/terrakok/kmm-awesome/graphs/contributors

## Contribution guide
Feel free to contribute. Follow common style and welcome! :)

## License
```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
