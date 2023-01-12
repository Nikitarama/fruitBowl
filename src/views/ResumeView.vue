<template>
  
  <div class="education">
      <h5>Resume | Education</h5>
    </div>

      <div class="card" v-for="item in education" :key="item">
        <div class="container">
        <img :src= "item.img" style="width: 160px; height:120px; border-radius:5px;">
        <h4> {{item.name}} <span class="material-symbols-outlined">
              school
            </span></h4>
        <p> {{item.text}}</p>
      </div>      
    
      </div>
    <div class="CV"> 
      
        <h3>Curriculum Vitae</h3>
        <img src="https://i.postimg.cc/xTRKCsXq/nikitacv.png">
      </div>
        <br>
  <div class="projects">
    <h3>Past Projects</h3>
  
    <div class="card" v-for="item in projects" :key="item">
            <img :src= "item.img" style="width:500px; height:300px;">
            
                <h5><b> {{item.name}}</b></h5>
                <p> {{item.text}}</p>
                <button class="open">Open</button>
            
    </div>
  </div>

  <br>

<div class="skills">
    <h2>My Skills</h2>
    <br>
    <div class="row">
            <div class="col-md-3" id="skillCard" style="width: 30vh;">
              
          <svg viewBox="0 0 452 520">
             <title>HTML5 Logo Badge</title>
              <path
               fill="RGB(227,79,38)"
                d="M 41,460 L 0,0 451,0 410,460 225,512"
              />
              <path
                fill="RGB(239,101,42)"
                d="M 226,472 L 375,431 410,37 226,37"
              />
              <path
                fill="RGB(236,237,238)"
                d="M 226,208 L 151,208 146,150 226,150 226,94 84,94 99,265 226,265 z M 226,355 L162,338 158,293 102,293 109,382 226,414 z"
              />
              <path
                fill="RGB(255,255,255)"
                d="M 226,265 L 295,265 288,338 226,355 226,414 341,382 357,208 226,208 z M 226,94 L226,150 362,150 367,94 z"
              />
        </svg>
      </div>
    </div>

    <br>
        <div class="progress" style="width:80vh;">
              <div class="progress-bar progress-bar-striped active bg-danger progress-bar-animated" role="progressbar"
                aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width:80%">
                80%
              </div>
        </div>
      
        <br>

      <div class="col-md-3" id="skillCard" style="width: 30vh;">
        
        <svg viewBox="0 0 452 520">
          <title>CSS3 Logo Badge</title>
          
          <path
            fill="RGB(12,115,184)"
            d="M 41,460 L 0,0 451,0 410,460 225,512"
          />
          <path
            fill="RGB(48,169,220)"
            d="M 226,472 L 375,431 410,37 226,37"
          />
          <path
            fill="RGB(236,237,238)"
            d="M 226,208 L 94,208 99,265 226,265 z M 226,94 L 84,94 89,150 226,150 z M 226,355 L 102,322 109,382 226,414 z"
          />
          <path
            fill="RGB(255,255,255)"
            d="M 226,265 L 295,265 288,338 226,355 226,414 341,382 367,94 226,94 226,150 306,150 300,208 226,208 z"
          />
        </svg>
      </div>
      <br>
        <div class="progress" style="width:80vh;">
          <div class="progress-bar progress-bar-striped active bg-primary progress-bar-animated" role="progressbar"
            aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width:70%">
            70%
          </div>
        </div>
      
        
        <br>
        
    <div class="row">
      <div class="col-md-3" id="skillCard" style="width: 30vh;">
        
        
        <svg viewBox="0 0 452 520">
          <title>Javascript Logo Badge</title>
          
          <path
            fill="RGB(229,162,40)"
            d="M 0,0 L 451,0 410,460 225,512 41,460"
          />
          <path
            fill="RGB(241,191,38)"
            d="M 226,472 L375,431 410,37 226,37"
          />
          <path
            fill="RGB(236,237,238)"
            d="M 226,94 L 113,94 102,265 226,265 226,208 160,208 165,150 226,150 z M 226,355 L 162,338 158,293 102,293 109,382 226,414 z"
          />
          <path
            fill="RGB(255,255,255)"
            d="M 226,265 L 295,265 288,338 226,355 226,414 341,382 357,208 226,208 z M 226,94 L 339,94 357,180 301,180 293,150 226,150 z"
          />
        </svg>
        <br>
        <br>
        <div class="progress" style="width:80vh; margin-left: 3px;">
          <div class="progress-bar progress-bar-striped active bg-warning progress-bar-animated" role="progressbar"
          aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width:60%">
            60%
        </div>
      </div>
    </div>
  
  <div class="bootstrap-logo col-md-3" id="skillCard" style="width: 30vh; margin-left: -220px; margin-top: 120px;">
        
        <svg xmlns="http://www.w3.org/2000/svg" height="200px" viewBox="0 0 512 407.864" width="300px"><path d="m106.344 0c-29.214 0-50.831 25.57-49.863 53.3.929 26.641-.278 61.145-8.964 89.283-8.717 28.217-23.449 46.098-47.517 48.393v25.912c24.068 2.3 38.8 20.172 47.516 48.393 8.687 28.138 9.893 62.642 8.964 89.283-.968 27.726 20.649 53.3 49.868 53.3h299.347c29.214 0 50.827-25.57 49.859-53.3-.929-26.641.278-61.145 8.964-89.283 8.717-28.221 23.413-46.1 47.482-48.393v-25.912c-24.068-2.3-38.764-20.172-47.482-48.393-8.687-28.134-9.893-62.642-8.964-89.283.968-27.726-20.645-53.3-49.859-53.3h-299.355zm240.775 251.067c0 38.183-28.481 61.34-75.746 61.34h-80.458a8.678 8.678 0 0 1 -8.678-8.678v-199.593a8.678 8.678 0 0 1 8.678-8.678h80c39.411 0 65.276 21.348 65.276 54.124 0 23.005-17.4 43.6-39.567 47.208v1.2c30.176 3.31 50.495 24.21 50.495 53.077zm-84.519-128.1h-45.876v64.8h38.639c29.87 0 46.34-12.028 46.34-33.527-.003-20.148-14.163-31.273-39.103-31.273zm-45.876 90.511v71.411h47.564c31.1 0 47.573-12.479 47.573-35.931s-16.935-35.484-49.573-35.484h-45.564z" fill="#7952b3" fill-rule="evenodd"/></svg>
     
      
       
        <div class="progress" style="width:80vh; margin-left: 16px;  margin-top: -20px;">
          <div class="progress-bar progress-bar-striped active bg-secondary progress-bar-animated" role="progressbar"
            aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width:85%">
            85%
          </div>
        </div>
    </div>    
  </div>
</div>



  </template>
  
<script>

export default {
  education: "card",
  data(){
    return {
 education : [
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
    }
  ],
  projects : [
  {
    name: "A calculator",
    text: "I built a calculator with only JS",
    img: "https://i.postimg.cc/D0JVsz9C/2022-12-27-1.png"
  },
  {
    name: "An ecommerce site",
    text: "I designed a fully functional ecom site for vintage cars",
    img: "https://i.postimg.cc/W4h7sJgf/2022-12-27.png"
  },
  {
    name: "A portfolio",
    text: "I created a portfolio in the first month at the coding bootcamp with only HTML, CSS and Bootstrap",
    img: "https://i.postimg.cc/x8CfZYWH/2022-12-27-2.png"
  }
    ]
  }},
    
    
  
}
  

</script>

<style scoped>

body {
  overflow: hidden;
}
.card {
    background-color: rgb(200, 121, 255);
    box-shadow: 0 0px 5px black;
    line-height: 20px;
    margin: 20px;
    width: 600px;
    height: 230px;
    margin-bottom: 20px;
    margin-left: 450px;
    color: aliceblue;
}
.card:hover {
    box-shadow: 0 0px 10px 0 black;
  }

.education {
  display: flex;
  margin-left: 3px;
  
  border: px solid rgb(78, 219, 186);
  background-color: rgb(200, 121, 255);
}

.education h5 {
  color:white;
  font-size: 40px;
  margin-left: 580px;
}



.card h4 {
  margin: 10px;
  
  font-size: 25px;
  color: antiquewhite;

}

.card p {
  margin: 6px;
  font-size: 14px;
  
}

.card img {
  margin: 5px;
  margin-left: 200px;
}

.CV img {
  margin-left: 500px;
  
  width: 500px;
  
}
.CV h3 {
  border: 2px solid  rgb(200, 121, 255);
  background-color:  rgb(200, 121, 255);
  color: aliceblue;
  padding-left: 640px;
}

.projects h3 {
  border: 2px solid  rgb(200, 121, 255);
  background-color:  rgb(200, 121, 255);
  color: aliceblue;
  padding-left: 680px;
}

.projects .card {
  height: 400px;
  margin-bottom: 100px;
  border-radius: 0px;
  background-color: rgb(200, 121, 255);
}

.projects button {
  width: 70px;
  height:50px;
  margin-top: 30px;
  margin-left: 280px;
  color: cadetblue;
  border: 0px solid grey;
}

.projects button:hover {
  background-color: cadetblue;
  color: aliceblue;
}

.projects p, h5 {
  margin: 10px;
  margin-top: 5px;
  color: aliceblue;
}

.projects p {
  margin-top: -10px;
}

.projects img {
  margin: 20px;
  margin-top: 50px;
  margin-left: 50px;
  width: 300px;
}

#skillCard, .progress {
  margin-left: 500px;
}

.skills h2 {
  border: 2px solid  rgb(200, 121, 255);
  background-color:  rgb(200, 121, 255);
  color: aliceblue;
  padding-left: 680px;
}
.bootstrap-logo {
  margin-left: 400px;
  margin-bottom: 0px;
}

.bootstrap-logo h3 {
  margin-left: 15px
}

svg {
  margin-left: 230px;
  width: 100px;
}

</style>