iOS-UserPreferences
================

iOS-UserPreferences provides convenience methods to get and set user preferences.

# Installation
If you're using [CocoaPods](http://cocoapods.org), then simply insert `pod 'iOS-iOS-UserPreferences'` in your application's `Podfile`.

Otherwise, copy  `iOS-UserPreferences.h` and `iOS-UserPreferences.m` into your project.

# Examples

>
    BOOL userWantsSoundOn = [UserPreferences getBoolWithKey:@"soundOn" withDefault:YES];
    [UserPreferences setInt:10 withKey:@"volume"];

    if ([UserPreferences isKeyUndefinedThenDefine:@"firstTime"]) {
        //  show intro
    }

# Authors
Norman Basham - [@nbasham](http://github.com/nbasham/)

# License
iOS-UserPreferences is made available under the Apache 2.0 License. A full copy of the license is available in the LICENSE file.