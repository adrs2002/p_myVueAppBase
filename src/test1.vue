<template>
  <div id="app1" @click="v_click()">

    <h1>{{ msg }}, {{mode}}</h1>

  </div>
</template>


<script>
export default {
  name: 'app',
  data () {
      return {
        msg : "test now",
        mode : false
      }
  },
    methods: {
        v_click: function () {
        this.mode = !this.mode;
    }

  }

}

</script>