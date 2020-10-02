<template>
    <footer class="footer-distributed">
        <div class="footer-left">
            <p class="footer-company-about">
            <span>Feel free to say Hi! <a href="#" class="footer-icons"><font-awesome-icon :icon="['fas', 'envelope']"/></a></span>
            You are magnificient beyond measure, perfect in your own imperfections and wonderfully made.</p>
        </div>
        <div class="footer-right">  
            <div class="footer-icons">
                <a href="#"><font-awesome-icon :icon="['fab', 'medium']"/></a>
                <a href="#"><font-awesome-icon :icon="['fab', 'twitter']"/></a>
                <a href="#"><font-awesome-icon :icon="['fab', 'linkedin']"/></a>
                <a href="#"><font-awesome-icon :icon="['fab', 'github']"/></a>
            </div>
            <p class="footer-company-name">Copyright &copy {{ new Date().getFullYear() }} Alisha Mohanty</p>
        </div>
    </footer>
</template>

<style scoped>

footer{
	position: relative;
	bottom: 0;
  	justify-content: space-between;
	height: 200px;
	clear: both;
	/* margin-top:-200px; */

}

.footer-distributed{
	background-color: #012E51;
	box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.12);
	box-sizing: border-box;
	width: 100%;
	text-align: left;
	font: bold 16px sans-serif;
 
	padding: 50px 50px;
  	display: flex;
}
 
.footer-distributed .footer-left,
.footer-distributed .footer-center,
.footer-distributed .footer-right{
	display: inline-block;
	vertical-align: top;
}
 
.footer-distributed .footer-left{
	width: 50%;
}
  
 
.footer-distributed .footer-links{
	color:  #ffffff;
	margin: 20px 0 12px;
	padding: 0;
}
 
.footer-distributed .footer-links a{
	display:inline-block;
	line-height: 1.8;
	text-decoration: none;
	color:  inherit;
}
 
.footer-distributed .footer-company-name{
	color:  #8f9296;
	font-size: 14px;
	font-weight: normal;
  text-align: center;
  letter-spacing: 0.5px;
}
 
.footer-distributed .footer-center p{
	display: inline-block;
	color: #fafafa;
	vertical-align: middle;
	margin:0;
}
 
.footer-distributed .footer-center p span{
	display:block;
	font-weight: normal;
	font-size:14px;
	line-height:2;
}
 
.footer-distributed .footer-center p a{
	color:  #fbb946;
	text-decoration: none;;
}
  
.footer-distributed .footer-company-about{
	line-height: 20px;
	color:  #92999f;
	font-size: 15px;
	font-weight: normal;
	margin: 0;
}
 
.footer-distributed .footer-company-about span{
	display: block;
	color:  #fbb946;
	font-size: 20px;
	font-weight: bold;
	margin-bottom: 20px;
}
 
.footer-distributed .footer-icons{
	text-align: center;
  color:  #fbb946;
}
 
.footer-distributed .footer-icons a{
	display: inline-block;
	width: 35px;
	height: 35px;
	cursor: pointer;
	border-radius: 2px;
  	margin: 0 20px;
 
	font-size: 30px;
	color: #ffffff;
	text-align: center;
	line-height: 35px;
 
	margin-right: 3px;
	margin-bottom: 5px;
}

@media (max-width: 880px) {
 
	.footer-distributed{
		font: bold 14px sans-serif;
	
	}
 
	.footer-distributed .footer-left,
	.footer-distributed .footer-center,
	.footer-distributed .footer-right{
		display: block;
		width: 100%;
		margin-bottom: 40px;
		text-align: center;
	}

	.main {
		line-height: normal;
		font-size: auto;
	}
 
}
@media (max-width: 735px) {

	footer{
		height: 280px;
	}
  .footer-distributed{
    display: grid;
    padding: 40px 30px;
  }
  .footer-distributed .footer-right {
    margin-bottom: 0;
  }
}
</style>