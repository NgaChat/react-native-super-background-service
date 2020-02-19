# react-native-super-background-service 




## Requirements

-   RN 0.60+
-   Android API 16+

## Supported platforms

-   Android

## Getting started

`$ yarn add react-native-super-background-service`

or

`$ npm install react-native-super-background-service --save`


#### Examples


`import React, { Component } from 'react';`
`import { Text, View, TouchableOpacity } from 'react-native';`
`import Background from 'react-native-super-background-service'`


`export default class App extends Component {`

  `render() {`
    `return (`
      <View style={{ flex: 1, justifyContent: "center", alignItems: "center" }}>
        <TouchableOpacity onPress={()=>Background.startService()} >
          <Text>Hello, world!</Text>
        </TouchableOpacity>
      </View>
    );
  }
}`


