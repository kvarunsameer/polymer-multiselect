# Simple Multiselect

* Simple Multiselect provides the following features:
* Simple json can convert to multiselect/tags with search option.

## License

MIT License

## Installation

The element can be installed using bower using

```js 

bower install simple-polymer-multiselect

```

### Importing component into page/component: 
```html
   
   <link rel="import" href="./bower_components/simple-multiselect/simple-multiselect.html" />

```
### Usage

```html

<simple-multiselect></simple-multiselect>

```

###Attributes
heading
```html
Adding 'enablesearch' will enable universal search functionality.
ex. <simple-multiselect enablesearch></simple-multiselect>

```


### sample data
Adding data inside 'msdata' attribute

```html
<simple-multiselect msdata="{{data}}"></simple-multiselect>

```

```js

    static get properties () {
      return {
          msdata: {
              type: Array,
              value: [
                    {"ID":"1", "technology":"Google Polymer","status":"selected"},
                    {"ID":"2", "technology":"AngularJs"},
                    {"ID":"3", "technology":"CSS","status":"selected"},
                    {"ID":"4", "technology":"HTML"},
                    {"ID":"5", "technology":"JavaScript"},
                    {"ID":"6", "technology":"BackBone","status":"selected"},
                    {"ID":"7", "technology":"ReactJs"},
                    {"ID":"8", "technology":"Jquery","status":"selected"},
                ],
          }
      }
    }

```