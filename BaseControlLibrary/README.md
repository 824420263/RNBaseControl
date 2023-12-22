
# react-native-base-control-library

## Getting started

`$ npm install react-native-base-control-library --save`

### Mostly automatic installation

`$ react-native link react-native-base-control-library`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-base-control-library` and add `RNBaseControlLibrary.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNBaseControlLibrary.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.controllibrary.RNBaseControlLibraryPackage;` to the imports at the top of the file
  - Add `new RNBaseControlLibraryPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-base-control-library'
  	project(':react-native-base-control-library').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-base-control-library/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-base-control-library')
  	```


## Usage
```javascript
import RNBaseControlLibrary from 'react-native-base-control-library';

// TODO: What to do with the module?
RNBaseControlLibrary;
```
  