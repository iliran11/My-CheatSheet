# React

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
```
Add the path of the SDK Tools (directories tools and platform-tools to the system PATH variable. Open the Control Panel, click System and Security, click System, click Change settings, click the Advanced tab, then click the Environment Variables button.

In the list User variables select PATH and click the Edit button.

At the end of the field Variable value, add a semicolon followed by the path to the tools and platform-tools directores of the Android SDK install. Here is an example of what to add (note that there are two paths in one line, separated by a semicolon):

;C:\Users\miki\AppData\Local\Android\android-sdk\tools;C:\Users\miki\AppData\Local\Android\android-sdk\platform-tools
```
