My Wallet Core is an open source, cross-platform, mobile-focused library
implementing low-level cryptographic wallet functionality for a high number of blockchains.
It is a core part of the popular [My Wallet](https://www.mywalletbsc.com), and some other projects.
Most of the code is C++ with a set of strict C interfaces, and idiomatic interfaces for supported languages:
Swift for iOS and Java for Android.

![iOS CI]
![Android CI]
![Linux CI]
![Docker CI]
![Typescript CI]

[![Gitpod Ready-to-Code]
![GitHub]
![GitHub release (latest by date)]
![Cocoapods]
![Cocoapods platforms]

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
    implementation 'com.mywallet:wallet-core:x.y.z'
}
```
Replace x.y.z with latest version:  
![GitHub release (latest by date)](https://img.shields.io/github/v/release/mywallet/wallet-core)

## iOS

We currently support only CocoaPods. Add this line to your Podfile and run `pod install`:

```ruby
pod 'myWalletCore'
```

# License

My Wallet Core is available under the MIT license. See the [LICENSE](LICENSE) file for more info.
