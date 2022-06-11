# JERRY-S-FITNESS
JERRY'S UNISEX GYM [A JERRY'S NATION VENTURE]
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JERRY'S UNISEX GYM [ A JERRY'S NATION VENTURE]</title>
</head>
<link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&display=swap" rel="stylesheet">
<style>
body{ font-family: 'Baloo Bhai 2', cursive;
    color: white;
    margin: 0px;
padding: 0px;
background:url(fitness-01.jpg);
background-repeat: no-repeat;
background-size: cover;
background-position-x: center;
}
.left{
    position:absolute;
    display: inline-block;
    left:auto;
    top: 1px;
border: 0px solid red;
}
.mid{
    display: block;
    width: 36%;
    margin:20px auto;
}
.right{
    position:absolute;
    right: 34px;
    top: 20px;
    display:inline-block;

}
.navbar{
 display:inline-block;
}
.navbar li{
    display: inline-block;
        font-size: 15px;
}
.navbar li a{
    color: white;
        text-decoration: none;
        padding: 35px 15px;   
        

}
.navbar li a:hover,
    .navbar li a.active {
        text-decoration: underline;
        color: grey;

}  

.left img{
    width: 150px,140px;
    height: 120px;
    background-color: rgb(0, 0, 0);
}
.head1{
    display: block;
    font-size: 10px;
    font-style:normal;
    text-align: center;
    text-decoration:none;
}
.btn{
    font-family: 'Baloo Bhai 2', cursive;
    margin: 0px,9px;
    color: white;
    background-color: black;
    padding: 5px,7px;
    border: 2px solid grey;
    border-radius: 10px;
    font-size: 15px;
    cursor: pointer;
}
.btn:hover {
        background-color: rgb(31, 30, 30);
    }
    .container {
        border: 2px solid white;
        margin: 106px 80px;
        padding: 75px;
        width: 33%;
        border-radius: 28px;
    }
    .container h1{
      font-size: x-large;
      text-align:center ;
    }

.formgroup input{
text-align: center;
display: block;
width: 400px;
padding: auto;
border: 2px solid black;
margin: 3px,auto;
border-radius: 20px;
font-size: 18px;
font-family: 'Baloo Bhai 2', cursive;
margin: 11px;
}
.container h1{
text-align: center;
}

.container button{

    display: block;
    width: 50%;
    margin: auto;
    border: 15px black;
    border-radius: 20px;
}
</style>


<body>
<header class="header">
    <div class="left">
        <img src="project logo.jpg"alt="logo">
     
            
            
    </div>
   <div class="mid">
    <ul class="navbar">
        <li><a href="#">Home</a></li>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Fitness Calculator</a></li>
        <li><a href="#">Contact Us</a></li>
        <br>
        <br>
        <br>
        <div class="head1"> 
            <h1><b><center><big>JERRY'S UNISEX GYM 
                <br>
                
              <small>[ A Jerry's Nation Venture..]</small></center></b></h1>
        </div>

    </ul>

   </div>

   <div class="right">
       <button class="btn">Call Us Now </button>
       <button class="btn">E-Mail Us</button>
   </div>

   <div class="container">
  <h1>Join The Best Gym Of Mumbai Now </h1>
  <form action="noaction.php">
    <div class="formgroup">
        <input type="text" name="" placeholder="Enter your'e name">
        <input type="text" name="" placeholder="Enter your'e age"> 
        <input type="text" name="" placeholder="Enter your'e gender"></div>
        <button class="submit">SUBMIT</button>

        

  </form>
</body>
</html>
