# React - Redux

## Class Definition - Component

```javascript
import React, {Component} from 'react';

export default class HelloWorld extends Component {
    render() {
        return (
          <div>HelloWorld</div>
        );
    }
}
```
## stateless react component

```javascript
import React from 'react';

const statelessComponent = (props) => {
  return <div>hello</div>;
}
export default statelessComponent

```

## Map actions to props

```javascript
import action.js from './action.js';
import {bindActionCreators} from 'redux';
function mapDispatchToProps(dispatch) {
    return bindActionCreators({
        action
    }, dispatch)
}
```

## Map state to props

```javascript
function mapStateToProps(state) {
  //object means:
  //key - how to map it to the props
  //value - what portion of the state to take
    return {weather: state.weather};
}
```

## Connect the component to redux

```javascript
import {connect} from 'react-redux';
export default connect(mapStateToProps, mapDispatchToProps)(ComponenetGoesHere)
```

## Basic Form defintion With Bootstrap
```html
<form>
  <h3>Form Header</h3>
  <div className="form-group">
    <label>
      Choose a car
    </label>
    <input type="text" className="form-control"/>
  </div>
  <button type="submit" className="btn btn-primary">Submit</button>
```

## Access the URL path
```javascript
this.props.location.pathname
```

## Iterating Over The Component Children

```javascript
const children = React.Children.map(this.props.children, child => {
  //manipulate or clone the objects
  return child
          }
```

# VS Code Shortcuts

## Zen Modev
```
Ctrl+k z
``` 

## open MarkDown preview
```
ctrl+K v
```

## open terminal
``` 
Ctrl+`
```

## Quick Open
```
Ctrl+P
```
## Multiple Cursors
`alt+ctrl+shift+ up/down arrow`

## Select all occurrences of current selection

`Ctrl+Shift+L`

# Android/Cordova


## New android project with Cordova
```
cordova create MyApp
cordova platform add android --save 
```

## get List of all AVD
`emulator -list-avds`

## open Emulator from command line
`emulator -avd <avd_name>` 

## setup Android Path

[Installing Android on Windows](https://evothings.com/doc/build/cordova-install-windows.html)

## how to git cordova
[how to git cordova](https://evothings.com/doc/build/cordova-install-windows.html)

## emulate fingerTip on android 6
  ```
  adb -e emu finger touch <touchID>
  ```

# VueJs

## how to export component on Vue

```html
<template>
<f7-page>
User Identification
<HeaderNav></HeaderNav>
</f7-page>
</template>

<script>
import HeaderNav from '../components/header.vue';
export default {
  components: {
    HeaderNav
  }
} 
</script>
```html


