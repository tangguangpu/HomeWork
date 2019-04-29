<template>
<div>
  <TopNav/>
  <Search/>
</div>
</template>

<script>
import TopNav from 'public/TopNav/index.vue'
import Search from 'public/Search/index.vue'
export default {
  components:{
    TopNav,
    Search
  }
}
</script>

<style>
 @import "./static/css/public.css";

</style>
