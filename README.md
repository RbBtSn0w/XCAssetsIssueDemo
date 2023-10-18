# XCAssetsIssueDemo

[![CI Status](https://img.shields.io/travis/RbBtSn0w/XCAssetsIssueDemo.svg?style=flat)](https://travis-ci.org/RbBtSn0w/XCAssetsIssueDemo)
[![Version](https://img.shields.io/cocoapods/v/XCAssetsIssueDemo.svg?style=flat)](https://cocoapods.org/pods/XCAssetsIssueDemo)
[![License](https://img.shields.io/cocoapods/l/XCAssetsIssueDemo.svg?style=flat)](https://cocoapods.org/pods/XCAssetsIssueDemo)
[![Platform](https://img.shields.io/cocoapods/p/XCAssetsIssueDemo.svg?style=flat)](https://cocoapods.org/pods/XCAssetsIssueDemo)

## Background

This is a DSL attribute in a podspec for CocoaPods called "resources". When encountering files in the Asset Catalog format included in the "resources", they will be handled and executed together in the "Pods-YOURTARGET-resources.sh" script.
[Detailed issue](https://github.com/CocoaPods/CocoaPods/issues/8431)

To better validate how to solve this issue, the demo includes a custom script to handle the aforementioned problem.
[Technical implementation logic](https://github.com/CocoaPods/CocoaPods/issues/8431#issuecomment-1594534923)

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

XCAssetsIssueDemo is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'XCAssetsIssueDemo'
```

## Author

RbBtSn0w, hamiltonsnow@gmail.com

## License

XCAssetsIssueDemo is available under the MIT license. See the LICENSE file for more info.
