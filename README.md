<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Creation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Create Your Blog</h1>
    </header>
    <nav>
        <!-- Navigation links can be added here -->
    </nav>
    <main>
        <section id="blog-editor">
            <h2>Blog Editor</h2>
            <form action="/create-blog" method="POST">
                <label for="title">Title:</label>
                <input type="text" id="title" name="title" placeholder="Enter your blog title" required>

                <label for="content">Content:</label>
                <textarea id="content" name="content" placeholder="Write your blog content" required></textarea>

                <label for="image">Image:</label>
                <input type="file" id="image" name="image" accept="image/*">
                <img id="image-preview" src="#" alt="Image Preview">

                <label for="video">Video (YouTube URL):</label>
                <input type="url" id="video" name="video" placeholder="Paste video URL">

                <!-- Other elements like tags, categories, etc., can be added here -->

                <button type="submit">Publish</button>
            </form>
        </section>
        <section id="preview">
            <h2>Blog Preview</h2>
            <article id="blog-preview">
                <!-- Preview of the blog content will be displayed here -->
            </article>
        </section>
    </main>
    <footer>
        <!-- Footer content can be added here -->
    </footer>
    <script src="script.js"></script>
</body>
</html>
