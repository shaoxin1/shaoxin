<script>
export default {
  data() {
    return {
      message: 'Hello World.'
    }
  },
  methods: {
    fanzhuanMessage() {
      this.message = this.message.split('').reverse().join('')
    },
    tanchuang() {
      alert('guanbitanchuang')
    }
  }
}
</script>

<template>
<h1>{{ message }}</h1>
<button @click="fanzhuanMessage">fanzhuanMessage</button>
<button @click="tanchuang">www.baidu.com</button>
<button @click="message += '!'">dianjijia"!"</button>
<a href="www.jingdong.com" @click.prevent="tanchuang">
  dakaizhegewangzhan

</a>

</template>

<style>


</style>