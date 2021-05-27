<template>
<div>
  <input type="text" v-model="test"><br />
  <input type="button" value="klik" @click="mat">{{number}}<br />
  {{test}}
</div>
</template>

<script>

export default {
  data(){
    return{
      test:"tak",
      number:1
    }
  },
  methods:{
    mat(){
      this.number++
    }
  }
}
</script>

<style lang="scss">
</style>
