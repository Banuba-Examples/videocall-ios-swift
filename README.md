The example shows how to get started using Banuba [Face AR SDK](https://docs.banuba.com/face-ar-sdk-v1/ios/ios_getting_started) and [Agora.io](https://www.agora.io/en/) SDK to enhance video calls with real-time face filters and virtual backgrounds.  
  
**Important**  
Please use [v0.x](../../tree/v0.x) branch for SDK version 0.x (e.g. v0.38).  
  
# Getting Started

1. Get the latest Banuba SDK archive for iOS and the client token. Please fill in our [form on banuba.com](https://www.banuba.com/face-filters-sdk) website, or contact us via [info@banuba.com](mailto:info@banuba.com).
2. Copy `BanubaEffectPlayer.xcframework` and `BanubaSdk` project folder from the Banuba SDK archive into `Frameworks` dir:
    `BNBEffectPlayer/bin/BanubaEffectPlayer.xcframework` => `videocall-ios-swift/Frameworks/`
    `BNBEffectPlayer/src/BanubaSdk/BanubaSdk/BanubaSdk` => `videocall-ios-swift/Frameworks/`
    `BNBEffectPlayer/src/BanubaSdk/BanubaSdk/BanubaSdk.xcodeproj` => `videocall-ios-swift/Frameworks/`
3. Run `pod install` for this project in order to install AgoraRtcEngine_iOS
4. Visit agora.io to sign up and get token, app and channel ID
5. Copy and Paste your banuba and agora token, app and chanel ID into appropriate section of `videocall-ios-swift/videocall-ios-swift/TokenService.swift`
6. Open the project in xCode and run the example.

# Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

