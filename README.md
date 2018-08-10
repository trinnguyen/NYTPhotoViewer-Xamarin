# NYTPhotoViewer for Xamarin.iOS

[![NuGet version](https://badge.fury.io/nu/Xamarin.NYTPhotoViewer.svg)](https://badge.fury.io/nu/Xamarin.NYTPhotoViewer)

- Latest release of NYTPhotoViewer
- Support loading remote image with FFImageLoading
- Nuget: https://www.nuget.org/packages/Xamarin.NYTPhotoViewer

`dotnet add package Xamarin.NYTPhotoViewer`

## Orignal library
https://github.com/NYTimes/NYTPhotoViewer

## Usage
```
_dataSource = CreatePhotoDatasource();
_controller = new NYTPhotosViewController(_dataSource, 0, null);
_controller.WeakDelegate = this;
PresentViewController(_controller, true, null);
```

- Checkout the Demo project to learn more
