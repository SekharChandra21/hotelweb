<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contactus</title>
</head>
<body background="https://free4kwallpapers.com/uploads/originals/2015/06/16/hotel-in-santorini.jpg" class="bdy">
    <nav class="navbar">
        <ul>
            <li><a href = "http://127.0.0.1:5500/homepage.html">Home</a></li>
            <li><a href = "http://127.0.0.1:5500/aboutus.html">About Us</a></li>
            <li><a href = "http://127.0.0.1:5500/services.html">Services</a></li>
            <li><a href = "http://127.0.0.1:5500/contactus.html">Contact Us</a></li>
            <li><a href = "http://127.0.0.1:5500/Login.html">Login</a></li>

        </ul>
    </nav>
    <div class="contact1">
        <h1 class="headings" align="center">CONATCT US</h1>
        <form action="" class="form1">
             
            <div class="fn">
                <label for="fname">FirstName</label>
                <input type="text" name="name" id="fname" placeholder=" Your Name">
            </div>
            <div class="ln">
                <label for="lname">LastName</label>
                <input type="text" name="name" id="lname" placeholder="Enter Your lastname">
            </div>
              
            <div class="em">
                <label for="email">E-mail</label>
                <input type="email" name="email"  id="email" placeholder="Enter Your Email">
            </div>
             <div class="msg"> 
                <label for="msg">Message</label>
                <input type="text" name="msg" id="msg" placeholder="Enter Your Message">
            </div>
            <div class="btn">
                  <input type="submit" value="SEND" id="send">
            </div>  
        </form>
    </div>
    
</body>
<style>
bdy{
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: 100% 100%;
}
    .contact1{
     
    background: rgba(145, 196, 51, 0.9);
    
}
.fn{
    position: absolute;
    left: 40%;
    bottom: 70%;
}
.ln{
    position: absolute;
    left: 40%;
    bottom: 65%;
}
.em{
    position: absolute;
    left: 40%;
    bottom: 60%;
}
.msg{
    position: absolute;
    left: 40%;
    bottom: 55%;
}
.btn{
    position: absolute;
    left: 47%;
    bottom: 50%;
}
.navbar{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: rgba(193, 96, 212, 0.5);
    position:sticky;
    top: 0;
}
.navbar ul{
    display: flex;
    list-style: none;
    margin: 20px 0px;
}
.navbar ul li{
    font-family: century;
    font-size: 1.1rem;
    font-weight: bold;
}
.navbar ul li a{
    text-decoration: none;
    color: white;
    padding: 8px 25px;
    transition: all .5s ease;
}
.navbar ul li a:hover{
    background-color: rgb(77, 201, 170);
    color: black;
    box-shadow: 0 0 10px white;
}
</style>
</html>
