<template>
  <div class="index">
    <vHeader></vHeader>
    <div class="container index">
      <div class="row">
        <vCarousel></vCarousel>
        
      </div>
    </div>
  </div>
</template>
<script>
import vHeader from './../common/header'
import vCarousel from './../common/carousel'
export default {
  name:'index',
  components:{
    vHeader,
    vCarousel
  }
}
</script>
<style scoped>

.index{
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
@media (min-width:992px){
  .container{
    width:960px
  }
}
@media (max-width:1080px){
  .container{
    width:750px
  }
}
.row {
    margin-left: -15px;
    margin-right: -15px;
}
</style>
