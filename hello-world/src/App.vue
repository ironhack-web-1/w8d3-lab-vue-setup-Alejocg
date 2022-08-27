/* eslint-disable */

<template>

<div id="app">
  <h1>Hola test</h1>
  <span>Message: {{ msg }}</span>

  <ul>
    <li>
      <to-do-item></to-do-item>
    </li>
  </ul>
</div>

</template>


<script>

import aboutMe from 'hello-world\src\components\aboutMe.vue';

export default {

  name: 'app',
  components: {
    aboutMe
  },

    data () {
        return {
            msg : "hola"
        }
    }


};



</script>

<style>

</style>