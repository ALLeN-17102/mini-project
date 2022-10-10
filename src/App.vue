<template>
  
  <div class="navigation">
    <div>
      <nav>
        <router-link to="/" class="navbar">Home</router-link>
        <router-link to="/about" class="navbar">For Developers</router-link>
        <router-link to="#" class="navbar">For Recruiter</router-link>
        <router-link to="#" class="navbar">Contact Us</router-link>
        <!-- <router-link :to="{name :'about'}">About</router-link> -->
      </nav>
      
    </div>

    <div>
      <button  class="btn navbar" id="btn-1" ><router-link to="/login" class="navbar">Log in</router-link></button>
      <button class="btn navbar" id="btn-2"><router-link to="/signup" class="navbar">Sign up</router-link></button>
    </div>
  </div>


<router-view />
</template>

<style>
* {
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.navigation {
  height: 80px;
 
  /* border: 2px solid red; */
  display: flex;
  justify-content: flex-end;
}
.navbar {
  margin: 10px 10px;
  text-decoration: none;
  
}

nav {
  padding: 20px;
  font-size: 20px;
}

nav a {
  /* font-weight: bold; */
  color: #2c3e50;
  text-decoration: none;
}
nav a:hover {
  color: #a510ec;
  text-decoration: underline;
}

.container {
  background-image: url("../src/assets/Group 11.png");
  background-size: 100% 100vh;
  height: 97vh;
  width: 100%;
  color: white;
  /* border: 2px solid green; */
  display: flex;
  justify-content: center;
  align-items: center;
}
.box {
  /* border: 2px solid red; */
  height: 70vh;
  width: 70%;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
}
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@500&display=swap");
.box-h1 {
  font-size: 3rem;
  /* font-weight: bolder; */
  font-family: "Inter", sans-serif;
}
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@300;500&display=swap");
.box-p {
  font-size: 1rem;
  /* font-weight: bold ; */
  font-family: "Inter", sans-serif;
}

@import url("https://fonts.googleapis.com/css2?family=Inter:wght@300;500&display=swap");
#btn-1 {
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  background-color: white;
  font-family: "Inter", sans-serif;
  font-size: 20px;
  font-weight: bold;
  /* text-decoration: none; */
}
#btn-2 {
  border: none;
  border-radius: 5px;
  background-color: white;
  font-family: "Inter", sans-serif;
  padding: 10px 20px;
  font-size: 20px;
  font-weight: bold;
  /* text-decoration: none; */
}
#btn-1:hover {
  cursor: pointer;
  color: white;
  background-color: #a510ec;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.5), 0 6px 20px 0 rgba(0, 0, 0, 0.39);
}
/* #btn-1:active{
  color: white;
} */
#btn-2:hover {
  cursor: pointer;
  color: white;
  background-color: #a510ec;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.5), 0 6px 20px 0 rgba(0, 0, 0, 0.39);

}

</style>
