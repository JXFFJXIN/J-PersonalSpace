<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="less" >
@yellow : #505007;
@gray : #828282;
@black : #101f1f;
* {
  color:@yellow;
  text-align: center;
  img {
    transform: rotateZ(45deg) translateY(80px);
  }
  button {
    color: @gray;
    background: @black;
    &:hover {
      color: @black;
      background: @gray;
      cursor: pointer;
    }
  }
}
</style>