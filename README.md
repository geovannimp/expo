[![Expo](/style/header.png)](https://expo.io)

<p align="center">
 
   <a aria-label="SDK version" href="https://www.npmjs.com/package/expo" target="_blank">
    <img alt="Expo SDK version" src="https://img.shields.io/npm/v/expo.svg?style=flat-square&label=SDK&labelColor=000000&color=4630EB">
  </a>
    
  <a aria-label="Join our forums" href="https://forums.expo.io" target="_blank">
    <img alt="" src="https://img.shields.io/badge/Ask%20Questions%20-blue.svg?style=flat-square&logo=discourse&logoWidth=15&labelColor=000000&color=4630EB">
  </a>
  <a aria-label="Follow @expo on Twitter" href="https://twitter.com/expo" target="_blank">
    <img alt="Twitter: expo" src="https://img.shields.io/twitter/follow/expo.svg?style=flat-square&label=Follow%20%40expo&logo=TWITTER&logoColor=FFFFFF&labelColor=00aced&logoWidth=15&color=lightgray" target="_blank" />
  </a>

  <a aria-label="Expo is free to use" href="https://github.com/expo/expo/blob/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-success.svg?style=flat-square&color=33CC12" target="_blank" />
  </a>
<a aria-label="expo downloads" href="http://www.npmtrends.com/expo" target="_blank">
    <img alt="Downloads" src="https://img.shields.io/npm/dm/expo.svg?style=flat-square&labelColor=gray&color=33CC12&label=Downloads" />
</a>
    <br>
    <a aria-label="Circle CI" href="https://circleci.com/gh/expo/expo/tree/master">
    <img alt="Circle CI" src="https://flat.badgen.net/circleci/github/expo/expo?label=Circle%20CI&labelColor=555555&color=33CC12&&icon=circleci">
  </a>
  
</p>

<p align="center">
    Check out our documentation <a aria-label="expo documentation" href="https://docs.expo.io">https://docs.expo.io</a> to learn more about developing with Expo.
  <br />

</p>

---

- [🗺 Project Layout](#-project-layout)
- [👏 Contributing](#-contributing)
- [❓ FAQ](#-faq)
- [💙 The Team](#-the-team)
- [License](#license)

Expo is an open-source platform for making universal native apps that run on Android, iOS, and the web. It includes a universal runtime and libraries that let you build native apps by writing React and JavaScript. This repository is where the Expo client software is developed, and includes the client apps, modules, apps, and more. The [Expo CLI](https://github.com/expo/expo-cli) repository contains the Expo development tools.

[Click here to view the Expo Community Guidelines](https://expo.io/guidelines). Thank you for helping keep the Expo community open and welcoming!

## 🗺 Project Layout

- [`packages`](/packages) All the source code for the Unimodules, if you want to edit a library or just see how it works this is where you'll find it.
- [`apps`](/apps) This is where you can find Expo projects which are linked to the development Unimodules. You'll do most of your testing in here.
- [`docs`](/docs) The source code for **https://docs.expo.io**
- [`templates`](/templates) The template projects you get when you run `expo start`
- [`react-native-lab`](/react-native-lab) This is our fork of `react-native`. We keep this very close to the upstream but sometimes need to add quick fixes locally before they can land.
- [`guides`](/guides) In-depth tutorials for our most advanced topics like contributing to the client.
- [`android`](/android) contains the Android project.
- [`home`](/home) contains the JavaScript source code of the app.
- [`ios`](/ios) contains the iOS project.
- [`ios/Exponent.xcworkspace`](/ios) is the Xcode workspace. Always open this instead of `Exponent.xcodeproj` because the workspace also loads the CocoaPods dependencies.
- [`tools-public`](/tools-public) contains build and configuration tools.
- [`template-files`](/template-files) contains templates for files that require private keys. They are populated using the keys in `template-files/keys.json`.
- [`template-files/ios/dependencies.json`](/template-files/ios/dependencies.json) specifies the CocoaPods dependencies of the app.

## 👏 Contributing

If you like Expo and want to help make it better then check out our [contributing guide](/CONTRIBUTING.md)! Check out the [Expo CLI repo](http://github.com/expo/expo-cli) to work on the Expo CLI, and various other universal development tools.

## ❓ FAQ

If you have questions about Expo and want answers, then check out our [Frequently Asked Questions](https://docs.expo.io/versions/latest/introduction/faq/)!

If you still have questions you can ask them on our [forums](https://forums.expo.io) or on Twitter [@Expo](https://twitter.com/expo).

## 💙 The Team

Curious about who makes Expo? Here are our [team members](https://expo.io/about)!

## License

The Expo source code is made available under the [MIT license](LICENSE). Some of the dependencies are licensed differently, with the BSD license, for example.
