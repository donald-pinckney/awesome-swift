# Awesome Swift
A curated list of awesome Swift frameworks, libraries and software. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

- [Core Swift Libraries](#core-swift-libraries) <br />
*That which is central to improving the Swift Langauge.*
	
	- [Timepiece](https://github.com/naoty/Timepiece)
	- [ExSwift](https://github.com/pNre/ExSwift)
	- [Easy-Cal-Swift](https://github.com/onevcat/Easy-Cal-Swift)
	
- [Secondary Libraries and Frameworks](#primary-libraries-and-frameworks) <br />
*What you might use in the actual code of an app.*

	- [General Purpose Swift Additions](#general-purpose-swift-additions)
	- [JSON / XML Manipulation](#jsonxml-manipulation)
	- [HTTP and Networking](#http-and-networking)
	- [Databases](#databases)
	- [UI](#ui)
	- [Colors](#colors)
	- [Fonts](#fonts)
	- [Time / Date Manipulation](#timedate-manipulation)
	- [Events](#events)
	- [Promises](#promises)
	- [Queue](#queue)
	- [Caching](#caching)
	- [Security](#security)
	- [Logging](#logging)
	- [Location](#location)
	- [Push Notifications](#push-notifications)
	- [Payment](#payment)
	- [Audio](#audio)
	- [Math](#math)
	- [Third Party APIs](#third-party-apis)
	- [Misc](#misc)
	
- [Awesome Libraries or Tools](#helpful-libraries-or-tools) <br />
*Awesome helpful and supporting tools for development.*

	- [Code Quality](#code-quality)
	- [Project Management](#project-management)
	- [Testing](#testing)
	- [Documentation](#documentation)

- [Resources](#resources)
	- [Swift Books](#swift-books)
	- [Swift Videos](#swift-videos)
	- [Swift Playgrounds](#swift-playgrounds)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

# Primary Libraries and Frameworks

## UI
* [FlourishUI](https://github.com/unicorn/FlourishUI) - Framework for modals, color extensions and buttons. 
* [FontAwesome.swift](https://github.com/thii/FontAwesome.swift) - Use FontAwesome in your Swift projects.
* [SwiftOverlays](https://github.com/peterprokop/SwiftOverlays) - GUI library for displaying various popups and notifications.
* [ios-charts](https://github.com/danielgindi/ios-charts) - A powerful chart / graph framework, the iOS equivalent to [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart).
* [TagListView](https://github.com/xhacker/TagListView) - Simple but highly customizable iOS tag list view.
* [Swiftstraints](https://github.com/Skyvive/Swiftstraints) - Powerful auto-layout framework that lets you write constraints in one line of code.
* [Cartography](https://github.com/robb/Cartography) - declarative auto layout lib for your project.

## Colors
* [SwiftColors](https://github.com/thii/SwiftColors) - HEX color handling as an extension for UIColor.
* [HexColor](https://github.com/artman/HexColor) - define UIColors as hex integers.
* [PrettyColors](https://github.com/jdhealy/PrettyColors) - Styles and colors text in the Terminal with ANSI escape codes. Conforms to ECMA Standard 48
* [RandomColorSwift](https://github.com/onevcat/RandomColorSwift) - An attractive color generator for Swift. Ported from randomColor.js.

## Fonts
* [Font-Awesome](https://github.com/hirohisa/Font-Awesome) - Use Font Awesome in project written in Swift.
* [FontBlaster](https://github.com/ArtSabintsev/FontBlaster) - Programmatically load custom fonts into your iOS app.

## JSON/XML Manipulation

* [SwiftyJSON](https://github.com/lingoer/SwiftyJSON) - The better way to deal with JSON data in Swift.
* [json-swift](https://github.com/owensd/json-swift) - A basic library for working with JSON in Swift.
* [Argo](https://github.com/thoughtbot/Argo) - JSON parsing library for Swift, inspired by Aeson.
* [ObjectMapper](https://github.com/Hearst-DD/ObjectMapper) - JSON Object mapping written in Swift.
* [Alamofire-SwiftyJSON](https://github.com/SwiftyJSON/Alamofire-SwiftyJSON) - Alamofire extension for serialize NSData to SwiftyJSON.
* [SWXMLHash](https://github.com/drmohundro/SWXMLHash) - Simple XML parsing in Swift.
* [AEXML](https://github.com/tadija/AEXML) - Simple and lightweight XML parser for iOS written in Swift.
* [Starscream](https://github.com/daltoniam/starscream) - WebSockets Library

## Time/Date Manipulation

* [Timepiece](https://github.com/naoty/Timepiece) - Intuitive NSDate extensions in Swift
* [AFDateHelper](https://github.com/melvitax/AFDateHelper) - Simple date helper.
* [Punctual.swift](https://github.com/harlanhaskins/Punctual.swift) - Swift date handler
* [SwiftMoment](https://github.com/akosma/SwiftMoment) - A time and calendar manipulation library.
* [SwiftyTimer](https://github.com/radex/SwiftyTimer) - Swifty API for NSTimer


## Databases
*Databases implemented in Swift.*

### Custom Databases
* [Realm](https://github.com/realm/realm-cocoa) - A mobile database that runs directly inside phones, tablets or wearables.
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift) - A pure Swift framework wrapping SQLite3. Small. Simple. Safe.
* [SwiftData](https://github.com/ryanfowler/SwiftData) - A simple and effective wrapper around the SQLite3 C API written completely in Swift.
* [Squeal](https://github.com/nerdyc/Squeal) - A Swift wrapper for SQLite databases.
* [SQLiteDB](https://github.com/FahimF/SQLiteDB) - Basic SQLite wrapper for Swift.
* [YapDatabase](https://github.com/yapstudios/YapDatabase) - YapDatabase is an extensible database for iOS & Mac.

### Core Data Extensions
* [AERecord](https://github.com/tadija/AERecord) - super awesome Core Data wrapper library for iOS written in Swift.
* [JSQCoreData](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack.
* [QueryKit](https://github.com/QueryKit/QueryKit) - an easy way to play with Core Data filtering within your swift projects.

* [AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData) - A simple Core Data wrapper library written in Swift.
* [Objective Record](https://github.com/supermarin/ObjectiveRecord) - Objective Record is a lightweight ActiveRecord way of managing Core Data objects.
* [MagicalRecord](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data.
* [ios-queryable](https://github.com/martydill/ios-queryable) - ios-queryable is an implementation of IQueryable/IEnumerable for Core Data
* [Ensembles](https://github.com/drewmccormack/ensembles) - A synchronization framework for Core Data.
* [mogenerator](https://github.com/rentzsch/mogenerator) - Automatic Core Data code generation.

## Events
*Libraries for one-to-many communications.*

* [Bond](https://github.com/SwiftBond/Bond) - a Swift binding framework.
* [EmitterKit](https://github.com/aleclarson/emitter-kit) - An elegant event framework built in Swift 
* [Signals](https://github.com/artman/Signals) - replaces delegates and notifications.
* [Swift-Custom-Events](https://github.com/StephenHaney/Swift-Custom-Events) - A very simple way to implement Backbone.js style custom event listeners and triggering in Swift for iOS development.
* [SwiftEventBus](https://github.com/cesarferreira/SwiftEventBus) - A publish / subscribe event bus optimized for iOS 8

## Queue
*Libraries for working with event and task queues.*

* [TaskQueue](https://github.com/icanzilb/TaskQueue) - A Task Queue Class developed in Swift.
* [Dispatcher](https://github.com/aleclarson/dispatcher) - Queues, timers, and task groups in Swift

## HTTP and Networking
*Swift libraries and wrappers for HTTP clients.*

* [Alamofire](https://github.com/Alamofire/Alamofire) - an HTTP networking library written in Swift.
* [SwiftHTTP](https://github.com/daltoniam/SwiftHTTP) - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests.
* [Net](https://github.com/nghialv/Net) - HttpRequest wrapper written in Swift.
* [OAuthSwift](https://github.com/dongri/OAuthSwift) - Swift based OAuth library for iOS
* [Moya](https://github.com/ashfurrow/Moya) - Network abstraction layer written in Swift
* [Just](https://github.com/JustHTTP/Just) - HTTP for Humans (python-requests style HTTP library)
* [MBNetwork] (https://github.com/emaloney/MBToolbox/tree/master/Code/Network) - Network Indicator and Network Status helpers
* [swifter](https://github.com/glock45/swifter) - HTTP server written in Swift.
* [SwiftSocket](https://github.com/swiftsocket/SwiftSocket) - Swift TCP socket implementation
* [Stargate](https://github.com/contentful-labs/Stargate) - A realtime communication channel from your Mac to your Watch.

## Caching
*Libraries for caching.*

* [HanekeSwift](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images.
* [KFSwiftImageLoader](https://github.com/kiavashfaisali/KFSwiftImageLoader) - An extremely high-performance, lightweight, and energy-efficient pure Swift async web image loader with memory and disk caching for iOS and Watch.

## Security
*Libraries for generating secure random numbers, encrypting data and scanning for vulnerabilities.*

* [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language.
* [SHA256-Swift](https://github.com/CryptoCoinSwift/SHA256-Swift) - Swift framework wrapping CommonCrypto's SHA256 methods.
* [SwiftSSL](https://github.com/SwiftP2P/SwiftSSL) - An Elegant crypto toolkit in Swift.
* [AESCrypt-ObjC](https://github.com/Gurpartap/AESCrypt-ObjC) - A simple and opinionated AES encrypt / decrypt Objective-C class that just works.
* [JMEasyTouchID](https://github.com/ulidev/JMEasyTouchID) - TouchID one line wrapper.

## Logging
*Libraries for generating and working with log files.*

* [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) - A configurable and extensible pure Swift logging API that is simple, lightweight and performant.
* [XCGLogger](https://github.com/DaveWoodCom/XCGLogger) - A debug log framework for use in Swift projects.
* [Swell](https://github.com/hubertr/Swell) - A logging utility for Swift and Objective C.

## Location
* [IngeoSDK](https://github.com/IngeoSDK/ingeo-ios-sdk) - Always-On Location monitoring framework for iOS.
* [MotionKit](https://github.com/MHaroonBaig/MotionKit) - iOS device sensors wrapper

## Push Notifications
* [PEM](https://github.com/fastlane/PEM) - Automatically generate push notification profiles for your server
* [Boxcar](https://boxcar.io/developer) - Cross-platform push notification service.

## Payment
* [Stripe](https://stripe.com) - Payment integration on your app with PAY. Suitable for people with low knowledge on Backend.

## Audio
* [AudioPlayer](https://github.com/delannoyk/AudioPlayer) - A wrapper around AVPlayer with some cool features.
* [MusicKit](https://github.com/benzguo/MusicKit) - A framework for composing and transforming music in Swift

## Third Party APIs
*Libraries for accessing third party APIs.*

* [GooglePlacesAutocomplete](https://github.com/watsonbox/ios_google_places_autocomplete) - Simple Google Places address entry for iOS.
* [Swifter](https://github.com/mattdonnelly/Swifter) - A Twitter framework for iOS & OS X written in Swift
* [Federal Data SDK](https://github.com/USDepartmentofLabor/Swift-Federal-Data-SDK) - Eases access to multiple federal government OpenGov APIs

## General Purpose Swift Additions
* [Dollar.swift](https://github.com/ankurp/Dollar.swift) - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore in Javascript.
* [swiftz](https://github.com/maxpow4h/swiftz) - A Swift library for functional programming.
* [ExSwift](https://github.com/pNre/ExSwift) - JavaScript (Lo-Dash, Underscore) & Ruby inspired set of Swift extensions for standard types and classes.
* [Pythonic.swift](https://github.com/practicalswift/Pythonic.swift) - Pythonic tool-belt for Swift – a Swift implementation of selected parts of Python standard library.
* [LlamaKit](https://github.com/LlamaKit/LlamaKit) - Collection of must-have functional Swift tools.
* [ReactKit](https://github.com/ReactKit/ReactKit) - Swift Reactive Programming.

## Promises
* [PromiseKit](https://github.com/mxcl/PromiseKit) - A delightful Promises implementation for iOS.
* [Promissum](https://github.com/tomlokhorst/Promissum) - Promise library with functional combinators like `map`, `flatMap`, `whenAll` & `whenAny`.
* [Promise](https://github.com/Coneko/Promise) - Simple promises library in Swift.
* [PureFutures](https://github.com/wiruzx/PureFutures) - Futures and Promises library
* [SwiftTask](https://github.com/ReactKit/SwiftTask) - Promise + progress + pause + cancel, using SwiftState (state machine).

## Math
* [Euler](https://github.com/mattt/Euler) - Swift Custom Operators for Mathematical Notation.
* [swix](https://github.com/scottsievert/swix) - Swift Matrix and Machine Learning Library.
* [Easy-Cal-Swift](https://github.com/onevcat/Easy-Cal-Swift) - Overload +-*/ operator for Swift, make it easier to use (and not so strict).
* [Surge](https://github.com/mattt/Surge) - Accelerate framework for swift.

## Misc
* [R.swift](https://github.com/mac-cain13/R.swift/) - tool to get strong typed, autocompleted resources like images and segues in your Swift project
* [Async](https://github.com/duemunk/Async) - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch.
* [SwiftState](https://github.com/inamiy/SwiftState) - Elegant state machine for Swift.
* [CAAnimation + Closure](https://github.com/honghaoz/Swift-CAAnimation-Closure) - Add start / completion closures for CAAnimation instances
* [SwiftyUserDefaults](https://github.com/radex/SwiftyUserDefaults) — a cleaner, swiftier API for NSUserDefaults
* [Observable-Swift](https://github.com/slazyk/Observable-Swift) - Value Observing and Events for Swift.
* [iBeacon](https://github.com/gemtot/iBeacon) - iBeacon implementation in Swift
* [SystemKit](https://github.com/beltex/SystemKit) - OS X system library in Swift
* [Toucan](https://github.com/gavinbunney/Toucan) - Image processing api


# Awesome Libraries or Tools

## Code Quality
Swift lint, style enforcers, debugging tools
* [SwiftLint](https://github.com/realm/SwiftLint)
* [Chisel](https://github.com/facebook/chisel) - Collection of LLDB commands to assist debugging iOS apps
* [FLEX](https://github.com/Flipboard/FLEX) - In-app debugging and exploration tool
* [KZAsserts](https://github.com/krzysztofzablocki/KZAsserts) - Asserts on roids

## Project Management
* [CocoaPods](https://cocoapods.org) - Dependency Manager
* [Carthage](https://github.com/Carthage/Carthage) - Lightweight dependence manager
* [Amaro](https://github.com/crushlovely/Amaro) - Xcode boilerplate project generator
* [Liftoff](https://github.com/thoughtbot/liftoff) - Project Template Creation
* [Crafter](https://github.com/krzysztofzablocki/crafter) - Project Template Creation

## Testing
*Libraries for testing codebases and generating test data.*

* [Quick](https://github.com/Quick/Quick) - A behavior-driven development test framework for Swift and Objective-C.
* [Sleipnir](https://github.com/railsware/Sleipnir) - A BDD-style framework for Swift.
* [Nimble](https://github.com/Quick/Nimble) - A Matcher Framework for Swift.

## Documentation
*Libraries for generating documentation files.*

* [jazzy](https://github.com/realm/jazzy) - A soulful way to generate docs for Swift & Objective-C

# Resources
Various resources, such as books, websites and articles, for improving your Swift development skills and knowledge.

## Swift Websites

* [Official website](https://developer.apple.com/swift/) - A home page of Swift programming language.
* [Official blog](https://developer.apple.com/swift/blog/) - Official Swift Blog.
* [Jameson Quave's blog](http://jamesonquave.com/blog/category/swift/) - Tips for everyday work with Swift.
* [Swift Collection on Medium](https://medium.com/swift-programming) - Collection of blog posts about Swift on Medium.
* [Swift Collection on raywenderlich.com](http://www.raywenderlich.com/?s=swift) - Collection of blog posts about Swift on raywenderlich.
* [SwiftInFlux](https://github.com/ksm/SwiftInFlux) - An attempt to gather all that is in flux in Swift.
* [We ❤ Swift](http://www.weheartswift.com/) - Tutorials and guides.
* [Natasha The Robot](http://natashatherobot.com/) - Nice blog about Swift by Natasha The Robot.
* [LearnSwift.tips](http://www.learnswift.tips/) - A curated list of helpful resources to learn Swift. Tutorials, Code Samples, References.
 

## Swift Books

* [The Swift Programming Language](https://itunes.apple.com/us/book/the-swift-programming-language/id881256329?mt=11)
* [Using Swift with Cocoa and Objective-C](https://itunes.apple.com/us/book/using-swift-cocoa-objective/id888894773?mt=11)
* [Swift Standard Library Reference](https://developer.apple.com/library/prerelease/ios/documentation/General/Reference/SwiftStandardLibraryReference/)
* [Learn to Program iOS and OS X with Apple Swift](https://www.kickstarter.com/projects/alanforbes/learn-to-program-ios-and-os-x-with-apple-swift?utm_medium=referral&utm_source=swift.zeef.com%2Frobin.eggenkamp&utm_campaign=ZEEF)

## Swift Videos

* [TheSwiftLanguage youtube channel](https://www.youtube.com/user/TheSwiftLanguage/) - Videos about the Swift programming language by Apple.
* [Brian Advent youtube channel](https://www.youtube.com/channel/UCysEngjfeIYapEER9K8aikw/videos) - High quality Swift tutorials. 
* [SkipCasts youtube channel](https://www.youtube.com/user/SkipCasts/videos) - Skip Wilson's casts on Swift.
* [Developing iOS 8 Apps with Swift](https://itunes.apple.com/us/course/developing-ios-8-apps-swift/id961180099) - Stanford course by Paul Hegarty. 

## Swift Playgrounds

* [Learn-swift playground](https://github.com/nettlep/learn-swift) - Learn Swift interactively through these playgrounds.
* [Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift) - Design Patterns implemented in Swift.


# Other Awesome Lists

Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

# Contributing

Your contributions are always welcome! Please submit a pull request or create an issue to add a new framework, library or software to the list. Do not submit a project, which hasn't been updated in the past 6 months or is not awesome.
