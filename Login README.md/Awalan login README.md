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
