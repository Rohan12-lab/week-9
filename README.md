<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Layout</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2f;
            color: white;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            color: #ffcc00;
        }
        nav {
            text-align: center;
            margin: 10px 0;
        }
        nav a {
            color: #ff66ff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .search {
            text-align: center;
            margin: 20px 0;
        }
        .search input[type="text"] {
            padding: 5px;
        }
        .search input[type="submit"] {
            padding: 5px 10px;
            background-color: #666;
            color: white;
            border: none;
            cursor: pointer;
        }
        .content {
            padding: 20px;
        }
        .content h2 {
            color: #ffcc00;
        }
        .subsection {
            border: 1px solid #00ffff;
            padding: 10px;
            margin-bottom: 20px;
        }
        .related {
            margin-top: 20px;
        }
        .related ul {
            list-style: none;
            padding: 0;
        }
        .related li a {
            color: #ff6666;
            text-decoration: none;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.8em;
            color: #999;
        }
    </style>
</head>
<body>
    <header>
        <h1>Header</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Our team</a>
            <a href="#">Projects</a>
            <a href="#">Contact</a>
        </nav>
    </header>
    <div class="search">
        <input type="text" placeholder="Search query">
        <input type="submit" value="Go!">
    </div>
    <div class="content">
        <h2>Article heading</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec a diam lectus...</p>
        <div class="subsection">
            <h3>Subsection</h3>
            <p>Donec ut libero sed accumsan vehicula...</p>
        </div>
        <div class="subsection">
            <h3>Another subsection</h3>
            <p>Donec viverra mi quis quam pulvinar at malesuada arcu rhoncus...</p>
        </div>
        <div class="related">
            <h3>Related</h3>
            <ul>
                <li><a href="#">Oh I do like to be beside the seaside</a></li>
                <li><a href="#">Oh I do like to be beside the sea</a></li>
                <li><a href="#">Although in the North of England</a></li>
                <li><a href="#">It never stops raining</a></li>
                <li><a href="#">Oh well...</a></li>
            </ul>
        </div>
    </div>
    <footer>
        &copy; Copyright 2050 by nobody. All rights reversed.
    </footer>
</body>
</html>
