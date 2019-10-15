<template>
  <div class="ViewProfile">
    <h1>ViewProfile</h1>
    <p>{{ msg }} ID on the url is : {{ userID }}</p>
 </div>
</template>

<script>
export default {
  name: 'ViewProfile',
  data () {
    return {
      msg: 'Dilshani Lakshika Dias',
      userID: this.$route.params.user_id
    }
  },
  methods: {
      UpdateID () {
          this.userID = this.$route.params.user_id
      }
  },
  watch: {
      $route: 'UpdateID'
  }
}
</script>

<style scoped>

</style>
