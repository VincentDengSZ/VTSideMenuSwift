# VTSideMenu
A simple Swift sideMenu lib for iOS

# GIF
![](https://github.com/VincentDengSZ/VTSideMenuSwift/raw/master/VTSideMenuSwift.gif)

#Requirements

iOS 8.0+

Swift 3.0+

#Getting Started

**Using [CocoaPods](http://cocoapods.org)**

1.Add the pod `VTSideMenu` to your [Podfile](http://guides.cocoapods.org/using/the-podfile.html).
```ruby
pod 'VTSideMenu', '~> 1.0.0'
```
2.Run `pod install` from Terminal, then open your app's `.xcworkspace` file to launch Xcode.

3.`#import UIViewController+SideMenu.h` wherever you want to use the API.

**Manually from GitHub**

1.Download the `UIViewControllerSideMenu.swift` , `VTSideMenuManager.swift` files in th [Source directory](https://github.com/VincentDengSZ/VTSideMenuSwift)  


2.Add the files to your Xcode project.

3.you don't need to import any file if you use the api Manually with Swift
#Example Usage

**Example location**

Check out the [example project](https://github.com/VincentDengSZ/VTSideMenuSwift/tree/master/VTSideMenuSwiftDemo) included in the repository. It contains a few demos of the API in use for various scenarios. 

**Usage**

The way to create a SideMenu:


```Swift

VTSideMenuManager.initSideMenu(sideMenu: SideMenuViewController(), width: 250)

```

The way to make side menu slide out:


```Swift

 self.sideMenuSlideOut()// called by a UIViewController instance 

```
The way to make side menu slide int:


```Swift

self.sideMenuSlideIn() // called by a UIViewController instance 

```

#License
MIT

