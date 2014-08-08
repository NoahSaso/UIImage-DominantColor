UIImage-DominantColor
=====================

A simple API to grab the dominant/average color from a UIImage

Code grabbed from: https://github.com/NikolaiRuhe/UIImageAverageColor

Re-made by Sassoty to make it easier to import in your projects (git submodule, etc.)

Usage
=====

```objc
#import "UIImage+DominantColor.h"

UIImage* image = [UIImage imageWithContentsOfFile:@"Icon.png"];
UIColor* domColor = [image dominantColor];
```
