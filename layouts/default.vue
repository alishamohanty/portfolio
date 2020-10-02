<template>
  <!-- <h1>Hello world!</h1> -->
  <div>
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
  <nuxt />
    <footer class="footer-distributed">
 
		<div class="footer-left">
 
		<p class="footer-company-about">
		<span>Feel free to say Hi! <a href="#" class="footer-icons"><font-awesome-icon :icon="['fas', 'envelope']"/></a></span>
	    You are magnificient beyond measure, perfect in your own imperfections and wonderfully made.</p>

		</div>
 
		<!-- <div class="footer-center">

		</div> -->
 
		<div class="footer-right">
  
		<div class="footer-icons">
 
		<a href="#"><font-awesome-icon :icon="['fab', 'facebook']"/></a>
        <a href="#"><font-awesome-icon :icon="['fab', 'medium']"/></a>
		<a href="#"><font-awesome-icon :icon="['fab', 'twitter']"/></a>
		<a href="#"><font-awesome-icon :icon="['fab', 'linkedin']"/></a>
		<a href="#"><font-awesome-icon :icon="['fab', 'github']"/></a>
 
		</div>
        <p class="footer-company-name">Copyright &copy {{ new Date().getFullYear() }} Alisha Mohanty</p>
 
		</div>
 
		</footer>
  </div>
</template>
