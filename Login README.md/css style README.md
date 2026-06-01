<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Stranger Things Store</title>

    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<div class="container">

    <div class="login-box">

        <h1>STRANGER THINGS</h1>
        <p>Welcome Back to Hawkins</p>

        <form id="loginForm">

            <div class="input-group">
                <label>Email</label>
                <input type="email" id="email">
                <small id="emailError"></small>
            </div>

            <div class="input-group">
                <label>Password</label>
                <input type="password" id="password">
                <small id="passwordError"></small>
            </div>

            <button type="submit">
                Login
            </button>

        </form>

        <div class="register-link">
            Don't have an account?
            <a href="register.html">Register</a>
        </div>

    </div>

</div>

<script src="js/login.js"></script>

</body>
</html>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#050505;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
}

.login-box{
    width:400px;
    padding:40px;
    background:#111;
    border:1px solid #ff0000;
    border-radius:15px;
    box-shadow:0 0 20px rgba(255,0,0,.4);
}

.login-box h1{
    text-align:center;
    color:#ff0000;
    margin-bottom:10px;
}

.login-box p{
    text-align:center;
    margin-bottom:30px;
}

.input-group{
    margin-bottom:20px;
}

.input-group label{
    display:block;
    margin-bottom:5px;
}

.input-group input{
    width:100%;
    padding:12px;
    border:none;
    border-radius:8px;
}

button{
    width:100%;
    padding:12px;
    background:#ff0000;
    color:white;
    border:none;
    border-radius:8px;
    cursor:pointer;
}

button:hover{
    background:#cc0000;
}

small{
    color:red;
}

.register-link{
    text-align:center;
    margin-top:20px;
}

.register-link a{
    color:#ff0000;
}
