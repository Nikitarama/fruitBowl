<template>
    <div class="test">
    <div class="card" v-for="item in testimonials" :key="item">
            <img :src= "item.img" style="width:200px; height:200px; border-radius: 100px;">
            <div class="container">
                <h3><b> {{item.name}}</b></h3>
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
      name: "Zoe Daniels",
      text: " Nikita is a hard working lady with a big heart. She is organised, efficient and extremely competent with excellent rapport with people of all ages.",
      img: "https://i.postimg.cc/zBnph3Bn/IMG-20221104-090808.jpg"

    }, 
    {
      name: "Mu'eed Brown",
      text: "Nikita is a great person to work with. Her creative mind can get you some of the best results on web development.",
      img: "https://i.postimg.cc/02bLFdHj/mueed.jpg"
    },
    {
      name: "Aneeqa Brown",
      text: "Nikita is a highly thought intellectual from my perspective. She is not only hardworking but ambitious to recreate her vision exactly as thought of.",
      img: "https://i.postimg.cc/C1xvDS35/aneqa.jpg"
    },
    {
      name: "Xolelwa Manqina",
      text: "Nikita exhibits exceptional creativity and determination. She has a efficient work ethic and always produces sophisticated projects to the best of her ability.",
      img: "https://i.postimg.cc/hvkWpXnp/xolelwa.jpg"

    }, 
    {
      name: "Abdul Azeez Kemp",
      text: "Nikita is a wonderful person, great to work with, always puts her 100% effort into working and a great team player.",
      img: "https://i.postimg.cc/sgFGZmkZ/azeez.jpg"

    }, 
    {
      name: "Ryan Thomas",
      text: "Nikita is hard working and her biggest trait is resilience. She thrives under pressure and always gives her 100% best to complete any task at hand.",
      img: "https://i.postimg.cc/8CkX9cMp/ryan-thomas.jpg"

    }
  ]
}}}




</script>


<style scoped>

.test .card {
    margin: 10px;
    padding-top: 10px;
    padding-left: 10px;
    margin-bottom: 10px;
    background-image: url(https://i.postimg.cc/sDnPt2cm/360-F-116611375-24-YKo-WE4kwk6o-Cue-N0cz-C1p4iuo0uz-Tm.jpg);
    background-size: cover;
    height: 300px;
    width: auto;
}





</style>