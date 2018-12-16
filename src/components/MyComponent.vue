<template>
  <div><img :src="imgUrl" /></div>
</template>

<script>
export default {
  name: 'MyComponent',
  props: {
    imgUrl: String
  }
}
</script>
