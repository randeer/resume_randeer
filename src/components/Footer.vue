<template>
  <div class="Footer">
    <footer id="sticky-footer" class="py-4 bg-dark text-white-50">
    <div class="container text-center">
      <small>Copyright &copy; randeer.l@randeer.me</small>
    </div>
 </footer>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {
      msg: 'Dilshani Dias'
    }
  }
}
</script>

<style scoped>
html,
body {
  height: 100%;
}

#page-content {
  flex: 1 0 auto;
}

#sticky-footer {
  position:absolute;
  bottom:0;
  width:100%;
  flex-shrink: none;
}

/* Other Classes for Page Styling */

body {
  background: #007bff;
  background: linear-gradient(to right, #0062E6, #33AEFF);
}
</style>
