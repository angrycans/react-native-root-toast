### fork react-native-root-toast https://github.com/magicismight/react-native-root-toast
### custom message text =>react component
-----------------------

#### Features
1. message support text and react component


### Install

`npm install react-native-root-toast-ct`


### Settings

```
Toast.show("hello world", { position: Toast.positions.CENTER });

or 

const msg = (
  <View><Text style={{ color: "red" }}>
    hello
      </Text>
    <Text style={{ color: "#ffffff" }}>
      world
      </Text>
  </View>
);

Toast.show(msg, { position: Toast.positions.CENTER });


```