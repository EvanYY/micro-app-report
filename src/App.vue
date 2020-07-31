<template>
   <div id="micro-app-report">
     <h1>micro-app-report</h1>
     <router-view :key="(new Date()).getTime()" />
   </div>
</template>

<script>
export default {
  components: {
  },
  data () {
    return {

    }
  }
}
</script>
<style lang="scss" scoped>

</style>
