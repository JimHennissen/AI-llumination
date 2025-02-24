

html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI-llumination</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Faculty+Glyphic&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Faculty Glyphic', sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f5efe4;
            display: flex;
            flex-direction: column;
            justify-content: center;
            min-height: 100vh;
        }
        header {
            background: linear-gradient(90deg, #5d4b7e, #a084ca);
            color: white;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed;
            width: 100%;
            top: 0;
        }
        header h1 {
            font-size: 24px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold;
        }
        main {
            flex-grow: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 60px 20px 20px; /* Adjust top padding to account for fixed header */
        }
        h2, h3 {
            margin: 10px 0;
        }
        img {
            width: 200px; /* Adjust size to fit design */
            height: auto;
            margin: 20px auto;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background: #5d4b7e; /* Single color for button */
            color: white;
            text-decoration: none;
            border-radius: 20px;
            font-weight: bold;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Jim Hennissen</h1>
        <nav>
            <a href="#blog">Blog</a>
            <a href="#newsletter">Newsletter</a>
            <a href="#preorder" class="btn">Pre-order</a>
        </nav>
    </header>
    <main>
        <h2>AI-llumination</h2>
        <h3>Your search for the truth starts here</h3>
        <img src="freepik__background__25379.png" alt="Spiritual Symbol">
        <a href="#preorder" class="btn">Pre-order Book</a>
    </main>
</body>
</html>
