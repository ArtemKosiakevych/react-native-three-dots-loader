# react-native-three-dots-loader
Simple react native animated loader
<p>
<img src="http://img.shields.io/npm/v/react-native-three-dots-loader.svg" />
<img src="https://img.shields.io/npm/dm/react-native-three-dots-loader.svg" />
<img src="https://img.shields.io/npm/dt/react-native-three-dots-loader.svg" />
</p>

Component doesn't use external libs, only `Animated` from react-native

## Installation
`yarn add react-native-three-dots-loader`

## Usage

![](./assets/demo.gif)

`import Loader from 'react-native-three-dots-loader'`

...

```
return (
  <Loader>
)
```

## Props

| Prop | Description |
| :------------ | :-----|
| size | Dot size |
| background | Dot background |
| activeBackground | Active dot background |
| dotMargin | Dots horizontal margin |
| animationDuration | Scale animation duration |
| animationScale | Maximum scale |