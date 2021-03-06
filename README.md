Swift
=====

## Tools

* [Online Swift Playground - http://online.swiftplayground.run/](http://online.swiftplayground.run/)

## Apple's Official Documentation

* [Apple's Github Page](https://github.com/apple)
* [Swift's Bug Tracker (JIRA)](https://bugs.swift.org/secure/Dashboard.jspa)
* [Official Apple Site](https://developer.apple.com/swift/)
* [Swift Resources](https://developer.apple.com/swift/resources/)
* [About Swift](https://developer.apple.com/library/prerelease/ios/documentation/Swift/Conceptual/Swift_Programming_Language/)
* [Language Guide](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)
* [Language Reference](https://docs.swift.org/swift-book/ReferenceManual/AboutTheLanguageReference.html)
* [The Swift Programming Language - iBook](https://itunes.apple.com/us/book/the-swift-programming-language/id881256329?mt=11)
* [Apple's Swift Book - Revision History](https://docs.swift.org/swift-book/)

    
## Open Source Swift

* [Swift Evolution Proposals Index](https://apple.github.io/swift-evolution/)
* [Source Code](https://github.com/apple/swift)


### Regular Expressions

* https://nshipster.com/swift-regular-expressions/

### JSON Parsing

* https://developer.apple.com/swift/blog/?id=37
* https://www.hackingwithswift.com/example-code/system/how-to-parse-json-using-jsonserialization

----------------

## Libraries / Tools / Examples

### NSNotificationCenter

* http://www.andrewcbancroft.com/2014/10/08/fundamentals-of-nsnotificationcenter-in-swift/
* 

## iOS Libs List

- https://github.com/mrkd/ios-libs


### Websockets

* [WWDC19 Advances in Networking](https://developer.apple.com/videos/play/wwdc2019/712/)
   - URLSession supports websockets now
* https://github.com/daltoniam/starscream
* https://github.com/tidwall/SwiftWebSocket

## Time / Dates

* https://github.com/malcommac/SwiftDate

## Reactive Swift

* [Combine - WWDC19](https://developer.apple.com/documentation/combine)
* [Reactive Cocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)
* [RxSwift](https://github.com/kzaher/RxSwift) - Microsoft Reactive Extensions (Rx) for Swift and iOS/OSX platform

## Models

### JSON -> Swift Models

* [SwiftyJSONAccelerator](https://github.com/insanoid/SwiftyJSONAccelerator) - Code Generation from JSON

#### Example Apps

* https://github.com/ColinEberhardt/ReactiveSwiftFlickrSearch
* [Eidolon by Artsy](https://github.com/artsy/eidolon)
  * [Blog post on Developing a Bidding Kiosk for iOS in Swift](https://artsy.github.io/blog/2014/11/13/eidolon-retrospective/)


## Server Side Swift

* Vapor - https://vapor.codes
* Kitura - https://github.com/IBM-Swift/Kitura

## Swift on Raspberry Pi

- [Official Swift-Arm Community Releases](https://swift-arm.com/2019/01/07/official-swift-arm-community-releases/)
- [SwiftyGPIO](https://github.com/uraimo/SwiftyGPIO)

### Install Swift on Pi (March 2019)

`$ curl -s https://packagecloud.io/install/repositories/swift-arm/release/script.deb.sh | sudo bash
sudo apt install swift4`

`$ sudo apt-get install swift4`

You should see swift version after running:

`$ swift --version`

Example:

```
$ swift --version
Swift version 4.2.3 (swift-4.2.3-RELEASE)
Target: armv7-unknown-linux-gnueabihf
```

### Install Vapor Example

```
$ sudo apt install git

$ sudo apt-get install openssl
$ sudo apt-get install libssl1.0

$ git clone https://github.com/twostraws/vapor-clean

$ swift build

$ swift run Run --hostname 0.0.0.0 --port 8080
```



```

```
----------
## Courses

* [Developing iOS 11 Apps with Swift](https://itunes.apple.com/us/course/developing-ios-11-apps-with-swift/id1309275316)
  * this is a great resource, taught by Paul Hegarty
* Udacity's Swift Courses
  * [Intro to iOS App Development with Swift](https://www.udacity.com/course/intro-to-ios-app-development-with-swift--ud585)
  * [iOS Networking with Swift - Web Services, APIs, and JSON](https://www.udacity.com/course/ios-networking-with-swift--ud421)
  * [Xcode Debugging - Print Statements, Breakpoints, and LLDB](https://www.udacity.com/course/xcode-debugging--ud774)
  * [iOS Persistence and Core Data - Storing Your App’s Data](https://www.udacity.com/course/ios-persistence-and-core-data--ud325)
* [Plymouth University: iOS Development in Swift](https://itunes.com/PlymouthSwift)

## Collection of links, resources, and snippets for Swift
* [Awesome Swift](https://github.com/matteocrippa/awesome-swift)
* https://swiftnews.curated.co
* Community supported list of iOS / OS X Swift libraries - [http://www.swifttoolbox.io](http://www.swifttoolbox.io)
* Auto Generated Documentation - [http://swifter.natecook.com](http://swifter.natecook.com)
* [Practical Swift](http://practicalswift.com/)
* [List of Swift tutorials maintained by Jameson Quave](http://jamesonquave.com/blog/tutorials/) 
* We love Swift - http://www.weheartswift.com/one-month-swift/
* http://www.h4labs.com/dev/ios/swift.html
* https://github.com/melling/SwiftResources


* Curated list of helpful resources to learn Swift - [www.learnswift.tips](http://www.learnswift.tips/)

## Articles / Discussions about Swift
* [The point of optionals?](http://www.bornsleepy.com/bornsleepy/point-optionals)
* 

## Books and Upcoming Books
* [Learn Swift](http://books.aidanf.net/learn-swift)
* [The Swift Programming Language - iBook](https://itunes.apple.com/us/book/the-swift-programming-language/id881256329?mt=11)
* [A Swift Kickstart by Daniel H Steinberg](https://itunes.apple.com/us/book/a-swift-kickstart/id891801923?mt=11)
* [Your first Swift App](https://leanpub.com/yourfirstswiftapp)
  * [Code for Your first Swift App](https://github.com/AshFurrow/yourfirstswiftapp)
* [Developing iOS 8 Apps in Swift](http://jamesonquave.com/swiftebook/)
* [Functional Programming in Swift](http://www.objc.io/books/)
* [Ray Wenderlich's Books](http://www.raywenderlich.com/74832/three-new-swift-books)
* [Ash Furrow's Swift Book](https://leanpub.com/swift_book)


## Videos
* Note: WWDC videos work best in the [Safari browser](https://www.apple.com/safari/)
* [WWDC 2014 - Introduction to Swift](http://devstreaming.apple.com/videos/wwdc/2014/402xxgg8o88ulsr/402/402_hd_introduction_to_swift.mov)
* [WWDC 2014 - Swift Playgrounds](http://devstreaming.apple.com/videos/wwdc/2014/408xxcm26svis12/408/408_hd_swift_playgrounds.mov)
* [dotswift 2015](http://www.thedotpost.com/conference/dotswift-2015)

### realm.io meetup videos

This is a list of an awesome resource from [realm.io's](realm.io) [blog](http://realm.io/news)
* [Jan 14, 2016 - Unidirectional Data Flow in Swift: An Alternative to Massive View Controllers](https://realm.io/news/benji-encz-unidirectional-data-flow-swift/)
* [Conquering Your Fear of Adopting Swift](https://realm.io/news/slug-brennan-stehling-conquering-fear-adopting-swift/)
* [Introduction to Protocol-Oriented MVVM](https://realm.io/news/doios-natasha-murashev-protocol-oriented-mvvm/)
* [Challenges Building a Swift Framework](https://realm.io/news/marius-rackwitz-challenges-building-swift-framework/)
* [Embrace Immutability](https://realm.io/news/slug-keith-smiley-embrace-immutability/)
* [Top 5 meetup videos for 2014](http://realm.io/news/top-5-swift-videos-of-2014/)
* [Swift for Javascript Developers](http://realm.io/news/swift-for-javascript-developers/)
* [Swift: Enums, Pattern Matching & Generics](http://realm.io/news/swift-enums-pattern-matching-generics/)
  * special guest: Chris Lattner, the creator of Swift! 
* [Converting Objective-C to Swift](http://realm.io/news/converting-objc-to-swift/)
* [Functional Programming in Swift](http://realm.io/news/functional-programming-swift-chris-eidhof/)
* [Swift and Objective-C: Best Friends Forever?](http://realm.io/news/swift-objc-best-friends-forever/)
* [Swift for Command-Line Tools](http://realm.io/news/swift-for-CLI/)
* [Enums, Pattern Matching & Generics](http://realm.io/news/swift-enums-pattern-matching-generics/)
* [Building tableviews in Swift](http://realm.io/news/building-tableviews-swift-ios8/)

## Style Guides / Best Practices
* [Vokal Engineering's Swift Style Guide](https://engineering.vokal.io/iOS/Swift.md.html)
* [Github's Swift style guide](https://github.com/github/swift-style-guide)
* [SlideShare Swift Style Guide](https://github.com/SlideShareInc/swift-style-guide/blob/master/swift_style_guide.md)
* [Best practices for software development with Swift](https://github.com/schwa/Swift-Community-Best-Practices/)
* [SwiftLint - An experimental tool to enforce Swift style and conventions.](https://github.com/realm/SwiftLint)
* [Ray Wenderlich](https://github.com/raywenderlich/swift-style-guide)
* [sportngin](https://github.com/sportngin/styleguide/blob/master/swift.md)

## Cheat Sheets
* [Swift Cheat Sheet and Quick Reference - Ray Wenderlich](http://www.raywenderlich.com/73967/swift-cheat-sheet-and-quick-reference)
* [Swift Cheat Sheet - github.com/grant/swift-cheat-sheet](https://github.com/grant/swift-cheat-sheet)







