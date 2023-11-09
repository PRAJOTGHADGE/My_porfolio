<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel=" stylesheet" href="prajot.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <title>porfolio</title>
</head>
<body>
    <nav>
        <div class="nav">
            <p>PRAJOT</p>
            <div class="nav1">
                <a href="#"> HOME </a>
                <a href="#"> ABOUT </a>
                <a href="#"> SERVICES </a>
                <a href="#"> PORTFOLIO </a>
                <a href="#"> CONTANCT </a> </div>

               <div class="nav2">
                <p1>
                    <span> MY NAME IS PRAJOT GADGHE </span><br>

                    I AM A CREATIVE <br>
                     FRONTED DEVELOPER <br>

                    FROM BHARAT.<br><br>
                    <span1> This is my portfolio i am exicted toward created<br>
                         different projects please contact me </span1><br><br>
                         <button>   Contact ME   </button>
                </p1>



               </div>

               <div class="img">
                <img src="prajot.jpg" height="500px" width="350px"></img>

               </div>
               <div class="img1">
                <a href="https://www.linkedin.com/in/prajot-ghadge-869a17259?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app "><img src="link.png" height="60px" width="60px"></a>
                </div>
    </nav>
</body>
</html>
*{
    padding:0%;
    margin:0%;
    font-family:'Courier New', Courier, monospace;
}
.nav {
    height:800px;
    width:auto;
    background-color: black;
    color:white;
    display: flex;


}
p{
    margin-top: 20px;
    font-size: 30px;
    margin-left: 200px;
}
.nav1{
    

    justify-content: space-between;
    display: flex;
    margin-left: 550px;
    gap: 50px;
    margin-top: 20px;
    font-size: 20px;
    color:white;
    height:25px;
   
}
a{
    list-style: none;
    text-decoration: none;
    color:white;

}
a:hover{
    border:1px solid black;
    background-color:bisque;
    color:brown;
    border-radius:10%;
}
.nav2 {
    margin-top: 200px;
    margin-left: 200px;
    position: absolute;
    font-size: 30px;
    font-weight: 800;
}
span {
    font-size: 18px;
    color:orange;
}
span1 {
    font-weight: 400;
    font-size: 18px;
}
button {
    border:1px solid black;
    background-color: rgb(255, 115, 0);
    padding: 13px;
    font-size: 15px;
    color : white;
}
.img{
    margin-top: 100px;
    margin-left: 900px;
    position: absolute;
    
}
.img1{
    position: absolute;
    margin-left: 200px;
    margin-top: 560px;
    border:2px solid black;
    border-radius:20px;
    position: absolute;
}
