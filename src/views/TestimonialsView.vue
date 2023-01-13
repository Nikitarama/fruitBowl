<template>
    <div class="test">
    <div class="card" v-for="item in testimonials" :key="item">
            <img :src= "item.img" style="width:298px; height:200px;">
            <div class="container">
                <h3><b> {{item.title}}</b></h3>
                <p> {{item.text}}</p>
            </div>
    </div>
  </div>
    
</template>



<script>

export default {
  testimonials: "card",
  data(){
    return {
 testimonials : [
    {
      name: "Plumstead High School | 2010-2014",
      text: "The subjects I did at high-school were: Business Studies, History and Geography.",
      img: "https://i.postimg.cc/vBx3z85c/Plumstead-logo-254x300.gif"

    }, 
    {
      name: "University of the Western Cape  | 2015-2022",
      text: "At University I double majored with History and Psychology. I thereafter obtained an Honours Degree in History, as well as my Masters the following year.",
      img: "https://i.postimg.cc/VLY0yGrL/UWClogo.jpg"
    },
    {
      name: "Life Choices  | 2022-2023",
      text: "I then joined the Life Choices bootcamp Academywhere I learnt how to code professionally, as well aslearning the basics of software and web development.",
      img: "https://i.postimg.cc/FHcP4VFP/LIFE-CHOICES-ACADEMY-LOGO-ON-BLUE-removebg-preview.png"
    },
    {
      name: "Plumstead High School | 2010-2014",
      text: "The subjects I did at high-school were: Business Studies, History and Geography.",
      img: "https://i.postimg.cc/vBx3z85c/Plumstead-logo-254x300.gif"

    }, 
    {
      name: "Plumstead High School | 2010-2014",
      text: "The subjects I did at high-school were: Business Studies, History and Geography.",
      img: "https://i.postimg.cc/vBx3z85c/Plumstead-logo-254x300.gif"

    }, 
    {
      name: "Plumstead High School | 2010-2014",
      text: "The subjects I did at high-school were: Business Studies, History and Geography.",
      img: "https://i.postimg.cc/vBx3z85c/Plumstead-logo-254x300.gif"

    }
  ]
}}}




</script>


<style scoped>




</style>