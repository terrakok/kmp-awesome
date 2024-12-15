# <img src="https://github.com/terrakok/kmp-awesome/raw/master/img/icon.svg" width="30"/> Awesome Kotlin Multiplatform

<img src="https://github.com/terrakok/kmp-awesome/raw/master/img/multiplatform-sharing.svg" align="center" width="400"/>

[![Pull request](https://img.shields.io/badge/PRs-welcome-success?style=flat)](https://github.com/terrakok/kmp-awesome/pulls)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub Repo stars](https://img.shields.io/github/stars/terrakok/kmp-awesome?style=flat)](https://github.com/terrakok/kmp-awesome)
[![Maven Central](https://img.shields.io/maven-central/v/org.jetbrains.kotlin/kotlin-maven-plugin.svg)](https://central.sonatype.com/search?q=g%3Aorg.jetbrains.kotlin)

Kotlin Multiplatform technology simplifies the development of cross-platform projects.
It reduces time spent writing and maintaining the same code for different platforms while retaining the flexibility and benefits of native programming.

**This list contains libraries which support iOS and Android targets in first place.**

## Resources
🖼 [Website](https://www.jetbrains.com/kotlin-multiplatform/)  
🚀 [KMP Library Wizard](https://terrakok.github.io/kmp-web-wizard/)  
🍏 [Compose Multiplatform App Wizard](https://terrakok.github.io/Compose-Multiplatform-Wizard/)  
📋 [Documentation](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html)  
❤️ [Kotlin -> Swift Interopedia](https://github.com/kotlin-hands-on/kotlin-swift-interopedia)  
📜 [Blog](https://blog.jetbrains.com/kotlin/category/multiplatform/)  
📺 [YouTube](https://www.youtube.com/playlist?list=PLlFc5cFwUnmy_oVc9YQzjasSNoAk4hk_C)  
🤩 [Samples](https://kotlinlang.org/docs/kmm-samples.html)  
🗄 [Jetpack Compose Components](https://m3.material.io/components)  
🗄 [Compose Material 3 Gallery](https://terrakok.github.io/compose-material-3-gallery/)  
🎨 [Material Theme Builder](https://materialkolor.com)  
📚 [Kotlin Multiplatform by Tutorials](https://www.kodeco.com/books/kotlin-multiplatform-by-tutorials)  
📚 [Simplifying Application Development with Kotlin Multiplatform Mobile](https://www.amazon.com/Simplifying-Application-Development-Kotlin-Multiplatform/dp/1801812586)  

## Contents
<table>
  <tr>
    <td><a href="https://github.com/terrakok/kmp-awesome#tooling">🛠 Tooling</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-log">📋 Log</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-network">🌎 Network</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmp-awesome#-storage">📦 Storage</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-device">📱 Device</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-dependency-injection">💉 Dependency Injection</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmp-awesome#-architecture">🏗 Architecture</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-analytics">🔍 Analytics</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-test">🩺 Test</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmp-awesome#-crypto">🔑 Crypto</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-file">📁 File</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-language-extensions">🚀 Language extensions</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmp-awesome#-serializer">🗃 Serializer</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-date-time">⏰ Date-Time</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-asynchronous">➿ Asynchronous</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmp-awesome#-compose-ui">🍎 Compose UI</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-graphics">🎨 Graphics</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-service-sdk">🧩 Service SDK</a></td>
  </tr>
  <tr>
    <td><a href="https://github.com/terrakok/kmp-awesome#-arithmetic">🧮 Arithmetic</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-resources">🛢 Resources</a></td>
    <td><a href="https://github.com/terrakok/kmp-awesome#-utils">🔧 Utils</a></td>
  </tr>
</table>

### 🛠 Tooling

[Kotlin Multiplatform Mobile plugin](https://plugins.jetbrains.com/plugin/14936-kotlin-multiplatform-mobile) for Android Studio
> The Kotlin Multiplatform Mobile (KMM) plugin helps you develop applications that work on both Android and iOS.

[CocoaPods](https://kotlinlang.org/docs/native-cocoapods.html) integration
> Kotlin/Native provides integration with the CocoaPods dependency manager. You can add dependencies on Pod libraries as well as use a multiplatform project with native targets as a CocoaPods dependency (Kotlin Pod).

[Amper](https://github.com/JetBrains/amper) new experimental way for project configuration
[![GitHub Repo stars](https://img.shields.io/github/stars/JetBrains/amper?style=flat)](https://github.com/JetBrains/amper)
> Improving developer experience while configuring project setup. Kotlin multiplatform support is out-of-the-box. Project now has experimental status.

[Swift Package](https://github.com/PaGr0m/kotlin-spm-plugin) integration 
[![GitHub Repo stars](https://img.shields.io/github/stars/PaGr0m/kotlin-spm-plugin?style=flat)](https://github.com/PaGr0m/kotlin-spm-plugin)
> This gradle plugin provides two-way interoperability between Kotlin dependencies and Kotlin-based Swift Package Multiplatform.

[Carthage](https://github.com/wireapp/carthage-gradle-plugin) integration 
[![GitHub Repo stars](https://img.shields.io/github/stars/wireapp/carthage-gradle-plugin?style=flat)](https://github.com/wireapp/carthage-gradle-plugin)
> Adds support for integrating Carthage dependencies into a KMM project.

[MOKO KSwift](https://github.com/icerockdev/moko-kswift) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-kswift?style=flat)](https://github.com/icerockdev/moko-kswift)
> KSwift it's gradle plugin for generation Swift-friendly API for Kotlin/Native framework.

[SKIE](https://github.com/touchlab/SKIE) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/SKIE?style=flat)](https://github.com/touchlab/SKIE)
> A Swift-friendly API Generator for Kotlin Multiplatform.

[CompleteKotlin](https://github.com/LouisCAD/CompleteKotlin) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/LouisCAD/CompleteKotlin?style=flat)](https://github.com/LouisCAD/CompleteKotlin)
> Gradle Plugin to enable auto-completion and symbol resolution for all Kotlin/Native platforms.

[gradle-buildconfig-plugin](https://github.com/gmazzo/gradle-buildconfig-plugin) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/gmazzo/gradle-buildconfig-plugin?style=flat)](https://github.com/gmazzo/gradle-buildconfig-plugin)
> A plugin for generating BuildConstants for any kind of Gradle projects: Java, Kotlin, Groovy, etc. Designed for KTS scripts. 

[BuildKonfig](https://github.com/yshrsmz/BuildKonfig) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/yshrsmz/BuildKonfig?style=flat)](https://github.com/yshrsmz/BuildKonfig)
> BuildConfig for Kotlin Multiplatform Project

[Kotlin Native Xcode Support](https://github.com/touchlab/xcode-kotlin) 
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/xcode-kotlin?style=flat)](https://github.com/touchlab/xcode-kotlin)
> Plugin to facilitate debugging iOS applications using Kotlin Native in Xcode. Defines Kotlin files as source code, with basic highlighting. Allows you to set breakpoints and includes llvm support to view data in the debug window. Xcode does not officially support custom language definitions, but they also don't explicitly block them.

[Dokka](https://github.com/Kotlin/dokka) documentation generation tool 
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/dokka?style=flat)](https://github.com/Kotlin/dokka)
> Dokka is a documentation engine for Kotlin, performing the same function as javadoc for Java. Just like Kotlin itself, Dokka fully supports mixed-language Java/Kotlin projects. It understands standard Javadoc comments in Java files and KDoc comments in Kotlin files, and can generate documentation in multiple formats including standard Javadoc, HTML and Markdown.

[KDoctor](https://github.com/Kotlin/kdoctor) command-line tool 
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kdoctor?style=flat)](https://github.com/Kotlin/kdoctor)
> KDoctor is a command-line tool that helps to set up the environment for Kotlin Multiplatform Mobile app development. It ensures that all required components are properly installed and ready for use. If something is missed or not configured Kdoctor highlights the problem and suggests how to fix the problem.

[Swift Klib](https://github.com/ttypic/swift-klib-plugin) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/ttypic/swift-klib-plugin?style=flat)](https://github.com/ttypic/swift-klib-plugin)
> Gradle Plugin to build Swift code as part of your Kotlin Multiplatform project. With this plugin, you can access Swift-only iOS libraries, such as CryptoKit and experiment with Swift to Kotlin interoperability.

[parcelize-darwin](https://github.com/arkivanov/parcelize-darwin) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/parcelize-darwin?style=flat)](https://github.com/arkivanov/parcelize-darwin)
> Kotlin/Native compiler plugin that generates Parcelable implementations for Darwin (Apple) targets. Allows writing Parcelable classes for all Darwin targets, similary to the Android's kotlin-parcelize plugin. Can be also used together with the kotlin-parcelize plugin to write Parcelable classes in the commonMain source set.

[AboutLibraries](https://github.com/mikepenz/AboutLibraries) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/mikepenz/AboutLibraries?style=flat)](https://github.com/mikepenz/AboutLibraries)
> Collects all dependencies and licenses of gradle projects (Kotlin Multiplatform) and provides an easy to integrate Attribution / Open Source library UI to integrate in Compose / Android targets.

[Power-Assert](https://kotlinlang.org/docs/power-assert.html) gradle plugin 
[![GitHub Repo stars](https://img.shields.io/github/stars/JetBrains/kotlin?style=flat)](https://github.com/JetBrains/kotlin/tree/master/plugins/power-assert)
> The Kotlin Power-assert compiler plugin improves the debugging experience by providing detailed failure messages with contextual information. It simplifies the process of writing tests by automatically generating intermediate values in failure messages. It helps you understand why a test failed without needing complex assertion libraries.

[Valkyrie](https://github.com/ComposeGears/Valkyrie) IntelliJ IDEA / Android Studio plugin 
![GitHub Repo stars](https://img.shields.io/github/stars/ComposeGears/Valkyrie?style=flat)
> Convert SVG/XML icons into Compose ImageVector with convenient code formatting. Plugin provides ability to one-click conversion or icon pack creation with batch export. 

## Libraries

### 📋 Log
[Napier](https://github.com/AAkira/Napier) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/AAkira/Napier?style=flat)](https://github.com/AAkira/Napier)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.aakira/napier)](https://central.sonatype.com/artifact/io.github.aakira/napier)
> Napier is a logger library for Kotlin Multiplatform. It supports for the Android, Darwin(iOS, macOS, watchOS, tvOS), JVM, JavaScript. Logs written in common module are displayed on logger viewer of each platform.

[Kermit](https://github.com/touchlab/Kermit) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/Kermit?style=flat)](https://github.com/touchlab/Kermit)
[![Maven Central](https://img.shields.io/maven-central/v/co.touchlab/kermit)](https://central.sonatype.com/artifact/co.touchlab/kermit)
> Kermit is a Kotlin Multiplatform logging utility with composable log outputs. The library provides prebuilt loggers for outputting to platform logging tools such as Logcat and NSLog.

[KmLogging](https://github.com/LighthouseGames/KmLogging) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/LighthouseGames/KmLogging?style=flat)](https://github.com/LighthouseGames/KmLogging)
[![Maven Central](https://img.shields.io/maven-central/v/org.lighthousegames/logging)](https://central.sonatype.com/artifact/org.lighthousegames/logging)
> Kotlin multiplatform logging. High performance, composable and simple to use. 

[kotlin-logging](https://github.com/oshai/kotlin-logging) - logger
[![GitHub Repo stars](https://img.shields.io/github/stars/oshai/kotlin-logging?style=flat)](https://github.com/oshai/kotlin-logging)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.oshai/kotlin-logging)](https://central.sonatype.com/artifact/io.github.oshai/kotlin-logging)
> Lightweight Multiplatform logging framework for Kotlin, written in Pure Kotlin. A convenient and performant logging facade.


### 🌎 Network
[Ktor](https://github.com/ktorio/ktor) - http client
[![GitHub Repo stars](https://img.shields.io/github/stars/ktorio/ktor?style=flat)](https://github.com/ktorio/ktor)
[![Maven Central](https://img.shields.io/maven-central/v/io.ktor/ktor)](https://central.sonatype.com/artifact/io.ktor)
> Ktor includes a multiplatform asynchronous HTTP client, which allows you to make requests and handle responses, extend its functionality with plugins (formerly known as features), such as authentication, JSON serialization, and so on. 

[Ktorfit](https://github.com/Foso/Ktorfit) - Retrofit for Kotlin Multiplatform on KTS
[![GitHub Repo stars](https://img.shields.io/github/stars/Foso/Ktorfit?style=flat)](https://github.com/Foso/Ktorfit)
[![Maven Central](https://img.shields.io/maven-central/v/de.jensklingenberg.ktorfit/ktorfit-lib)](https://central.sonatype.com/artifact/de.jensklingenberg.ktorfit/ktorfit-lib)
> HTTP client / Kotlin Symbol Processor for Kotlin Multiplatform (Android,Js, Jvm , Native, iOS) using KSP and Ktor clients inspired by Retrofit https://foso.github.io/Ktorfit

[Apollo GraphQL](https://github.com/apollographql/apollo-android) - GraphQL client
[![GitHub Repo stars](https://img.shields.io/github/stars/apollographql/apollo-android?style=flat)](https://github.com/apollographql/apollo-android)
[![Maven Central](https://img.shields.io/maven-central/v/com.apollographql.apollo3/apollo-runtime)](https://central.sonatype.com/artifact/com.apollographql.apollo3/apollo-runtime)
> A strongly-typed, caching GraphQL client for the JVM, Android, and Kotlin multiplatform.

[kgql](https://github.com/yshrsmz/kgql) - GraphQL Document wrapper generator
[![GitHub Repo stars](https://img.shields.io/github/stars/yshrsmz/kgql?style=flat)](https://github.com/yshrsmz/kgql)
[![Maven Central](https://img.shields.io/maven-central/v/com.codingfeline.kgql/core)](https://central.sonatype.com/artifact/com.codingfeline.kgql/core)
> GraphQL Document wrapper generator for Kotlin Multiplatform Project. Currently, available for JVM/Android/iOS

[WebRTC KMP](https://github.com/shepeliev/webrtc-kmp) - WebRTC client
[![GitHub Repo stars](https://img.shields.io/github/stars/shepeliev/webrtc-kmp?style=flat)](https://github.com/shepeliev/webrtc-kmp)
[![Maven Central](https://img.shields.io/maven-central/v/com.shepeliev/webrtc-kmp)](https://central.sonatype.com/artifact/com.shepeliev/webrtc-kmp)
> WebRTC Kotlin Multiplatform SDK

[Krossbow](https://github.com/joffrey-bion/krossbow) - WebSocket client
[![GitHub Repo stars](https://img.shields.io/github/stars/joffrey-bion/krossbow?style=flat)](https://github.com/joffrey-bion/krossbow)
[![Maven Central](https://img.shields.io/maven-central/v/org.hildan.krossbow/krossbow-stomp-core)](https://central.sonatype.com/artifact/org.hildan.krossbow/krossbow-stomp-core)
> A coroutine-based Kotlin multi-platform WebSocket client and STOMP 1.2 client over web sockets.

[MOKO SocketIo](https://github.com/icerockdev/moko-socket-io) - Socket.IO implementation
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-socket-io?style=flat)](https://github.com/icerockdev/moko-socket-io)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/socket-io)](https://central.sonatype.com/artifact/dev.icerock.moko/socket-io)
> This is a Kotlin Multiplatform library that provides real-time, event-based communication for iOS and Android.

[rsocket](https://github.com/rsocket/rsocket-kotlin) - RSocket Kotlin multi-platform implementation
[![GitHub Repo stars](https://img.shields.io/github/stars/rsocket/rsocket-kotlin?style=flat)](https://github.com/rsocket/rsocket-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/io.rsocket.kotlin/rsocket-core)](https://central.sonatype.com/artifact/io.rsocket.kotlin/rsocket-core)
> RSocket is a binary protocol for use on byte stream transports such as TCP, WebSockets and Aeron.

### 📦 Storage
[Multiplatform-Settings](https://github.com/russhwolf/multiplatform-settings) - Key-Value preferences
[![GitHub Repo stars](https://img.shields.io/github/stars/russhwolf/multiplatform-settings?style=flat)](https://github.com/russhwolf/multiplatform-settings)
[![Maven Central](https://img.shields.io/maven-central/v/com.russhwolf/multiplatform-settings)](https://central.sonatype.com/artifact/com.russhwolf/multiplatform-settings)
> This is a Kotlin library for Multiplatform apps, so that common code can persist key-value data

[KVault](https://github.com/Liftric/KVault) - secure key-value storage
[![GitHub Repo stars](https://img.shields.io/github/stars/Liftric/KVault?style=flat)](https://github.com/Liftric/KVault)
[![Maven Central](https://img.shields.io/maven-central/v/com.liftric/kvault)](https://central.sonatype.com/artifact/com.liftric/kvault)
> It acts as an iOS Keychain wrapper and implements encrypted SharedPreferences for Android.

[SQLDelight](https://github.com/cashapp/sqldelight) - SQLite database
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/sqldelight?style=flat)](https://github.com/cashapp/sqldelight)
[![Maven Central](https://img.shields.io/maven-central/v/com.squareup.sqldelight/com.squareup.sqldelight.gradle.plugin)](https://central.sonatype.com/artifact/com.squareup.sqldelight/com.squareup.sqldelight.gradle.plugin)
> SQLDelight generates typesafe kotlin APIs from your SQL statements. It verifies your schema, statements, and migrations at compile-time and provides IDE features like autocomplete and refactoring which make writing and maintaining SQL simple.

[Realm](https://github.com/realm/realm-kotlin) - NoSQL database
[![GitHub Repo stars](https://img.shields.io/github/stars/realm/realm-kotlin?style=flat)](https://github.com/realm/realm-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/io.realm.kotlin/gradle-plugin)](https://central.sonatype.com/artifact/io.realm.kotlin/gradle-plugin)
> Realm is a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the Kotlin SDK for Realm, which runs on Kotlin Multiplatform and Android.

[Kotbase](https://github.com/jeffdgr8/kotbase) - NoSQL JSON document database
[![GitHub Repo stars](https://img.shields.io/github/stars/jeffdgr8/kotbase?style=flat)](https://github.com/jeffdgr8/kotbase)
[![Maven Central](https://img.shields.io/maven-central/v/dev.kotbase/couchbase-lite)](https://central.sonatype.com/namespace/dev.kotbase)
> Kotlin Multiplatform library for Couchbase Lite—a lightweight, embedded, NoSQL JSON document database—supporting SQL++, key/value, and full-text search queries; observability; binary attachments; and data sync.

[Store 5](https://github.com/MobileNativeFoundation/Store) - Kotlin Library for Async Data Loading and Caching 
[![GitHub Repo stars](https://img.shields.io/github/stars/MobileNativeFoundation/Store?style=flat)](https://github.com/MobileNativeFoundation/Store)
[![Maven Central](https://img.shields.io/maven-central/v/org.mobilenativefoundation.store/store5)](https://central.sonatype.com/artifact/org.mobilenativefoundation.store/store5)
> A Store is responsible for managing a particular data request. When you create an implementation of a Store, you provide it with a Fetcher, a function that defines how data will be fetched over network. You can also define how your Store will cache data in-memory and on-disk.

[Flower](https://github.com/hadiyarajesh/flower) - Flower simplifies networking and database caching on Android/Multiplatform. 
[![GitHub Repo stars](https://img.shields.io/github/stars/hadiyarajesh/flower?style=flat)](https://github.com/hadiyarajesh/flower)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.hadiyarajesh.flower-core/flower-core)](https://central.sonatype.com/artifact/io.github.hadiyarajesh.flower-core/flower-core)
> Flower is a Kotlin multi-platform library that makes networking and database caching easy. It enables developers to fetch network resources and use them as is OR combine them with local database at single place with fault-tolerant architecture.

[cache4k](https://github.com/ReactiveCircus/cache4k) - In-memory Cache
[![GitHub Repo stars](https://img.shields.io/github/stars/ReactiveCircus/cache4k?style=flat)](https://github.com/ReactiveCircus/cache4k)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.reactivecircus.cache4k/cache4k)](https://central.sonatype.com/artifact/io.github.reactivecircus.cache4k/cache4k)
> Provides a simple in-memory key-value cache for Kotlin Multiplatform, with support for time-based (expiration) and size-based evictions.

[SQLiter](https://github.com/touchlab/SQLiter) - SQLite driver
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/SQLiter?style=flat)](https://github.com/touchlab/SQLiter)
[![Maven Central](https://img.shields.io/maven-central/v/co.touchlab/sqliter)](https://central.sonatype.com/artifact/co.touchlab/sqliter)
> SQLiter is a SQLite driver for Kotlin Native, currently Apple and Windows variants. It is designed to serve as a driver to power user-friendly libraries rather than something to use directly. Currently SQLiter powers the SQLDelight library on native clients.

[SQLlin](https://github.com/ctripcorp/SQLlin) - Low-level API for SQLite in Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/ctripcorp/SQLlin?style=flat)](https://github.com/ctripcorp/SQLlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.ctrip.kotlin/sqllin-driver)](https://central.sonatype.com/artifact/com.ctrip.kotlin/sqllin-driver)
> SQLlin is a Kotlin Multiplatform SQLite library that based on DSL and KSP. You can write SQL statements with your Kotlin code and these can be verified by Kotlin compiler.

[KStore](https://github.com/xxfast/KStore) - File-based object storage
[![GitHub Repo stars](https://img.shields.io/github/stars/xxfast/KStore?style=flat)](https://github.com/xxfast/KStore)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.xxfast/kstore)](https://central.sonatype.com/artifact/io.github.xxfast/kstore/)
> A Kotlin multiplatform library that assists in saving and restoring objects to and from disk

[Universal-Cache](https://github.com/andrew0000/universal-cache) - Kotlin caching and request sharing
[![GitHub Repo stars](https://img.shields.io/github/stars/andrew0000/universal-cache?style=flat)](https://github.com/andrew0000/universal-cache)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.andrew0000/universal-cache)](https://central.sonatype.com/artifact/io.github.andrew0000/universal-cache/)
> Kotlin Flow caching and request sharing. Main idea: don't request data more times than it's needed.

[kotlin-cacheable](https://github.com/mori-atsushi/kotlin-cacheable) - Annotation-based caching library
[![GitHub Repo stars](https://img.shields.io/github/stars/mori-atsushi/kotlin-cacheable?style=flat)](https://github.com/mori-atsushi/kotlin-cacheable)
[![Maven Central](https://img.shields.io/maven-central/v/com.moriatsushi.cacheable/cacheable-core)](https://central.sonatype.com/artifact/com.moriatsushi.cacheable/cacheable-core)
> Kotlin Cacheable is an annotation-based caching library for Kotlin Multiplatform.

### 📱 Device
[MOKO Permissions](https://github.com/icerockdev/moko-permissions) - System permissions manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-permissions?style=flat)](https://github.com/icerockdev/moko-permissions)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/permissions)](https://central.sonatype.com/artifact/dev.icerock.moko/permissions)
> Kotlin Multiplatform library for providing runtime permissions on iOS & Android

[abc-kmm-notifications](https://github.com/line/abc-kmm-notifications) - Notification Manager
[![GitHub Repo stars](https://img.shields.io/github/stars/line/abc-kmm-notifications?style=flat)](https://github.com/line/abc-kmm-notifications)
[![Maven Central](https://img.shields.io/maven-central/v/com.linecorp.abc/kmm-notifications)](https://central.sonatype.com/artifact/com.linecorp.abc/kmm-notifications)
> Remote Notification Manager for Kotlin Multiplatform Mobile

[abc-kmm-Location](https://github.com/line/abc-kmm-location) - Location manager
[![GitHub Repo stars](https://img.shields.io/github/stars/line/abc-kmm-location?style=flat)](https://github.com/line/abc-kmm-location)
[![Maven Central](https://img.shields.io/maven-central/v/com.linecorp.abc/kmm-location)](https://central.sonatype.com/artifact/com.linecorp.abc/kmm-location)
> Location Service Manager for Kotlin Multiplatform Mobile iOS and android

[MOKO Geo](https://github.com/icerockdev/moko-geo) - Location manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-geo?style=flat)](https://github.com/icerockdev/moko-geo)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/geo)](https://central.sonatype.com/artifact/dev.icerock.moko/geo)
> Geolocation access for mobile (android & ios) Kotlin Multiplatform development

[MOKO Biometry](https://github.com/icerockdev/moko-biometry) - System biometry manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-biometry?style=flat)](https://github.com/icerockdev/moko-biometry)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/biometry)](https://central.sonatype.com/artifact/dev.icerock.moko/biometry)
> This is a Kotlin Multiplatform library that provides authentication by FaceId and TouchId (Fingerprint)

[MOKO Media](https://github.com/icerockdev/moko-media) - System media manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-media?style=flat)](https://github.com/icerockdev/moko-media)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/media)](https://central.sonatype.com/artifact/dev.icerock.moko/media)
> This is a Kotlin Multiplatform library that provides media picking in common code (photo/video) and video player controls.

[MOKO Maps](https://github.com/icerockdev/moko-maps) - Google/Mapbox maps manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-maps?style=flat)](https://github.com/icerockdev/moko-maps)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/maps)](https://central.sonatype.com/artifact/dev.icerock.moko/maps)
> This is a Kotlin Multiplatform library that provides controls of maps to common code.

[Kable](https://github.com/juullabs/kable) - Coroutines-powered API for interacting with Bluetooth Low Energy devices.
[![GitHub Repo stars](https://img.shields.io/github/stars/juullabs/kable?style=flat)](https://github.com/juullabs/kable)
[![Maven Central](https://img.shields.io/maven-central/v/com.juul.kable/kable-core)](https://central.sonatype.com/artifact/com.juul.kable/kable-core/)
>Kotlin Asynchronous Bluetooth Low Energy provides a simple Coroutines-powered API for interacting with Bluetooth Low Energy devices.

[Blue-Falcon](https://github.com/Reedyuk/blue-falcon) - A Bluetooth kotlin multiplatform library for iOS and Android
[![GitHub Repo stars](https://img.shields.io/github/stars/Reedyuk/blue-falcon?style=flat)](https://github.com/Reedyuk/blue-falcon)
[![Maven Central](https://img.shields.io/maven-central/v/dev.bluefalcon/blue-falcon-rpi)](https://central.sonatype.com/artifact/dev.bluefalcon/blue-falcon-rpi)
>A Bluetooth "Cross Platform" Kotlin Multiplatform library for iOS, Android, MacOS, Raspberry Pi and Javascript.
Bluetooth in general has the same functionality for all platforms, e.g. connect to device, fetch services, fetch characteristics.

[Connectivity status](https://github.com/ln-12/multiplatform-connectivity-status) - Multiplatform connectivity status
[![GitHub Repo stars](https://img.shields.io/github/stars/ln-12/multiplatform-connectivity-status?style=flat)](https://github.com/rsocket/rsocket-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.ln-12/multiplatform-connectivity-status)](https://central.sonatype.com/artifact/com.github.ln-12/multiplatform-connectivity-status)
> This Kotlin multiplatform mobile utility library allows monitoring the internet connection status of the device. You can use it from shared code as well as directly from Android or iOS code.

[Kontrol](https://github.com/chopyourbrain/kontrol) - Debug menu
[![GitHub Repo stars](https://img.shields.io/github/stars/chopyourbrain/kontrol?style=flat)](https://github.com/chopyourbrain/kontrol)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.chopyourbrain/kontrol)](https://central.sonatype.com/artifact/io.github.chopyourbrain/kontrol)
> A Kotlin Multiplatform library for creating debug menu.

[KMPNotifier](https://github.com/mirzemehdi/KMPNotifier) - Firebase Push Notification library for iOS and Android
[![GitHub Repo stars](https://img.shields.io/github/stars/mirzemehdi/KMPNotifier?style=flat)](https://github.com/mirzemehdi/KMPNotifier)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.mirzemehdi/kmpnotifier)](https://central.sonatype.com/artifact/io.github.mirzemehdi/kmpnotifier)
> Kotlin Multiplatform Push Notification Library using Firebase for iOS and Android.

[Compass](https://github.com/jordond/compass) - 🧭 Location toolkit for geocoding, geolocation, and autocomplete
[![GitHub Repo stars](https://img.shields.io/github/stars/jordond/compass?style=flat)](https://github.com/jordond/compass)
[![Maven Central](https://img.shields.io/maven-central/v/dev.jordond.compass/core)](https://central.sonatype.com/namespace/dev.jordond.compass)
> Compass is a Kotlin Multiplatform library location toolkit. It provides a set of tools for working with location data, including geocoding, reverse geocoding, and more.

[Connectivity](https://github.com/jordond/connectivity) - Retrieve and monitor internet connectivity
[![GitHub Repo stars](https://img.shields.io/github/stars/jordond/connectivity?style=flat)](https://github.com/jordond/connectivity)
[![Maven Central](https://img.shields.io/maven-central/v/dev.jordond.connectivity/connectivity-core)](https://central.sonatype.com/namespace/dev.jordond.connectivity)
> Connectivity provides network monitoring capabilities for multiplatform projects. It can monitor network connectivity using native APIs on Android and Apple devices, or by making HTTP requests to specified hosts.

### 💉 Dependency Injection
[Koin](https://github.com/InsertKoinIO/koin) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/InsertKoinIO/koin?style=flat)](https://github.com/InsertKoinIO/koin)
[![Maven Central](https://img.shields.io/maven-central/v/io.insert-koin/koin-core)](https://central.sonatype.com/artifact/io.insert-koin/koin-core)
> A pragmatic lightweight dependency injection framework for Kotlin developers. Koin is a DSL, a light container and a pragmatic API

[Kodein](https://github.com/kosi-libs/Kodein) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/kosi-libs/kodein?style=flat)](https://github.com/kosi-libs/kodein)
[![Maven Central](https://img.shields.io/maven-central/v/org.kodein.di/kodein-di)](https://mvnrepository.com/artifact/org.kodein.di/kodein-di)
> Kodein is a very simple and yet very useful dependency retrieval container.

[kotlin-inject](https://github.com/evant/kotlin-inject) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/evant/kotlin-inject?style=flat)](https://github.com/evant/kotlin-inject)
[![Maven Central](https://img.shields.io/maven-central/v/me.tatarka.inject/kotlin-inject-runtime)](https://central.sonatype.com/artifact/me.tatarka.inject/kotlin-inject-runtime)
> A compile-time dependency injection library for kotlin.

[Koject](https://github.com/mori-atsushi/koject) - KSP DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/mori-atsushi/koject?style=flat)](https://github.com/mori-atsushi/koject)
[![Maven Central](https://img.shields.io/maven-central/v/com.moriatsushi.koject/koject-core)](https://central.sonatype.com/artifact/com.moriatsushi.koject/koject-core)
> Koject is a DI Container Library for Kolin Multiplatform using KSP.

[DI.kt](https://github.com/sergeshustoff/dikt) - DI for kotlin multiplatform 
[![GitHub Repo stars](https://img.shields.io/github/stars/sergeshustoff/dikt?style=flat)](https://github.com/sergeshustoff/dikt)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.sergeshustoff.dikt/dikt-compiler-plugin)](https://central.sonatype.com/artifact/io.github.sergeshustoff.dikt/dikt-compiler-plugin)
> Simple DI with compile-time dependency graph validation for kotlin multiplatform. It uses IR to create method's bodies with dependency injection.

[PopKorn](https://github.com/corbella83/PopKorn) - DI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/corbella83/PopKorn?style=flat)](https://github.com/corbella83/PopKorn)
[![Maven Central](https://img.shields.io/maven-central/v/cc.popkorn/popkorn)](https://central.sonatype.com/artifact/cc.popkorn/popkorn)
> PopKorn is a simple, powerful and lightweight Kotlin Multiplatform Dependency Injector. It doesn't need any modules or components, just use it without writing a single extra file! It supports AND, IOS, JVM, JS and NATIVE.

### 🏗 Architecture
[KmpEssentials](https://github.com/TheArchitect123/KmpEssentials)
[![GitHub Repo stars](https://img.shields.io/github/stars/thearchitect123/kmpEssentials?style=flat)](https://github.com/TheArchitect123/KmpEssentials)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.thearchitect123/kmpEssentials)](https://github.com/TheArchitect123/KmpEssentials)
 > **KmpEssentials** is a library that contains apis (40+ Modules) to accelerate your development. Everything from managing the Battery, File System, getting Package information, or taking Photos. Supports iOS, Android & AppleWatch

[Evas](https://github.com/sellmair/evas) - Events and States for Kotlin
[![GitHub Repo stars](https://img.shields.io/github/stars/sellmair/evas?style=flat)](https://github.com/sellmair/evas)
[![Maven Central](https://img.shields.io/maven-central/v/io.sellmair/evas)](https://central.sonatype.com/artifact/io.sellmair/evas)
> Evas is a library providing  
> **Events:** A performant, scalable and most importantly scoped Event-Channel integrated with coroutines. **States:** A pragmatic state container.

[MVI Kotlin](https://github.com/arkivanov/MVIKotlin) - MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/MVIKotlin?style=flat)](https://github.com/arkivanov/MVIKotlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.arkivanov.mvikotlin/mvikotlin)](https://central.sonatype.com/artifact/com.arkivanov.mvikotlin/mvikotlin)
> MVIKotlin is a Kotlin Multiplatform framework that provides a way of (not only) writing shared code using MVI pattern. It also includes powerful debug tools like logging and time travel.

[Orbit MVI](https://github.com/orbit-mvi/orbit-mvi) - MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/orbit-mvi/orbit-mvi?style=flat)](https://github.com/orbit-mvi/orbit-mvi)
[![Maven Central](https://img.shields.io/maven-central/v/org.orbit-mvi/orbit-core)](https://central.sonatype.com/artifact/org.orbit-mvi/orbit-core)
> Orbit is a Redux/MVI-like library for KMM, targetting Android and iOS.

[FlowMVI](https://github.com/respawn-app/FlowMVI) - Plugin-based MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/respawn-app/FlowMVI?style=flat)](https://github.com/respawn-app/FlowMVI)
[![Maven Central](https://img.shields.io/maven-central/v/pro.respawn.flowmvi/core)](https://central.sonatype.com/namespace/pro.respawn.flowmvi)
> FlowMVI is a KMP MVI library based on coroutines with a rich DSL and a powerful plugin system.

[KMP-ObservableViewModel](https://github.com/rickclephas/KMP-ObservableViewModel) - KMP ViewModels
[![GitHub Repo stars](https://img.shields.io/github/stars/rickclephas/KMP-ObservableViewModel?style=flat)](https://github.com/rickclephas/KMP-ObservableViewModel)
[![Maven Central](https://img.shields.io/maven-central/v/com.rickclephas.kmp/kmp-observableviewmodel-core)](https://central.sonatype.com/artifact/com.rickclephas.kmp/kmp-observableviewmodel-core)
> A library (previously known as KMM-ViewModel) that allows you to use AndroidX/Kotlin ViewModels with SwiftUI.

[VisualFSM](https://github.com/Kontur-Mobile/VisualFSM) - FSM-based MVI framework
[![GitHub Repo stars](https://img.shields.io/github/stars/Kontur-Mobile/VisualFSM?style=flat)](https://github.com/Kontur-Mobile/VisualFSM)
[![MavenCentral](https://img.shields.io/maven-central/v/ru.kontur.mobile.visualfsm/visualfsm-core)](https://central.sonatype.com/artifact/ru.kontur.mobile.visualfsm/visualfsm-core)
> VisualFSM is a Kotlin Multiplatform library for implements an FSM-based (Finite-state machine) MVI pattern and a set of tools for visualization and analysis of FSM's diagram of states.

[Redux Kotlin](https://github.com/reduxkotlin/redux-kotlin) - Redux framework
[![GitHub Repo stars](https://img.shields.io/github/stars/reduxkotlin/redux-kotlin?style=flat)](https://github.com/reduxkotlin/redux-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/org.reduxkotlin/redux-kotlin-threadsafe)](https://central.sonatype.com/artifact/org.reduxkotlin/redux-kotlin-threadsafe)
> Redux implementation for Kotlin (supports multiplatform JVM, native, JS, WASM)

[FlowRedux](https://github.com/freeletics/FlowRedux) - Statemachine library with nice DSL
[![GitHub Repo stars](https://img.shields.io/github/stars/freeletics/FlowRedux?style=flat)](https://github.com/freeletics/FlowRedux)
[![Maven Central](https://img.shields.io/maven-central/v/com.freeletics.flowredux/flowredux)](https://central.sonatype.com/artifact/com.freeletics.flowredux/flowredux)
> Building async. running Kotlin Multiplatform state machine made easy with a DSL and coroutines.

[Mobius.kt](https://github.com/DrewCarlson/mobius.kt) - Mobius Framework
[![GitHub Repo stars](https://img.shields.io/github/stars/DrewCarlson/mobius.kt?style=flat)](https://github.com/DrewCarlson/mobius.kt)
[![Maven Central](https://img.shields.io/maven-central/v/org.drewcarlson/mobiuskt-core)](https://central.sonatype.com/artifact/org.drewcarlson/mobiuskt-core)
> Kotlin Multiplatform [Mobius](https://github.com/spotify/mobius) implementation.

[MOKO MVVM](https://github.com/icerockdev/moko-mvvm) - MVVM framework
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-mvvm?style=flat)](https://github.com/icerockdev/moko-mvvm)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/mvvm)](https://central.sonatype.com/artifact/dev.icerock.moko/mvvm)
> This is a Kotlin Multiplatform library that provides architecture components of Model-View-ViewModel for UI applications. Components are lifecycle-aware on Android.

[Oolong](https://github.com/oolong-kt/oolong) - MVU for Kotlin Multiplatform 
[![GitHub Repo stars](https://img.shields.io/github/stars/oolong-kt/oolong?style=flat)](https://github.com/oolong-kt/oolong)
[![Maven Central](https://img.shields.io/maven-central/v/org.oolong-kt/oolong)](https://central.sonatype.com/artifact/org.oolong-kt/oolong)
> Oolong is an [Elm](https://guide.elm-lang.org/architecture) inspired Model-View-Update (MVU) implementation for Kotlin multiplatform.

[Premo](https://github.com/dmdevgo/Premo) — Presentation Model (aka View Model) and Navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/dmdevgo/premo?style=flat)](https://github.com/dmdevgo/Premo)
[![Maven Central](https://img.shields.io/maven-central/v/me.dmdev.premo/premo)](https://central.sonatype.com/artifact/me.dmdev.premo/premo)
> Premo is a Kotlin Multiplatform library that helps to implement the Presentation Layer and share it on iOS, Android, Desktop and Web. Focus on writing logic instead of solving common and boring UI related issues: lifecycle, persistence, navigation, etc.

[Decompose](https://github.com/arkivanov/Decompose) - componentization and navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/Decompose?style=flat)](https://github.com/arkivanov/Decompose)
[![Maven Central](https://img.shields.io/maven-central/v/com.arkivanov.decompose/decompose)](https://central.sonatype.com/artifact/com.arkivanov.decompose/decompose)
> Decompose is a Kotlin Multiplatform library for breaking down your code into lifecycle-aware business logic components (aka BLoC), with routing functionality and pluggable UI (Jetpack Compose, Android Views, SwiftUI, JS React, etc.)

[Decompose-Router](https://github.com/xxfast/Decompose-Router) - navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/xxfast/Decompose-Router?style=flat)](https://github.com/xxfast/Decompose-Router)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.xxfast/decompose-router)](https://central.sonatype.com/artifact/io.github.xxfast/decompose-router/)
> A Compose-multiplatform navigation library that leverage Decompose to create an API inspired by Conductor

[Ballast](https://github.com/copper-leaf/ballast) - State Management framework
[![GitHub Repo stars](https://img.shields.io/github/stars/copper-leaf/ballast?style=flat)](https://github.com/copper-leaf/ballast)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.copper-leaf/ballast-core)](https://central.sonatype.com/artifact/io.github.copper-leaf/ballast-core)
> Opinionated Application State Management framework for Kotlin Multiplatform

[Essenty/Lifecycle](https://github.com/arkivanov/Essenty#lifecyle) - lifecycle handling in the Kotlin Multiplatform common code 
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/Essenty?style=flat)](https://github.com/arkivanov/Essenty)
[![Maven Central](https://img.shields.io/maven-central/v/com.arkivanov.essenty/lifecycle)](https://central.sonatype.com/artifact/com.arkivanov.essenty/lifecycle)
> Essenty provides the Lifecycle API to help with lifecycle handling in the common code. It is very similar to Android Activity lifecycle.

[multiplatform-paging](https://github.com/cashapp/multiplatform-paging) - Pagination library for KMM by `Cash App`
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/multiplatform-paging?style=flat)](https://github.com/cashapp/multiplatform-paging)
[![Maven Central](https://img.shields.io/maven-central/v/app.cash.paging/paging-common)](https://central.sonatype.com/artifact/app.cash.paging/paging-common)
> A Kotlin Multiplatform library for pagination with the same API as AndroidX Paging

[multiplatform-paging](https://github.com/kuuuurt/multiplatform-paging) - Pagination library for KMM
[![GitHub Repo stars](https://img.shields.io/github/stars/kuuuurt/multiplatform-paging?style=flat)](https://github.com/kuuuurt/multiplatform-paging)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.kuuuurt/multiplatform-paging)](https://central.sonatype.com/artifact/io.github.kuuuurt/multiplatform-paging)
> A Kotlin Multiplatform library for pagination.

[lazy-pagination-compose](https://github.com/Ahmad-Hamwi/lazy-pagination-compose) - Pagination library for Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/Ahmad-Hamwi/lazy-pagination-compose?style=flat)](https://github.com/Ahmad-Hamwi/lazy-pagination-compose)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.ahmad-hamwi/lazy-pagination-compose)](https://central.sonatype.com/artifact/io.github.ahmad-hamwi/lazy-pagination-compose)
> Intuitive and customizable Compose Multiplatform pagination composables that are built on top of lazy scrollables. 

[kmp-viewmodel](https://github.com/hoc081098/kmp-viewmodel) - Kotlin Multiplatform ViewModel
[![GitHub Repo stars](https://img.shields.io/github/stars/hoc081098/kmp-viewmodel?style=flat)](https://github.com/hoc081098/kmp-viewmodel)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.hoc081098/kmp-viewmodel)](https://central.sonatype.com/artifact/io.github.hoc081098/kmp-viewmodel/)
> A Kotlin Multiplatform library that provides shared MVVM. Supports Android Parcelable, Kotlin Parcelize, AndroidX SavedStateHandle for restoring state after process death.

[Meteor](https://github.com/getspherelabs/meteor-kmp)  - MVI framework with CommonViewModel, CommonStateFlow, UseCase
[![GitHub Repo stars](https://img.shields.io/github/stars/getspherelabs/meteor-kmp?style=flat)](https://github.com/getspherelabs/meteor-kmp)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.behzodhalil/meteor-mvi)](https://central.sonatype.com/artifact/io.github.behzodhalil/meteor-mvi)
>  MVI/Redux framework for Kotlin Multiplatform

[Passage](https://github.com/tweener/passage) Authentication with Firebase (Google, Apple, Email/password).
[![GitHub Repo stars](https://img.shields.io/github/stars/tweener/passage?style=flat)](https://github.com/tweener/passage)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.tweener/passage)](https://central.sonatype.com/artifact/io.github.tweener/passage)
> A Kotlin/Compose Multiplatform library for easy authentication on Android and iOS.

[KStateMachine](https://github.com/nsk90/kstatemachine) - Multiplatform state machine library with coroutines support
[![GitHub Repo stars](https://img.shields.io/github/stars/nsk90/kstatemachine?style=flat)](https://github.com/nsk90/kstatemachine)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.nsk90/kstatemachine)](https://central.sonatype.com/artifact/io.github.nsk90/kstatemachine)
> KStateMachine is a Kotlin DSL library for creating state machines and statecharts.

[Rinku](https://github.com/theolm/Rinku) - Deep Link Handling for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/theolm/Rinku?style=flat)](https://github.com/theolm/Rinku)
[![Maven Central](https://img.shields.io/maven-central/v/dev.theolm/rinku)](https://mvnrepository.com/artifact/dev.theolm)
> A Kotlin Multiplatform library for deeplink handling

[Resaca](https://github.com/sebaslogen/resaca) - Scope ViewModels to a Composable, surviving config. changes and navigation
[![GitHub Repo stars](https://img.shields.io/github/stars/sebaslogen/resaca?style=flat)](https://github.com/sebaslogen/resaca/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.sebaslogen/resaca)](https://central.sonatype.com/artifact/io.github.sebaslogen/resaca)
> Scope ViewModels (or plain objects) to a Composable, surviving configuration changes and navigation, to break your app's logic into smaller and reusable components.

### 🔍 Analytics
[MOKO Crash Reporting](https://github.com/icerockdev/moko-crash-reporting) - reporting to Crashlytics
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-crash-reporting?style=flat)](https://github.com/icerockdev/moko-crash-reporting)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/crash-reporting-crashlytics)](https://central.sonatype.com/artifact/dev.icerock.moko/crash-reporting-crashlytics)
> Fatal and Non-Fatal reporting to Crashlytics for Kotlin Multiplatform Mobile

[CrashKiOS](https://github.com/touchlab/CrashKiOS) - Crash reporting for Kotlin/Native iOS applications 
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/CrashKiOS?style=flat)](https://github.com/touchlab/CrashKiOS)
[![Maven Central](https://img.shields.io/maven-central/v/co.touchlab/crashkios)](https://central.sonatype.com/artifact/co.touchlab/crashkios)
> Thin library that provides symbolicated crash reports for Kotlin code on iOS.

[NSExceptionKt](https://github.com/rickclephas/NSExceptionKt) - Better crash reports on Apple platforms
[![GitHub Repo stars](https://img.shields.io/github/stars/rickclephas/NSExceptionKt?style=flat)](https://github.com/rickclephas/NSExceptionKt)
[![Maven Central](https://img.shields.io/maven-central/v/com.rickclephas.kmp/nsexception-kt-core)](https://central.sonatype.com/artifact/com.rickclephas.kmp/nsexception-kt-core)
> Unhandled Kotlin exceptions logging for Apple platforms.

[trckr](https://github.com/dzmpr/trckr) - KSP processor
[![GitHub Repo stars](https://img.shields.io/github/stars/dzmpr/trckr?style=flat)](https://github.com/dzmpr/trckr)
[![Maven Central](https://img.shields.io/maven-central/v/ru.cookedapp.trckr/trckr-core)](https://central.sonatype.com/artifact/ru.cookedapp.trckr/trckr-core)
> KSP processer that simplifies the collection of analytics

### 🩺 Test
[Kotest](https://github.com/kotest/kotest) - test framework
[![GitHub Repo stars](https://img.shields.io/github/stars/kotest/kotest?style=flat)](https://github.com/kotest/kotest)
[![Maven Central](https://img.shields.io/maven-central/v/io.kotest/kotest-mpp)](https://central.sonatype.com/artifact/io.kotest/kotest-mpp)
> Powerful, elegant and flexible test framework for Kotlin with additional assertions, property testing and data driven testing 

[Turbine](https://github.com/cashapp/turbine) - test library
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/turbine?style=flat)](https://github.com/mpetuska/klip)
[![Maven Central](https://img.shields.io/maven-central/v/app.cash.turbine/turbine)](https://central.sonatype.com/artifact/app.cash.turbine/turbine)
> A small testing library for kotlinx.coroutines Flow

[MockingBird](https://github.com/careem/mockingbird) - test framework
[![GitHub Repo stars](https://img.shields.io/github/stars/careem/mockingbird?style=flat)](https://github.com/careem/mockingbird)
[![Maven Central](https://img.shields.io/maven-central/v/com.careem.mockingbird/mockingbird)](https://central.sonatype.com/artifact/com.careem.mockingbird/mockingbird)
> A Koltin multiplatform library that provides an easier way to mock and write unit tests for a multiplatform project 

[Mockative](https://github.com/mockative/mockative) - Mocking with KSP
[![GitHub Repo stars](https://img.shields.io/github/stars/mockative/mockative?style=flat)](https://github.com/mockative/mockative)
[![Maven Central](https://img.shields.io/maven-central/v/io.mockative/mockative)](https://central.sonatype.com/artifact/io.mockative/mockative)
> Mocking for Kotlin/Native and Kotlin Multiplatform using the Kotlin Symbol Processing API (KSP)

[MocKMP](https://github.com/kosi-libs/MocKMP) - Mocking with KSP
[![GitHub Repo stars](https://img.shields.io/github/stars/kosi-libs/MocKMP?style=flat)](https://github.com/kosi-libs/MocKMP)
[![Maven Central](https://img.shields.io/maven-central/v/org.kodein.mock.mockmp/org.kodein.mock.mockmp.gradle.plugin)](https://central.sonatype.com/artifact/org.kodein.mock.mockmp/org.kodein.mock.mockmp.gradle.plugin)
> A Kotlin/Multiplatform Kotlin Symbol Processor that generates Mocks & Fakes.

[Mokkery](https://github.com/lupuuss/Mokkery) - Mocking library
[![GitHub Repo stars](https://img.shields.io/github/stars/lupuuss/Mokkery?style=flat)](https://github.com/lupuuss/Mokkery)
[![Maven Central](https://img.shields.io/maven-central/v/dev.mokkery/mokkery-plugin)](https://central.sonatype.com/artifact/dev.mokkery/mokkery-plugin)
> Mokkery is a mocking library for Kotlin Multiplatform, easy to use, boilerplate-free and compiler plugin driven. Highly inspired by MockK.

[KLIP](https://github.com/mpetuska/klip) - Snapshot ((c|k)lip) manager for tests. 
[![GitHub Repo stars](https://img.shields.io/github/stars/mpetuska/klip?style=flat)](https://github.com/mpetuska/klip)
[![Maven Central](https://img.shields.io/maven-central/v/dev.petuska/klip)](https://central.sonatype.com/artifact/dev.petuska/klip)
> Kotlin Multiplatform snapshot ((c|k)lip) manager for tests. Automatically generates and asserts against a persistent Any::toString() representation of the object until you explicitly trigger an update. Powered by kotlin compiler plugin to inject relevant keys and paths.

[Assertk](https://github.com/willowtreeapps/assertk) - Fluent assertions library
[![GitHub Repo stars](https://img.shields.io/github/stars/willowtreeapps/assertk?style=flat)](https://github.com/willowtreeapps/assertk)
[![Maven Central](https://img.shields.io/maven-central/v/com.willowtreeapps.assertk/assertk)](https://central.sonatype.com/artifact/com.willowtreeapps.assertk/assertk)
> Fluent assertions library for Kotlin with full Multiplatform support.

### 🔑 Crypto
[Cryptography-Kotlin](https://github.com/whyoleg/cryptography-kotlin) - Type-safe Multiplatform cryptography library for Kotlin 
[![GitHub Repo stars](https://img.shields.io/github/stars/whyoleg/cryptography-kotlin?style=flat)](https://github.com/whyoleg/cryptography-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/dev.whyoleg.cryptography/cryptography-core)](https://central.sonatype.com/artifact/dev.whyoleg.cryptography/cryptography-core)
> The library doesn’t implement any cryptography algorithm on its own, but wraps well-known future-proof solutions like OpenSSL 3.x, WebCrypto or JCA with type-safe multiplatform API providing uniform experience with aligned default behavior, and same expected results using identical parameters while allowing to use platform-specific capabilities.

[Libsodium](https://github.com/ionspin/kotlin-multiplatform-libsodium) - Libsodium bindings for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/ionspin/kotlin-multiplatform-libsodium?style=flat)](https://github.com/ionspin/kotlin-multiplatform-libsodium)
[![Maven Central](https://img.shields.io/maven-central/v/com.ionspin.kotlin/multiplatform-crypto-libsodium-bindings)](https://central.sonatype.com/artifact/com.ionspin.kotlin/multiplatform-crypto-libsodium-bindings)
> Libsodium bindings project uses libsodium c sources and libsodium.js to provide a kotlin multiplatform wrapper library for libsodium.

[korlibs-crypto](https://github.com/korlibs/korlibs/tree/main/korlibs-crypto) - Pure Kotlin cryptography library
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korlibs?style=flat)](https://github.com/korlibs/korlibs/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korge/korlibs-crypto)](https://central.sonatype.com/artifact/com.soywiz.korge/korlibs-crypto)
> SecureRandom, Hash (MD5/SHA1/SHA256), AES

[cryptohash](https://github.com/appmattus/crypto/tree/main/cryptohash) - A set of cryptographic (and not so cryptographic) hashing functions
[![GitHub Repo stars](https://img.shields.io/github/stars/appmattus/crypto?style=flat)](https://github.com/appmattus/crypto)
[![Maven Central](https://img.shields.io/maven-central/v/com.appmattus.crypto/cryptohash)](https://central.sonatype.com/artifact/com.appmattus.crypto/cryptohash)
> xxHash, Blake, HMAC, Keccak, MD5, SHA, etc

[murmurhash](https://github.com/goncalossilva/kotlinx-murmurhash) - library for hashing using MurmurHash
[![GitHub Repo stars](https://img.shields.io/github/stars/goncalossilva/kotlinx-murmurhash?style=flat)](https://github.com/goncalossilva/kotlinx-murmurhash)
[![Maven Central](https://img.shields.io/maven-central/v/com.goncalossilva/murmurhash)](https://central.sonatype.com/artifact/com.goncalossilva/murmurhash)
> Kotlin Multiplatform (KMP) library for MurmurHash, a non-cryptographic hash function for general hash-based lookup focused on simplicity and performance.

[Diglol Crypto](https://github.com/diglol/crypto) - Diglol Crypto for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/diglol/crypto?style=flat)](https://github.com/diglol/crypto)
[![Maven Central](https://img.shields.io/maven-central/v/com.diglol.crypto/aead)](https://central.sonatype.com/artifact/com.diglol.crypto/aead)
> Lots of crypto algorithms for Kotlin Multiplatform.

[KotlinCrypto/MACs](https://github.com/KotlinCrypto/MACs) - Message Authentication Code algorithms for Kotlin Multiplatform 
[![GitHub Repo stars](https://img.shields.io/github/stars/KotlinCrypto/MACs?style=flat)](https://github.com/KotlinCrypto/MACs)
[![Maven Central](https://img.shields.io/maven-central/v/org.kotlincrypto.macs/hmac)](https://central.sonatype.com/artifact/org.kotlincrypto.macs/hmac)
> Message Authentication Code algorithms for Kotlin Multiplatform: HmacMD5, HmacSHA1, HmacSHA224, HmacSHA256, HmacSHA384, HmacSHA512, HmacSHA512/224, HmacSHA512/256

[KotlinCrypto/hash](https://github.com/KotlinCrypto/hash) - Cryptographic hash functions for Kotlin Multiplatform 
[![GitHub Repo stars](https://img.shields.io/github/stars/KotlinCrypto/hash?style=flat)](https://github.com/KotlinCrypto/hash)
[![Maven Central](https://img.shields.io/maven-central/v/org.kotlincrypto.hash/md5)](https://central.sonatype.com/artifact/org.kotlincrypto.hash/md5)
> Cryptographic hash functions for Kotlin Multiplatform: MD5, SHA-1, SHA-224, SHA-256, SHA-384, SHA-512, SHA-512/224, SHA-512/256

[KotlinCrypto/secure-random](https://github.com/KotlinCrypto/secure-random) - cryptographically secure random data from system sources 
[![GitHub Repo stars](https://img.shields.io/github/stars/KotlinCrypto/secure-random?style=flat)](https://github.com/KotlinCrypto/secure-random)
[![Maven Central](https://img.shields.io/maven-central/v/org.kotlincrypto/secure-random)](https://central.sonatype.com/artifact/org.kotlincrypto/secure-random)
> Kotlin Multiplatform library for obtaining cryptographically secure random data from the system. Modeled after Java's SecureRandom class, it provides a simple API surface area. Under the hood it utilizes system functions so that SecureRandom is accessible from common code.

### 📁 File
[kotlinx-io](https://github.com/Kotlin/kotlinx-io) - Kotlin multiplatform I/O library
[![Github Repo starts](https://img.shields.io/github/stars/Kotlin/kotlinx-io?style=flat)](https://github.com/Kotlin/kotlinx-io)
[![Maven Central](https://img.shields.io/maven-central/v/org.jetbrains.kotlinx/kotlinx-io-core)](https://central.sonatype.com/artifact/org.jetbrains.kotlinx/kotlinx-io-core)
> A multiplatform Kotlin library providing basic IO primitives. kotlinx-io is based on Okio but does not preserve backward compatibility with it.

[Okio](https://github.com/square/okio) - access, store, and process your data
[![GitHub Repo stars](https://img.shields.io/github/stars/square/okio?style=flat)](https://github.com/square/okio)
[![Maven Central](https://img.shields.io/maven-central/v/com.squareup.okio/okio)](https://central.sonatype.com/artifact/com.squareup.okio/okio)
> Okio is a library that complements java.io and java.nio to make it much easier to access, store, and process your data.

[korlibs](https://github.com/korlibs/korlibs) - access, store, and process your data
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korlibs?style=flat)](https://github.com/korlibs/korlibs)
> Libraries for Charsets, Encodings, Checksums, Compression, I/O, Streams, Virtual File System, Networking, Http, WebSockets, Serialization…

[Suparnatural FS](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/fs) - file system i/o
[![GitHub Repo stars](https://img.shields.io/github/stars/suparngp/kotlin-multiplatform-projects?style=flat)](https://github.com/suparngp/kotlin-multiplatform-projects/tree/master/fs)
[![Maven Central](https://img.shields.io/maven-central/v/com.suparnatural.kotlin/fs)](https://central.sonatype.com/artifact/com.suparnatural.kotlin/fs)
> Kotlin multiplatform file system i/o for android, iOS, Java and NodeJS

[FileKit](https://github.com/vinceglb/FileKit) - Pick and save Files, Medias and Folder
[![GitHub Repo stars](https://img.shields.io/github/stars/vinceglb/FileKit?style=flat)](https://github.com/vinceglb/FileKit)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.vinceglb/filekit-core)](https://central.sonatype.com/artifact/io.github.vinceglb/filekit-core)
> Files, Medias, Folder Picker and File saver library for Kotlin Multiplatform and Compose Multiplatform

### 🚀 Language extensions
[Arrow](https://github.com/arrow-kt/arrow) - Functional companion to Kotlin's Standard Library 
[![GitHub Repo stars](https://img.shields.io/github/stars/arrow-kt/arrow?style=flat)](https://github.com/arrow-kt/arrow)
[![Maven Central](https://img.shields.io/maven-central/v/io.arrow-kt/arrow-core)](https://central.sonatype.com/artifact/io.arrow-kt/arrow-core)
> Arrow aims to provide a lingua franca of interfaces and abstractions across Kotlin libraries. For this, it includes the most popular data types such as Option, Either, Validated etc and functional operators such as traverse and computation blocks to empower users to write pure FP apps and libraries built atop higher order abstractions.

[Result](https://github.com/kittinunf/Result) - success/failure result
[![GitHub Repo stars](https://img.shields.io/github/stars/kittinunf/Result?style=flat)](https://github.com/kittinunf/Result)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.kittinunf.result/result)](https://central.sonatype.com/artifact/com.github.kittinunf.result/result)
> This is a tiny framework for modelling success/failure of operations in Kotlin. In short, it is a model in type of Result<V: Any?, E : Throwable>.

[ApiResult](https://github.com/respawn-app/ApiResult) - Declarative Error Handling
[![GitHub Repo stars](https://img.shields.io/github/stars/respawn-app/ApiResult?style=flat)](https://github.com/respawn-app/ApiResult)
[![Maven Central](https://img.shields.io/maven-central/v/pro.respawn.apiresult/core)](https://central.sonatype.com/namespace/pro.respawn.apiresult)
> ApiResult is a Kotlin Multiplatform declarative error handling framework that is performant, easy to use and feature-rich.

[Sandwich](https://github.com/skydoves/sandwich) - Handling API responses and exceptions in Kotlin for Retrofit, Ktor, Ktorfit
[![GitHub Repo stars](https://img.shields.io/github/stars/skydoves/sandwich?style=flat)](https://github.com/skydoves/sandwich)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.skydoves/sandwich.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22com.github.skydoves%22%20AND%20a:%22sandwich%22)
> Sandwich is an adaptable and lightweight sealed API library designed for handling API responses and exceptions in Kotlin for Retrofit, Ktor, and Kotlin Multiplatform.

### 🗃 Serializer
[kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - JSON serialization
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx.serialization?style=flat)](https://github.com/Kotlin/kotlinx.serialization)
[![Maven Central](https://img.shields.io/maven-central/v/net.peanuuutz.tomlkt/tomlkt)](https://central.sonatype.com/artifact/net.peanuuutz.tomlkt/tomlkt)
> Kotlin serialization consists of a compiler plugin, that generates visitor code for serializable classes, runtime library with core serialization API and support libraries with various serialization formats.

[Ksoup](https://github.com/fleeksoft/ksoup) - HTML & XML Parser (Jsoup Alternative)
[![GitHub Repo stars](https://img.shields.io/github/stars/fleeksoft/ksoup?style=flat)](https://github.com/fleeksoft/ksoup)
[![Maven Central](https://img.shields.io/maven-central/v/com.fleeksoft.ksoup/ksoup)](https://central.sonatype.com/artifact/com.fleeksoft.ksoup/ksoup)
> Ksoup: A Kotlin Multiplatform port of the renowned Java library, jsoup. Designed to scrape, parse, manipulate, and clean HTML and XML documents with ease and efficiency.

[XmlUtil](https://github.com/pdvrieze/xmlutil) - Component of the XMLUtil library
[![GitHub Repo stars](https://img.shields.io/github/stars/pdvrieze/xmlutil?style=flat)](https://github.com/pdvrieze/xmlutil)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.pdvrieze.xmlutil/core)](https://central.sonatype.com/artifact/io.github.pdvrieze.xmlutil/core)
> XmlUtil is a set of packages that supports multiplatform XML in Kotlin.

[tomlkt](https://github.com/Peanuuutz/tomlkt) - Multiplatform TOML encoder and decoder, powered by kotlinx.serialization 
[![GitHub Repo stars](https://img.shields.io/github/stars/Peanuuutz/tomlkt?style=flat)](https://github.com/Peanuuutz/tomlkt)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.pdvrieze.xmlutil/core)](https://central.sonatype.com/artifact/io.github.pdvrieze.xmlutil/core)
> Lightweight and easy to use kotlinx.serialization plugin for TOML serialization and deserialization.

[Ksoup](https://github.com/MohamedRejeb/ksoup) - Kotlin Multiplatform HTML Parser
[![GitHub Repo stars](https://img.shields.io/github/stars/MohamedRejeb/ksoup?style=flat)](https://github.com/MohamedRejeb/ksoup)
[![Maven Central](https://img.shields.io/maven-central/v/com.mohamedrejeb.ksoup/ksoup-html)](https://central.sonatype.com/artifact/com.mohamedrejeb.ksoup/ksoup-html)
> Ksoup is a lightweight Kotlin Multiplatform library for parsing HTML, extracting HTML tags, attributes, and text, and encoding and decoding HTML entities. 

[Essenty/Parcelable](https://github.com/arkivanov/Essenty#parcelable-and-parcelize) - @Parcelize annotation for Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/arkivanov/Essenty?style=flat)](https://github.com/arkivanov/Essenty)
[![Maven Central](https://img.shields.io/maven-central/v/com.arkivanov.essenty/parcelable)](https://central.sonatype.com/artifact/com.arkivanov.essenty/parcelable)
> Essenty brings both Android Parcelable interface and the `@Parcelize` annotation from kotlin-parcelize compiler plugin to Kotlin Multiplatform, so they both can be used in common code. 

[Kotlin Object Notation](https://github.com/mpetuska/kon) - Lightweight DSL to build fluid JSON trees
[![GitHub Repo stars](https://img.shields.io/github/stars/mpetuska/kon?style=flat)](https://github.com/mpetuska/kon)
[![Maven Central](https://img.shields.io/maven-central/v/dev.petuska/kon)](https://central.sonatype.com/artifact/dev.petuska/kon)
> Kotlin Object Notation - Lightweight DSL to build fluid JSON trees

[MOKO Parcelize](https://github.com/icerockdev/moko-parcelize) - Parcelize in common code
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-parcelize?style=flat)](https://github.com/icerockdev/moko-parcelize)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/parcelize)](https://central.sonatype.com/artifact/dev.icerock.moko/parcelize)
> This is a Kotlin Multiplatform library that supports Parcelize in common code.

[Pbandk](https://github.com/streem/pbandk) - Kotlin code generator and runtime for Protocol Buffers.
[![GitHub Repo stars](https://img.shields.io/github/stars/streem/pbandk?style=flat)](https://github.com/streem/pbandk)
[![Maven Central](https://img.shields.io/maven-central/v/pro.streem.pbandk/protoc-gen-pbandk-jvm)](https://central.sonatype.com/artifact/pro.streem.pbandk/protoc-gen-pbandk-jvm)
>It has the core set of protobuf features implemented and is being used in production.

### ⏰ Date-Time
[Kotlinx DateTime](https://github.com/Kotlin/kotlinx-datetime) - Date & Time library
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx-datetime?style=flat)](https://github.com/Kotlin/kotlinx-datetime)
[![Maven Central](https://img.shields.io/maven-central/v/org.jetbrains.kotlinx/kotlinx-datetime)](https://central.sonatype.com/artifact/org.jetbrains.kotlinx/kotlinx-datetime)
> A multiplatform Kotlin library for working with date and time.

[Island Time](https://github.com/erikc5000/island-time) - Date & Time library
[![GitHub Repo stars](https://img.shields.io/github/stars/erikc5000/island-time?style=flat)](https://github.com/erikc5000/island-time)
[![Maven Central](https://img.shields.io/maven-central/v/io.islandtime/core)](https://central.sonatype.com/artifact/io.islandtime/core)
> A Kotlin Multiplatform library for working with dates and times, heavily inspired by the java.time library.

[Kronos Multiplatform](https://github.com/softartdev/Kronos-Multiplatform) - Network Time Protocol (NTP) client
[![GitHub Repo stars](https://img.shields.io/github/stars/softartdev/Kronos-Multiplatform?style=flat)](https://github.com/softartdev/Kronos-Multiplatform)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.softartdev/kronos)](https://central.sonatype.com/artifact/io.github.softartdev/kronos)
> Kotlin Multiplatform library for network time synchronization. Extension for [Kotlinx DateTime](https://github.com/Kotlin/kotlinx-datetime) library.

[KCron](https://github.com/Scogun/kcron-common) - Kotlin multiplatform Cron library
[![GitHub Repo stars](https://img.shields.io/github/stars/Scogun/kcron-common?style=flat)](https://github.com/Scogun/kcron-common)
[![Maven Central](https://img.shields.io/maven-central/v/com.ucasoft.kcron/kcron-common)](https://central.sonatype.com/artifact/com.ucasoft.kcron/kcron-common)
> Kotlin Multiplatform library for build and parsing cron expression. Support custom date time providers. Has default implementation based on [Kotlinx DateTime](https://github.com/Kotlin/kotlinx-datetime) library. 

### ➿ Asynchronous
[Kotlinx Coroutines](https://github.com/Kotlin/kotlinx.coroutines) - Kotlin coroutines
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx.coroutines?style=flat)](https://github.com/Kotlin/kotlinx.coroutines)
[![Maven Central](https://img.shields.io/maven-central/v/org.jetbrains.kotlinx/kotlinx-coroutines-core)](https://central.sonatype.com/artifact/org.jetbrains.kotlinx/kotlinx-coroutines-core)
> Library support for Kotlin coroutines

[molecule](https://github.com/cashapp/molecule) - Build a StateFlow stream using Jetpack Compose
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/molecule?style=flat)](https://github.com/cashapp/molecule)
[![Maven Central](https://img.shields.io/maven-central/v/app.cash.molecule/molecule-runtime)](https://central.sonatype.com/artifact/app.cash.molecule/molecule-runtime)
> Build a StateFlow or Flow stream using Jetpack Compose and NOT Jetpack Compose UI!

[Reaktive](https://github.com/badoo/Reaktive) - Reactive Extensions
[![GitHub Repo stars](https://img.shields.io/github/stars/badoo/Reaktive?style=flat)](https://github.com/badoo/Reaktive)
[![Maven Central](https://img.shields.io/maven-central/v/com.badoo.reaktive/reaktive)](https://central.sonatype.com/artifact/com.badoo.reaktive/reaktive)
> Kotlin multiplatform implementation of Reactive Extensions.

[Kotlinx Atomicfu](https://github.com/Kotlin/kotlinx.atomicfu) - atomic operations
[![GitHub Repo stars](https://img.shields.io/github/stars/Kotlin/kotlinx.atomicfu?style=flat)](https://github.com/Kotlin/kotlinx.atomicfu)
[![Maven Central](https://img.shields.io/maven-central/v/org.jetbrains.kotlinx/atomicfu)](https://central.sonatype.com/artifact/org.jetbrains.kotlinx/atomicfu)
> The idiomatic way to use atomic operations in Kotlin.

[Stately](https://github.com/touchlab/Stately) - Kotlin Multiplatform State Library 
[![GitHub Repo stars](https://img.shields.io/github/stars/touchlab/Stately?style=flat)](https://github.com/touchlab/Stately)
[![Maven Central](https://img.shields.io/maven-central/v/co.touchlab/stately)](https://central.sonatype.com/artifact/co.touchlab/stately)
> Stately is a state utility library to facilitate state management in Kotlin Multiplatform.

[CoroutineWorker](https://github.com/Autodesk/coroutineworker) - Workers for Kotlin Native
[![GitHub Repo stars](https://img.shields.io/github/stars/Autodesk/coroutineworker?style=flat)](https://github.com/Autodesk/coroutineworker)
[![Maven Central](https://img.shields.io/maven-central/v/com.autodesk/CoroutineWorker)](https://central.sonatype.com/artifact/com.autodesk/CoroutineWorker)
> Kotlin Coroutine-based workers for native

[Koru](https://github.com/FutureMind/koru) - Coroutine wrappers for Kotlin Native 
[![GitHub Repo stars](https://img.shields.io/github/stars/FutureMind/koru?style=flat)](https://github.com/FutureMind/koru)
[![Maven Central](https://img.shields.io/maven-central/v/com.futuremind/koru)](https://central.sonatype.com/artifact/com.futuremind/koru)
> Automatically generates wrappers for suspend functions and Flow for easy access from Swift code in Kotlin Multiplatform projects.

[KMP-NativeCoroutines](https://github.com/rickclephas/KMP-NativeCoroutines) - Swift wrapper for Kotlin Coroutines 
[![GitHub Repo stars](https://img.shields.io/github/stars/rickclephas/KMP-NativeCoroutines?style=flat)](https://github.com/rickclephas/KMP-NativeCoroutines)
[![Maven Central](https://img.shields.io/maven-central/v/com.rickclephas.kmp/kmp-nativecoroutines-core)](https://central.sonatype.com/artifact/com.rickclephas.kmp/kmp-nativecoroutines-core)
> Library to use Kotlin Coroutines from Swift code in KMP apps

[FlowExt](https://github.com/hoc081098/FlowExt) - Kotlinx Coroutines Flow Extensions
[![GitHub Repo stars](https://img.shields.io/github/stars/hoc081098/FlowExt?style=flat)](https://github.com/hoc081098/FlowExt)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.hoc081098/FlowExt)](https://central.sonatype.com/artifact/io.github.hoc081098/FlowExt)
> A Kotlin Multiplatform library, that provides many operators and extensions to Kotlin Coroutines Flow.

[Human-Readable](https://github.com/jacobras/Human-Readable) - A small set of data formatting utilities. 
[![GitHub Repo stars](https://img.shields.io/github/stars/jacobras/human-readable?style=flat)](https://github.com/jacobras/Human-Readable/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/nl.jacobras/Human-Readable)](https://central.sonatype.com/artifact/nl.jacobras/Human-Readable)
> Works with kotlinx-datetime and offers features like relative time ("2 hours ago"), durations and file sizes.

### 🍎 Compose UI
[Alarmee](https://github.com/tweener/alarmee) Alarm scheduler with local notifications.
[![GitHub Repo stars](https://img.shields.io/github/stars/tweener/alarmee?style=flat)](https://github.com/tweener/alarmee)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.tweener/alarmee)](https://central.sonatype.com/artifact/io.github.tweener/alarmee)
> A Compose Multiplatform library for effortless alarm and local notification scheduling on both Android and iOS.

[Appyx](https://github.com/bumble-tech/appyx) Navigation, transition animations, gestures, UI components.
[![GitHub Repo stars](https://img.shields.io/github/stars/bumble-tech/appyx?style=flat)](https://github.com/bumble-tech/appyx)
[![Maven Central](https://img.shields.io/maven-central/v/com.bumble.appyx/appyx-interactions)](https://central.sonatype.com/artifact/com.bumble.appyx/appyx-interactions)
> Model-driven navigation + UI components with gesture control for Compose Multiplatform

[Voyager](https://github.com/adrielcafe/voyager) Compose Multiplatform Navigation. 
[![GitHub Repo stars](https://img.shields.io/github/stars/adrielcafe/voyager?style=flat)](https://github.com/adrielcafe/voyager)
[![Maven Central](https://img.shields.io/maven-central/v/cafe.adriel.voyager/voyager-core)](https://central.sonatype.com/artifact/cafe.adriel.voyager/voyager-core)
> A multiplatform navigation library built for, and seamlessly integrated with, Jetpack Compose.

[Calf](https://github.com/MohamedRejeb/Calf) Compose Adaptive Look & Feel 
[![GitHub Repo stars](https://img.shields.io/github/stars/MohamedRejeb/Calf?style=flat)](https://github.com/MohamedRejeb/Calf)
[![Maven Central](https://img.shields.io/maven-central/v/com.mohamedrejeb.calf/calf-ui)](https://central.sonatype.com/artifact/com.mohamedrejeb.calf/calf-ui)
> Calf is a library that allows you to easily create adaptive UIs for your Compose Multiplatform apps.

[Compose DND](https://github.com/MohamedRejeb/compose-dnd) Compose Drag And Drop
[![GitHub Repo stars](https://img.shields.io/github/stars/MohamedRejeb/compose-dnd?style=flat)](https://github.com/MohamedRejeb/compose-dnd)
[![Maven Central](https://img.shields.io/maven-central/v/com.mohamedrejeb.dnd/compose-dnd)](https://central.sonatype.com/artifact/com.mohamedrejeb.dnd/compose-dnd)
> Compose DND is a library that allows you to easily add drag and drop functionality to your Jetpack Compose and Compose Multiplatform projects.

[Window Size Class](https://github.com/chrisbanes/material3-windowsizeclass-multiplatform) Window Size Class
[![GitHub Repo stars](https://img.shields.io/github/stars/chrisbanes/material3-windowsizeclass-multiplatform?style=flat)](https://github.com/chrisbanes/material3-windowsizeclass-multiplatform)
[![Maven Central](https://img.shields.io/maven-central/v/dev.chrisbanes.material3/material3-window-size-class-multiplatform)](https://central.sonatype.com/artifact/dev.chrisbanes.material3/material3-window-size-class-multiplatform)
> Compose Multiplatform: Material 3 Window Size Class

[Compose-Imageloader](https://github.com/qdsfdhvh/compose-imageloader) Compose Image library for Kotlin Multiplatform. 
[![GitHub Repo stars](https://img.shields.io/github/stars/qdsfdhvh/compose-imageloader?style=flat)](https://github.com/qdsfdhvh/compose-imageloader)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.qdsfdhvh/image-loader)](https://central.sonatype.com/artifact/io.github.qdsfdhvh/image-loader)
> Compose Image library for Kotlin Multiplatform.

[Kamel](https://github.com/Kamel-Media/Kamel) Compose Multiplatform image loading.
[![GitHub Repo stars](https://img.shields.io/github/stars/Kamel-Media/Kamel?style=flat)](https://github.com/Kamel-Media/Kamel)
[![Maven Central](https://img.shields.io/maven-central/v/media.kamel/kamel-core)](https://central.sonatype.com/artifact/media.kamel/kamel-core)
> An asynchronous media loading library for Compose Multiplatform.

[Sketch](https://github.com/panpf/sketch) Image loader for Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/panpf/sketch?style=flat)](https://github.com/panpf/sketch)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.panpf.sketch4/sketch-core)](https://search.maven.org/artifact/io.github.panpf.sketch4/sketch-core)
> Sketch is an image loading library designed for Compose Multiplatform. It is powerful and rich in functions. In addition to basic functions, it also supports GIF, SVG, video thumbnails, Exif Orientation, etc.

[Compose Icons](https://github.com/DevSrSouza/compose-icons) Open Source icon packs for Compose Multiplatform. 
[![GitHub Repo stars](https://img.shields.io/github/stars/DevSrSouza/compose-icons?style=flat)](https://github.com/DevSrSouza/compose-icons)
[![Maven Central](https://img.shields.io/maven-central/v/br.com.devsrsouza.compose.icons/simple-icons)](https://central.sonatype.com/artifact/br.com.devsrsouza.compose.icons/simple-icons)
> Compose Multiplatform icons is a pack of libraries that provide well known Icon Packs. The library usage is inspired by Compose Material Icons.

[Compose Rich Editor](https://github.com/MohamedRejeb/Compose-Rich-Editor) Provides Rich Editor component for Compose Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/MohamedRejeb/Compose-Rich-Editor?style=flat)](https://github.com/MohamedRejeb/Compose-Rich-Editor)
[![Maven Central](https://img.shields.io/maven-central/v/com.mohamedrejeb.richeditor/richeditor-compose)](https://central.sonatype.com/artifact/com.mohamedrejeb.richeditor/richeditor-compose)
> A Rich text editor library for both Jetpack Compose and Compose Multiplatform, fully customizable and supports the common rich text editor features.

[Material Theme Preferences](https://github.com/softartdev/MaterialThemePrefs) Switching Dark/Light Material themes.
[![GitHub Repo stars](https://img.shields.io/github/stars/softartdev/MaterialThemePrefs?style=flat)](https://github.com/softartdev/MaterialThemePrefs)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.softartdev/material-theme-prefs)](https://central.sonatype.com/artifact/io.github.softartdev/material-theme-prefs)
> Kotlin Multiplatform library for easy switching Dark/Light Material themes on Compose.

[Drag Select Compose](https://github.com/jordond/drag-select-compose) Google Photos style drag-to-select multi-selection.
[![GitHub Repo stars](https://img.shields.io/github/stars/jordond/drag-select-compose?style=flat)](https://github.com/jordond/drag-select-compose)
[![Maven Central](https://img.shields.io/maven-central/v/com.dragselectcompose/dragselect)](https://central.sonatype.com/artifact/com.dragselectcompose/dragselect)
> Compose Multiplatform library that allows you to easily implement a "Google Photos"-style multi-selection in
your Compose apps.

[MaterialKolor](https://github.com/jordond/materialkolor) Generate Material3 color schemes from a seed color.
[![GitHub Repo stars](https://img.shields.io/github/stars/jordond/materialkolor?style=flat)](https://github.com/jordond/materialkolor)
[![Maven Central](https://img.shields.io/maven-central/v/com.materialkolor/material-kolor)](https://central.sonatype.com/artifact/com.materialkolor/material-kolor)
> Compose multiplatform library for generating dynamic Material3 color schemes from a seed color.

[Compose-placeholder](https://github.com/eygraber/compose-placeholder) Modifier for displaying 'placeholder' UI while content is loading.
[![GitHub Repo stars](https://img.shields.io/github/stars/eygraber/compose-placeholder?style=flat)](https://github.com/eygraber/compose-placeholder)
[![Maven Central](https://img.shields.io/maven-central/v/com.eygraber/compose-placeholder)](https://central.sonatype.com/artifact/com.eygraber/compose-placeholder)
> Compose multiplatform library which provides a modifier for displaying 'placeholder' UI while content is loading.

[kmPalette](https://github.com/jordond/kmpalette) A port of Androidx Palette, generate palettes from image.
[![GitHub Repo stars](https://img.shields.io/github/stars/jordond/kmpalette?style=flat)](https://github.com/jordond/kmpalette)
[![Maven Central](https://img.shields.io/maven-central/v/com.kmpalette/kmpalette-core)](https://central.sonatype.com/artifact/com.kmpalette/kmpalette-core)
> A Compose Multiplatform library for generating color palettes from images, including the dominant color.

[Reveal](https://github.com/svenjacobs/reveal) Reveal effect for Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/svenjacobs/reveal?style=flat)](https://github.com/svenjacobs/reveal)
[![Maven Central](https://img.shields.io/maven-central/v/com.svenjacobs.reveal/reveal-core)](https://central.sonatype.com/artifact/com.svenjacobs.reveal/reveal-core/badge.svg)
> A reveal effect (coach mark, tutorial, onboarding) for Compose Multiplatform (Android, iOS, desktop, Web)

[KMP-ComposeUIViewController](https://github.com/GuilhE/KMP-ComposeUIViewController) KMP-ComposeUIViewController.
[![GitHub Repo stars](https://img.shields.io/github/stars/GuilhE/KMP-ComposeUIViewController?style=flat)](https://github.com/GuilhE/KMP-ComposeUIViewController)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.guilhe.kmp/kmp-composeuiviewcontroller-ksp)](https://central.sonatype.com/artifact/com.github.guilhe.kmp/kmp-composeuiviewcontroller-ksp)
> KSP library for generating ComposeUIViewController and UIViewControllerRepresentable files when using Compose Multiplatform for iOS.

[KodeView](https://github.com/SnipMeDev/KodeView) KodeView
[![GitHub Repo stars](https://img.shields.io/github/stars/SnipMeDev/KodeView?style=flat)](https://github.com/SnipMeDev/KodeView)
[![Maven Central](https://img.shields.io/maven-central/v/dev.snipme/kodeview)](https://central.sonatype.com/artifact/dev.snipme/kodeview/badge.svg)
> Kotlin Multiplatform syntax highlighting views.

[QRose](https://github.com/alexzhirkevich/qrose) - Multiplatform QR code generator
[![GitHub Repo stars](https://img.shields.io/github/stars/alexzhirkevich/qrose?style=flat)](https://github.com/alexzhirkevich/qrose)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.alexzhirkevich/qrose)](https://central.sonatype.com/artifact/io.github.alexzhirkevich/qrose/badge.svg)
> Styled QR code generation library for Compose Multiplatform.

[rebugger](https://github.com/theapache64/rebugger) - A recomposition debugger
[![GitHub Repo stars](https://img.shields.io/github/stars/theapache64/rebugger?style=flat)](https://github.com/theapache64/rebugger)
[![jitpack.io](https://jitpack.io/v/theapache64/rebugger.svg)](https://jitpack.io/#theapache64/rebugger)
> A simple Compose library to print the reason for recomposition in your `Logcat` window.

[Compose WebView Multiplatform](https://github.com/KevinnZou/compose-webview-multiplatform) WebView for Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/KevinnZou/compose-webview-multiplatform?style=flat)](https://github.com/KevinnZou/compose-webview-multiplatform)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.kevinnzou/compose-webview-multiplatform.svg)](https://search.maven.org/artifact/io.github.kevinnzou/compose-webview-multiplatform)
> A WebView library that offers essential WebView features for Compose Multiplatform. It supports loading URLs and HTML data, evaluating JavaScript, and managing cookies. Currently, it is available for Android, iOS, and Desktop platforms.

[ZoomImage](https://github.com/panpf/zoomimage) Library for zoom images
[![GitHub Repo stars](https://img.shields.io/github/stars/panpf/zoomimage?style=flat)](https://github.com/panpf/zoomimage)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.panpf.zoomimage/zoomimage-core)](https://search.maven.org/artifact/io.github.panpf.zoomimage/zoomimage-core)
> Library for zoom images, supported Android View, Compose and Compose Multiplatform; supported double-click zoom, One or two fingers gesture zoom, single-finger drag, inertial sliding, positioning, rotation, super-large image subsampling and other functions.

[peekaboo](https://github.com/TEAM-PREAT/peekaboo) - Image Picker Library for Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/TEAM-PREAT/peekaboo?style=flat)](https://github.com/TEAM-PREAT/peekaboo)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.team-preat/peekaboo-image-picker)](https://search.maven.org/search?q=g:io.github.team-preat)
> Kotlin Multiplatform library for Compose Multiplatform, designed for seamless integration of an image picker feature in iOS and Android applications.

[FlexibleBottomSheet](https://github.com/skydoves/FlexibleBottomSheet) - Flexible BottomSheet library Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/skydoves/FlexibleBottomSheet?style=flat)](https://github.com/skydoves/FlexibleBottomSheet)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.skydoves/flexible-core)](https://central.sonatype.com/artifact/com.github.skydoves/flexible-core)
> Advanced Compose Multiplatform bottom sheet for segmented sizing and non-modal type, similar to Google Maps.

[orbitral](https://github.com/skydoves/orbital) - Dynamic animation library for Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/skydoves/orbital?style=flat)](https://github.com/skydoves/orbital)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.skydoves/orbital)](https://central.sonatype.com/artifact/com.github.skydoves/orbital)
> Jetpack Compose animation library that allows you to implement animations such as shared element transition.

[compose-stable-marker](https://github.com/skydoves/compose-stable-marker) - Compose stable markers for KMP to tell stable/immutable guarantees
[![GitHub Repo stars](https://img.shields.io/github/stars/skydoves/compose-stable-marker?style=flat)](https://github.com/skydoves/compose-stable-marker)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.skydoves/compose-stable-marker)](https://central.sonatype.com/artifact/com.github.skydoves/compose-stable-marker)
> Compose stable markers were originated Compose runtime, which improves Compose performance by telling stable and skippable guarantees to the compose compiler from non-compose dependent modules. 

[Wavy slider](https://github.com/mahozad/wavy-slider) A dancing slider/progress bar. 
[![GitHub Repo stars](https://img.shields.io/github/stars/mahozad/wavy-slider?style=flat)](https://github.com/mahozad/wavy-slider/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/ir.mahozad.multiplatform/wavy-slider)](https://central.sonatype.com/artifact/ir.mahozad.multiplatform/wavy-slider)
> Inpired by Android 13 squiggly progress bar. Also, a demo for how to create a multiplatform Composable.

[Koala Plot](https://github.com/KoalaPlot/koalaplot-core) - A charting and plotting library for Compose Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/KoalaPlot/koalaplot-core?style=flat)](https://github.com/KoalaPlot/koalaplot-core/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.koalaplot/koalaplot-core)](https://central.sonatype.com/artifact/io.github.koalaplot/koalaplot-core)
> Build great-looking interactive plots for Android, Desktop, iOS, and Web using a single API and common code base. Supports over 7 graph types.

[Precompose](https://github.com/Tlaster/PreCompose) Compose Multiplatform Navigation.
[![GitHub Repo stars](https://img.shields.io/github/stars/Tlaster/PreCompose?style=flat)](https://github.com/Tlaster/PreCompose)
[![Maven Central](https://img.shields.io/maven-central/v/moe.tlaster/precompose)](https://central.sonatype.com/artifact/moe.tlaster/precompose)
> Compose Multiplatform Navigation && ViewModel library, inspired by Jetpack Navigation, ViewModel and Lifecycle.

[Compose Action Menu](https://github.com/jacobras/ComposeActionMenu) An easy-to-use action/overflow menu for Compose UI.
[![GitHub Repo stars](https://img.shields.io/github/stars/jacobras/composeactionmenu?style=flat)](https://github.com/jacobras/ComposeActionMenu/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/nl.jacobras/compose-action-menu)](https://central.sonatype.com/artifact/nl.jacobras/compose-action-menu)

[KMPAuth](https://github.com/mirzemehdi/KMPAuth) Compose Multiplatform Authentication Library. 
[![GitHub Repo stars](https://img.shields.io/github/stars/mirzemehdi/KMPAuth?style=flat)](https://github.com/mirzemehdi/KMPAuth)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.mirzemehdi/kmpauth-core)](https://central.sonatype.com/artifact/io.github.mirzemehdi/kmpauth-core)
> Compose Multiplatform Authentication Library targetting android and iOS.

[Kottie](https://github.com/ismai117/kottie) Compose Multiplatform Animation library. 
[![GitHub Repo stars](https://img.shields.io/github/stars/ismai117/Kottie?style=flat)](https://github.com/ismai117/kottie)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.ismai117/kottie)](https://central.sonatype.com/artifact/io.github.ismai117/kottie)
> Compose Multiplatform animation library that parses Adobe After Effects animations. Inspired by Airbnb/Lottie.

[Compose Cupertino](https://github.com/alexzhirkevich/compose-cupertino/) - Compose Multiplatform UI components for iOS.
[![GitHub Repo stars](https://img.shields.io/github/stars/alexzhirkevich/compose-cupertino?style=flat)](https://github.com/alexzhirkevich/compose-cupertino/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.alexzhirkevich/cupertino)](https://central.sonatype.com/artifact/io.github.alexzhirkevich/cupertino)
> Compose Cupertino is a Kotlin Multiplatform library for the Compose Multiplatform UI framework. It provides various UI components and adaptive wrappers for making native-looking iOS applications.

[ConstraintLayout Compose Multiplatform](https://github.com/Lavmee/constraintlayout-compose-multiplatform/) - ConstraintLayout Compose for Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/lavmee/constraintlayout-compose-multiplatform?style=flat)](https://github.com/lavmee/constraintlayout-compose-multiplatform/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/tech.annexflow.compose/constraintlayout-compose-multiplatform)](https://central.sonatype.com/artifact/tech.annexflow.compose/constraintlayout-compose-multiplatform)
> Useful when implementing larger layouts with more complicated alignment requirements.

[Compose Settings](https://github.com/alorma/Compose-Settings/) - Compose Settings.
[![GitHub Repo stars](https://img.shields.io/github/stars/alorma/Compose-Settings?style=flat)](https://github.com/alorma/Compose-Settings/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.alorma.compose-settings/ui-tiles.svg)](https://central.sonatype.com/namespace/com.github.alorma.compose-settings)
> Compose Multiplatform #Compose Settings library.

[material-motion-compose](https://github.com/fornewid/material-motion-compose) - Material Motion for Compose Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/fornewid/material-motion-compose?style=flat)](https://github.com/fornewid/material-motion-compose/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.fornewid/material-motion-compose-core)](https://central.sonatype.com/artifact/io.github.fornewid/material-motion-compose-core)
> A library for implementing motion system in Material Components for Compose Multiplatform.

[Tiamat](https://github.com/ComposeGears/Tiamat) - Compose Multiplatform navigation library.
[![GitHub Repo stars](https://img.shields.io/github/stars/ComposeGears/Tiamat?style=flat)](https://github.com/ComposeGears/Tiamat/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.composegears/tiamat)](https://central.sonatype.com/artifact/io.github.composegears/tiamat)
> Key features: code generation free, pure Compose, nested navigation support, back-stack alteration (+deep-links), pass ANY types between screens as data, even lambdas, customizable transitions.

[Landscapist](https://github.com/skydoves/landscapist): Compose image loading library for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/skydoves/landscapist?style=flat)](https://github.com/skydoves/landscapist/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.skydoves/landscapist.svg?label=Maven%20Central)](https://central.sonatype.com/search?q=skydoves%2520landscapist)
> A pluggable, highly optimized Jetpack Compose and Kotlin Multiplatform image loading library that fetches and displays network images with Glide, Coil, and Fresco.

[colorpicker-compose](https://github.com/skydoves/colorpicker-compose): Color Picker library for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/skydoves/colorpicker-compose?style=flat)](https://github.com/skydoves/colorpicker-compose/stargazers)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.skydoves/colorpicker-compose.svg?label=Maven%20Central)](https://central.sonatype.com/search?q=skydoves%colorpicker-compose)
> Kotlin Multiplatform color picker library for getting colors from any images by tapping on the desired color.

### 🎨 Graphics
[MOKO Graphics](https://github.com/icerockdev/moko-graphics) - Graphics primitives
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-graphics?style=flat)](https://github.com/icerockdev/moko-graphics)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/graphics)](https://central.sonatype.com/artifact/dev.icerock.moko/graphics)
> This is a Kotlin Multiplatform library that provides graphics primitives to common code.

[Korim](https://github.com/korlibs/korim) - Imaging utilities
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korim?style=flat)](https://github.com/korlibs/korim)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.korim/korim)](https://central.sonatype.com/artifact/com.soywiz.korlibs.korim/korim)
> Kotlin cORoutines IMaging, Bitmap and Vector graphics for Multiplatform Kotlin

### 🧩 Service SDK
[Firebase Kotlin SDK](https://github.com/GitLiveApp/firebase-kotlin-sdk) - A Kotlin-first SDK for Firebase 
[![GitHub Repo stars](https://img.shields.io/github/stars/GitLiveApp/firebase-kotlin-sdk?style=flat)](https://github.com/GitLiveApp/firebase-kotlin-sdk)
[![Maven Central](https://img.shields.io/maven-central/v/dev.gitlive/firebase-auth)](https://central.sonatype.com/artifact/dev.gitlive/firebase-auth)
> The Firebase Kotlin SDK is a Kotlin-first SDK for Firebase. It's API is similar to the Firebase Android SDK Kotlin Extensions but also supports multiplatform projects, enabling you to use Firebase directly from your common source targeting iOS, Android or JS.

[supabase-kt](https://github.com/supabase-community/supabase-kt) - KMP Client for Supabase 
[![GitHub Repo stars](https://img.shields.io/github/stars/supabase-community/supabase-kt?style=flat)](https://github.com/supabase-community/supabase-kt)
[![Maven Central](https://img.shields.io/maven-central/v/dio.github.jan-tennert.supabase/supabase-kt)](https://central.sonatype.com/artifact/io.github.jan-tennert.supabase/supabase-kt)
> Supabase is an open source Firebase alternative. Database, Auth, Storage, Edge Functions, Realtime, AI & Vectors

[openai-kotlin](https://github.com/Aallam/openai-kotlin) - OpenAI SDK 
[![GitHub Repo stars](https://img.shields.io/github/stars/Aallam/openai-kotlin?style=flat)](https://github.com/Aallam/openai-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.aallam.openai/openai-client)](https://central.sonatype.com/artifact/com.aallam.openai/openai-client)
> Kotlin client for [OpenAI's API](https://beta.openai.com/docs/api-reference) with multiplatform and coroutines capabilities.

[Sentry SDK](https://github.com/getsentry/sentry-kotlin-multiplatform) - Sentry Kotlin Multiplatform SDK 
[![GitHub Repo stars](https://img.shields.io/github/stars/getsentry/sentry-kotlin-multiplatform?style=flat)](https://github.com/getsentry/sentry-kotlin-multiplatform)
[![Maven Central](https://img.shields.io/maven-central/v/io.sentry/sentry-kotlin-multiplatform)](https://central.sonatype.com/artifact/io.sentry/sentry-kotlin-multiplatform)
> This project is an experimental SDK for Kotlin Multiplatform. This SDK is a wrapper around different platforms such as JVM, Android, iOS, macOS, watchOS, tvOS that can be used on Kotlin Multiplatform.

[bitcoin-kmp](https://github.com/ACINQ/bitcoin-kmp) - Kotlin Multiplatform Bitcoin Library
[![GitHub Repo stars](https://img.shields.io/github/stars/ACINQ/bitcoin-kmp?style=flat)](https://github.com/ACINQ/bitcoin-kmp)
[![Maven Central](https://img.shields.io/maven-central/v/fr.acinq.bitcoin/bitcoin-kmp)](https://central.sonatype.com/artifact/fr.acinq.bitcoin/bitcoin-kmp)
> This is a simple Kotlin Multiplatform library which implements most of the bitcoin protocol

[MOKO Tensorflow](https://github.com/icerockdev/moko-tensorflow) - Mobile Kotlin TensorFlow
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-tensorflow?style=flat)](https://github.com/icerockdev/moko-tensorflow)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/tensorflow)](https://central.sonatype.com/artifact/dev.icerock.moko/tensorflow)
> This is a Kotlin MultiPlatform library that provides access to TensorFlow-Lite functionality from common source set.

[qBittorrent](https://github.com/DrewCarlson/qBittorrent-Kotlin) - wrapper for the qBittorrent Web API
[![GitHub Repo stars](https://img.shields.io/github/stars/DrewCarlson/qBittorrent-Kotlin?style=flat)](https://github.com/DrewCarlson/qBittorrent-Kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/org.drewcarlson/qbittorrent-client)](https://central.sonatype.com/artifact/org.drewcarlson/qbittorrent-client)
> Multiplatform Kotlin wrapper for the qBittorrent Web API using Ktor.

[Cognito-idp](https://github.com/Liftric/cognito-idp) - AWS Cognito Identity Provider
[![GitHub Repo stars](https://img.shields.io/github/stars/Liftric/cognito-idp?style=flat)](https://github.com/Liftric/cognito-idp)
[![Maven Central](https://img.shields.io/maven-central/v/com.liftric/cognito-idp)](https://central.sonatype.com/artifact/com.liftric/cognito-idp)
> Lightweight AWS Cognito Identity Provider client for Kotlin Multiplatform and Typescript projects.

[TMDb API](https://github.com/MoviebaseApp/tmdb-api) - access to TMDb API 
[![GitHub Repo stars](https://img.shields.io/github/stars/MoviebaseApp/tmdb-api?style=flat)](https://github.com/MoviebaseApp/tmdb-api)
[![Maven Central](https://img.shields.io/maven-central/v/app.moviebase/tmdb-api)](https://central.sonatype.com/artifact/app.moviebase/tmdb-api)
> This library gives access to TMDb API version 3 and 4 for mobile, desktop, and web applications. It supports Swift, Kotlin, and JavaScript by setting up as a Kotlin Multiplatform project.

[Growth Book SDK](https://github.com/growthbook/growthbook-kotlin) - GrowthBook Kotlin SDK 
[![GitHub Repo stars](https://img.shields.io/github/stars/growthbook/growthbook-kotlin?style=flat)](https://github.com/growthbook/growthbook-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/io.growthbook.sdk/GrowthBook)](https://central.sonatype.com/artifact/io.growthbook.sdk/GrowthBook)
> GrowthBook is an open-source platform for feature flagging and a/b testing built for data teams, engineers, and product managers. It's great whether you're looking to just analyze experiment results or looking to make it easier to deploy code.

[ConfigCat](https://github.com/configcat/kotlin-sdk) - Kotlin Multiplatform SDK for ConfigCat
[![GitHub Repo stars](https://img.shields.io/github/stars/configcat/kotlin-sdk?style=flat)](https://github.com/configcat/kotlin-sdk)
[![Maven Central](https://img.shields.io/maven-central/v/com.configcat/configcat-kotlin-client)](https://central.sonatype.com/artifact/com.configcat/configcat-kotlin-client)
> Kotlin Multiplatform SDK for ConfigCat, a feature flag, feature toggle, and configuration management service. That lets you launch new features and change your software configuration remotely without actually (re)deploying code. ConfigCat even helps you do controlled roll-outs like canary releases and blue-green deployments.

### 🧮 Arithmetic
[KBigNum](https://github.com/korlibs/kbignum) - Big Numbers
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/kbignum?style=flat)](https://github.com/korlibs/kbignum)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.kbignum/kbignum)](https://central.sonatype.com/artifact/com.soywiz.korlibs.kbignum/kbignum)
> Library for Big Numbers

[BigNum](https://github.com/ionspin/kotlin-multiplatform-bignum) - Big Numbers
[![GitHub Repo stars](https://img.shields.io/github/stars/ionspin/kotlin-multiplatform-bignum?style=flat)](https://github.com/ionspin/kotlin-multiplatform-bignum)
[![Maven Central](https://img.shields.io/maven-central/v/com.ionspin.kotlin/bignum)](https://central.sonatype.com/artifact/com.ionspin.kotlin/bignum)
> Kotlin Multiplatform BigNum library is a pure kotlin implementation of arbitrary precision arithmetic operations. It follows the same approach as Kotlin does on JVM to keep the interface familiar.

### 🛢 Resources
[Libres](https://github.com/Skeptick/libres) - Resources manager.
[![GitHub Repo stars](https://img.shields.io/github/stars/Skeptick/libres?style=flat)](https://github.com/Skeptick/libres)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.skeptick.libres/libres)](https://central.sonatype.com/artifact/io.github.skeptick.libres/libres)
> String/Image resources generation in Kotlin Multiplatform.

[MOKO Resources](https://github.com/icerockdev/moko-resources) - System resources manager
[![GitHub Repo stars](https://img.shields.io/github/stars/icerockdev/moko-resources?style=flat)](https://github.com/icerockdev/moko-resources)
[![Maven Central](https://img.shields.io/maven-central/v/dev.icerock.moko/resources)](https://central.sonatype.com/artifact/dev.icerock.moko/resources)
> This is a Kotlin Multiplatform library that provides access to the resources on iOS & Android with the support of the default system localization.

[Kotlinx-Resources](https://github.com/goncalossilva/kotlinx-resources) - text resources manager
[![GitHub Repo stars](https://img.shields.io/github/stars/goncalossilva/kotlinx-resources?style=flat)](https://github.com/goncalossilva/kotlinx-resources)
[![Maven Central](https://img.shields.io/maven-central/v/com.goncalossilva/resources)](https://central.sonatype.com/artifact/com.goncalossilva/resources)
> Kotlin Multiplatform (KMP) plugin and library that add support for reading resources in tests.  
> The plugin and a library work in tandem to provide a unified API across platforms for reading resources from each source set's resources folder.

### 🔧 Utils
[UUID](https://github.com/benasher44/uuid) - UUID generator
[![GitHub Repo stars](https://img.shields.io/github/stars/benasher44/uuid?style=flat)](https://github.com/benasher44/uuid)
[![Maven Central](https://img.shields.io/maven-central/v/com.benasher44/uuid)](https://central.sonatype.com/artifact/com.benasher44/uuid)
> Kotlin Multiplatform UUID generator

[Uri KMP](https://github.com/eygraber/uri-kmp) - A library for working with URIs in Kotlin Multiplatform
[![GitHub Repo stars](https://img.shields.io/github/stars/eygraber/uri-kmp?style=flat)](https://github.com/eygraber/uri-kmp)
[![Maven Central](https://img.shields.io/maven-central/v/com.eygraber/uri-kmp)](https://central.sonatype.com/artifact/com.eygraber/uri-kmp)
> A library for working with URIs in Kotlin Multiplatform

[Diglol Encoding](https://github.com/diglol/encoding) - Common encodings for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/diglol/encoding?style=flat)](https://github.com/diglol/encoding)
[![Maven Central](https://img.shields.io/maven-central/v/com.diglol.encoding/encoding)](https://central.sonatype.com/artifact/com.diglol.encoding/encoding)
> Diglol Encoding provides Hex/Base16, Base32, Base64 encodings for Kotlin Multiplatform.

[Diglol Id](https://github.com/diglol/id) - A global Id generator for Kotlin Multiplatform.
[![GitHub Repo stars](https://img.shields.io/github/stars/diglol/id?style=flat)](https://github.com/diglol/id)
[![Maven Central](https://img.shields.io/maven-central/v/com.diglol.id/id)](https://central.sonatype.com/artifact/com.diglol.id/id)
> A global Id generator for Kotlin Multiplatform. It modifies the timestamp to 5 bytes based on Xid.

[ByteBuffer](https://github.com/DitchOoM/buffer) - Kotlin Multiplatform bytebuffer/byte[] wrapper 
[![GitHub Repo stars](https://img.shields.io/github/stars/DitchOoM/buffer?style=flat)](https://github.com/DitchOoM/buffer)
[![Maven Central](https://img.shields.io/maven-central/v/com.ditchoom/buffer)](https://central.sonatype.com/artifact/com.ditchoom/buffer)
> A kotlin multiplatform library that allows you to allocate and modify byte[] natively using an API similar to Java's ByteBuffer API.

[zipline](https://github.com/cashapp/zipline) - Run Kotlin/JS libraries in Kotlin/JVM and Kotlin/Native programs 
[![GitHub Repo stars](https://img.shields.io/github/stars/cashapp/zipline?style=flat)](https://github.com/cashapp/zipline)
[![Maven Central](https://img.shields.io/maven-central/v/app.cash.zipline/zipline)](https://central.sonatype.com/artifact/app.cash.zipline/zipline)
> Zipline works by embedding the QuickJS JavaScript engine in your Kotlin/JVM or Kotlin/Native program. It's a small and fast JavaScript engine that's well-suited to embedding in applications.

[Kase64](https://github.com/saschpe/kase64) - Base64 encoder/decoder 
[![GitHub Repo stars](https://img.shields.io/github/stars/saschpe/kase64?style=flat)](https://github.com/saschpe/kase64)
[![Maven Central](https://img.shields.io/maven-central/v/de.peilicke.sascha/kase64)](https://central.sonatype.com/artifact/de.peilicke.sascha/kase64)
> Base64 encoder/decoder for Kotlin/Multiplatform. Supports Android, iOS, JavaScript and plain JVM environments. 

[Colormath](https://github.com/ajalt/colormath) - Multiplatform Kotlin color conversion and manipulation 
[![GitHub Repo stars](https://img.shields.io/github/stars/ajalt/colormath?style=flat)](https://github.com/ajalt/colormath)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.ajalt/colormath)](https://central.sonatype.com/artifact/com.github.ajalt/colormath)
> Colormath is a Kotlin Multiplatform library for color manipulation and conversion.

[GEOK](https://github.com/piruin/geok) - Kotlin geometry library 
[![GitHub Repo stars](https://img.shields.io/github/stars/piruin/geok?style=flat)](https://github.com/piruin/geok)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.piruin/geok)](https://central.sonatype.com/artifact/io.github.piruin/geok)
> Small geometry library for Java and Kotlin. Contains useful basic utilities that require on most application.

[fluid-currency](https://github.com/fluidsonic/fluid-currency) - currency library
[![GitHub Repo stars](https://img.shields.io/github/stars/fluidsonic/fluid-currency?style=flat)](https://github.com/fluidsonic/fluid-currency)
[![Maven Central](https://img.shields.io/maven-central/v/io.fluidsonic.currency/fluid-currency)](https://central.sonatype.com/artifact/io.fluidsonic.currency/fluid-currency)
> Kotlin multiplatform currency library.

[fluid-country](https://github.com/fluidsonic/fluid-country) - country library
[![GitHub Repo stars](https://img.shields.io/github/stars/fluidsonic/fluid-country?style=flat)](https://github.com/fluidsonic/fluid-country)
[![Maven Central](https://img.shields.io/maven-central/v/io.fluidsonic.country/fluid-country)](https://central.sonatype.com/artifact/io.fluidsonic.country/fluid-country)
> Kotlin multiplatform country library.

[Kmem](https://github.com/korlibs/kmem) - Data primitives
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/kmem?style=flat)](https://github.com/korlibs/kmem)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.kmem/kmem)](https://central.sonatype.com/artifact/com.soywiz.korlibs.kmem/kmem)
> Kmem is bit, array and fast memory utilities library for multiplatform Kotlin

[KaseChange](https://github.com/pearxteam/kasechange) - convert strings between various case formats
[![GitHub Repo stars](https://img.shields.io/github/stars/pearxteam/kasechange?style=flat)](https://github.com/pearxteam/kasechange)
[![Maven Central](https://img.shields.io/maven-central/v/net.pearx.kasechange/kasechange)](https://central.sonatype.com/artifact/net.pearx.kasechange/kasechange)
> Multiplatform Kotlin library to convert strings between various case formats including Camel Case, Snake Case, Pascal Case and Kebab Case

[FuzzyWuzzy-Kotlin](https://github.com/willowtreeapps/fuzzywuzzy-kotlin) - Fuzzy string matching for Kotlin
[![GitHub Repo stars](https://img.shields.io/github/stars/willowtreeapps/fuzzywuzzy-kotlin?style=flat)](https://github.com/willowtreeapps/fuzzywuzzy-kotlin)
[![Maven Central](https://img.shields.io/maven-central/v/com.willowtreeapps/fuzzywuzzy-kotlin)](https://central.sonatype.com/artifact/com.willowtreeapps/fuzzywuzzy-kotlin)
> Useful for selecting the closest matching string from a collection of strings. Various algorithms are available.

[kotlin-semver](https://github.com/z4kn4fein/kotlin-semver) - Semantic versioning
[![GitHub Repo stars](https://img.shields.io/github/stars/z4kn4fein/kotlin-semver?style=flat)](https://github.com/z4kn4fein/kotlin-semver)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.z4kn4fein/semver)](https://central.sonatype.com/artifact/io.github.z4kn4fein/semver)
> Semantic Versioning library for Kotlin Multiplatform.

[Kontrol](https://github.com/chopyourbrain/kontrol) - Debug menu
[![GitHub Repo stars](https://img.shields.io/github/stars/chopyourbrain/kontrol?style=flat)](https://github.com/chopyourbrain/kontrol)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.chopyourbrain/kontrol)](https://central.sonatype.com/artifact/io.github.chopyourbrain/kontrol/)
> Kotlin Multiplatform library for creating a debugging menu.

[Korau](https://github.com/korlibs/korau) - Kotlin cORoutines AUdio
[![GitHub Repo stars](https://img.shields.io/github/stars/korlibs/korau?style=flat)](https://github.com/korlibs/korau)
[![Maven Central](https://img.shields.io/maven-central/v/com.soywiz.korlibs.korau/korau)](https://central.sonatype.com/artifact/com.soywiz.korlibs.korau/korau)
> Pure Kotlin WAV, MP3 and OGG vorbis decoders

[Kim](https://github.com/Ashampoo/kim) - Kotlin Image Metadata
[![GitHub Repo stars](https://img.shields.io/github/stars/Ashampoo/kim?style=flat)](https://github.com/Ashampoo/kim)
[![Maven Central](https://img.shields.io/maven-central/v/com.ashampoo/kim)](https://central.sonatype.com/artifact/com.ashampoo/kim)
> Kotlin Multiplatform library for reading and writing image metadata

[XMP Core for Kotlin Multiplatform](https://github.com/Ashampoo/xmpcore) - Kotlin Multiplatform port of Adobe's XMP SDK
[![GitHub Repo stars](https://img.shields.io/github/stars/Ashampoo/xmpcore?style=flat)](https://github.com/Ashampoo/xmpcore)
[![Maven Central](https://img.shields.io/maven-central/v/com.ashampoo/xmpcore)](https://central.sonatype.com/artifact/com.ashampoo/xmpcore)
> Kotlin Multiplatform library for reading and writing XMP (Extensible Metadata Platform) files

[Highlights](https://github.com/SnipMeDev/Highlights) - Kotlin Multiplatform syntax highlighting engine
[![GitHub Repo stars](https://img.shields.io/github/stars/SnipMeDev/Highlights?style=flat)](https://github.com/SnipMeDev/Highlights)
[![Maven Central](https://img.shields.io/maven-central/v/dev.snipme/highlights)](https://central.sonatype.com/artifact/dev.snipme/highlights)
 > Kotlin Multiplatform library for analyzing and coloring syntax of code string

[BlahBlah](https://github.com/getspherelabs/blahblah)  - Blah-Blah generates fake data for robust testing and development
[![GitHub Repo stars](https://img.shields.io/github/stars/getspherelabs/blahblah?style=flat)](https://github.com/getspherelabs/blahblah)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.behzodhalil/blahblah-fake)](https://central.sonatype.com/artifact/io.github.behzodhalil/blahblah-fake)
> Blah-Blah generates fake data for robust testing and development

[KMPUtils](https://github.com/respawn-app/KMMUtils) - Kotlin STL Extensions & Utils
[![GitHub Repo stars](https://img.shields.io/github/stars/respawn-app/KMMUtils?style=flat)](https://github.com/respawn-app/KMMUtils)
[![Maven Central](https://img.shields.io/maven-central/v/pro.respawn.kmmutils/core)](https://central.sonatype.com/namespace/pro.respawn.kmmutils)
> KMPUtils is a collection of everything missing from the Kotlin Multiplatform Standard Library.

[RSSParser](https://github.com/prof18/RSS-Parser) - A Kotlin Multiplatform library to parse a RSS Feed
[![GitHub Repo stars](https://img.shields.io/github/stars/prof18/RSS-Parser?style=flat)](https://github.com/prof18/RSS-Parser)
[![Maven Central](https://img.shields.io/maven-central/v/com.prof18.rssparser/rssparser)](https://central.sonatype.com/namespace/com.prof18.rssparser)
> RSS Parser is a Kotlin Multiplatform library for parsing RSS and Atom feeds. It supports Android, iOS, and the JVM.

## Contribution guide
Feel free to contribute. Follow common style and welcome!  
Few rules:  
 1) every suggesion should contain link to any project uses the library (not an author's sample)
 2) the library is supposed to support Android + iOS targets
 3) the library must be published to the MavenCentral
 4) the library should be a popular (github stars ~ 50, at least)

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
