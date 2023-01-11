<template>
  <div class="education">
      <h5>Education</h5>
    </div>
    
   

      <div class="card" v-for="item in education" :key="item">
        <h4> {{item.name}}</h4>
        <p> {{item.text}}</p>
        <img :src= "item.img" style="width: 298px; height:250px; border-radius:5px;">
    
    
  </div>



  </template>
  
<script>

export default {
  education: "card",
  data(){
    return {
 education : [
  {
    name: "Plumstead High School",
    text: "I've always been playing game as long as I can remember. I first started on the old PC's when we still used floppy disks lol. And then, on Console when I got my very own PlayStation 2 at 7 years old.",
    img: "https://i.postimg.cc/vBx3z85c/Plumstead-logo-254x300.gif"
  }, 
  {
    name: "University of the Western Cape",
    text: "I think it's worth bragging that I baked my first cake at the tender age of 3. I've got to give my Grandma some credit though for always making the best cakes and pastries and teaching me all the tricks. I've loved baking ever since. ",
    img: ""
  },
  {
    name: "Life Choices",
    text: "Something I also really enjoy doing is growing my own vegetables (I haven't gotten to growing fruits yet) and watching something grow from just a little seed.",
    img: "https://i.postimg.cc/FHcP4VFP/LIFE-CHOICES-ACADEMY-LOGO-ON-BLUE-removebg-preview.png"
  }
] 
  }}}
  

</script>

<style scoped>
.card {
    background-color: beige;
    box-shadow: 0 0 2px black;
    line-height: 20px;
    margin: 20px;
    width: 300px;
    margin-bottom: 20px;
    margin-left: 40px;
}

.education {
  
  margin-left: 3px;
  border: 2px solid rgb(235, 239, 14);
  background-color: rgb(200, 121, 255);
}

.education h5 {
  color:aliceblue;
  font-size: 40px;
  margin-left: 700px;
}

</style>