<script>
  import { Crisp } from "crisp-sdk-web";

  // 自动加载
  // Crisp.configure('0de87b57-f520-4955-99fd-f9557fc7adc6');

  //关闭自动加载
  Crisp.configure('c7e085e8-fb04-4a11-bf21-74d981af2dab', {
    autoload: false
  });
  export default {
    mounted () {
      setTimeout(() => {
        Crisp.load()
      }, 2000)
    }
  }
</script>
<template></template>
<style></style>