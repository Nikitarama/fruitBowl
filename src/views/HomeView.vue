<template>
<div class="name">
    <img alt="Vue logo" src="../assets/nikita_instg.jpg" style="width:300px ">
    <h1>I am Nikita Ramawoothar</h1>
    <h5>    and I'm an 
            aspiring web developer, and hopefully game 
            developer in the future.
        </h5> <div class="circle"></div>
    
  </div> <!--
    
        
        <div><h1>I am Nikita Ramawoothar</h1> <div class="circle"></div> </div>
        <div><h5>
            and I'm an 
            aspiring web developer, and hopefully game 
            developer in the future.
        </h5></div> 
    

    <div>
                <p>Nikita Ramawoothar © | 2023</p>
                <a href="#"><i class="fab-fa-twitter"></i></a>
                <a href="#"><i class="fab fa-twitch"></i></a>
                <a href="#"><i class="fab fa-linkedin-in"></i></a> 
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-github"></i></a></div> -->
    
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

// export default {
//   name: 'HomeView',
//   components: {
//     HelloWorld
//   }
// }
</script>

<style scoped>

h2 {
  color:lime;
}

.name {
    margin: 100px;
    margin-left: 70px;
    margin-bottom: 20px;
    position: relative;
    
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
    z-index: 1;
    color: white;
    border-bottom: 2px solid white;
    width: 350px;
}

.name h5 {
    margin-left: 500px;
    margin-top:-20px;
    font-size: 20px;
    width: 400px;
    z-index: 1;
    color: white;
}

.circle {
    margin-left: 370px;
    margin-top: 280px;
    width: 450px;
    height: 160px;
    border-radius: 0px;
    position: absolute;
    animation-name: example;
    animation-duration: 3s;
    animation-fill-mode: forwards;
    z-index: -2;
  }
  @keyframes example {
    0%  {background-color:rgb(145, 213, 240); left:0px; top:0px;}
    50%  {background-color:rgb(242, 192, 247); left:400px; top:0px;}
    100%  {background-color:rgb(148, 238, 178); left:100px; top:0px;}
  }


</style>
