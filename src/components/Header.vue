<template>
    <div class="header-container d-flex justify-content-between align-items-center">
        <div class="header-logo">
            <img class="img-fluid" src="../assets/Logo-2.svg" alt="">
        </div>
        <div class="header-menu">
            <a href="#" class="header-link-btn link-btn-normalize">About</a>
            <a href="#" class="header-link-btn link-btn-normalize">Features</a>
            <a href="#" class="header-link-btn link-btn-normalize">Pricing</a>
            <a href="#" class="header-link-btn link-btn-normalize">Testimonials</a>
            <a href="#" class="header-link-btn link-btn-normalize">Help</a>
        </div>
        <div class="header-sign">
            <a href="#" class="header-link-sign-btn link-btn-normalize">Sign In</a>
            <a href="#" class="header-link-sign-btn active-header-link link-btn-normalize">Sign up</a>
        </div>
    </div>
</template>


<script>

export default{
    name: 'Header'
}
</script>

<style scoped>
.header-container{
    width: 100%;
    height: 80px;
}

.header-logo, .header-menu, .header-sign{
    display: inline-block;
    padding: 0;
    margin: 0;
}

.link-btn-normalize{
    text-decoration: none;
    color: rgb(146, 146, 146);
}

.header-menu .header-link-btn:nth-child(n + 2), .header-sign .header-link-sign-btn:nth-child(n + 2){
    margin-left: 0.5rem;
}

.header-link-btn, .header-link-sign-btn{
    font-style: normal;
    font-size: 0.9rem;
    font-weight: 400;
    padding: 0.25rem;
}

.header-link-btn, .header-link-sign-btn{
    font-style: normal;
    font-size: 0.9rem;
    font-weight: 400;
    padding: 0.25rem;
}

.header-sign .header-link-sign-btn:last-child{
    padding: 0.5rem 1.25rem !important;
}

.active-header-link{
    border: 1px solid #F53855;
    box-sizing: border-box;
    border-radius: 60px;
}

</style>
