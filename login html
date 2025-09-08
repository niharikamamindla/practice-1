<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Login Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f2f2f2;
            display: flex;
            height: 100vh;
            justify-content: center;
            align-items: center;
        }
        .login-container {
            background: #fff;
            padding: 30px 40px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.15);
            width: 320px;
        }
        .login-container h2 {
            margin-bottom: 24px;
            text-align: center;
        }
        .login-container label {
            display: block;
            margin-bottom: 8px;
            margin-top: 15px;
        }
        .login-container input[type="text"],
        .login-container input[type="password"] {
            width: 100%;
            padding: 8px 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .login-container button {
            width: 100%;
            padding: 10px;
            background: #007bff;
            color: #fff;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
        }
        .login-container button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>Login</h2>
        <form id="loginForm" onsubmit="return validateLogin()">
            <label for="username">Username</label>
            <input type="text" id="username" name="username" required>

            <label for="password">Password</label>
            <input type="password" id="password" name="password" required>

            <button type="submit">Login</button>
        </form>
        <div id="message" style="color:red; text-align:center; margin-top:10px;"></div>
    </div>

    <script>
        function validateLogin() {
            var username = document.getElementById("username").value;
            var password = document.getElementById("password").value;
            var messageDiv = document.getElementById("message");

            // Simple validation logic (replace with real authentication)
            if(username === "admin" && password === "1234") {
                messageDiv.style.color = "green";
                messageDiv.innerText = "Login successful!";
                // You can redirect to another page here
                // window.location.href = "dashboard.html";
                return false; // Prevent form submission for demo
            } else {
                messageDiv.style.color = "red";
                messageDiv.innerText = "Invalid username or password";
                return false; // Prevent form submission
            }
        }
    </script>
</body>
</html>
