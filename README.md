<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Forum</title>
    <!-- CSS Framework (e.g., Bootstrap for styling) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.1.3/css/bootstrap.min.css">
    <style>
        /* Custom styling */
        body {
            background-color: #f8f9fa;
            font-family: Arial, sans-serif;
        }
        .navbar-brand {
            font-weight: bold;
        }
        .forum-post {
            border-bottom: 1px solid #ddd;
            padding: 15px 0;
        }
        .footer {
            background-color: #343a40;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Tech Forum</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#topics">Topics</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#login">Login</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#signup">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header Section -->
    <header class="container text-center my-4">
        <h1>Welcome to Tech Forum</h1>
        <p>Your go-to place for all things tech!</p>
    </header>

    <!-- Forum Topics Section -->
    <div class="container">
        <h2>Latest Topics</h2>
        <div class="forum-post">
            <h3><a href="#">Getting Started with Python</a></h3>
            <p>Posted by <strong>User123</strong> on October 12, 2024</p>
            <p>Discuss the best practices, resources, and tools for learning Python programming.</p>
        </div>
        <div class="forum-post">
            <h3><a href="#">Understanding Web Development</a></h3>
            <p>Posted by <strong>User456</strong> on October 10, 2024</p>
            <p>Explore HTML, CSS, JavaScript, and frameworks that power modern websites.</p>
        </div>
        <div class="forum-post">
            <h3><a href="#">AI and Machine Learning Basics</a></h3>
            <p>Posted by <strong>User789</strong> on October 8, 2024</p>
            <p>Discuss machine learning algorithms, data science, and AI applications.</p>
        </div>
    </div>

    <!-- Footer Section -->
    <footer class="footer">
        <p>&copy; 2024 Tech Forum. All rights reserved.</p>
    </footer>

    <!-- JS Framework (e.g., Bootstrap and jQuery) -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.1.3/js/bootstrap.bundle.min.js"></script>
</body>
</html>
