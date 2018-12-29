<template>
    <div class="header_contain">
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark cus_nav">
            <nuxt-link class="navbar-brand logo" :to="{name:'home'}"><img src="https://static.panpay.cn/static/image/en/header/logoW@2x.png" alt="logo" class="img-responsive logo_w" /></nuxt-link>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto cus_ul">
                    <li class="nav-item active">
                        <nuxt-link class="nav-link" :to="{name:'home'}">Home</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" :to="{name:'about'}">About Us</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" :to="{name:'products'}">Products</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" :to="{name:'solutions'}">Solutions</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" :to="{name:'faqs'}">FAQ's</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" :to="{name:'fee'}">Fee</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" :to="{name:'contact'}">Contact Us</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link class="nav-link" :to="{name:'career'}">Careers</nuxt-link>
                    </li>
                    <!-- <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        About Us
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item" href="#"><nuxt-link :to="{name:'contact'}">Contact Us</nuxt-link></a>
                            <a class="dropdown-item" href="#"><nuxt-link :to="{name:'career'}">Career</nuxt-link></a>
                        </div>
                    </li> -->
                </ul>
            </div>
        </nav>        
    </div>
</template>
<script>
export default {
    
}
</script>

<style>
.header_contain{
    width: 100%;
    height: 60px;
    flex-flow: row wrap;
    justify-content: center;
    background-color: #343a40;
    box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.6);
    position: fixed;
    top: 0px;
    left: 0px;
    z-index: 9999;
}
.cus_nav{
    width: 1200px;
    display: flex;
    padding: 0px;
    margin: auto;
}
a.logo{
    font-size: 40px;
    font-weight: 300;
    text-align: left;
    color: #ffffff;
    text-decoration: none;
    line-height: 60px;
    padding: 0px;
}
a.logo .logo_w{
    width: 86px;
    height: 38px;
}
.cus_ul{
    line-height: 40px;
}
.cus_ul li{
    margin: 0px 10px;
}
.cus_ul li a{line-height: 40px;}
</style>
