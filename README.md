## FlutterExample

# This project uses Flutter 2.8.1

Sample project to reproduce Apple Distribution error
```
Invalid Bundle. The bundle at 'FlutterWrapper.framework' contains disallowed nested bundles
```

### Using Flutter 2.8.1 the error cannot be reproduced and the uploading to TestFlight works fine, however using Flutter 3.3.7 the error is reproducible, check this other repo: https://github.com/alansteiman/FlutterExample

## High level architecture
![diagram](https://user-images.githubusercontent.com/90182796/210980316-0b26cd77-f694-447a-965c-efedac76a467.jpg)
Flutter project added using the official documentation: https://docs.flutter.dev/development/add-to-app/ios/project-setup


## Installation

```
cd FlutterExample
pod install
```
