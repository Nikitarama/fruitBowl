<template>
<div class="aboutPage">
  <img src="../assets/nikita_instg.jpg" style="width:300px; height: 300px;" > 
  
  <div class= "aboutMe">
    
            <h1>| About Me</h1>
            <p>I got into coding quite late in my life,
                after having already studied something
                in a completely different field for more 
                than 8 years.</p>
            <p>However, coding is something I've always 
                wanted to do, initially because I wanted to learn
                how to hack lol. 
            </p>
            <p>
                I now seriously enjoy what I'm doing
                unlike before and want to become skilled 
                in as much programming languages as I can.
            </p>
            <p>
                My short term goal is to become a competent web
                 developer and eventually to get into game development,
                  as well as UX Design and Cybersecurity.
            </p>
            <p>
                I've managed to so far create the layout of a 
                game I'm trying to make using Blender and Unity, 
                which has been challenging but super fun.
            </p>
  </div>

  
  
  <div class="about">
    <div class="card" v-for="item in hobbies" :key="item">
            <img :src= "item.img" style="width:298px; height:200px;">
            <div class="container">
                <h3><b> {{item.title}}</b></h3>
                <p> {{item.text}}</p>
            </div>
    </div>
  </div>
</div>
  

</template>

<script>
// import { url } from 'inspector';


export default {
  hobbies: "card",
  data(){
    return {
 hobbies : [
  {
    title: "Gaming",
    text: "I've always been playing game as long as I can remember. I first started on the old PC's when we still used floppy disks lol. And then, on Console when I got my very own PlayStation 2 at 7 years old.",
    img: "https://i.postimg.cc/kXDRp8WB/Mario-1.gif"
  }, 
  {
    title: "Baking",
    text: "I think it's worth bragging that I baked my first cake at the tender age of 3. I've got to give my Grandma some credit though for always making the best cakes and pastries and teaching me all the tricks. I've loved baking ever since. ",
    img: "https://i.postimg.cc/qBsK9nbL/baking.gif"
  },
  {
    title: "Gardening",
    text: "Something I also really enjoy doing is growing my own vegetables (I haven't gotten to growing fruits yet) and watching something grow from just a little seed.",
    img: "https://i.postimg.cc/SNNcpRzz/gardening-plot.gif"
  }
] 
  }}}




</script>

<style scoped>

.aboutPage {
  background-image: url(https://i.postimg.cc/sDnPt2cm/360-F-116611375-24-YKo-WE4kwk6o-Cue-N0cz-C1p4iuo0uz-Tm.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
.card:hover {
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  }
  
  .aboutPage img {
    margin-top: 30px;
    
    border-radius: 200px;
  }

  .container {
    
    padding: 2px 16px;
  }
  .card {
    margin: 40px;
    
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    transition: 0.3s;
    border-radius: 5px; 
    width: 300px;
  }
  
  .card p {
    
    font-size: 14px;
  }
  
  .card img {
    margin-top: -0px;
    margin-left: 0.5px;
    margin-bottom: 0px;
    border-radius: 5px 5px 0 0;
  }

  .aboutPage {
    margin: 100px;
    padding: 30px;
    box-shadow: 0 2px 8px 0;
    display: flex;
  }

  .aboutMe {
    margin: 50px;
    padding: 10px;
    width: 600px;
    height: 750px;
    font-size: 19px;
    background-color: rgb(185, 211, 245);
    box-shadow: 0 0 5px black;
    border-radius: 10px;
    color:aliceblue;
  }

  .aboutMe h1 {
    
    font-weight: bold;
    font-size: 40px;
    color: white;
  }

  .aboutMe p {
    margin-top: 50px;
    font-weight: bold;
    font-size: 18px;
  }


</style>
