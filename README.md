
# react-native-glideview

## Getting started

`$ npm install react-native-glideview --save`

### Mostly automatic installation

`$ react-native link react-native-glideview`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-glideview` and add `RNGlideview.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNGlideview.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.waterfairy.glideview.RNGlideviewPackage;` to the imports at the top of the file
  - Add `new RNGlideviewPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-glideview'
  	project(':react-native-glideview').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-glideview/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-glideview')
  	```


## Usage
```javascript
import RNGlideview from 'react-native-glideview';

// TODO: What to do with the module?
RNGlideview;
```
  