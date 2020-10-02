<template>
    <div>
        <Header />
        <nuxt />
        <Footer />
    </div>
</template>

<script>
import Footer from './Footer'
import Header from './Header'

export default {
    components:{
        Footer,
        Header
    }
}

</script>
