<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website!</h1>
        <p>My first website hosted on GitHub Pages 🚀</p>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p>Hi! I'm learning how to make websites. This is my first project!</p>
        </section>

        <section>
            <h2>My Hobbies</h2>
            <ul>
                <li>Coding</li>
                <li>Reading</li>
                <li>Gaming</li>
            </ul>
        </section>

        <section>
            <h2>Contact</h2>
            <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
        </section>
    </main>

    <footer>
        <p>© 2025 My First Website</p>
    </footer>
</body>
</html>
2. style.css
css
Copy code
/* Reset some default styles */
body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

/* Page layout */
body {
    line-height: 1.6;
    background-color: #f0f8ff;
    color: #333;
    padding: 20px;
}

header {
    text-align: center;
    padding: 20px 0;
    background-color: #4CAF50;
    color: white;
    border-radius: 10px;
}

header h1 {
    font-size: 2.5em;
}

main {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: white;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

section {
    margin-bottom: 20px;
}

ul {
    list-style-type: square;
    margin-left: 20px;
}

footer {
    text-align: center;
    margin-top: 20px;
    padding: 10px;
    font-size: 0.9em;
    color: #555;
