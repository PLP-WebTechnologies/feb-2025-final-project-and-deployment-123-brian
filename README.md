# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

Good luck and happy coding! 🚀💻



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Blog</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <ul class="nav">
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
    <h1>Welcome to My Blog</h1>
  </header>

  <main>
    <section class="blog-posts">
      <article>
        <h2>First Post</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
        <button class="read-more">Read More</button>
      </article>
      <article>
        <h2>Second Post</h2>
        <p>Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
        <button class="read-more">Read More</button>
      </article>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Blog. All rights reserved.</p>
  </footer>
  
  <script src="script.js"></script>
</body>
</html>



body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background-color: #f8f9fa;
  color: #333;
}

header {
  background: #007bff;
  color: #fff;
  padding: 10px 0;
  text-align: center;
}

.nav {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
}

.nav li {
  margin: 0 10px;
}

.nav a {
  text-decoration: none;
  color: #fff;
}

.blog-posts {
  padding: 20px;
}

article {
  margin-bottom: 20px;
  padding: 15px;
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

button {
  background: #007bff;
  color: #fff;
  border: none;
  padding: 10px;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background: #0056b3;
}




// Add interactivity to "Read More" buttons
const buttons = document.querySelectorAll(".read-more");

buttons.forEach((button) => {
  button.addEventListener("click", () => {
    alert("This feature is coming soon!");
  });
});





myblog.github.io
