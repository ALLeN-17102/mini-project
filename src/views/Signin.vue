<template>
     <div class="main-container">

        <section class="container-1">
            <!-- <h1 class="container1-h1">ArtFront</h1> -->
            <div class="box2">
                <div>
                    <h1 class="box2-h1">Already Have An Account?</h1>
                </div>
                <div>
                    <a href="login.html"><button class="box2-btn">Log In</button></a>
                </div>

            </div>
        </section>
        <section class="container-2">
            <div class="box1">
                <div>
                    <h1 class="box1-h1">Create Your Account!!</h1>
                </div>
                <div>
                    <form action="/register" method="POST">

                        <input type="text" name="username" id="name" placeholder="Name">
                        <input type="email" name="email" id="email" placeholder="E-mail">
                        <input type="password" name="password" id="password" placeholder="Password">
                        <input type="password" name="confirmPassword" id="c-password" placeholder="Confirm Password">
                        <input type="submit" value="Sign Up" class="box1-btn">
                    </form>
                </div>

            </div>
        </section>
    </div>
</template>
<style >
*{
    margin: 0px;
    padding: 0px;
}
.main-container{
    display: flex;
}
/* CONTAINER 1 */
.container-1{
    width: 35%;
    height: 100vh;
    /* border: 2px solid red; */
    background-color: #A510EC;
    /* background-image: url(/img/signin.jpeg); */
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
   
  
    
}
.container1-h1{
    
    font-weight: bolder;
    font-family: 'Roboto', sans-serif;
     margin-left: 60px;
    width: 20%; 
    /* background-color: red; */
    font-size: 2.8rem;
    font-weight: bolder;
    text-align: center;
    line-height: 70px;
    color: white;

}
.box2{
    width: 70%;  
    height: 300px;
    /* border: 2px solid blue; */
    margin: auto;
    margin-top: 180px ;
    display: flex;
    flex-direction: column;
    justify-content: start;
    align-items: center;
}
.box2-h1{
    font-weight: bolder;
    font-family: 'Roboto', sans-serif;
    font-weight: bolder;
    margin-top: 10px;
    font-size: 2.5rem;
    color: white;
    text-align: center;
}
.box2-btn{
    width: 200px;
    margin: auto;
    /* font-size: 1.8rem; */
    font-family: 'Nunito', sans-serif;
    font-weight: bolder;
    font-size: 16px;
    /* padding: 3px 40px; */
    /* margin-left: 470px; */
    margin-top: 48px;
    border-radius: 30px;
    border: none;
    cursor: pointer;
    transition: 0.4s;
    background-color: white;
    color: black;
    padding: 9px;
}
.box2-btn:hover{
    background-color: #000000;
    color: white;
    text-decoration: underline;
    /* box-shadow: 0px 3px 1px grey; */
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.5), 0 6px 20px 0 rgba(0, 0, 0, 0.39);
}





/* CONTAINER 2 */
.container-2{
    width: 65%;
    height: 100vh;
    /* border: 2px solid red;    */
}

.box1{
    width: 50%;
    height: 400px;
    /* border: 2px solid blue; */
    margin: auto;
    margin-top: 70px ;
    display: flex;
    flex-direction: column;
    justify-content: start;
    align-items: center;
}
.box1-h1{
    font-weight: bolder;
    font-family: 'Roboto', sans-serif;
    font-weight: bolder;
    margin-top: 10px;
    font-size: 2rem;
}
input{
    display: block;
    border-radius: 30px;
    margin-top: 40px;
    padding: 9px;
    width: 400px;
    border: none;
    font-weight: bolder;
    background-color: rgb(235, 235, 235);
}
.box1-btn{
    width: 200px;
    margin: auto;
    /* font-size: 1.8rem; */
    font-family: 'Nunito', sans-serif;
    font-weight: bolder;
    font-size: 16px;

    /* padding: 3px 40px; */
    /* margin-left: 470px; */
    margin-top: 50px;
    border-radius: 30px;
    border: none;
    cursor: pointer;
    transition: 0.4s;
    background-color: #A510EC;
    color: white;
}

.box1-btn:hover{
    background-color: #000000;
    color: white;
    text-decoration: underline;
    /* box-shadow: 0px 3px 1px grey; */
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.5), 0 6px 20px 0 rgba(0, 0, 0, 0.39);
}

::placeholder{
    font-weight: bold;
    color: black;
    opacity: 1;
}
</style>