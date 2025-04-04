-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Math Panorama</title>
    <style>
        /* Basic styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            display: inline-block;
        }
        nav a:hover {
            background-color: #ddd;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        section {
            margin: 20px 0;
            padding: 20px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            margin: 10px 0;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Math Panorama</h1>
        <p>Your Hub for Learning Math - Articles, Topics, Books</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#articles">Articles</a>
        <a href="#topics">Topics</a>
        <a href="#books">Books</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Main Content -->
    <div class="container">
        <!-- Articles Section -->
        <section id="articles">
            <h2>Articles</h2>
            <p>Explore the latest articles to enhance your understanding of mathematics:</p>
            <ul>
                <li><a href="#">The Power of Math in Everyday Life</a></li>
                <li><a href="#">Why Learning Algebra is Important</a></li>
                <li><a href="#">How Geometry Shapes the World Around Us</a></li>
            </ul>
        </section>

        <!-- Topics Section -->
        <section id="topics">
            <h2>Topics</h2>
            <p>Browse through various math topics and their subtopics:</p>
            <ul>
                <li><strong>Arithmetic</strong>
                    <ul>
                        <li>Addition</li>
                        <li>Subtraction</li>
                        <li>Multiplication</li>
                        <li>Division</li>
                    </ul>
                </li>
                <li><strong>Algebra</strong>
                    <ul>
                        <li>Linear Equations</li>
                        <li>Quadratic Equations</li>
                        <li>Polynomials</li>
                    </ul>
                </li>
                <li><strong>Geometry</strong>
                    <ul>
                        <li>Shapes and Angles</li>
                        <li>Area and Volume</li>
                        <li>Coordinate Geometry</li>
                    </ul>
                </li>
            </ul>
        </section>

        <!-- Books Section -->
        <section id="books">
            <h2>Books to Purchase</h2>
            <p>Here are some recommended books to help you in your math journey:</p>
            <ul>
                <li><a href="https://www.amazon.com/Mathematics-For-Dummies-Books/dp/1119282436">Mathematics for Dummies</a></li>
                <li><a href="https://www.amazon.com/Algebra-Dummies-Mary-Jane-Stanke/dp/0764570724">Algebra For Dummies</a></li>
                <li><a href="https://www.amazon.com/Geometry-Dummies-Mark-Ryan/dp/0471792846">Geometry For Dummies</a></li>
            </ul>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact</h2>
            <p>If you have any questions or need further assistance, feel free to contact me!</p>
            <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Math Panorama - All Rights Reserved</p>
    </footer>

</body>
</html>

