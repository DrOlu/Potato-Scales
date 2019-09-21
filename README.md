<h1 align="center">
<img src="images/logo_vector.svg" width=300px href="https://makeml.app?from=github_potato_weigher" alt="Object Detection and Segmentation MakeML">
</h1>

[MakeML](https://makeml.app?from=github_potato_weigher) is a Developer Tool for Creating Object Detection and Segmentation Neural Networks without a Line of Code. It's built to make the training process easy to setup. It is designed to handle data sets, training configurations, markup and training processes — all in one place.

## MakeML Potato Scales
Is an iOS app example that shows how you can weigh potatoes using only iPhone with semantic segmentation. The machine learning model was trained for 20 minutes with 13 photos. Have used tensorflow (deeplab) for training model and their SDK for iOS.
<div align="center">
<img src="images/potato_result.gif">
</div>

## Train Objects Segmentation .tflite model
[![MakeML object detection and segmentation ML models](https://img.shields.io/static/v1?label=platform&message=macOS&color=blue)](https://makeml.app)

See the [Tutorial](https://makeml.app/docs/potato_scales_editorial?from=github_potato_weigher) for the training object segmentation model without a line of code with macOS desktop application.

<div align="center">
<img src="images/nails_adding_annotations.gif">
</div>

## Using another .tflite model in iOS application
[![MakeML object detection and segmentation ML models](https://img.shields.io/static/v1?label=platform&message=iOS&color=blue)](https://makeml.app)    [![MakeML object detection and segmentation ML models](https://img.shields.io/static/v1?label=language&message=swift&nbsp;&#124;&nbsp;objective-c&color=green)](https://makeml.app)

For using MakeML Nails project with another .tflite file, add it to the project and change this line with your name of the model.
```
NSString *modelPath = FilePathForResourceName(@"result_model", @"tflite");
```

Change the number of classes and add colors to the array:
```
int class_count = 2;
unsigned int colors[class_count] = {  0000000000, additionalColor };
```

## Links

[More Tutorials](https://makeml.app/tutorials?from=github_potato_weigher) | [MakeML in App Store](https://apps.apple.com/us/app/makeml/id1469520792?mt=12) | [Full Documentation](https://makeml.app/docs/doc1?from=github_potato_weigher) | [MakeML Chat](https://discordapp.com/invite/vgcG3Su) | [Support page](https://makeml.app/support?from=github_potato_weigher)
