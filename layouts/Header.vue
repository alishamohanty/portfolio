<template>
    <div class="header">
    <div class="logo">
      <img/>
    </div>
    <div class="side_options">
      <ul>
        <li>Projects</li>
        <li>Experience</li>
        <li>About Me</li>
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
  }

  .logo{
    width: 130px;
    height: 50px;
    background-color: blue;
  }

</style>