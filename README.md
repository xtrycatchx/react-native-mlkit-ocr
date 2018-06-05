
# react-native-ml-kit-ocr

## Getting started

`$ npm install react-native-ml-kit-ocr --save`

### Mostly automatic installation

`$ react-native link react-native-ml-kit-ocr`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-ml-kit-ocr` and add `RNMlKitOcr.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNMlKitOcr.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNMlKitOcrPackage;` to the imports at the top of the file
  - Add `new RNMlKitOcrPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-ml-kit-ocr'
  	project(':react-native-ml-kit-ocr').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-ml-kit-ocr/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-ml-kit-ocr')
  	```


## Usage
```javascript
import RNMlKitOcr from 'react-native-ml-kit-ocr';

// TODO: What to do with the module?
RNMlKitOcr;
```
  