<template>
<div class="name">
    <img class="animate__animated animate__bounce" alt="image" src="../assets/nikita_instg.jpg" style="width:300px; animation-duration: 3s; "> 
    <h1>I am Nikita Ramawoothar</h1>
    <h5>    and I'm an 
            aspiring web developer, and hopefully game 
            developer in the future.
        </h5> <div id="circle" class="animate_animated animate__slideInUp"></div>
    
  </div> 
    
        
      
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>

body {
  background-image: url(https://i.postimg.cc/sDnPt2cm/360-F-116611375-24-YKo-WE4kwk6o-Cue-N0cz-C1p4iuo0uz-Tm.jpg);
}



.name {
    margin: 100px;
    margin-left: 70px;
    margin-bottom: 20px;
    position: relative;
    /* background-image: url(https://i.postimg.cc/sDnPt2cm/360-F-116611375-24-YKo-WE4kwk6o-Cue-N0cz-C1p4iuo0uz-Tm.jpg); z-index:-3; margin-top:100px; 
    background-size:cover; */
   background: radial-gradient(black 0% 10%, transparent 15% 30% , lightsteelblue 40% 60%, transparent 70% 100%);
    z-index: 1;
  }

img {
    padding: 0;
    margin-top: -50px;
    margin-left: 530px;
    background-size: contain;
    width: 300px;
    height:300px;
    z-index: 1;
    border-radius: 200px;
    box-shadow: 0 0 20px;
}

.name h1 {
  margin: 30px;
    margin-left: 520px;
    font-size: 34px;
    font-weight: bold;
    z-index: 2;
    color: white;
    border-bottom: 2px solid white;
    width: 350px;
    
}

.name h5 {
    margin-left: 500px;
    margin-top:-20px;
    font-size: 20px;
    width: 400px;
    z-index: 2;
    color: white;
}

#circle {
    margin-left: 470px;
    margin-top: 280px;
    width: 450px;
    height: 160px;
    border-radius: 0px;
    position: absolute;
    animation-name: example;
    animation-duration: 3s;
    animation-fill-mode: forwards;
    z-index: -1;
  }
  @keyframes example {
    0%  {background-color:rgb(145, 213, 240); left:0px; top:100px;}
    50%  {background-color:rgb(242, 192, 247); left:0px; top:0px;}
    100%  {background-color:rgb(148, 238, 178); left:0px; top:0px;}
  }


</style>
