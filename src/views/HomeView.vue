<template>
  <view>
    <p>{{ apple }}</p>
    <button @click="a">点击</button>
  </view>
</template>

<script setup>
import { ref } from 'vue';

// @ is an alias to /src
const apple = ref("苹果")
function a(e){
  apple.value = "香蕉"
}
</script>
