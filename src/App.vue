<template>
  <nav>
    <router-link to="/home"> <span class="material-symbols-outlined">
home
</span>Home</router-link> |
    <router-link to="/about"><span class="material-symbols-outlined">
demography
</span>About</router-link> |
    <router-link to="/resume"><span class="material-symbols-outlined">
code_blocks
</span>Resume</router-link> |
    <router-link to="/testimonials"><span class="material-symbols-outlined">
groups
</span>Testimonials</router-link> |
    <router-link to="/contact"><span class="material-symbols-outlined">
call
</span>Contact</router-link>
  </nav>
  <router-view/>

  <footer class="footer-icons">
                <p>Nikita Ramawoothar © | 2023</p>
                <a href="#"><i class="fab-fa-twitter"></i></a>
                <a href="#"><i class="fab fa-twitch"></i></a>
                <a href="#"><i class="fab fa-linkedin-in"></i></a> 
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-github"></i></a>
  </footer>

</template>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  overflow:hidden;
}

nav {
  padding: 30px;
  margin-left: 550px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #75d7ab;
}

footer {
  display: flex;
  gap: 40px;
  margin-top: 20px;
  margin-left: 0px;
  background-color: rgb(215, 231, 245);
}

.footer-icons a {
  margin: -800px;
  margin-top: 0px;
  font-size: 25px;
  margin-left: 675px;
  padding: -0px;
}

</style>
