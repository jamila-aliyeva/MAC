<template>
    <footer class="container">
         <div class="footer-wrap">
         <h3>Ready to work with us ?</h3>
         <button>Get Started </button>
         </div>

         <div class="total-footer">
         <div class="first-one">
         <img src="../assets//images/logo.svg" alt="">
         <p>We offers a comprehensive suite of digital marketing services that cover all aspects of our online presence. From SEO and social media marketing to content creation and PPC advertising, they have the expertise and resources to handle our diverse marketing needs.</p>
         <div class="social">
         <a href="#"><img src="../assets/images/facebook.svg" alt=""></a>
        <a href="#"> <img src="../assets/images/linkidin.svg" alt=""></a>
         <a href="#"><img src="../assets/images/instagram.svg" alt=""></a>
         <a href="#"><img src="../assets/images/twitter.svg" alt=""></a>

         </div>
         </div>

         <div class="second-one">
           <h4>Navigation</h4>
           <p>Service</p>
           <p>Agency</p>
           <p>Case Study</p>
           <p>Resource</p>
            <p>Contact</p>
         </div> 

         <div class="second-one">
           <h4>Licence</h4>
           <p>Privacy Policy</p>
           <p>Copyright</p>
           <p>Email Address </p>
         </div> 

         <div class="second-one">
          <h4>Contact</h4>
           <p>(406) 555-0120</p>
           <p>Hey@boostim.com</p>
           <p>2972 Westheimer Rd. Santa Ana, Illinois 85486 </p>
         </div> 
         </div>
    </footer>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.footer-wrap{
    display: flex;
    background-color: rgba(2, 6, 9, 1);
    // justify-content: center;
    text-align: center;
    padding: 50px 20px;
    margin-bottom: 50px;
    border-radius: 30px;
    h3{
        font-size: 50px;
        font-weight: 600;
        width: 839px;
        color: #ffff;
    }
    button{
        border-radius: 30px;
        padding: 5px 40px;
        background-color: #ffff;
        color: black;
        font-size: 16px;
        font-weight: 700;
    }

}
.total-footer{
    display: flex;
    // justify-content: space-between;
    gap: 108px;
    margin-bottom: 30px;
    .first-one{
        p{
            padding: 20px 0;
            font-size: 14px;
            font-weight: 400;
            color: rgba(155, 155, 156, 1);
            width: 534px;
        }
        .social{

            display: flex;
            gap: 10px;
        }
    }
    .second-one{
     h4{
        margin-bottom: 25px;
        font-size: 18px;
        font-weight: 600;
     }
     p{
        color: rgba(155, 155, 156, 1);
        padding-bottom: 15px;
     }
    }
}
</style>