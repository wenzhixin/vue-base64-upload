<template>
  <base64-upload class="user"
    imageSrc="user.jpg"
    :imageStyle="{'border-radius': '50%'}"
    @change="onChangeImage"></base64-upload>
</template>
<script>
import Base64Upload from '../src/Base64Upload.vue'

export default {
  components: {
    Base64Upload
  },
  methods: {
    onChangeImage(file) {
      console.log(file)
    }
  }
}
</script>

<style>
.user {
  width: 128px;
  height: 128px;
}
</style>
