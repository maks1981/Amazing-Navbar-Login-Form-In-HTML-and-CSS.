# Amazing-Navbar and Login-Form-In-HTML-and-CSS.

// 1. First create simple Html code where our navbar and login form will

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="style.css">
    <title>Html Tags</title>
</head>

<body>

// Our Amazing simple navbar codes
<nav>
        <div >
            <h4 class="logo"><a href="index.html"></a>L<span>o</span>go</h4>
        </div>
        <ul class="nav-links">
            <li>
                <a href="#">Home</a>
            </li>
            <li>
                <a href="#">About</a>
            </li>
            <li>
                <a href="#">Media</a>
            </li>
            <li>
                <a href="#">Contacts</a>
            </li>
        </ul>
</nav>

// Our Login form codes 

<form class="login" id="header" action="/sign-in-url" method="GET">
    <h2>Sign In</h2>
    <input type="text" placeholder="Username">
    <input type="password" placeholder="password">
    <input type="Submit"> <a href="https://www.youtube.com/watch?v=Ko4qoZOktZM&t=1646s" target="_blank"></a>
</form>


</body>
</html>




// 2. Our css files for style 


* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}
/* Style navbar */
nav {
    display: flex;
    justify-content: space-around;
    align-items: center;
    min-height: 8vh;
    font-family: Arial, Helvetica, sans-serif;
}
.logo span {
    color: #ff0202;
}

.logo {
    color: rgb(0, 0, 0);
    text-transform: uppercase;
    letter-spacing: 5px;
    font-size: 20px;
}

.nav-links{
    display: flex;
    justify-content: space-around;
    width: 30rem;
}
.nav-links li {
    list-style: none;
}

.nav-links a {
    color: #1504fa;
    text-decoration: none;
    letter-spacing: 3px;
    font-weight: bold;
    font-size: 14px;
}

body{
    font-family: sans-serif;
    background-image: url("https://images.unsplash.com/photo-1414546017025-34e6468be913?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1353&q=80");
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
}

.login{
   width: 350px;
   padding: 40px;
   position: absolute;
   top: 50%;
   left: 50%;
   transform: translate(-50%, -40%);
   background: #99b6913b;
   text-align: center;
   border-radius: 40px;
}
.login h2{
    color: rgb(240, 100, 6);
    text-transform: uppercase;
    font-weight: 500;
}

.login input[type="text"],.login input[type="password"]{
    border: 0;
    background: none;
    display: block;
    margin: 20px auto;
    text-align: center;
    border: 2px solid #3498db;
    padding: 14px 10px;
    width: 200px;
    outline: none;
    color: azure;
    border-radius: 24px;
    transition: 0.25s;
}

.login input[type = "text"]:focus, .login input[type = "password"]:focus{
    width: 280px;
    border-color: #c79f30;
}

.login input[type = "submit"]{
    border: 0;
    background: none;
    display: block;
    color: aliceblue;
    margin: 20px auto;
    text-align: center;
    border: 2px solid #2ecc71;
    padding: 14px 40px;
    outline: none;
    border-radius: 24px;
    transition: 0.25s;
    cursor: pointer;
}

.login input[ type = "submit"]:hover{
    background: #65a8a3;
}

