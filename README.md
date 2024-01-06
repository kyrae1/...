<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KY Rai - Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
        }

        nav {
            display: flex;
            justify-content: space-around;
            background-color: #444;
            padding: 0.5em;
        }

        nav a {
            color: #fff;
            text-decoration: none;
        }

        main {
            padding: 2em;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        #search-bar {
            margin-top: 1em;
            padding: 0.5em;
            width: 100%;
            box-sizing: border-box;
        }
    </style>
</head>
<body>
    <header>
        <h1>ky ko 1st website</h1>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#search">Search</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>
                Hello! My name is Kunghang. I am passionate about web development and technology. 
                This is my personal website where I share information about myself and my projects.
            </p>
        </section>

        <section id="search">
            <h2>Search</h2>
            <input type="text" id="search-bar" placeholder="Search...">
            <!-- Add JavaScript for search functionality -->
            <script>
                // Example: Add your search functionality using JavaScript
                document.getElementById('search-bar').addEventListener('input', function(event) {
                    // Add your search logic here
                    console.log("Search query: " + event.target.value);
                });
            </script>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>
                Feel free to reach out to me at <a href="rkunghang2@gmail.com">rkunghang2@gmail.com</a>.
            </p>
        </section>
    </main>

    <footer>
        &copy; 2024 KY
    </footer>
</body>
</html>
