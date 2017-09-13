<template>
  <nav class="header">
      <div class="width-limit">
          <a href="/" class="logo">
            <img src="./../../assets/logo.png" alt="logo">
          </a>
      </div>
  </nav>
</template>
<script>
export default {
  name:'header'
}
</script>
<style scoped>
.header{
    height: 60px;
    width: 100%;
    background: #fff;
    border-bottom: 1px solid #efefef;
}
.width-limit{
    min-width: 768px;
    max-width: 1440px;
    margin: 0 auto;
}
nav .logo {
    float: left;
    height: 56px;
    padding: 14px 25px 15px 20px;
}
nav .logo img {
    height: 40px;
}
</style>
