<h1 align="center">
<img src="https://raw.githubusercontent.com/everdrone/react-native-super-ellipse-mask/master/media/banner.png" alt="SuperEllipse" />
<br/><br/>
</h1>

Apple flavored smooth corners for React Native

## Install

```bash
yarn add react-native-super-ellipse-mask
```

### Linking

#### Automatic

```bash
react-native link react-native-super-ellipse-mask
```

#### Manual

##### iOS

1.  In XCode, in the project navigator, right click `Libraries` > `Add Files to [your project's name]`
2.  Go to `node_modules` > `react-native-super-ellipse-mask` and add `RNSuperEllipseMask.xcodeproj`
3.  In XCode, in the project navigator, select your project. Add `libRNSuperEllipseMask.a` to your project's `Build Phases` > `Link Binary With Libraries`
4.  Run your project (`Cmd+R`)

## Usage

```javascript
<SuperEllipseMask radius={30}>
  <View
    style={{
      width: 200,
      height: 300,
      backgroundColor: 'black',
    }}
  />
</SuperEllipseMask>
```
