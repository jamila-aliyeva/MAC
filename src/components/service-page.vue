<template>
    <div class="container">
 <div class="service-header-wrap">
 
 <h2>Provide the best service with out of the box ideas</h2>


 <p>we are a passionate team of digital marketing enthusiasts dedicated to helping businesses succeed in the digital world. With years of experience and a deep understanding of the ever-evolving online landscape, we stay at the forefront of industry trends and technologies.</p>

 </div>

 <div class="service-content-wrap">
 <div class="service-left">
 <img src="../assets/images/service.png" alt="">
 </div>
 <div class="service-right">
 <h2>HOW WE WORK</h2>
 <img class="service-icon" src="../assets/images/service-icon.png" alt="">
 </div>
 <!-- <div></div> -->
 
 </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.service-header-wrap{
    display: flex;
    text-align: center;
    // justify-content: space-between;
    gap: 50px;
    margin: 100px 0;
    
        h2{
            width: 600;
            width: 744px;
            font-size: 48px;
        }
        p{
            width: 535px;
            font-weight: 500;
            font-size: 16px;
            color: rgba(135, 140, 145, 1);
        }
    
}
.service-content-wrap{
    display: flex;
    text-align: center;
    justify-content: space-between;
    align-items: center;
    gap: 54px;
    margin-bottom: 50px;
    .service-right{
        padding: 163px ;
        font-weight: 600;
        font-size:28px;
        letter-spacing: 27%;
        background-color: rgba(0, 0, 0, 0.2);
        border-radius: 30px;
       color: #ffff;
        display: flex;
        justify-content: center; 
        align-items: center;
        position: relative;
        .service-icon {
            position: absolute;
            cursor: pointer;
            bottom: -4px;
            right: -7px; 
            width: 100px; 
            height: 100px; 
            background-color: #a6e22e; 
            border-radius: 50%; 
            border: 4px solid white; 
            padding: 10px; 
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);
    }
    }
}
</style>