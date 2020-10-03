<template>
    <div class="index_page">
        <div class="index_left_side">
          <div>Hey, I'm</div>
          <div class="Alisha">Alisha!</div>
          <div class="short_message">I am a developer who loves to paint and cook delicious food!</div>
        </div>
        <div class="div-portrait">
          <img src="../static/portrait.png" alt="Alisha Mohanty Illustration" class="portrait">
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style scoped>
.portrait{
  height: 320px;
  width: 400px;
}
/* @media(max-width: 800px)
{
  .portrait{
    
  }
}
@media(max-width: 800px)
{
  .portrait{
    
  }
} */
.index_page{
  display: flex;
  justify-content: space-between;
}
.index_left_side{
  margin: 40px auto;
  padding-top: 2em;
}
.Alisha{
  font-size: 60px;
  color: #012E51;
  font-weight: 600;
}
.Alisha:after{
    background: none repeat scroll 0 0 transparent;
    margin-top: -27px;
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
@media (max-width: 800px)
{
    .index_page{
    display: grid;
    justify-content:center;
    justify-items: center;
  }
  .portrait{
      height: 250px;
      width: 300px;
  }
  .container {
    justify-self: center;
  }
}
</style>