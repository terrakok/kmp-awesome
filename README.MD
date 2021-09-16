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
#### [Napier](https://github.com/AAkira/Napier) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/AAkira/Napier)](https://github.com/AAkira/Napier)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.aakira/napier/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.aakira/napier)
> Napier is a logger library for Kotlin Multiplatform. It supports for the Android, Darwin(iOS, macOS, watchOS, tvOS), JVM, JavaScript. Logs written in common module are displayed on logger viewer of each platform.

#### [Kermit](https://github.com/touchlab/Kermit) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/Kermit)](https://github.com/touchlab/Kermit)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/co.touchlab/kermit/badge.svg)](https://maven-badges.herokuapp.com/maven-central/co.touchlab/kermit)
> Kermit is a Kotlin Multiplatform logging utility with composable log outputs. The library provides prebuilt loggers for outputting to platform logging tools such as Logcat and NSLog.

### 🌎 Network
#### [Ktor](https://github.com/ktorio/ktor) - http client
[![GitHub Repo stars](https://img.shields.io/github/stars/ktorio/ktor)](https://github.com/ktorio/ktor)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.ktor/ktor/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.ktor)
> Ktor includes a multiplatform asynchronous HTTP client, which allows you to make requests and handle responses, extend its functionality with plugins (formerly known as features), such as authentication, JSON serialization, and so on. In this tutorial, we'll create a simple client application for sending a request and receiving a response.

#### [Apollo GraphQL](https://github.com/apollographql/apollo-android) - GraphQL client
[![GitHub Repo stars](https://img.shields.io/github/stars/apollographql/apollo-android)](https://github.com/apollographql/apollo-android)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.apollographql.apollo3/apollo-runtime/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.apollographql.apollo3)
> A strongly-typed, caching GraphQL client for the JVM, Android, and Kotlin multiplatform.

#### [WebRTC KMP](https://github.com/shepeliev/webrtc-kmp) - WebRTC client
[![GitHub Repo stars](https://img.shields.io/github/stars/shepeliev/webrtc-kmp)](https://github.com/shepeliev/webrtc-kmp)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.shepeliev/webrtc-kmp/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.shepeliev/webrtc-kmp)
> WebRTC Kotlin Multiplatform SDK

#### [Krossbow](https://github.com/joffrey-bion/krossbow) - WebSocket client
[![GitHub Repo stars](https://img.shields.io/github/stars/joffrey-bion/krossbow)](https://github.com/joffrey-bion/krossbow)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.hildan.krossbow/krossbow-stomp-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.hildan.krossbow/krossbow-stomp-core)
> A coroutine-based Kotlin multi-platform WebSocket client and STOMP 1.2 client over web sockets.

#### [MOKO SocketIo](https://github.com/icerockdev/moko-socket-io) - Socket.IO implementation
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-socket-io)](https://github.com/icerockdev/moko-socket-io)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/socket-io/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/socket-io)
> This is a Kotlin MultiPlatform library that provides real-time, event-based communication for iOS and Android.

### 📦 Storage
#### [Multiplatform-Settings](https://github.com/russhwolf/multiplatform-settings) - Key-Value preferences
[![GitHub Repo stars](https://img.shields.io/github/stars/russhwolf/multiplatform-settings)](https://github.com/russhwolf/multiplatform-settings)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.russhwolf/multiplatform-settings/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.russhwolf/multiplatform-settings)
> This is a Kotlin library for Multiplatform apps, so that common code can persist key-value data.

#### [SQLDelight](https://github.com/cashapp/sqldelight) - SQLite database
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/sqldelight)](https://github.com/cashapp/sqldelight)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.squareup.sqldelight/com.squareup.sqldelight.gradle.plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.squareup.sqldelight/com.squareup.sqldelight.gradle.plugin)
> SQLDelight generates typesafe kotlin APIs from your SQL statements. It verifies your schema, statements, and migrations at compile-time and provides IDE features like autocomplete and refactoring which make writing and maintaining SQL simple.

#### [Realm](https://github.com/realm/realm-kotlin) - NoSQL database
[![GitHub Repo stars](https://img.shields.io/github/stars/realm/realm-kotlin)](https://github.com/realm/realm-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.realm.kotlin/gradle-plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.realm.kotlin/gradle-plugin)
> Realm is a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the Kotlin SDK for Realm, which runs on Kotlin Multiplatform and Android.

### 📱 Device
#### [MOKO Permissions](https://github.com/icerockdev/moko-permissions) - System permissions manager
#### [MOKO Geo](https://github.com/icerockdev/moko-geo) - Location manager
#### [MOKO Biometry](https://github.com/icerockdev/moko-biometry) - System biometry manager

### 💉 Dependency Injection
#### [Koin](https://github.com/InsertKoinIO/koin) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/InsertKoinIO/koin)](https://github.com/InsertKoinIO/koin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.insert-koin/koin-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.insert-koin/koin-core)
> A pragmatic lightweight dependency injection framework for Kotlin developers. Koin is a DSL, a light container and a pragmatic API

#### [Kodein](https://github.com/Kodein-Framework/Kodein-DI) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/Kodein-DI)](https://github.com/Kodein-Framework/Kodein-DI)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.kodein.di/kodein-di/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.kodein.di/kodein-di)
> Kodein-DI is a very simple and yet very useful dependency retrieval container.

#### [PopKorn](https://github.com/corbella83/PopKorn) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/corbella83/PopKorn)](https://github.com/corbella83/PopKorn)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/cc.popkorn/popkorn/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cc.popkorn/popkorn)
> PopKorn is a simple, powerful and lightweight Kotlin Multiplatform Dependency Injector. It doesn't need any modules or components, just use it without writing a single extra file! It supports AND, IOS, JVM, JS and NATIVE.

### 🏗 Architecture
#### [MVI Kotlin](https://github.com/arkivanov/MVIKotlin) - MVI framework

### 🔍 Analytics
#### [MOKO Crash Reporting](https://github.com/icerockdev/moko-crash-reporting) - reporting to Crashlytics

### 🩺 Test
#### [Kotest](https://github.com/kotest/kotest) - test framework

### 📁 File
#### [Okio](https://github.com/square/okio) - access, store, and process your data

### 🗃 Serializer
#### [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - JSON serialization

### ⏰ Date-Time

### ➿ Asynchronous

### 🔧 Utils