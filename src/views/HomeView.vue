<template>
 <div class="name">
  <!-- <img class="animate__animated animate__bounce" alt="image" src="../assets/nikita_instg.jpg" style="width:300px; animation-duration: 3s; ">  -->
  <div class="info" id="bottom">
    <h1>I am Nikita Ramawoothar</h1>
    <h5>    and I'm an 
            aspiring web developer, and hopefully game 
            developer in the future.
        </h5> <div id="circle" class="animate_animated animate__slideInUp"></div>
     
  </div> 
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
    margin-bottom: 200px;
    padding-bottom: 200px;
    position: relative;
    height: 40vh;
    /* background-image: url(https://i.postimg.cc/sDnPt2cm/360-F-116611375-24-YKo-WE4kwk6o-Cue-N0cz-C1p4iuo0uz-Tm.jpg); z-index:-3; margin-top:100px; 
    background-size:cover; */
   
    z-index: 3;
    background: radial-gradient(rgb(0, 0, 0) 10% 10%, transparent 15% 30% , lightsteelblue 40% 40%, transparent 70% 100%);
  }

img {
    padding: 0;
    padding-top: 100px;
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
    margin-left: 510px;
    margin-top: -10px;
    font-size: 35px;
    font-weight: bold;
    z-index: 2;
    color: white;
    border-bottom: 2px solid white;
    width: 350px;
    justify-content: center;
}

.name h5 {
    margin-left: 500px;
    margin-top: -20px;
    font-size: 20px;
    width: 400px;
    z-index: 2;
    color: white;
}

#circle {
    margin-left: 485px;
    margin-top: -20px;
    width: 400px;
    height: 400px;
    border-radius: 400px;
    position: absolute;
    animation-name: example;
    animation-duration: 3s;
    animation-fill-mode: forwards;
    z-index: -1;
    
  }

  .info  {
    margin-top: 100px;
    padding-top: 100px;
    z-index: -2;
    
  }

  @keyframes example {
    0%  {background-color:rgb(145, 213, 240); left:0px; top:100px;}
    50%  {background-color:rgb(242, 192, 247); left:0px; top:0px;}
    100%  {background-color:rgb(148, 238, 178); left:0px; top:0px;}
  }


</style>
