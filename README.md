UIColor-HSVExtras
=================

Objective-C Category for UIColor allowing to use and convert to HSV space.
Inspired by https://github.com/mateagar/Color-Picker-for-iOS



Examples of use
------------

Firstly, import the .h at the header of your file.

  	#import "UIColor+HSVExtras.h"

For example, if you would need to change a parameter of a color using the HSV space color it should be like this:

    UIColor *color = [UIColor red];
    color = [UIColor colorWithHue:color.hue saturation:color.saturation brightness:color.brightness-0.2 alpha:color.alpha];
    

You can get the following parameters from UIColor:

    -(CGFloat)hue;
    -(CGFloat)saturation;
    -(CGFloat)brightness;
    -(CGFloat)value;
    -(CGFloat)red;
    -(CGFloat)green;
    -(CGFloat)blue;
    -(CGFloat)white;
    -(CGFloat)alpha;
    
    
##License

Free use. Don't hesitate adding things, please.
