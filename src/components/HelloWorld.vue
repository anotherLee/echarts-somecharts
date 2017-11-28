<template>
  <div class="hello">
    <!-- <div id="radar">
    </div> -->
    <!-- <div id="funnel"></div> -->
    <div id="scatter"></div>
  </div>
</template>

<script>
import drawRadar from '../../static/js/radar'
import drawFunnel from '../../static/js/funnel'
import drawScatter from '../../static/js/scatter'
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  mounted () {
    // drawRadar()
    // drawFunnel()
    drawScatter()
  }
}
</script>

<style scoped>
#radar{
  width:600px;
  height:600px;
  margin:150px auto 0;
  border:1px solid #ccc;
}
#funnel{
  width:600px;
  height: 800px;
  margin:50px auto 0;
  border:1px solid #fff;
}
#scatter{
  width:900px;
  height:700px;
  margin:100px auto 0;
  border:1px solid #eee;
}
</style>
