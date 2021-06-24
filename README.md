<img src="docs/banner.png" align="center" title="Trust logo">

My Wallet Core is an open source, cross-platform, mobile-focused library
implementing low-level cryptographic wallet functionality for a high number of blockchains.
It is a core part of the popular [My Wallet](https://www.mywalletbsc.com), and some other projects.
Most of the code is C++ with a set of strict C interfaces, and idiomatic interfaces for supported languages:
Swift for iOS and Java for Android.

![iOS CI](https://github.com/trustwallet/wallet-core/workflows/iOS%20CI/badge.svg)
![Android CI](https://github.com/trustwallet/wallet-core/workflows/Android%20CI/badge.svg)
![Linux CI](https://github.com/trustwallet/wallet-core/workflows/Linux%20CI/badge.svg)
![Docker CI](https://github.com/trustwallet/wallet-core/workflows/Docker%20CI/badge.svg)
![Typescript CI](https://github.com/trustwallet/wallet-core/workflows/Typescript%20CI/badge.svg)

[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/trustwallet/wallet-core)
![GitHub](https://img.shields.io/github/license/TrustWallet/wallet-core.svg)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/trustwallet/wallet-core)
![Cocoapods](https://img.shields.io/cocoapods/v/TrustWalletCore.svg)
![Cocoapods platforms](https://img.shields.io/cocoapods/p/TrustWalletCore.svg)

# Supported Blockchains

Wallet Core supports more than **50** blockchains: Bitcoin, Ethereum, Binance Chain, and most major blockchain platforms.
The full list is [here](docs/coins.md).

# Using from your project

If you want to use wallet core in your project follow these instructions.

## Android

Add this dependency to build.gradle and run `gradle install`

```groovy
plugins {
    id 'maven'
}

dependencies {
    implementation 'com.trustwallet:wallet-core:x.y.z'
}
```
Replace x.y.z with latest version:  
![GitHub release (latest by date)](https://img.shields.io/github/v/release/trustwallet/wallet-core)

## iOS

We currently support only CocoaPods. Add this line to your Podfile and run `pod install`:

```ruby
pod 'TrustWalletCore'
```

# License

My Wallet Core is available under the MIT license. See the [LICENSE](LICENSE) file for more info.
