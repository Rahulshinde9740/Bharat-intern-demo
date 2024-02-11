# Bharat-intern-demo
This is my first git repository 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sign In</title>
,<link rel="stylesheet" href="index.html">
<style>
    body {
        font-family: Arial, sans-serif;
    }
    .container {
        width: 300px;
        margin: 0 auto;
        padding: 20px;
        border: 1px solid #ccc;
        border-radius: 5px;
        margin-top: 50px;
    }
    input[type="text"],
    input[type="password"] {
        width: 100%;
        padding: 10px;
        margin: 5px 0 20px 0;
        display: inline-block;
        border: 1px solid #ccc;
        border-radius: 4px;
        box-sizing: border-box;
    }
    input[type="submit"] {
        background-color:red;
        color: white;
        padding: 14px 20px;
        margin: 8px 0;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        width: 100%;
    }
    
    input[type="submit"]:hover {
        background-color: #45a049;
    }
    .remember-me {
        margin-bottom: 10px;
    }
</style>
</head>
<body>

<div class="container">
    <h2>Sign In</h2>
    <form action="login_process.php" method="post">
        <label for="email_phone">Email or Phone Number:</label>
        <input type="text" id="email_phone" name="email_phone" placeholder="Email or Phone Number">

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Password">

        <input type="submit" value="Send Sign In ccode">
        <h1>OR</h1>
        <form action="use_password.php" method="post" class="use-password">
            <input type="submit" value="Use Password">
        </form>
        
        <div class="forgot-password">
            <a href="forgot_email_password.php">Forgot Email or Password?</a>
        </div>
    
    
    </form>
    <div class="remember-me">
        <input type="checkbox" id="remember_me" name="remember_me">
        <label for="remember_me">Remember Me</label>
    </div>
</div>

</body>
</html>
