# ZSign Framework

## What is this repo?
It's a repository for helping iOS developers be more efficient and consume less time. Instead of grabbing the whole ZSign source code, you can drop the `.framework` in the app and call it via `#include` on Obj-C++ or `#import` on Swift.

## How to use it?
Drag the framework into your iOS app and use these in your script

- **FOR OBJECTIVE-C++ SCRIPTS:**  
```cpp
#include <ZSign/zsign.hpp>
```
- FOR SWIFT SCRIPTS (ZSign-Bridging-Header.h)
```swift
#import <ZSign/zsign.hpp>
```
