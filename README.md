# About-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Page</title>
    <style>
        body {
            font-family: Helvetica, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-image: url(image.jpg);
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: rgb(red, green, blue);
        }

        header {
            background-color: #ff3363;
            color: white;
            text-align: center;
            padding: 1em;
        }

        nav {
            background-color: #33d1ff;
            color: white;
            padding: 0.5em;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 0.5em 1em;
            margin: 0 1em;
        }

        main {
            padding: 2em;
        }

        img {
            flex: 1 800px;
            width: 400px; 
            height: 400px; 
            object-fit: cover;
        }
        footer {
            background-color: #ff3363;
            color: white;
            text-align: center;
            padding: 1em;
            position: bottom;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Creative Minds</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
<!--on this page I will display flex boxes of images below the header that shows art tutorials and types of materials-->
    <main>
        <h2>About Creative Minds</h2>
        <p>Art Content Here</p>
        <img scr="image_1.jpg">
   <img scr="image_2.jpg">
   <img scr="image_3.jpg">
   <p>more art content</p>
    </main>

    <footer>
        Creative Minds.
    </footer>

</body>
</html>
