# AppleSystemApps
[ [RU](https://github.com/itsflameee/AppleSystemApps/blob/main/README_ru.md) / [**EN**](https://github.com/itsflameee/AppleSystemApps/blob/main/README.md) ] 

A collection of original system .ipa apps dumped from iOS 18, featuring a detailed compatibility list for sideloading

## What is this?
In this repository, you can find a variety of system applications pre-extracted from the iOS 18.7.9 firmware for iPhone XS ([iPhone11,2,iPhone11,4,iPhone11,6_18.7.9_22H355_Restore.ipsw](https://ipsw.me/download/iPhone11,2/22H355/)). All compatibility tests were conducted on an iPhone 14 Pro Max running iOS 18.6.2, using LiveContainer to sideload the system apps. A complete list of these applications is provided in the table below.

## Compatibility
All applications from this repository can be installed inside LiveContainer, but not all of them will launch or function properly. To understand how a specific application behaves, please refer to the application list.
In the application list, compatibility status is displayed in the corresponding column. The status variants are defined below:

* **⭕ Does not launch** - the app installs in LiveContainer and displays metadata, but crashes the container upon launch attempt.
* **🔴 UI does not render** - the app launches, but the UI fails to render (displays a static black or white screen).
* **🟠 Incomplete UI only** - the app renders the UI with minor issues, but the main core functionality is unavailable.
* **🟡 UI only** - the app renders the UI properly, but the application's features are completely non-functional.
* **🟢 Launches** - the app opens but has highly limited functionality.
* **🔵 Working** - the app launches and functions with minor bugs or slight UI rendering issues.
* **🟣 Perfect** - the app is fully functional with no noticeable issues.


## Application List
### (from iPhone XS 18.7.9, tested on iPhone 14 Pro Max with iOS 18.6.2)
| Icon | App Name | Bundle ID | File | Compatibility | Known Issues | Working Features | 
| :---: | --- | --- | --- | :-------: | --- | --- |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Phone%20Icon.png?raw=true" width="45" height="45"/> | Phone | com.apple.mobilephone | [MobilePhone.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/MobilePhone.ipa) | **🔵 Working** | "Voicemail" tab is unavailable; making calls triggers an iOS system pop-up confirmation prompt | Making calls, adding and viewing contacts |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Camera%20Icon.png?raw=true" width="45" height="45"/> | Camera | com.apple.camera | [Camera.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Camera.ipa) | **🟢 Launches** | Captured photos/videos are not saved to the device storage; using Cinematic or Portrait mode causes a crash | Camera viewfinder display, switching lenses, viewing previously saved photos/videos, visual ProRAW/ProRES toggles, Action Mode |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Settings%20Icon.png?raw=true" width="45" height="45"/> | Settings | com.apple.preferences | [Preferences.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Preferences.ipa) | **⭕ Does not launch** | The application crashes immediately after rendering the first few frames | None |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Siri%20Icon.png?raw=true" width="45" height="45"/> | Siri | com.apple.siri | [Siri.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Siri.ipa) | **🔴 UI does not render** | The UI does not display upon launch, though the application process does not crash | None |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Calculator%20Icon.png?raw=true" width="45" height="45"/> | Calculator | com.apple.calculator | [Calculator.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Calculator.ipa) | **🟣 Perfect** | "Math Notes" mode fails to work due to the absence of the native system Notes app | All original functionality except for "Math Notes" |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/PosterBoard%20Icon.png?raw=true" width="45" height="45"/> | PosterBoard | com.apple.PosterBoard | [PosterBoard.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/PosterBoard.ipa) | **🟡 UI only** | System wallpapers do not load (as they are missing within the container environment) | Basic UI elements inherited from standard PosterBoard |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/App%20Store%20Icon.png?raw=true" width="45" height="45"/> | App Store | com.apple.AppStore | [AppStore.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/AppStore.ipa) | **🟡 UI only** | Due to the inability to sign in with an Apple ID, core features are unavailable | All basic UI elements |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Apple%20Vision%20Pro%20Icon.png?raw=true" width="45" height="45"/> | Apple Vision Pro | com.apple.visionproapp | [AppleVisionProApp.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/AppleVisionProApp.ipa) | **🔴 UI does not render** | The UI does not display upon launch, though the application process does not crash | None |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/FaceTime%20Icon.png?raw=true" width="45" height="45"/> | FaceTime | com.apple.facetime | [FaceTime.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/FaceTime.ipa) | **⭕ Does not launch** | The application crashes before rendering any UI | None |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Files%20Icon.png?raw=true" width="45" height="45"/> | Files | com.apple.DocumentsApp | [Files.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Files.ipa) | **🟢 Launches** | The native iOS file system does not display in any capacity | Document scanning, connecting to a remote server |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/FindMy%20Icon.png?raw=true" width="45" height="45"/> | FindMy | com.apple.findmy | [FindMy.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/FindMy.ipa) | **⭕ Does not launch** | The application crashes before rendering any UI | None |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Fitness%20Icon.png?raw=true" width="45" height="45"/> | Fitness | com.apple.Fitness | [Fitness.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Fitness.ipa) | **🔴 UI does not render** | The UI does not display upon launch, though the application process does not crash | None |
| <img src="https://github.com/itsflameee/AppleSystemApps/blob/main/Health%20Icon.png?raw=true" width="45" height="45"/> | Health | com.apple.Health | [Health.ipa](https://github.com/itsflameee/AppleSystemApps/releases/download/systemapps1/Health.ipa) | **⭕ Does not launch** | The application crashes before rendering any UI | Prompts for permission to access data from the native "Health" system app on first launch |
