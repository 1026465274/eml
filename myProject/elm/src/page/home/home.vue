<template>
  <div> 

    <head-top> 
    <span slot='logo' class="head_logo">ele.me</span>
    </head-top>
    <nav class="city_nav">
      <div class="city_tip">
        <span>当前定位城市:</span>
        <span>定位不准时,请在城市列表中选择</span>
      </div>
    </nav>
  </div> 

</template>



<script>
import headTop from '../../components/header/header.vue'

export default {
  setup() {
    
  },
  components:{headTop:headTop}
  
}
</script>