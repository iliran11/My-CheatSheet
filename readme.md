# Basic Form defintion With Bootstrap
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

# `<Link>`

# Access the URL path
```javascript
this.props.location.pathname
```

#Iterating Over The Component Children

```javascript
const children = React.Children.map(this.props.children, child => {
  //manipulate or clone the objects
  return child
          }
```
