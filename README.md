# RealmDemo
Basic Operations(insert, update, delete &amp;amp; select Records) with Realm Database.

### Introduction ###

Realm is a cross platform mobile database for iOS (available in Swift & Objective-C) and Android. Realm is built to be better and faster than SQLite and Core Data.

### Requirements ###

  * XCode 8.3.3 or higher
  * Target of iOS 8 or higher, macOS 10.9 or higher
  
### Documentation ###
  
  * Documentation can be found at <https://realm.io/docs/swift/latest>
  
### Installation ###
  
  #### CocoaPods ####
  
   1. Install CocoaPods 1.1.0 or later. 
   2. Run pod repo update to make CocoaPods aware of the latest available Realm versions. 
   3. In your Podfile, add use_frameworks! and pod 'RealmSwift' to your main and test targets. 
   4. From the command line, run pod install. 
   5. Use the .xcworkspace file generated by CocoaPods to work on your project!

#### Carthage ####

  1. Install Carthage 0.17.0 or later. 
  2. Add github "realm/realm-cocoa" to your Cartfile. 
  3. Run carthage update. 
  4. Drag RealmSwift.framework and Realm.framework from the appropriate platform directory in Carthage/Build/ to the “Linked Frameworks and Libraries” section of your Xcode project’s “General” settings.
  
### Realm Studio ###

  * You can download Realm Studio from here <https://realm.io/products/realm-studio/#download-studio>