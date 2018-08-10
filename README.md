# NYTPhotoViewer-Xamarin
Xamarin.iOS Binding Library for NYTPhotoViewer

- Latest release of NYTPhotoViewer
- Support loading remote image with FFImageLoading

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
