<template>
    <div class="form">
        <h1>Fill out the form: </h1>
        
<form>
  <div class="mb-3">
    <!-- <form action="https://formspree.io/f/xeqwqbnr" method="post" role="form" class="formspree-form"> -->
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>
  <div class="mb-3 form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Check me out</label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
  </form>

</div>

</template>


<script>

</script>


<style scoped>

.form {
  margin-top: 100px;
  margin-left: 500px;
  padding: 30px;
  border-radius: 30px;
  width: 600px;
  background-color: powderblue;
}

.form h1 {
  margin-bottom: 10px;
  padding-left: 100px;
  font-size: 50px;
  background-color: rgba(107, 238, 192, 0.995);
  border: 3px solid rgba(121, 244, 255, 0.823);
  color: aliceblue;
  border-radius: 20px;
}

</style>