<template>
    <div class="header">
    <div class="logo">
      <img/>
    </div>
    <div class="side_options">
      <ul>
        <li><a href="#">Experience</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">About Me</a></li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
  .header{
      display: flex;
      justify-content: space-between;
  }

  .side_options ul li{
    list-style: none;
    text-align: center;
    display: inline;
    margin: 0 2rem;
    cursor: pointer;
    font-size: 20px;
  }

  .side_options ul li a{
    text-decoration: none;
    color: #464545;
    text-decoration: none;
    letter-spacing: 0.3px;
    display: inline-block;
    position: relative;
    font-weight: 600;
  }

  .side_options ul li a:after {    
    background: none repeat scroll 0 0 transparent;
    bottom: -2px;
    content: "";
    display: block;
    height: 5px;
    position: absolute;
    background: #FAD165;
    transition:width 0.4s ;
    
    width: 0;
    z-index: -2;
}
  .side_options ul li a:hover{
    color: #012E51;
  }
  .logo{
    width: 130px;
    height: 50px;
    background-color: blue;
  }

  .side_options ul li a:hover:after { 
    width: 100%; 
    transition: width 0.4s ease;
}
@media (max-width:620px){
  .side_options ul li{

    display: grid;
    padding: 5px 0;
    text-align: right;
  }
}
</style>