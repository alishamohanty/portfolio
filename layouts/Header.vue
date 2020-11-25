<template>
  <div class="header header-container">
    <div class="logo">
      <img />
    </div>
    <div class="side_options">
      <ul>
        <li><a href="#">Experience</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="/about">About Me</a></li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
.header-container {
  padding: 40px 0;
  margin-right: auto;
  margin-left: auto;
  width: 90%;
}
.header {
  display: flex;
  justify-content: space-between;
  font-family: Nunito;
}

.side_options ul li {
  list-style: none;
  text-align: center;
  display: inline;
  margin: 0 2rem;
  cursor: pointer;
  font-size: 18px;
}

.side_options ul li a {
  text-decoration: none;
  color: #012e51;
  text-decoration: none;
  letter-spacing: 0.3px;
  display: inline-block;
  position: relative;
  font-weight: 300;
}

.side_options ul li a:after {
  background: none repeat scroll 0 0 transparent;
  bottom: 2.2px;
  content: "";
  display: block;
  height: 7px;
  position: absolute;
  background: #fbb946;
  transition: width 0.4s;

  width: 0;
  z-index: -2;
}
.logo {
  width: 130px;
  height: 50px;
  background-color: blue;
}

.side_options ul li a:hover:after {
  width: 100%;
  transition: width 0.4s ease;
}
@media (max-width: 745px) {
  .side_options ul li {
    display: grid;
    padding: 5px 0;
    text-align: right;
  }
  .side_options ul li {
    margin: 0 1em;
  }
  .side_options ul {
    margin: 0;
  }
}
</style>
