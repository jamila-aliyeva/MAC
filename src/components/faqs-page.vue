<template>
    <div class="container">

   <div class="faqs-wrapper">

    <div class="faqs-right">
       <h3>Digital Marketing FAQs</h3>
       <p>As a leading digital marketing agency, we are dedicated to providing comprehensive educational resources and answering frequently asked questions to help our clients.</p>
    <div class="faqs-btn">
        <div><button><a href="#">More Questions</a></button></div>
       <div> <button><a href="#">Contanct Us</a></button></div>
</div>
    </div>


  
    <div class="accordion">
        <div
          v-for="(faq, index) in faqs"
          :key="index"
          class="accordion-item"
          :class="{ active: activeIndex === index }"
        >
          <div class="accordion-title" @click="toggleAccordion(index)">
            <h3>{{ faq.question }}</h3>
            <span class="accordion-icon">{{ activeIndex === index ? '-' : '+' }}</span>
          </div>
          <div class="accordion-content" v-show="activeIndex === index">
            <p>{{ faq.answer }}</p>
          </div>
        </div>
      </div>

   </div>

    </div>
</template>

<script setup>
import { ref } from 'vue';

const faqs = ref([
  {
    question: 'Why is digital marketing important for my business?',
    answer:
      'Digital marketing allows businesses to reach and engage with a wider audience, generate leads, drive website traffic, and increase brand visibility. It provides measurable results, allows for targeted marketing efforts, and enables businesses to adapt and optimize their strategies based on data and insights.',
  },
  {
    question: 'How can digital marketing help improve my website\'s visibility?',
    answer:
      'Digital marketing allows businesses to reach and engage with a wider audience, generate leads, drive website traffic, and increase brand visibility. It provides measurable results, allows for targeted marketing efforts, and enables businesses to adapt and optimize their strategies based on data and insights.',
  },
  {
    question: 'How long does it take to see results from digital marketing efforts?',
    answer:
      'Digital marketing allows businesses to reach and engage with a wider audience, generate leads, drive website traffic, and increase brand visibility. It provides measurable results, allows for targeted marketing efforts, and enables businesses to adapt and optimize their strategies based on data and insights.',
  },
  {
    question: 'How do you measure the success of digital marketing campaigns?',
    answer:
      'Digital marketing allows businesses to reach and engage with a wider audience, generate leads, drive website traffic, and increase brand visibility. It provides measurable results, allows for targeted marketing efforts, and enables businesses to adapt and optimize their strategies based on data and insights.',
  },
  
]);
const activeIndex = ref(null);

function toggleAccordion(index) {
  activeIndex.value = activeIndex.value === index ? null : index;
}

</script>

<style lang="scss" scoped>
.faqs-wrapper{
   background-color: #fff;
   display: flex;
   margin-bottom: 50px;
   border-radius: 20px;
   padding: 50px ;
    gap: 24px;
    .faqs-right{

        h3{
            font-size: 35px;
            font-weight: 600;
            padding-bottom: 20px;
        }
        p{
            font-size: 16px;
            color: rgba(135, 140, 145, 1);
            width: 523px;
            padding-bottom: 25px;
            
        }
        .faqs-btn{
            gap: 24px;
            display: flex;
            button{
                border: none;
                padding: 15px;
                background-color: transparent;
                border: 1px solid black;
                border-radius: 30px;
                transition: 0.5s;
                // &:hover{
                //     background-color: black;
                //     color: #ffff;
                // }
               a{
                color: black;
                font-size: 16px;
                font-weight: 700;
               }
            }
        }
    }
    .accordion {
    border-top: 1px solid #ddd;
    width: 100%;
  }

  .accordion-item {
    border-bottom: 1px solid #ddd;
  }


  .accordion-title {
    display: flex;
    justify-content: space-between;
    align-items: center;
    cursor: pointer;
    padding: 25px;
    font-weight: bold;
    font-size: 18px;
    font-weight: 600;
  }

  .accordion-content {
    padding: 15px;
    color: #7a7a7a;
    font-size: 14px;
  }

  .accordion-item.active .accordion-title {
    font-weight: bold;
  }
 
}

</style>


