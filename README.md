# My-Html-Project

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Interview Preview Portal</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Interview Previews</h1>
    <input type="text" id="searchInput" placeholder="Search by name or role..." />
  </header>

  <main id="previewList">
    <div class="card">
      <img src="assets/profile.jpg" alt="Profile" />
      <div class="info">
        <h2>Rahul Mehta</h2>
        <p>Role: Front-End Developer</p>
        <button onclick="showDetails('Rahul')">Preview</button>
      </div>
    </div>

    <div class="card">
      <img src="assets/profile.jpg" alt="Profile" />
      <div class="info">
        <h2>Anjali Sharma</h2>
        <p>Role: Data Analyst</p>
        <button onclick="showDetails('Anjali')">Preview</button>
      </div>
    </div>
  </main>

  <footer>
    <p>&copy; 2025 Interview Preview Portal</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
