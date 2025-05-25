<!-- Ethical Hacking Website - Stylish & Free -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free Ethical Hacking</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
        }
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
            color: #ffffff;
            scroll-behavior: smooth;
        }
        header {
            background: #111;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 3px solid #00ff99;
        }
        header h1 {
            color: #00ff99;
            font-size: 3rem;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2rem;
            color: #ccc;
        }
        nav {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            background: #1c1c1c;
            padding: 10px 0;
        }
        nav a {
            color: #00ff99;
            text-decoration: none;
            margin: 10px 20px;
            font-weight: bold;
            font-size: 1.1rem;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffffff;
        }
        .content {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        .code-box, .course-box, .material-box, .links-box, .auth-box {
            background: rgba(0,0,0,0.6);
            padding: 25px;
            margin-top: 30px;
            border-radius: 12px;
            box-shadow: 0 0 15px rgba(0, 255, 153, 0.2);
        }
        .course-box {
            border-left: 5px solid #00ff99;
        }
        .material-box ul, .links-box ul {
            list-style-type: square;
            padding-left: 20px;
        }
        pre, code {
            font-family: 'Courier New', Courier, monospace;
            color: #00ff99;
        }
        h2 {
            color: #00ffcc;
        }
        footer {
            background: #101010;
            color: #888;
            text-align: center;
            padding: 30px 20px;
            border-top: 3px solid #00ff99;
            margin-top: 50px;
            font-size: 0.95rem;
        }
        a.resource-link {
            color: #00ff99;
            text-decoration: underline;
        }
        .auth-box input {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: none;
            border-radius: 6px;
        }
        .auth-box button {
            padding: 12px 20px;
            background: #00ff99;
            border: none;
            color: #000;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            transition: background 0.3s;
        }
        .auth-box button:hover {
            background: #00cc7a;
        }
    </style>
</head>
<body>
    <header>
        <h1>Free Ethical Hacking</h1>
        <p>Learn, Practice, and Secure the Web Ethically</p>
    </header>
    <nav>
        <a href="#cpp">C++ Snippet</a>
        <a href="#html">HTML</a>
        <a href="#js">JavaScript</a>
        <a href="#course">Course</a>
        <a href="#materials">Hacking Materials</a>
        <a href="#links">Useful Links</a>
        <a href="#login">Login</a>
        <a href="#signup">Sign Up</a>
    </nav>
    <div class="content">
        <!-- (Content sections like C++, HTML, JS, Courses, etc. remain unchanged) -->

        <section id="login">
            <h2>Login</h2>
            <div class="auth-box">
                <form action="#" method="POST">
                    <input type="text" placeholder="Username" name="username" required>
                    <input type="password" placeholder="Password" name="password" required>
                    <button type="submit">Login</button>
                </form>
            </div>
        </section>

        <section id="signup">
            <h2>Sign Up</h2>
            <div class="auth-box">
                <form action="#" method="POST">
                    <input type="text" placeholder="Username" name="username" required>
                    <input type="email" placeholder="Email" name="email" required>
                    <input type="password" placeholder="Password" name="password" required>
                    <input type="password" placeholder="Confirm Password" name="confirm_password" required>
                    <button type="submit">Sign Up</button>
                </form>
            </div>
        </section>
    </div>

    <footer>
        &copy; 2025 Free Ethical Hacking | For Educational Purposes Only<br>
        Developed by <strong>Asad Ali</strong>
    </footer>
</body>
</html>
