# ios-extensions
🎉 Collection of Swift iOS-related extensions for various use cases. Many of the extension works on macOS, tvOS and watchOS. Basically it's a collection of extensions that I started implementing for my own needs. There are about `30` different extensions. Feel free to constribute something new and amazing. 

# List of extensions
All the extensions are split into separete `groups` each of which represents a separete `SDK framework`. 

## Core Graphics
### CGRect
- [CGRect+Scale](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/CoreGraphics/CGRect%2BScale.swift)
- [CGRect+Mid](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/CoreGraphics/CGRect%2BMid.swift)

## Foundation
### Bool
- [Bool+Int](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Bool/Bool%2BInt.swift)
- [Bool+Random](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Bool/Bool%2BRandom.swift)
### ClosedRange
- [ClosedRange+Random](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/ClosedRange/ClosedRange%2BRandom.swift)   
### Collection 
- [Collection+ParallelIteration](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Collection/Collection%2BParallelIteration.swift)
- [Collection+RandomItem](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Collection/Collection%2BRandomItem.swift)
- [Collection+Sum&Average](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Collection/Collection%2BSum%26Average.swift)
### Dictionary
- [Dictionary+JSON](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Dictionary/Dictionary%2BJSON.swift)
### Int
- [Int+Clamp](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Int/Int%2BClamp.swift)
- [Int+Digita](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Int/Int%2BDigits.swift)
- [Int+EvenOdd](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Int/Int%2BEvenOdd.swift)
- [Int+Factorial](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Int/Int%2BFactorial.swift)
- [Int+Power](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Int/Int%2BPower.swift)
- [Int+Random](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Int/Int%2BRandom.swift)
- [Int+Roman](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Int/Int%2BRoman.swift)
### MutableCollection 
- [MutableCollection+Shuffle](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/MutableCollection/MutableCollection%2BShuffle.swift)

### Sequence  
- [Sequence+Shuffle](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Foundation/Sequence/Sequence%2BShuffle.swift)

## UIKit
### UIImage
- [UIImage+LandscapeCameraOrientationFix](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/UIKit/UIImage/UIImage%2BLandscapeCameraOrientationFix.swift)
- [UIImage+RawOrientation](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/UIKit/UIImage/UIImage%2BRawOrientation.swift)
- [UIImage+Resize](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/UIKit/UIImage/UIImage%2BResize.swift)
- [UIImage+SolidColor](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/UIKit/UIImage/UIImage%2BSolidColor.swift)

### UIImageView
- [UIImageView+DownloadFromURL](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/UIKit/UIImageView/UIImageView%2BDownloadFromURL.swift)
- [UIImageView+Masking](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/UIKit/UIImageView/UIImageView%2BMasking.swift)

## SpriteKit
### SKScene
- [SKScene+SerialSpriteLoading](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/SpriteKit/SKScene/SKScene%2BSerialSpriteLoading.swift)

### SKTexture
- [SKTexture+LinearGradient](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/SpriteKit/SKTexture/SKTexture%2BLinearGradient.swift)

### SKTextureAtlas
- [SKTextureAtlas+FramesLoader](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/SpriteKit/SKTextureAtlas/SKTextureAtlas%2BFramesLoader.swift)

## SceneKit
- [SCNVector3+Operators](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/SceneKit/SCNVector3%2BOperators.swift)

## Grapnd Central Dispatch
- [DispatchQueue+DispatchOnce](https://github.com/jVirus/ios-extensions/blob/master/ios-extensions/Extensions/Grand%20Central%20Dispatch/DispatchQueue%2BDispatchOnce.swift)


# Contributing 
- There is just one main rule for contributors - **please include your extensions in separete files**. It's important since such extension can be more easily referenced and reused.
- The other `soft` rule is - please include `unit tests` with your extensions. 

# Author 
[Astemir Eleev](https://github.com/jVirus)

# Licence
The project is available under [MIT licence](https://github.com/jVirus/ios-extensions/blob/master/LICENSE)