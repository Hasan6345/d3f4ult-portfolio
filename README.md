<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>D3f4ult - Portfolio</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: 'Poppins', sans-serif;
      color: #ffffff;
      background: url('https://images.unsplash.com/photo-1549924231-f129b911e442?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80') no-repeat center center fixed;
      background-size: cover;
    }
    header {
      background: rgba(0,0,0,0.7);
      padding: 30px 20px;
      text-align: center;
      animation: fadeIn 2s ease;
    }
    header h1 {
      margin: 0;
      font-size: 3em;
      color: #00FFFF;
    }
    nav {
      margin-top: 15px;
    }
    nav a {
      color: #00FFFF;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      font-size: 1.2em;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ff00ff;
    }
    section {
      background: rgba(0,0,0,0.6);
      padding: 50px 20px;
      margin: 40px auto;
      max-width: 1000px;
      border-radius: 12px;
      animation: fadeIn 2s ease;
    }
    h2 {
      text-align: center;
      color: #00FFFF;
      margin-bottom: 30px;
      font-size: 2.5em;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .project-card {
      background: rgba(255,255,255,0.1);
      border: 1px solid rgba(255,255,255,0.2);
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .project-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 20px rgba(0,255,255,0.4);
    }
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(0,0,0,0.7);
      font-size: 14px;
      margin-top: 40px;
    }
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
  </style>
</head>
<body>

<header>
  <h1>D3f4ult</h1>
  <nav>
    <a href="#projects">Projects</a>
  </nav>
</header>

<section id="projects">
  <h2>My Projects</h2>
  <div class="projects">
    <div class="project-card">
      <h3>Project One</h3>
      <p>Short description of your first project.</p>
    </div>
    <div class="project-card">
      <h3>Project Two</h3>
      <p>Short description of your second project.</p>
    </div>
    <div class="project-card">
      <h3>Project Three</h3>
      <p>Short description of your third project.</p>
    </div>
  </div>
</section>

<footer>
  &copy; 2025 D3f4ult. All rights reserved.
</footer>

</body>
</html>
