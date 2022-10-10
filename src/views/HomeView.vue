<template>

  <div class="container">
    <div class="box">
      <h1 class="box-h1">WEBSITE NAME</h1>
      <p class="box-p">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic
        reprehenderit earum fuga laudantium, maiores et esse voluptatem.
        Sapiente doloremque odio fugiat incidunt tenetur, nostrum itaque
        voluptatibus obcaecati voluptas illum, commodi delectus. Commodi
        deleniti saepe suscipit corrupti voluptatum dignissimos possimus in
        maxime nemo esse consequuntur, eius reprehenderit est illum assumenda
        eveniet quisquam error dolorum. Natus impedit id quidem dolorem sint
        quaerat nulla! Impedit molestiae quibusdam quaerat velit ullam
        distinctio sapiente voluptatibus!
      </p>
    </div>
  </div>
  <div class="dev-container">
    <div class="dev-box"></div>
    <div class="dev-box" id="dev-box-2">
      <h1 id="dev-h1">For Developers</h1>
      <p id="dev-p">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis sit
        rerum commodi nam illo, explicabo autem delectus quas magnam suscipit
        tempore laudantium! Temporibus recusandae, laudantium natus quaerat
        nulla velit unde vero obcaecati amet? Esse sint nisi animi quaerat non
        consectetur iusto deleniti culpa iste. Quam minus possimus magnam quae
        illo?
      </p>
      <button id="rec-btn">EXPLORE MORE</button>
    </div>
  </div>
  <div class="rec-container">
    <div class="rec-box" id="rec-box-1">
      <div id="rec-box-shift">
        <h1 id="rec-h1">For Recruiters</h1>
        <p id="rec-p">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis sit
          rerum commodi nam illo, explicabo autem delectus quas magnam suscipit
          tempore laudantium! Temporibus recusandae, laudantium natus quaerat
          nulla velit unde vero obcaecati amet? Esse sint nisi animi quaerat non
          consectetur iusto deleniti culpa iste. Quam minus possimus magnam quae
          illo?
        </p>
        <button id="rec-btn">EXPLORE MORE</button>
      </div>
    </div>
    <div class="rec-box" id="rec-box-2"></div>
  </div>
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
  /* border: 2px solid red; */
  display: flex;
  justify-content: flex-end;
}
.navbar {
  margin: 10px 10px;
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
  background-image: url("/src/assets/Group 11.png");
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
  font-size: 15px;
  font-weight: bold;
}
#btn-2 {
  border-radius: 5px;
  background-color: white;
  font-family: "Inter", sans-serif;
  padding: 10px 20px;
  font-size: 15px;
  font-weight: bold;
}
#btn-1:hover {
  cursor: pointer;
  color: white;
  background-color: #a510ec;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.5), 0 6px 20px 0 rgba(0, 0, 0, 0.39);
}
#btn-2:hover {
  cursor: pointer;
  color: white;
  background-color: #a510ec;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.5), 0 6px 20px 0 rgba(0, 0, 0, 0.39);
}

  .dev-container {
            /* border: 2px solid red; */
            height: 98vh;
            width: 100%;
            background-image: url("/src/assets/Group 13.png");
            display: flex;
            justify-content: center;
            align-items: center;


        }

        .dev-box {
            /* border: 2px solid blue; */
            width: 50%;
            height: 60vh;
        }

        #dev-box-2 {
           
            font-family: 'Inter', sans-serif;

        }

        #dev-h1 {
            font-size: 3rem;
            
        }

        #dev-p {
            margin-top: 90px;
            font-size: 20px;
            
        }

        #dev-btn {
            margin-top: 60px;
            padding: 20px 25px;
            background-color: #00ff0d;
            /* font-weight: bold; */
            border-radius: 4px 4px;
            cursor: pointer;
            border: none;
            font-family: 'Inter', sans-serif;

               
        }

         .rec-container {
            /* border: 2px solid red; */
            height: 98vh;
            width: 100%;
            background-image: url("/src/assets/Group 15.png");
            background-size: 100%;
            background-repeat: no-repeat;
            display: flex;
            justify-content: center;
            align-items: center;


        }

        .rec-box {
            /* border: 2px solid blue; */
            width: 50%;
            height: 60vh;
        }

        #rec-box-1 {

            font-family: 'Inter', sans-serif;
            color: white;
            /* display: flex;
            flex-direction: column;
            align-items: center; */

        }
        #rec-box-shift{
            margin-left: 30px;
        }

        #rec-h1 {
            font-size: 2.5rem;
            margin-top:125px;

        }

        #rec-p {
            margin-top: 50px;
            font-size: 20px;

        }

        #rec-btn {
            margin-top: 40px;
            padding: 20px 25px;
            background-color: #00ff0d;
            /* font-weight: bold; */
            border-radius: 4px 4px;
            cursor: pointer;
            border: none;
            font-family: 'Inter', sans-serif;


        }
</style>
