<template>
    <div class="container">

 <main class="hero">


        <div class="hero-content">
            <h1>Stay ahead of the curve with our forward-thinking </h1>
            <p>An award-winning SEO agency with disciplines in digital marketing, design, and website development. focused on understanding you.</p>
            <div class="hero-action">
                <button>Schedule Call -></button>
                <a href="#">View Case Study</a>
            </div>
            <div class="companies">
                <span>Trusted by the world's biggest brands</span>
                <div>
                    <img src="../assets/images/Company logo.png" alt="">
                    <img src="../assets/images/Company logo (1).png" alt="">
                    <img src="../assets/images/Company logo (2).png" alt="">
                </div>
            </div>
        </div>



        <div class="hero-image">
            <img src="../assets/images/header-img.png" alt="">
        </div>
    </main>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

.hero{
    display: flex;
    align-items: center;
    justify-content: center;
}
.hero-content{
    display: flex;
    flex-direction: column;
    gap: 48px 0;
    h1{
        width: 650px;
        font-weight: 600;
        font-size: 72px;
        line-height: 79px;
        color: #010205;
    }
    p{
        width: 500px;
        font-weight: 500;
        color: #878C91;
        line-height: 28.8px;
    }
   
}

.hero-action{
    display: flex;
    align-items: center;
    gap: 0 56px;
    button{
        padding: 16px 32px;
        background-color: #010205;
        color: #ffffff;
        border: none;
        border-radius: 70px;
        font-weight: 700;
    }
    a{
        font-weight: 600;
        color: #010205;
        text-decoration: underline;
    }
}

.companies{
    display: flex;
    align-items: center;
    gap: 0 64px;
    span{
        width: 200px;
        font-weight: 600;
        line-height: 22px;
        font-size: 14px;
    }
    div{
        display: flex;
        align-items: center;
        gap: 0 20px;
    }
}

</style>