
# react-native-unified-push

## Getting started

`$ npm install react-native-unified-push --save`

### Mostly automatic installation

`$ react-native link react-native-unified-push`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-unified-push` and add `RNUnifiedPush.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNUnifiedPush.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNUnifiedPushPackage;` to the imports at the top of the file
  - Add `new RNUnifiedPushPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-unified-push'
  	project(':react-native-unified-push').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-unified-push/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-unified-push')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNUnifiedPush.sln` in `node_modules/react-native-unified-push/windows/RNUnifiedPush.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Com.Reactlibrary.RNUnifiedPush;` to the usings at the top of the file
  - Add `new RNUnifiedPushPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNUnifiedPush from 'react-native-unified-push';

// TODO: What to do with the module?
RNUnifiedPush;
```
  