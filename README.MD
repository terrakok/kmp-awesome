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
🖼 [Website](https://kotlinlang.org/lp/mobile/)  
🚀 [Web Wizard](https://terrakok.github.io/kmp-web-wizard/)  
🍏 [Compose Multiplatform Wizard](https://terrakok.github.io/Compose-Multiplatform-Wizard/)  
📋 [Documentation](https://kotlinlang.org/docs/kmm-overview.html)  
📜 [Blog](https://blog.jetbrains.com/kotlin/category/mobile/)  
📺 [YouTube](https://www.youtube.com/playlist?list=PLlFc5cFwUnmy_oVc9YQzjasSNoAk4hk_C)  
🤩 [Samples](https://kotlinlang.org/docs/kmm-samples.html)  
📚 [Kotlin Multiplatform by Tutorials](https://www.kodeco.com/books/kotlin-multiplatform-by-tutorials)  
📚 [Simplifying Application Development with Kotlin Multiplatform Mobile](https://www.amazon.com/Simplifying-Application-Development-Kotlin-Multiplatform/dp/1801812586)

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
    <td><a href="https://github.com/terrakok/kmm-awesome#-compose-ui">🍎 Compose UI</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Graphics">🎨 Graphics</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Service-SDK">🧩 Service SDK</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Arithmetic">🧮 Arithmetic</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Resources">🛢 Resources</a></td>
    <td><a href="https://github.com/terrakok/kmm-awesome#-Utils">🔧 Utils</a></td>
  </tr>
</table>

### 🛠 Tooling

[Kotlin Multiplatform Mobile plugin](https://plugins.jetbrains.com/plugin/14936-kotlin-multiplatform-mobile) for Android Studio
> The Kotlin Multiplatform Mobile (KMM) plugin helps you develop applications that work on both Android and iOS.

[CocoaPods](https://kotlinlang.org/docs/native-cocoapods.html) integration
> Kotlin/Native provides integration with the CocoaPods dependency manager. You can add dependencies on Pod libraries as well as use a multiplatform project with native targets as a CocoaPods dependency (Kotlin Pod).

[Swift Package](https://github.com/PaGr0m/kotlin-spm-plugin) integration 
[![GitHub Repo stars](https://img.shields.io/github/stars/PaGr0m/kotlin-spm-plugin)](https://github.com/PaGr0m/kotlin-spm-plugin)
> This gradle plugin provides two-way interoperability between Kotlin dependencies and Kotlin-based Swift Package Multiplatform.

[Carthage](https://github.com/wireapp/carthage-gradle-plugin) integration 
[![GitHub Repo stars](https://img.shields.io/github/stars/wireapp/carthage-gradle-plugin)](https://github.com/wireapp/carthage-gradle-plugin)
> Adds support for integrating Carthage dependencies into a KMM project.

[Libres](https://github.com/Skeptick/libres) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/Skeptick/libres)](https://github.com/Skeptick/libres)
> String/Image resources generation in Kotlin Multiplatform.

[MOKO KSwift](https://github.com/icerockdev/moko-kswift) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-kswift)](https://github.com/icerockdev/moko-kswift)
> KSwift it's gradle plugin for generation Swift-friendly API for Kotlin/Native framework.

[CompleteKotlin](https://github.com/LouisCAD/CompleteKotlin) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/LouisCAD/CompleteKotlin)](https://github.com/LouisCAD/CompleteKotlin)
> Gradle Plugin to enable auto-completion and symbol resolution for all Kotlin/Native platforms.

[gradle-buildconfig-plugin](https://github.com/gmazzo/gradle-buildconfig-plugin) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/gmazzo/gradle-buildconfig-plugin)](https://github.com/gmazzo/gradle-buildconfig-plugin)
> A plugin for generating BuildConstants for any kind of Gradle projects: Java, Kotlin, Groovy, etc. Designed for KTS scripts. 

[BuildKonfig](https://github.com/yshrsmz/BuildKonfig) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/yshrsmz/BuildKonfig)](https://github.com/yshrsmz/BuildKonfig)
> BuildConfig for Kotlin Multiplatform Project

[Kotlin Native Xcode Support](https://github.com/touchlab/xcode-kotlin) 
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/xcode-kotlin)](https://github.com/touchlab/xcode-kotlin)
> Plugin to facilitate debugging iOS applications using Kotlin Native in Xcode. Defines Kotlin files as source code, with basic highlighting. Allows you to set breakpoints and includes llvm support to view data in the debug window. Xcode does not officially support custom language definitions, but they also don't explicitly block them.

[Dokka](https://github.com/Kotlin/dokka) documentation generation tool 
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/dokka)](https://github.com/Kotlin/dokka)
> Dokka is a documentation engine for Kotlin, performing the same function as javadoc for Java. Just like Kotlin itself, Dokka fully supports mixed-language Java/Kotlin projects. It understands standard Javadoc comments in Java files and KDoc comments in Kotlin files, and can generate documentation in multiple formats including standard Javadoc, HTML and Markdown.

[KDoctor](https://github.com/Kotlin/kdoctor) command-line tool 
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kdoctor)](https://github.com/Kotlin/kdoctor)
> KDoctor is a command-line tool that helps to set up the environment for Kotlin Multiplatform Mobile app development. It ensures that all required components are properly installed and ready for use. If something is missed or not configured Kdoctor highlights the problem and suggests how to fix the problem.

[Swift Klib](https://github.com/ttypic/swift-klib-plugin) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/ttypic/swift-klib-plugin)](https://github.com/ttypic/swift-klib-plugin)
> Gradle Plugin to build Swift code as part of your Kotlin Multiplatform project. With this plugin, you can access Swift-only iOS libraries, such as CryptoKit and experiment with Swift to Kotlin interoperability.

[parcelize-darwin](https://github.com/arkivanov/parcelize-darwin) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/parcelize-darwin)](https://github.com/arkivanov/parcelize-darwin)
> Kotlin/Native compiler plugin that generates Parcelable implementations for Darwin (Apple) targets. Allows writing Parcelable classes for all Darwin targets, similary to the Android's kotlin-parcelize plugin. Can be also used together with the kotlin-parcelize plugin to write Parcelable classes in the commonMain source set.

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

[kmp-xlog](https://github.com/HackWebRTC/kmp-xlog) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/HackWebRTC/kmp-xlog)](https://github.com/HackWebRTC/kmp-xlog)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.piasy/kmp-xlog/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.piasy/kmp-xlog)
> KMP wrapper for [tencent mars xlog](https://github.com/Tencent/mars).

### 🌎 Network
[Ktor](https://github.com/ktorio/ktor) - http client
[![GitHub Repo stars](https://img.shields.io/github/stars/ktorio/ktor)](https://github.com/ktorio/ktor)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.ktor/ktor/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.ktor)
> Ktor includes a multiplatform asynchronous HTTP client, which allows you to make requests and handle responses, extend its functionality with plugins (formerly known as features), such as authentication, JSON serialization, and so on. 

[Ktorfit](https://github.com/Foso/Ktorfit) - Retrofit for Kotlin Multiplatform on KTS
[![GitHub Repo stars](https://img.shields.io/github/stars/Foso/Ktorfit)](https://github.com/Foso/Ktorfit)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/de.jensklingenberg.ktorfit/ktorfit-lib/badge.svg)](https://maven-badges.herokuapp.com/maven-central/de.jensklingenberg.ktorfit/ktorfit-lib)
> HTTP client / Kotlin Symbol Processor for Kotlin Multiplatform (Android,Js, Jvm , Native, iOS) using KSP and Ktor clients inspired by Retrofit https://foso.github.io/Ktorfit

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

[abc-kmm-shared-storage](https://github.com/line/abc-kmm-shared-storage) - Key-Value storage
[![GitHub Repo stars](https://img.shields.io/github/stars/line/abc-kmm-shared-storage)](https://github.com/line/abc-kmm-shared-storage)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.linecorp.abc/kmm-shared-storage/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.linecorp.abc/kmm-shared-storage)
> A local storage management library for Kotlin Multiplatform Mobile iOS and Android 

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

[Store 5](https://github.com/MobileNativeFoundation/Store) - Kotlin Library for Async Data Loading and Caching 
[![GitHub Repo stars](https://img.shields.io/github/stars/MobileNativeFoundation/Store)](https://github.com/MobileNativeFoundation/Store)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.mobilenativefoundation.store/store5/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.mobilenativefoundation.store/store5)
> A Store is responsible for managing a particular data request. When you create an implementation of a Store, you provide it with a Fetcher, a function that defines how data will be fetched over network. You can also define how your Store will cache data in-memory and on-disk.

[Flower](https://github.com/hadiyarajesh/flower) - Flower simplifies networking and database caching on Android/Multiplatform. 
[![GitHub Repo stars](https://img.shields.io/github/stars/hadiyarajesh/flower)](https://github.com/hadiyarajesh/flower)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.hadiyarajesh.flower-core/flower-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.hadiyarajesh.flower-core/flower-core)
> Flower is a Kotlin multi-platform library that makes networking and database caching easy. It enables developers to fetch network resources and use them as is OR combine them with local database at single place with fault-tolerant architecture.

[cache4k](https://github.com/ReactiveCircus/cache4k) - In-memory Cache
[![GitHub Repo stars](https://img.shields.io/github/stars/ReactiveCircus/cache4k)](https://github.com/ReactiveCircus/cache4k)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.reactivecircus.cache4k/cache4k/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.reactivecircus.cache4k/cache4k)
> Provides a simple in-memory key-value cache for Kotlin Multiplatform, with support for time-based (expiration) and size-based evictions.

[SQLiter](https://github.com/touchlab/SQLiter) - SQLite driver
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/SQLiter)](https://github.com/touchlab/SQLiter)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/co.touchlab/sqliter/badge.svg)](https://maven-badges.herokuapp.com/maven-central/co.touchlab/sqliter)
> SQLiter is a SQLite driver for Kotlin Native, currently Apple and Windows variants. It is designed to serve as a driver to power user-friendly libraries rather than something to use directly. Currently SQLiter powers the SQLDelight library on native clients.

[SQLlin](https://github.com/ctripcorp/SQLlin) - Low-level API for SQLite in Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/ctripcorp/SQLlin)](https://github.com/ctripcorp/SQLlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.ctrip.kotlin/sqllin-driver/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.ctrip.kotlin/sqllin-driver)
> SQLlin is a Kotlin Multiplatform SQLite library that based on DSL and KSP. You can write SQL statements with your Kotlin code and these can be verified by Kotlin compiler.

[Kodein-DB](https://github.com/Kodein-Framework/Kodein-DB) - NoSQL database
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/Kodein-DB)](https://github.com/Kodein-Framework/Kodein-DB)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.kodein.db/kodein-db/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.kodein.db/kodein-db)
> Kodein-DB is a Kotlin/Multiplatform embedded NoSQL database that works on JVM, Android, Kotlin/Native and iOS. It is suited for client or mobile applications.

[KStore](https://github.com/xxfast/KStore) - File-based object storage
[![GitHub Repo stars](https://img.shields.io/github/stars/xxfast/KStore)](https://github.com/xxfast/KStore)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.xxfast/kstore/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.xxfast/kstore/)
> A Kotlin multiplatform library that assists in saving and restoring objects to and from disk

### 📱 Device
[MOKO Permissions](https://github.com/icerockdev/moko-permissions) - System permissions manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-permissions)](https://github.com/icerockdev/moko-permissions)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/permissions/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/permissions)
> Kotlin Multiplatform library for providing runtime permissions on iOS & Android

[abc-kmm-notifications](https://github.com/line/abc-kmm-notifications) - Notification Manager
[![GitHub Repo stars](https://img.shields.io/github/stars/line/abc-kmm-notifications)](https://github.com/line/abc-kmm-notifications)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.linecorp.abc/kmm-notifications/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.linecorp.abc/kmm-notifications)
> Remote Notification Manager for Kotlin Multiplatform Mobile

[abc-kmm-Location](https://github.com/line/abc-kmm-location) - Location manager
[![GitHub Repo stars](https://img.shields.io/github/stars/line/abc-kmm-location)](https://github.com/line/abc-kmm-location)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.linecorp.abc/kmm-location/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.linecorp.abc/kmm-location)
> Location Service Manager for Kotlin Multiplatform Mobile iOS and android

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

[Kontrol](https://github.com/chopyourbrain/kontrol) - Debug menu
[![GitHub Repo stars](https://img.shields.io/github/stars/chopyourbrain/kontrol)](https://github.com/chopyourbrain/kontrol)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.chopyourbrain/kontrol/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.chopyourbrain/kontrol)
> A Kotlin Multiplatform library for creating debug menu.

### 💉 Dependency Injection
[Koin](https://github.com/InsertKoinIO/koin) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/InsertKoinIO/koin)](https://github.com/InsertKoinIO/koin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.insert-koin/koin-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.insert-koin/koin-core)
> A pragmatic lightweight dependency injection framework for Kotlin developers. Koin is a DSL, a light container and a pragmatic API

[Kodein](https://github.com/Kodein-Framework/Kodein-DI) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/Kodein-DI)](https://github.com/Kodein-Framework/Kodein-DI)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.kodein.di/kodein-di/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.kodein.di/kodein-di)
> Kodein-DI is a very simple and yet very useful dependency retrieval container.

[kotlin-inject](https://github.com/evant/kotlin-inject) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/evant/kotlin-inject)](https://github.com/evant/kotlin-inject)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/me.tatarka.inject/kotlin-inject-runtime/badge.svg)](https://maven-badges.herokuapp.com/maven-central/me.tatarka.inject/kotlin-inject-runtime)
> A compile-time dependency injection library for kotlin.

[DI.kt](https://github.com/sergeshustoff/dikt) - DI for kotlin multiplatform 
[![GitHub Repo stars](https://img.shields.io/github/stars/sergeshustoff/dikt)](https://github.com/sergeshustoff/dikt)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.sergeshustoff.dikt/dikt-compiler-plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.sergeshustoff.dikt/dikt-compiler-plugin)
> Simple DI with compile-time dependency graph validation for kotlin multiplatform. It uses IR to create method's bodies with dependency injection.

[PopKorn](https://github.com/corbella83/PopKorn) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/corbella83/PopKorn)](https://github.com/corbella83/PopKorn)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/cc.popkorn/popkorn/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cc.popkorn/popkorn)
> PopKorn is a simple, powerful and lightweight Kotlin Multiplatform Dependency Injector. It doesn't need any modules or components, just use it without writing a single extra file! It supports AND, IOS, JVM, JS and NATIVE.

### 🏗 Architecture
[MVI Kotlin](https://github.com/arkivanov/MVIKotlin) - MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/MVIKotlin)](https://github.com/arkivanov/MVIKotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.mvikotlin/mvikotlin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.mvikotlin/mvikotlin)
> MVIKotlin is a Kotlin Multiplatform framework that provides a way of (not only) writing shared code using MVI pattern. It also includes powerful debug tools like logging and time travel.

[Orbit MVI](https://github.com/orbit-mvi/orbit-mvi) - MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/orbit-mvi/orbit-mvi)](https://github.com/orbit-mvi/orbit-mvi)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.orbit-mvi/orbit-core/badge.svg)](https://search.maven.org/artifact/org.orbit-mvi/orbit-core)
> Orbit is a Redux/MVI-like library for KMM, targetting Android and iOS.

[KMM-ViewModel](https://github.com/rickclephas/KMM-ViewModel) - KMM ViewModels
[![GitHub Repo stars](https://img.shields.io/github/stars/rickclephas/KMM-ViewModel)](https://github.com/rickclephas/KMM-ViewModel)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.rickclephas.kmm/kmm-viewmodel-core/badge.svg)](https://search.maven.org/artifact/com.rickclephas.kmm/kmm-viewmodel-core)
> A library that allows you to share ViewModels between Android and iOS.

[VisualFSM](https://github.com/Kontur-Mobile/VisualFSM) - FSM-based MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/Kontur-Mobile/VisualFSM)](https://github.com/Kontur-Mobile/VisualFSM)
[![MavenCentral](https://maven-badges.herokuapp.com/maven-central/ru.kontur.mobile.visualfsm/visualfsm-core/badge.svg)](https://search.maven.org/artifact/ru.kontur.mobile.visualfsm/visualfsm-core)
> VisualFSM is a Kotlin Multiplatform library for implements an FSM-based (Finite-state machine) MVI pattern and a set of tools for visualization and analysis of FSM's diagram of states.

[Redux Kotlin](https://github.com/reduxkotlin/redux-kotlin) - Redux framework
[![GitHub Repo stars](https://img.shields.io/github/stars/reduxkotlin/redux-kotlin)](https://github.com/reduxkotlin/redux-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.reduxkotlin/redux-kotlin-threadsafe/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.reduxkotlin/redux-kotlin-threadsafe)
> Redux implementation for Kotlin (supports multiplatform JVM, native, JS, WASM)

[CoRed](https://github.com/kittinunf/CoRed) - Opinionated Redux-like implementation
[![GitHub Repo stars](https://img.shields.io/github/stars/kittinunf/CoRed)](https://github.com/kittinunf/CoRed)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.kittinunf.cored/cored/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.kittinunf.cored/cored)
> CoRed is Redux-like implementation that maintains the benefits of Redux's core idea without the boilerplate. No more action types, action creators, switch statements or complicated setup. It is Kotlin and it has coroutine supported right out-of-the-box.

[Flywheel](https://github.com/abhimuktheeswarar/Flywheel) - Redux for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/abhimuktheeswarar/Flywheel)](https://github.com/abhimuktheeswarar/Flywheel)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.msabhi/flywheel/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.msabhi/flywheel)
> A simple and predictable state management library inspired by Redux for Kotlin Multiplatform using the concepts of actors.

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

[Premo](https://github.com/dmdevgo/Premo) — Presentation Model (aka View Model) and Navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/dmdevgo/premo)](https://github.com/dmdevgo/Premo)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/me.dmdev.premo/premo/badge.svg)](https://maven-badges.herokuapp.com/maven-central/me.dmdev.premo/premo)
> Premo is a Kotlin Multiplatform library that helps to implement the Presentation Layer and share it on iOS, Android, Desktop and Web. Focus on writing logic instead of solving common and boring UI related issues: lifecycle, persistence, navigation, etc.

[Decompose](https://github.com/arkivanov/Decompose) - componentization and navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/Decompose)](https://github.com/arkivanov/Decompose)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.decompose/decompose/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.decompose/decompose)
> Decompose is a Kotlin Multiplatform library for breaking down your code into lifecycle-aware business logic components (aka BLoC), with routing functionality and pluggable UI (Jetpack Compose, Android Views, SwiftUI, JS React, etc.)

[Decompose-Router](https://github.com/xxfast/Decompose-Router) - navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/xxfast/Decompose-Router)](https://github.com/xxfast/Decompose-Router)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.xxfast/decompose-router/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.xxfast/decompose-router/)
> A Compose-multiplatform navigation library that leverage Decompose to create an API inspired by Conductor

[Ballast](https://github.com/copper-leaf/ballast) - State Management framework
[![GitHub Repo stars](https://img.shields.io/github/stars/copper-leaf/ballast)](https://github.com/copper-leaf/ballast)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.copper-leaf/ballast-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.copper-leaf/ballast-core)
> Opinionated Application State Management framework for Kotlin Multiplatform

[Essenty/Lifecycle](https://github.com/arkivanov/Essenty#lifecyle) - lifecycle handling in the Kotlin Multiplatform common code 
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/Essenty)](https://github.com/arkivanov/Essenty)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.essenty/lifecycle/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.essenty/lifecycle)
> Essenty provides the Lifecycle API to help with lifecycle handling in the common code. It is very similar to Android Activity lifecycle.

[multiplatform-paging](https://github.com/cashapp/multiplatform-paging) - Pagination library for KMM by `Cash App`
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/multiplatform-paging)](https://github.com/cashapp/multiplatform-paging)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/app.cash.paging/paging-common/badge.svg)](https://maven-badges.herokuapp.com/maven-central/app.cash.paging/paging-common)
> A Kotlin Multiplatform library for pagination with the same API as AndroidX Paging

[multiplatform-paging](https://github.com/kuuuurt/multiplatform-paging) - Pagination library for KMM
[![GitHub Repo stars](https://img.shields.io/github/stars/kuuuurt/multiplatform-paging)](https://github.com/kuuuurt/multiplatform-paging)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.kuuuurt/multiplatform-paging/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.kuuuurt/multiplatform-paging)
> A Kotlin Multiplatform library for pagination.

[Kotlin Bloc](https://github.com/1gravity/Kotlin-Bloc) - UI framework for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/1gravity/Kotlin-Bloc)](https://github.com/1gravity/Kotlin-Bloc)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.1gravity/bloc-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.1gravity/bloc-core)
> Kotlin Bloc is a simple, predictable and composable UI framework for Kotlin Multiplatform supporting Android, iOS and JVM.

[kmp-viewmodel](https://github.com/hoc081098/kmp-viewmodel) - Kotlin Multiplatform ViewModel
[![GitHub Repo stars](https://img.shields.io/github/stars/hoc081098/kmp-viewmodel)](https://github.com/hoc081098/kmp-viewmodel)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.hoc081098/kmp-viewmodel/badge.svg)](https://search.maven.org/artifact/io.github.hoc081098/kmp-viewmodel/)
> A Kotlin Multiplatform library that provides shared MVVM. Supports Android Parcelable, Kotlin Parcelize, AndroidX SavedStateHandle for restoring state after process death.

### 🔍 Analytics
[MOKO Crash Reporting](https://github.com/icerockdev/moko-crash-reporting) - reporting to Crashlytics
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-crash-reporting)](https://github.com/icerockdev/moko-crash-reporting)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/crash-reporting-crashlytics/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/crash-reporting-crashlytics)
> Fatal and Non-Fatal reporting to Crashlytics for Kotlin Multiplatform Mobile

[CrashKiOS](https://github.com/touchlab/CrashKiOS) - Crash reporting for Kotlin/Native iOS applications 
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/CrashKiOS)](https://github.com/touchlab/CrashKiOS)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/co.touchlab/crashkios/badge.svg)](https://maven-badges.herokuapp.com/maven-central/co.touchlab/crashkios)
> Thin library that provides symbolicated crash reports for Kotlin code on iOS.

[NSExceptionKt](https://github.com/rickclephas/NSExceptionKt) - Better crash reports on Apple platforms
[![GitHub Repo stars](https://img.shields.io/github/stars/rickclephas/NSExceptionKt)](https://github.com/rickclephas/NSExceptionKt)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.rickclephas.kmp/nsexception-kt-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.rickclephas.kmp/nsexception-kt-core)
> Unhandled Kotlin exceptions logging for Apple platforms.

[abc-kmm-analytics-tools](https://github.com/line/abc-kmm-analytics-tools) - Analytics Tools 
[![GitHub Repo stars](https://img.shields.io/github/stars/line/abc-kmm-analytics-tools)](https://github.com/line/abc-kmm-analytics-tools)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.linecorp.abc/kmm-analytics-tools/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.linecorp.abc/kmm-analytics-tools)
> Automatically tracking and sending events of screen view and capture

[Analytics](https://github.com/ppav/analytics) - analytics facade
[![GitHub Repo stars](https://img.shields.io/github/stars/ppav/analytics)](https://github.com/ppav/analytics)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.ppav.analytics/analytics/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.ppav/analytics/analytics)
> Kotlin Multiplatform library as a simple facade or abstraction for analytics.

### 🩺 Test
[Kotest](https://github.com/kotest/kotest) - test framework
[![GitHub Repo stars](https://img.shields.io/github/stars/kotest/kotest)](https://github.com/kotest/kotest)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.kotest/kotest-mpp/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.kotest/kotest-mpp)
> Powerful, elegant and flexible test framework for Kotlin with additional assertions, property testing and data driven testing 

[Turbine](https://github.com/cashapp/turbine) - test library
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/turbine)](https://github.com/mpetuska/klip)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/app.cash.turbine/turbine/badge.svg)](https://maven-badges.herokuapp.com/maven-central/app.cash.turbine/turbine)
> A small testing library for kotlinx.coroutines Flow

[MockingBird](https://github.com/careem/mockingbird) - test framework
[![GitHub Repo stars](https://img.shields.io/github/stars/careem/mockingbird)](https://github.com/careem/mockingbird)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.careem.mockingbird/mockingbird/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.careem.mockingbird/mockingbird)
> A Koltin multiplatform library that provides an easier way to mock and write unit tests for a multiplatform project 

[Mockative](https://github.com/mockative/mockative) - Mocking with KSP
[![GitHub Repo stars](https://img.shields.io/github/stars/mockative/mockative)](https://github.com/mockative/mockative)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.mockative/mockative/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.mockative/mockative)
> Mocking for Kotlin/Native and Kotlin Multiplatform using the Kotlin Symbol Processing API (KSP)

[MocKMP](https://github.com/Kodein-Framework/MocKMP) - Mocking with KSP
[![GitHub Repo stars](https://img.shields.io/github/stars/Kodein-Framework/MocKMP)](https://github.com/Kodein-Framework/MocKMP)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.kodein.mock.mockmp/org.kodein.mock.mockmp.gradle.plugin/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.kodein.mock.mockmp/org.kodein.mock.mockmp.gradle.plugin)
> A Kotlin/Multiplatform Kotlin Symbol Processor that generates Mocks & Fakes.

[KLIP](https://github.com/mpetuska/klip) - Snapshot ((c|k)lip) manager for tests. 
[![GitHub Repo stars](https://img.shields.io/github/stars/mpetuska/klip)](https://github.com/mpetuska/klip)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.petuska/klip/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.petuska/klip)
> Kotlin Multiplatform snapshot ((c|k)lip) manager for tests. Automatically generates and asserts against a persistent Any::toString() representation of the object until you explicitly trigger an update. Powered by kotlin compiler plugin to inject relevant keys and paths.

### 🔑 Crypto
[Cryptography-Kotlin](https://github.com/whyoleg/cryptography-kotlin) - Type-safe Multiplatform cryptography library for Kotlin 
[![GitHub Repo stars](https://img.shields.io/github/stars/whyoleg/cryptography-kotlin)](https://github.com/whyoleg/cryptography-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.whyoleg.cryptography/cryptography-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.whyoleg.cryptography/cryptography-core)
> The library doesn’t implement any cryptography algorithm on its own, but wraps well-known future-proof solutions like OpenSSL 3.x, WebCrypto or JCA with type-safe multiplatform API providing uniform experience with aligned default behavior, and same expected results using identical parameters while allowing to use platform-specific capabilities.

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

[murmurhash](https://github.com/goncalossilva/kotlinx-murmurhash) - library for hashing using MurmurHash
[![GitHub Repo stars](https://img.shields.io/github/stars/goncalossilva/kotlinx-murmurhash)](https://github.com/goncalossilva/kotlinx-murmurhash)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.goncalossilva/murmurhash/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.goncalossilva/murmurhash)
> Kotlin Multiplatform (KMP) library for MurmurHash, a non-cryptographic hash function for general hash-based lookup focused on simplicity and performance.

[Diglol Crypto](https://github.com/diglol/crypto) - Diglol Crypto for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/diglol/crypto)](https://github.com/diglol/crypto)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.diglol.crypto/aead/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.diglol.crypto/aead)
> Lots of crypto algorithms for Kotlin Multiplatform.

[KotlinCrypto/MACs](https://github.com/KotlinCrypto/MACs) - Message Authentication Code algorithms for Kotlin Multiplatform 
[![GitHub Repo stars](https://img.shields.io/github/stars/KotlinCrypto/MACs)](https://github.com/KotlinCrypto/MACs)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.kotlincrypto.macs/hmac/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.kotlincrypto.macs/hmac)
> Message Authentication Code algorithms for Kotlin Multiplatform: HmacMD5, HmacSHA1, HmacSHA224, HmacSHA256, HmacSHA384, HmacSHA512, HmacSHA512/224, HmacSHA512/256

[KotlinCrypto/hash](https://github.com/KotlinCrypto/hash) - Cryptographic hash functions for Kotlin Multiplatform 
[![GitHub Repo stars](https://img.shields.io/github/stars/KotlinCrypto/hash)](https://github.com/KotlinCrypto/hash)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.kotlincrypto.hash/md5/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.kotlincrypto.hash/md5)
> Cryptographic hash functions for Kotlin Multiplatform: MD5, SHA-1, SHA-224, SHA-256, SHA-384, SHA-512, SHA-512/224, SHA-512/256

[KotlinCrypto/secure-random](https://github.com/KotlinCrypto/secure-random) - cryptographically secure random data from system sources 
[![GitHub Repo stars](https://img.shields.io/github/stars/KotlinCrypto/secure-random)](https://github.com/KotlinCrypto/secure-random)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.kotlincrypto/secure-random/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.kotlincrypto/secure-random)
> Kotlin Multiplatform library for obtaining cryptographically secure random data from the system. Modeled after Java's SecureRandom class, it provides a simple API surface area. Under the hood it utilizes system functions so that SecureRandom is accessible from common code.

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

### 🚀 Language extensions
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

[XmlUtil](https://github.com/pdvrieze/xmlutil) - Component of the XMLUtil library
[![GitHub Repo stars](https://img.shields.io/github/stars/pdvrieze/xmlutil)](https://github.com/pdvrieze/xmlutil)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.pdvrieze.xmlutil/core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.pdvrieze.xmlutil/core)
> XmlUtil is a set of packages that supports multiplatform XML in Kotlin.

[Ksoup](https://github.com/MohamedRejeb/ksoup) - Kotlin Multiplatform HTML Parser
[![GitHub Repo stars](https://img.shields.io/github/stars/MohamedRejeb/ksoup)](https://github.com/MohamedRejeb/ksoup)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.mohamedrejeb.ksoup/ksoup-html/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.mohamedrejeb.ksoup/ksoup-html)
> Ksoup is a lightweight Kotlin Multiplatform library for parsing HTML, extracting HTML tags, attributes, and text, and encoding and decoding HTML entities. 

[Essenty/Parcelable](https://github.com/arkivanov/Essenty#parcelable-and-parcelize) - @Parcelize annotation for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/Essenty)](https://github.com/arkivanov/Essenty)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.essenty/parcelable/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.arkivanov.essenty/parcelable)
> Essenty brings both Android Parcelable interface and the `@Parcelize` annotation from kotlin-parcelize compiler plugin to Kotlin Multiplatform, so they both can be used in common code. 

[Kotlin Object Notation](https://github.com/mpetuska/kon) - Lightweight DSL to build fluid JSON trees
[![GitHub Repo stars](https://img.shields.io/github/stars/mpetuska/kon)](https://github.com/mpetuska/kon)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.petuska/kon/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.petuska/kon)
> Kotlin Object Notation - Lightweight DSL to build fluid JSON trees

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

[Kronos Multiplatform](https://github.com/softartdev/Kronos-Multiplatform) - Network Time Protocol (NTP) client
[![GitHub Repo stars](https://img.shields.io/github/stars/softartdev/Kronos-Multiplatform)](https://github.com/softartdev/Kronos-Multiplatform)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.softartdev/kronos/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.softartdev/kronos)
> Kotlin Multiplatform library for network time synchronization. Extension for [Kotlinx DateTime](https://github.com/Kotlin/kotlinx-datetime) library.

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

[Stately](https://github.com/touchlab/Stately) - Kotlin Multiplatform State Library 
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/Stately)](https://github.com/touchlab/Stately)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/co.touchlab/stately/badge.svg)](https://maven-badges.herokuapp.com/maven-central/co.touchlab/stately)
> Stately is a state utility library to facilitate state management in Kotlin Multiplatform.

[CoroutineWorker](https://github.com/Autodesk/coroutineworker) - Workers for Kotlin Native
[![GitHub Repo stars](https://img.shields.io/github/stars/Autodesk/coroutineworker)](https://github.com/Autodesk/coroutineworker)
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

[FlowExt](https://github.com/hoc081098/FlowExt) - Kotlinx Coroutines Flow Extensions
[![GitHub Repo stars](https://img.shields.io/github/stars/hoc081098/FlowExt)](https://github.com/hoc081098/FlowExt)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.hoc081098/FlowExt/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.hoc081098/FlowExt)
> A Kotlin Multiplatform library, that provides many operators and extensions to Kotlin Coroutines Flow.

### 🍎 Compose UI
[Voyager](https://github.com/adrielcafe/voyager) Compose Multiplatform Navigation. 
[![GitHub Repo stars](https://img.shields.io/github/stars/adrielcafe/voyager)](https://github.com/adrielcafe/voyager)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/cafe.adriel.voyager/voyager-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cafe.adriel.voyager/voyager-core)
> A multiplatform navigation library built for, and seamlessly integrated with, Jetpack Compose.

[Libres-Compose](https://github.com/Skeptick/libres) Resources generation in Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/Skeptick/libres)](https://github.com/Skeptick/libres)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.skeptick.libres/libres-compose/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.skeptick.libres/libres-compose)
> This artifact provides painterResource function that can be used to get Painter from io.github.skeptick.libres.Image in common code.

[InsetsX](https://github.com/mori-atsushi/insetsx) WindowInsets
[![GitHub Repo stars](https://img.shields.io/github/stars/mori-atsushi/insetsx)](https://github.com/mori-atsushi/insetsx)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.moriatsushi.insetsx/insetsx/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.moriatsushi.insetsx/insetsx)
> InsetsX provides a WindowInsets utility for Compose Multiplatform.

[Compose-Imageloader](https://github.com/qdsfdhvh/compose-imageloader) Compose Image library for Kotlin Multiplatform. 
[![GitHub Repo stars](https://img.shields.io/github/stars/qdsfdhvh/compose-imageloader)](https://github.com/qdsfdhvh/compose-imageloader)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.qdsfdhvh/image-loader/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.qdsfdhvh/image-loader)
> Compose Image library for Kotlin Multiplatform.

[Kamel](https://github.com/Kamel-Media/Kamel) Compose Multiplatform image loading.
[![GitHub Repo stars](https://img.shields.io/github/stars/Kamel-Media/Kamel)](https://github.com/Kamel-Media/Kamel)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/media.kamel/kamel-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/media.kamel/kamel-core)
> An asynchronous media loading library for Compose Multiplatform.

[Compose Icons](https://github.com/DevSrSouza/compose-icons) Open Source icon packs for Compose Multiplatform. 
[![GitHub Repo stars](https://img.shields.io/github/stars/DevSrSouza/compose-icons)](https://github.com/DevSrSouza/compose-icons)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/br.com.devsrsouza.compose.icons/simple-icons/badge.svg)](https://maven-badges.herokuapp.com/maven-central/br.com.devsrsouza.compose.icons/simple-icons)
> Compose Multiplatform icons is a pack of libraries that provide well known Icon Packs. The library usage is inspired by Compose Material Icons.

[Compose Rich Editor](https://github.com/MohamedRejeb/Compose-Rich-Editor) Provides Rich Editor component for Compose Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/MohamedRejeb/Compose-Rich-Editor)](https://github.com/MohamedRejeb/Compose-Rich-Editor)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.mohamedrejeb.richeditor/richeditor-compose/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.mohamedrejeb.richeditor/richeditor-compose)
> A Rich text editor library for both Jetpack Compose and Compose Multiplatform, fully customizable and supports the common rich text editor features.

[Material Theme Preferences](https://github.com/softartdev/MaterialThemePrefs) Switching Dark/Light Material themes.
[![GitHub Repo stars](https://img.shields.io/github/stars/softartdev/MaterialThemePrefs)](https://github.com/softartdev/MaterialThemePrefs)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.softartdev/material-theme-prefs/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.softartdev/material-theme-prefs)
> Kotlin Multiplatform library for easy switching Dark/Light Material themes on Compose.

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

[openai-kotlin](https://github.com/Aallam/openai-kotlin) - OpenAI SDK 
[![GitHub Repo stars](https://img.shields.io/github/stars/Aallam/openai-kotlin)](https://github.com/Aallam/openai-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.aallam.openai/openai-client/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.aallam.openai/openai-client)
> Kotlin client for [OpenAI's API](https://beta.openai.com/docs/api-reference) with multiplatform and coroutines capabilities.

[Sentry SDK](https://github.com/getsentry/sentry-kotlin-multiplatform) - Sentry Kotlin Multiplatform SDK 
[![GitHub Repo stars](https://img.shields.io/github/stars/getsentry/sentry-kotlin-multiplatform)](https://github.com/getsentry/sentry-kotlin-multiplatform)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.sentry/sentry-kotlin-multiplatform/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.sentry/sentry-kotlin-multiplatform)
> This project is an experimental SDK for Kotlin Multiplatform. This SDK is a wrapper around different platforms such as JVM, Android, iOS, macOS, watchOS, tvOS that can be used on Kotlin Multiplatform.

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

[Growth Book SDK](https://github.com/growthbook/growthbook-kotlin) - GrowthBook Kotlin SDK 
[![GitHub Repo stars](https://img.shields.io/github/stars/growthbook/growthbook-kotlin)](https://github.com/growthbook/growthbook-kotlin)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.growthbook.sdk/GrowthBook/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.growthbook.sdk/GrowthBook)
> GrowthBook is an open-source platform for feature flagging and a/b testing built for data teams, engineers, and product managers. It's great whether you're looking to just analyze experiment results or looking to make it easier to deploy code.

[ConfigCat](https://github.com/configcat/kotlin-sdk) - Kotlin Multiplatform SDK for ConfigCat
[![GitHub Repo stars](https://img.shields.io/github/stars/configcat/kotlin-sdk)](https://github.com/configcat/kotlin-sdk)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.configcat/configcat-kotlin-client/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.configcat/configcat-kotlin-client)
> Kotlin Multiplatform SDK for ConfigCat, a feature flag, feature toggle, and configuration management service. That lets you launch new features and change your software configuration remotely without actually (re)deploying code. ConfigCat even helps you do controlled roll-outs like canary releases and blue-green deployments.

### 🧮 Arithmetic
[KBigNum](https://github.com/korlibs/kbignum) - Big Numbers
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/kbignum)](https://github.com/korlibs/kbignum)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.kbignum/kbignum/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.kbignum/kbignum)
> Library for Big Numbers

[BigNum](https://github.com/ionspin/kotlin-multiplatform-bignum) - Big Numbers
[![GitHub Repo stars](https://img.shields.io/github/stars/ionspin/kotlin-multiplatform-bignum)](https://github.com/ionspin/kotlin-multiplatform-bignum)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.ionspin.kotlin/bignum/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.ionspin.kotlin/bignum)
> Kotlin Multiplatform BigNum library is a pure kotlin implementation of arbitrary precision arithmetic operations. It follows the same approach as Kotlin does on JVM to keep the interface familiar.

### 🛢 Resources
[MOKO Resources](https://github.com/icerockdev/moko-resources) - System resources manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-resources)](https://github.com/icerockdev/moko-resources)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/resources/badge.svg)](https://maven-badges.herokuapp.com/maven-central/dev.icerock.moko/resources)
> This is a Kotlin Multiplatform library that provides access to the resources on iOS & Android with the support of the default system localization.

[Kotlinx-Resources](https://github.com/goncalossilva/kotlinx-resources) - text resources manager
[![GitHub Repo stars](https://img.shields.io/github/stars/goncalossilva/kotlinx-resources)](https://github.com/goncalossilva/kotlinx-resources)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.goncalossilva/resources/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.goncalossilva/resources)
> Kotlin Multiplatform (KMP) plugin and library that add support for reading resources in tests.  
> The plugin and a library work in tandem to provide a unified API across platforms for reading resources from each source set's resources folder.

### 🔧 Utils
[UUID](https://github.com/benasher44/uuid) - UUID generator
[![GitHub Repo stars](https://img.shields.io/github/stars/benasher44/uuid)](https://github.com/benasher44/uuid)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.benasher44/uuid/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.benasher44/uuid)
> Kotlin Multiplatform UUID generator

[Uri KMP](https://github.com/eygraber/uri-kmp) - A library for working with URIs in Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/eygraber/uri-kmp)](https://github.com/eygraber/uri-kmp)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.eygraber/uri-kmp/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.eygraber/uri-kmp)
> A library for working with URIs in Kotlin Multiplatform

[Diglol Encoding](https://github.com/diglol/encoding) - Common encodings for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/diglol/encoding)](https://github.com/diglol/encoding)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.diglol.encoding/encoding/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.diglol.encoding/encoding)
> Diglol Encoding provides Hex/Base16, Base32, Base64 encodings for Kotlin Multiplatform.

[Diglol Id](https://github.com/diglol/id) - A global Id generator for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/diglol/id)](https://github.com/diglol/id)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.diglol.id/id/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.diglol.id/id)
> A global Id generator for Kotlin Multiplatform. It modifies the timestamp to 5 bytes based on Xid.

[ByteBuffer](https://github.com/DitchOoM/buffer) - Kotlin Multiplatform bytebuffer/byte[] wrapper 
[![GitHub Repo stars](https://img.shields.io/github/stars/DitchOoM/buffer)](https://github.com/DitchOoM/buffer)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.ditchoom/buffer/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.ditchoom/buffer)
> A kotlin multiplatform library that allows you to allocate and modify byte[] natively using an API similar to Java's ByteBuffer API.

[zipline](https://github.com/cashapp/zipline) - Run Kotlin/JS libraries in Kotlin/JVM and Kotlin/Native programs 
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/zipline)](https://github.com/cashapp/zipline)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/app.cash.zipline/zipline/badge.svg)](https://maven-badges.herokuapp.com/maven-central/app.cash.zipline/zipline)
> Zipline works by embedding the QuickJS JavaScript engine in your Kotlin/JVM or Kotlin/Native program. It's a small and fast JavaScript engine that's well-suited to embedding in applications.

[Kase64](https://github.com/saschpe/kase64) - Base64 encoder/decoder 
[![GitHub Repo stars](https://img.shields.io/github/stars/saschpe/kase64)](https://github.com/saschpe/kase64)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/de.peilicke.sascha/kase64/badge.svg)](https://maven-badges.herokuapp.com/maven-central/de.peilicke.sascha/kase64)
> Base64 encoder/decoder for Kotlin/Multiplatform. Supports Android, iOS, JavaScript and plain JVM environments. 

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

[kotlin-semver](https://github.com/z4kn4fein/kotlin-semver) - Semantic versioning
[![GitHub Repo stars](https://img.shields.io/github/stars/z4kn4fein/kotlin-semver)](https://github.com/z4kn4fein/kotlin-semver)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.z4kn4fein/semver/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.z4kn4fein/semver)
> Semantic Versioning library for Kotlin Multiplatform.

[Kontrol](https://github.com/chopyourbrain/kontrol) - Debug menu
[![GitHub Repo stars](https://img.shields.io/github/stars/chopyourbrain/kontrol)](https://github.com/chopyourbrain/kontrol)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.github.chopyourbrain/kontrol/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.github.chopyourbrain/kontrol/)
> Kotlin Multiplatform library for creating a debugging menu.

[Korau](https://github.com/korlibs/korau) - Kotlin cORoutines AUdio
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korau)](https://github.com/korlibs/korau)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.korau/korau/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.soywiz.korlibs.korau/korau)
> Pure Kotlin WAV, MP3 and OGG vorbis decoders

[Kim](https://github.com/realAshampoo/kim) - Kotlin Image Metadata
[![GitHub Repo stars](https://img.shields.io/github/stars/realAshampoo/kim)](https://github.com/realAshampoo/kim)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.ashampoo/kim/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.ashampoo/kim)
> Kotlin Multiplatform library for reading and writing image metadata

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
