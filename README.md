
# react-native-juvo-player-api

## Getting started

`$ npm install react-native-juvo-player-api --save`

### Mostly automatic installation

`$ react-native link react-native-juvo-player-api`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-juvo-player-api` and add `RNJuvoPlayerApi.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNJuvoPlayerApi.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNJuvoPlayerApiPackage;` to the imports at the top of the file
  - Add `new RNJuvoPlayerApiPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-juvo-player-api'
  	project(':react-native-juvo-player-api').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-juvo-player-api/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-juvo-player-api')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNJuvoPlayerApi.sln` in `node_modules/react-native-juvo-player-api/windows/RNJuvoPlayerApi.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Juvo.Player.Api.RNJuvoPlayerApi;` to the usings at the top of the file
  - Add `new RNJuvoPlayerApiPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNJuvoPlayerApi from 'react-native-juvo-player-api';

// TODO: What to do with the module?
RNJuvoPlayerApi;
```
  