<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CSS Basics</title>
  <!-- Link to external CSS -->
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1 class="main-title">Learning CSS Basics</h1>
  </header>

  <!-- Navigation -->
  <nav id="main-nav">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Lessons</a></li>
      <li><a href="#">Practice</a></li>
    </ul>
  </nav>

  <!-- Main Content -->
  <main>
    <section>
      <h2>Why CSS?</h2>
      <p>CSS helps you style your webpage and improve the user experience with colors, spacing, and fonts.</p>
      <img src="https://via.placeholder.com/300" alt="Learning CSS" class="styled-image" />
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <p>Created with ❤️ | Contact: csslearner@example.com</p>
  </footer>

</body>
</html>


STYLE.CSS
/* General body styles */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f0f4f8;
  margin: 0;
  padding: 0;
  color: #333;
}

/* Class selector */
.main-title {
  color: #1e90ff;
  text-align: center;
  padding: 20px;
}

/* ID selector */
#main-nav {
  background-color: #333;
  padding: 10px;
  text-align: center;
}

#main-nav ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

#main-nav li {
  display: inline;
  margin: 0 15px;
}

#main-nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

#main-nav a:hover {
  text-decoration: underline;
}

/* Image styling with class selector */
.styled-image {
  display: block;
  margin: 20px auto;
  border: 4px solid #1e90ff;
  padding: 10px;
  border-radius: 8px;
  max-width: 100%;
}

/* Footer styles */
footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}
