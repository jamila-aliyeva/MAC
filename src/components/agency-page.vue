<template>
    <div class="container">
      <div class="agency-top">
      <h3>Digital Marketing & SEO ServicesThat Grow Traffic & Increase Revenue</h3>
      <div class="agency-btn">
      <p>We are the top digital marketing agency for  branding corp. We offer a full range of services to help clients improve their search engine rankings and drive more traffic to their websites.</p>
      <button>See more</button>
      </div>
      </div>

      <div class="agency-boxes">
         <div class="box">
         <div class="box-top">
         <div class="blue"></div>
         <p>5 min read</p>
         </div>
         <h3>How a Digital Marketing Agency Can Boost Your Business</h3>
         <div class="box-bottom">
         <p>We are the top digital marketing agency for  branding corp. We offer a full rang  engine ....</p>
         </div>
         <button>-></button>
         </div>

         <div class="box">
         <div class="box-top">
         <div class="blue"></div>
         <p>5 min read</p>
         </div>
         <h3>The Latest Trends and Strategies with a Digital Marketing Agency</h3>
         <div class="box-bottom">
         <p>We are the top digital marketing agency for  branding corp. We offer a full rang  engine ....</p>
         </div>
         <button>-></button>
         </div>
         <div class="box">
         <div class="box-top">
         <div class="blue"></div>
         <p>5 min read</p>
         </div>
         <h3>Maximizing ROI with the Expertise of a Digital Marketing Agency</h3>
         <div class="box-bottom">
         <p>We are the top digital marketing agency for  branding corp. We offer a full rang  engine ....</p>
         </div>
         <button>-></button>
         </div>
         
      </div>



      
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.agency-top{
   display: flex;
   gap: 24px;
   h3{
    font-weight: 600;
    font-size: 48px;
   }
   
   .agency-btn{
    p{
    font-size: 16px;
    font-weight: 500;
    padding-bottom: 40px;
    color: rgba(135, 140, 145, 1);
   }
       button{
        font-size: 16px;
        padding: 10px 20px;
        border-radius: 30px;
        font-weight: 600;
        background-color: transparent;
        border: 1px solid;
       }
   }
}
.agency-boxes{
    display:flex;
    gap: 30px;
    margin: 50px 0;
    .box{
        background-color: #fff;
        padding: 20px;
        border-radius: 30px;
    .box-top{
        display: flex;
        justify-content: space-between;
        .blue{
            width: 10px;
            height: 10px;
            background-color: blue; 
            border-radius: 50%;
        }
        p{
            color: rgba(135, 140, 145, 1);
        }
    }
    h3{
        padding: 15px 0 ;
        font-size: 26px;
        font-weight: 600;
        width: 346px;
        letter-spacing: -3%;
    }
    .box-bottom{
    //   display: flex;
    //   gap: 30px;
    // justify-content: space-between;
        p{
            color: rgba(135, 140, 145, 1);
            font-weight: 500;
            font-size: 16px;
            width: 260px;
            padding-bottom: 20px;
        }
    }
    button{
        background-color: transparent;
        padding: 5px 25px;
        border-radius: 30px;
        border: 1px solid ;
        transition: 0.5s;
        &:hover{
            background-color: black;
            color: #fff;
        }
    }
    }
   
}

</style>