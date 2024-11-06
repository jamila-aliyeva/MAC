<template>
    <div class="container">
   <div class="objectives">
   <h3>Real-world examples of how we have helped companies achieve their marketing objectives.</h3>

   <div class="obj-buttons">
   <button>All Work [20]</button>
   <button>UI/UX Design[10]</button>
   <button>Digital Marketing [5]</button>
   <button>Branding [5]</button>
   </div>

   <div class="circle-container">
    <div class="circle">
        <div class="inner-circle"><a href="#">See Details</a></div>
    </div>

    <div class="card">
        <div class="header">Ai Corporation. 2023</div>
        <div class="title">Ai Wave – Ai Chatbot Mobile App</div>
    </div>

    <div class="card">
        <div class="header">Lancer Corporation. 2023</div>
        <div class="title">App Lancer – Freelance App</div>
    </div>
</div>

   </div>

    <p class="obj-text">“ They thoroughly analyze our industry and target audience, allowing them to develop customized campaigns that effectively reach and engage our customers. Their creative ideas and cutting-edge techniques have helped us stay ahead of the competition.”</p>

    <div class="obj-footer">
    <div class="obj-ava">
    <div class="ava"></div>
    <div class="obj-fish">
    <h3>Michael Kaizer</h3>
    <p>CEO of Basecamp Corp</p>
    </div>
    </div>

    <div class="obj-info">
    <button><-</button>
    <p><span class="bold">01</span> <span class="grey">/ 05</span></p>
    <button>-></button>
    </div>
    </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.objectives{
    background-color: rgba(2, 6, 9, 1);
    border-radius: 30px;
    padding: 50px;
    position: relative;
    text-align: center;

    .circle-container{
        display: flex;
        margin-top: 40px;
        gap: 20px;
             .circle {
            margin-top: 50px;
            width: 450px;
            height: 350px;
            border-radius: 50%;
            background-color: #c4c4c4;
            display: flex;
            justify-content: center;
            align-items: center;
            border: 10px solid grey;
            // position: relative;
       

      .inner-circle a {
            width: 150px;
            height: 150px;
            color: black;
            background-color: #b3ff00;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-weight: bold;
            }
        }

            .card{
                // top: 280px;
                // right: -200px;
                // position: absolute;
              border: 10px solid grey;
              margin-top: 50px;
               width: 430px;
               height: 350px; 
               background-color: #c4c4c4;
               border-radius: 15px;
               padding: 20px;
               color: #fff;
               box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
               display: flex;
            flex-direction: column;
            justify-content: space-between;
            }
    }
     
    // .circle-container {
    //     display: flex;
    //     justify-content: center; 
    //     align-items: center;
    //     width: 100%;
    //     max-width: 800px;
    //     padding: 50px 0;
    //     gap: 50px;
    //     }

       
    //     .card {
    //         width: 300px;
    //         height: 300px;
    //         background-color: #c4c4c4;
    //         border-radius: 10px;
    //         padding: 15px;
    //         color: #fff;
    //         display: flex;
    //         flex-direction: column;
    //         justify-content: space-between;
    //         box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    //         text-align: center;
    //     }

    //     .card .header {
    //         font-size: 12px;
    //         color: #ffff;
    //     }

    //     .card .title {
    //         font-weight: bold;
    //         margin-top: auto;
    //     }

    
        h3{
            color: #fff;
            font-size: 40px;
            font-weight: 600;
            padding-bottom: 40px;
            // width: 1120px;
           
        
    }
    .obj-buttons{
        display: flex;
    gap: 24px;
    justify-content: center;
        button{
            padding: 15px 35px;
            border-radius: 50px;
            border: 1px solid #fff;
            cursor: pointer;
            background-color: transparent;
            color: #fff;
            transition: 0.5s;
            &:hover {
            background-color: rgba(153, 207, 99, 1);
            color: black;
    }
        }
    }
}
.obj-text{
    padding: 70px 0 ;
    font-size: 36px;
    // font-weight: 600;
    color: rgba(1, 2, 5, 1);
    width: 1210px;
}
.obj-footer{
    background-color: rgba(250, 250, 250, 1);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-bottom: 50px;
    .obj-ava{
        display: flex;
        align-items: center;
        gap: 16px;
        .ava{
            width: 50px;
            height: 50px;
            background-color: #ccc; 
            border-radius: 50%;
        }
    }
    .obj-fish{
        p{
            color: rgba(135, 140, 145, 1);
            padding-top: 5px;
            color: 16px;
            font-weight: 500;
        }
    }
    .obj-info{
        display: flex;
        text-align: center;
        align-items: center;
        justify-content: space-between;
        gap: 30px;
        button{
            border-radius: 20px;
            padding: 10px 20px;
            border: 1px solid black;
            background-color: transparent;
            transition: 0.5s;
            &:hover {
            background-color: black;
            color: #fff;
    }
        }
    }
    .bold{
        color: black;
        font-weight: 600;
        text-decoration:underline;
    }
    .grey{
        color: grey;
    }

}


</style>