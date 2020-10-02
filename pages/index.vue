import portrait from '.';

<template>
  <div class="container content">
    <div class="index_page">
      <div class="index_left_side">
        <div>Hey, I'm</div>
        <div class="Alisha">Alisha!</div>
        <div class="short_message">I am a developer who loves to paint and cook delicious food!</div>
      </div>
          <img src="../static/portrait.png" alt="Alisha Mohanty Illustration" class="portrait">
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.portrait{
  height: 330px;
  width: 400px;
}
.index_page{
  display: flex;
}
.index_left_side{
  margin: auto auto;
}
.Alisha{
  font-size: 60px;
  color: #012E51;
}
.Alisha:after{
    background: none repeat scroll 0 0 transparent;
    margin-top: -22px;
    content: "";
    display: block;
    height: 15px;
    background: #fbb946;
    transition:width 0.4s ;
    
    width: 60%;
    z-index: -2;
}
.short_message{
  margin-top: 12px;
}
</style>