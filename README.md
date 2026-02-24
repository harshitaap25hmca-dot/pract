# pract

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Login Page</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #4e73df, #1cc88a);
        }

        .login-container {
            background: #ffffff;
            padding: 40px;
            border-radius: 10px;
            width: 350px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            text-align: center;
        }

        .login-container h2 {
            margin-bottom: 25px;
            color: #333;
        }

        .input-group {
            margin-bottom: 20px;
            text-align: left;
        }

        .input-group label {
            display: block;
            margin-bottom: 6px;
            font-weight: bold;
            color: #555;
        }

        .input-group input {
            width: 100%;
            padding: 10px;
            border-radius: 6px;
            border: 1px solid #ccc;
            outline: none;
            transition: 0.3s;
        }

        .input-group input:focus {
            border-color: #4e73df;
        }

        .login-btn {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 6px;
            background: #4e73df;
            color: #fff;
            font-size: 16px;
            cursor: pointer;
            transition: 0.3s;
        }

        .login-btn:hover {
            background: #2e59d9;
        }

        .extra-links {
            margin-top: 15px;
            font-size: 14px;
        }

        .extra-links a {
            color: #4e73df;
            text-decoration: none;
        }

        .extra-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="login-container">
        <h2>Login</h2>

        <form action="#" method="POST">
            <div class="input-group">
                <label for="username">Username</label>
                <input type="text" id="username" name="username" required>
            </div>

            <div class="input-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" required>
            </div>

            <button type="submit" class="login-btn">Login</button>

            <div class="extra-links">
                <p><a href="#">Forgot Password?</a></p>
                <p>Don't have an account? <a href="#">Sign Up</a></p>
            </div>
        </form>
    </div>

</body>
</html>
