<template>
    <footer class="footer-distributed">
        <div class="footer-left">
            <p class="footer-company-about">
            <span>Feel free to say Hi! <a href="#" class="footer-icons"><font-awesome-icon :icon="['fas', 'envelope']"/></a></span>
            You are magnificient beyond measure, perfect in your own imperfections and wonderfully made.</p>
        </div>
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
</template>