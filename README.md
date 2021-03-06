# Minamo

[![Pod Version](http://img.shields.io/cocoapods/v/Minamo.svg?style=flat)](http://cocoadocs.org/docsets/Minamo/)
[![Pod Platform](http://img.shields.io/cocoapods/p/Minamo.svg?style=flat)](http://cocoadocs.org/docsets/Minamo/)
[![Pod License](http://img.shields.io/cocoapods/l/Minamo.svg?style=flat)](http://opensource.org/licenses/MIT)

Simple coach mark library written in Swift

![Demo](https://cloud.githubusercontent.com/assets/6880730/12576111/bf03362a-c454-11e5-95af-4a1670935f9e.gif)

## Usage

#### Initialize

``` swift
let rippeleView = RippleView()
rippeleView.tintColor = UIColor(red: 0.3, green: 0.7, blue: 1, alpha: 1)
rippeleView.coreImage = UIImage(named: "q")
```

#### Appear at the UIView

``` swift
rippeleView.appearAtView(someView)
```

#### Appear at the UIBarButtonItem

``` swift
if let buttonItem = navigationItem.rightBarButtonItems?.first {
    rippeleView.appearAtBarButtonItem(buttonItem, offset: CGPointMake(-10, 10))
}
```

#### Dismiss

``` swift
rippleView.disappear()
```

## Properties

`RippleView` has some properties.

* duration
* coreImage
* coreHidden
* ringScale
* ringWidth
* ringHidden
* contentInset

## Installation

#### CocoaPods

```
pod 'Minamo'
```

## License

Minamo is released under the MIT license. See LICENSE for details.
