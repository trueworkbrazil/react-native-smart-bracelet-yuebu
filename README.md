
# react-native-smart-bracelet-yuebu

## Getting started

`$ npm install react-native-smart-bracelet-yuebu --save`

### Mostly automatic installation

`$ react-native link react-native-smart-bracelet-yuebu`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import br.com.truework.reactnative.RNSmartBraceletYuebuPackage;` to the imports at the top of the file
  - Add `new RNSmartBraceletYuebuPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-smart-bracelet-yuebu'
  	project(':react-native-smart-bracelet-yuebu').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-smart-bracelet-yuebu/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-smart-bracelet-yuebu')
  	```


## Usage
```javascript
import RNSmartBraceletYuebu from 'react-native-smart-bracelet-yuebu';

// TODO: What to do with the module?
RNSmartBraceletYuebu;
```
  