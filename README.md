Flat-SlideControl
=====================

Made in [![Appus Studio](https://github.com/appus-studio/Appus-Splash/blob/master/image/logo.png)](http://appus.pro)

'Flat-SlideControl' is a control in material design, which gives you an opportunity to make a selection of a range of values

* [Demo](#demo)
* [Getting Started](#getting-started)
* [Customization](#customization)
* [Info](#info)

# Demo

##Configuration:

![](https://github.com/CrazyRA2Ivan/Test/blob/qweqwe/storyboardConfig.gif)

##Usage:

![](https://github.com/CrazyRA2Ivan/Test/blob/qweqwe/usage.gif)

##Setup:
```Ruby
pod 'Flat-SlideControl', '~> 0.0.1'
```

##Usage example:

    FlatSlideControl *flatSlideControl = [[FlatSlideControl alloc] initWithFrame:<#(CGRect)frame#>];
    flatSlideControl.groundColor = [UIColor lightGrayColor];
    flatSlideControl.tintColor = [UIColor redColor];
    flatSlideControl.thumbRadius = 30;
    flatSlideControl.lineWidth = 5;
    flatSlideControl.thumbsCount = 4;
    [flatSlideControl setLeftValue:1 rightValue:2];
    [self.view addSubview:flatSlideControl];
