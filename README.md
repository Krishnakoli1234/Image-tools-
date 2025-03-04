<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Your one-stop destination for free online tools. Compress images, convert PDFs, and more!">
    <meta name="keywords" content="image tools, PDF tools, online tools, compress images, convert PDF">
    <meta name="author" content="Your Name">
    <title>Online Tools - Free Image & PDF Tools</title>
    <style>
        /* CSS Variables for easy theming */
        :root {
            --primary-color: #007bff;
            --secondary-color: #6c757d;
            --background-color: #f8f9fa;
            --text-color: #333;
            --border-radius: 8px;
            --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        /* Reset and Basic Styling */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: var(--primary-color);
        }

        a:hover {
            text-decoration: underline;
        }

        /* Header and Navigation */
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: var(--box-shadow);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }

        nav a {
            color: white;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Main Content */
        main {
            padding: 20px;
            max-width: 1200px;
            margin: 20px auto;
        }

        .tool-categories {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .category-card {
            background: white;
            padding: 20px;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .category-card:hover {
            transform: translateY(-5px);
        }

        .category-card h2 {
            margin-top: 0;
            color: var(--primary-color);
        }

        .category-card p {
            color: var(--secondary-color);
        }

        .featured-tools {
            margin-top: 40px;
        }

        .featured-tools h2 {
            text-align: center;
            color: var(--primary-color);
        }

        .tool-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .tool-card {
            background: white;
            padding: 20px;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .tool-card:hover {
            transform: translateY(-5px);
        }

        .tool-card h3 {
            margin: 0;
            color: var(--primary-color);
        }

        .tool-card p {
            color: var(--secondary-color);
        }

        /* Footer */
        footer {
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            box-shadow: var(--box-shadow);
        }

        footer p {
            margin: 0;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }

            nav {
                flex-direction: column;
                gap: 10px;
            }

            .tool-categories, .tool-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Online Tools</h1>
        <nav>
            <a href="#image-tools">Image Tools</a>
            <a href="#pdf-tools">PDF Tools</a>
            <a href="#featured-tools">Featured Tools</a>
        </nav>
    </header>
    <main>
        <!-- Tool Categories -->
        <section class="tool-categories">
            <div class="category-card" id="image-tools">
                <h2>Image Tools</h2>
                <p>Compress, resize, and convert images easily.</p>
                <a href="#">Explore Image Tools</a>
            </div>
            <div class="category-card" id="pdf-tools">
                <h2>PDF Tools</h2>
                <p>Merge, split, and convert PDFs in seconds.</p>
                <a href="#">Explore PDF Tools</a>
            </div>
        </section>

        <!-- Featured Tools -->
        <section class="featured-tools">
            <h2>Featured Tools</h2>
            <div class="tool-grid">
                <div class="tool-card">
                    <h3>Image Compressor</h3>
                    <p>Reduce image size without losing quality.</p>
                    <a href="#">Use Tool</a>
                </div>
                <div class="tool-card">
                    <h3>PDF Merger</h3>
                    <p>Combine multiple PDFs into one.</p>
                    <a href="#">Use Tool</a>
                </div>
                <div class="tool-card">
                    <h3>Image Converter</h3>
                    <p>Convert images to different formats.</p>
                    <a href="#">Use Tool</a>
                </div>
                <div class="tool-card">
                    <h3>PDF Splitter</h3>
                    <p>Split PDFs into individual pages.</p>
                    <a href="#">Use Tool</a>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Online Tools. All rights reserved.</p>
    </footer>
</body>
</html>
