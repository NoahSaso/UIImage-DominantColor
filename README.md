UIImage-DominantColor
=====================

A simple API to determine the dominant/average color from a UIImage instance

Code grabbed from: https://github.com/NikolaiRuhe/UIImageAverageColor

Modified to ease the process of incorporating into projects (git submodule, etc.)

Usage
=====

```objc
#import "UIImage+DominantColor.h"

UIImage* image = [UIImage imageWithContentsOfFile:@"Icon.png"];
UIColor* domColor = [image dominantColor];
```
