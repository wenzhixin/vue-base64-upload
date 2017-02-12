# vue-base64-upload

vue-base64-upload is an ui component library base on Vue.js(2.x).

```html
<base64-upload :imageSrc="user.png" @change="onChangeImage"></base64-upload>
```

```js
onChangeImage(file) {
  /*
  {
    size: 55832,
    filetype: 'image/jpeg',
    filename: 'profile.jpg',
    base64:   '/9j/4AAQS...'
  }
  */
}
```

## Installation

```
npm install vue-base64-upload
```

## Example

See [jsFiddle]()

## Documentation

### props

* imageSrc: String, The default image
* imageStyle: Object, Style of the default image

### events

* change: Trigger when upload an image file
