<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aniket Dubey | Portfolio</title>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <!-- Font Awesome -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #f9fafb;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #1f2937, #3b82f6);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header img {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      margin-bottom: 20px;
      border: 4px solid white;
    }

    h1 {
      font-size: 2.5rem;
    }

    .container {
      max-width: 960px;
      margin: auto;
      padding: 40px 20px;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #1f2937;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li {
      margin-bottom: 10px;
    }

    a {
      color: #3b82f6;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .contact a {
      display: block;
      margin: 5px 0;
      font-size: 1.1rem;
    }

    .projects img {
      width: 100%;
      max-width: 500px;
      border-radius: 12px;
      margin-top: 10px;
    }

    footer {
      background: #1f2937;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    .icon {
      color: #3b82f6;
      margin-right: 8px;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }

      .projects img {
        width: 100%;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="https://avatars.githubusercontent.com/u/124523880?v=4" alt="Aniket Dubey">
    <h1>Aniket Dubey</h1>
    <p>🚀 Passionate Developer | Open Source Enthusiast | Tech Explorer</p>
  </header>

  <section class="container about">
    <h2>🌟 About Me</h2>
    <p>Hey there! I'm Aniket, a passionate software developer with expertise in:</p>
    <ul>
      <li><i class="fas fa-code icon"></i><strong>Web Development:</strong> ASP.NET, JavaScript, React, Node.js</li>
      <li><i class="fas fa-mobile-alt icon"></i><strong>Mobile Development:</strong> Android (Java)</li>
      <li><i class="fas fa-server icon"></i><strong>Backend:</strong> .NET Core, Express.js</li>
      <li><i class="fas fa-database icon"></i><strong>Databases:</strong> SQL Server, MongoDB</li>
      <li><i class="fab fa-git-alt icon"></i><strong>Version Control:</strong> Git, GitHub</li>
    </ul>
    <p>💡 I love solving real-world problems with technology and contributing to open-source projects.</p>
  </section>

  <section class="container projects">
    <h2>🚀 My Projects</h2>
    <ul>
      <li>🔹 <strong>OIBSIP</strong> - Android development tasks for Oasis Internship</li>
      <img src="https://via.placeholder.com/500x250?text=OIBSIP+Project" alt="OIBSIP Project">
      
      <li>🔹 <strong>Plantree E-Commerce App</strong> - Java-based Android App</li>
      <img src="https://via.placeholder.com/500x250?text=Plantree+E-Commerce+App" alt="Plantree App">

      <li>🔹 <strong>MERN Register-Login</strong> - A simple login system using MERN stack</li>
      <img src="https://via.placeholder.com/500x250?text=MERN+Login+System" alt="MERN Login">

      <li>🔹 <strong>ASP.NET Assignments</strong> - ASP.NET applications</li>
      <img src="https://via.placeholder.com/500x250?text=ASP.NET+Assignments" alt="ASP.NET Assignments">
    </ul>
  </section>

  <section class="container contact">
    <h2>📫 Get in Touch</h2>
    <p>💬 Feel free to reach out for collaborations or just a chat about tech!</p>
    <a href="mailto:aniketdubey638@gmail.com"><i class="fas fa-envelope icon"></i>Email: aniketdubey638@gmail.com</a>
    <a href="https://linkedin.com/in/aniket638" target="_blank"><i class="fab fa-linkedin icon"></i>LinkedIn: linkedin.com/in/aniket638</a>
    <a href="https://github.com/aniket638" target="_blank"><i class="fab fa-github icon"></i>GitHub: github.com/aniket638</a>
  </section>

  <footer>
    <p>📍 Surat, India | © 2025 Aniket Dubey</p>
  </footer>

</body>
</html>
