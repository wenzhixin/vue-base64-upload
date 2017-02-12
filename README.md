# vue-base64-upload

vue-base64-upload is an ui component library base on Vue.js(2.x).

# Usage

```html
<template>
  <base64-upload imageSrc="user.png" @change="onChangeImage"></base64-upload>
</template>
<script>
import Base64Upload from 'vue-base64-upload'

export default {
  components: {
    Base64Upload
  },
  methods: {
    onChangeImage(file) {
      /*
      {
        size: 93602,
        filetype: 'image/jpeg',
        filename: 'user.jpg',
        base64:   '/9j/4AAQSkZJRg...'
      }
      */
    }
  }
}
</script>
```

## Installation

```
npm install vue-base64-upload
```

## Example

* [Demo](https://github.com/wenzhixin/vue-base64-upload/tree/master/demo)
* [Live Example](https://wenzhixin.github.io/vue-base64-upload/demo)

## Documentation

### props

* imageSrc: String, The default image
* imageStyle: Object, Style of the default image

### events

* change: Trigger when upload an image file
