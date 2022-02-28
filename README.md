# react-native-otp-inputs

![npm](https://img.shields.io/npm/dw/react-native-otp-inputs.svg)
![npm](https://img.shields.io/npm/v/react-native-otp-inputs.svg)

### Demo

![Demo](https://user-images.githubusercontent.com/17621507/36565065-a03b98b0-181f-11e8-9a54-09d978bec892.gif)

## Description

`react-native-otp-inputs` is fully customizable, React-Native package, that provides solution for One-time password feature with user friendly events like moving to previous input with backspace or going to next when filled in. It supports pasting and otp code into inputs

## Installation

Supported version: `react-native >= 0.59.0`

```bash
$ yarn add react-native-otp-inputs expo-clipboard
```

## Basic usage

```js
import React, { Component } from 'react';
import { View } from 'react-native';
import OtpInputs from 'react-native-otp-inputs';

export default class App extends Component {
  render() {
    return (
      <View style={styles.container}>
        <OtpInputs
          handleChange={(code) => console.log(code)}
          numberOfInputs={6}
        />
      </View>
    );
  }
}
```

## [API](./docs/API.md)

### Contributors

Great thanks to :
[@kantorm](https://github.com/kantorm).
