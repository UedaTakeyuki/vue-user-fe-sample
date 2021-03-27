<template>
  <div class="home">
    <h1>Homepage</h1>
    <VueUserFeSample />
    <FccButton />
  </div>
</template>

<script>
// @ is an alias to /src
import * as vuf from "vue-user-fe"
var VueUserFeSample = vuf.VueUserFeSample
var FccButton = vuf.FccButton
//var keroyon = vuf.kerokero
//var VueUserFeSample = require("vue-user-fe").VueUserFeSample
//var FccButton = require("vue-user-fe").FccButton
//var keroyon = require("vue-user-fe").kerokero
export default {
  name: 'Home',
  components: {
    VueUserFeSample,
    FccButton
  },
  mounted(){
    vuf.kerokero()
//    console.log(vuf)
  }
}
</script>
