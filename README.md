<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hussein Mohamed Portfolio</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins:400,600&display=swap">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f9;
      color: #333;
    }

    p, h1, h2 {
      margin: 0;
      padding: 0;
    }

    hr {
      border: 1px solid #ddd;
      width: 80%;
      margin: 20px auto;
    }

    .container {
      text-align: center;
      padding: 50px;
      max-width: 800px;
      margin: auto;
    }

    .intro {
      font-size: 1.5em;
      font-weight: bold;
      transition: transform 0.4s ease-in-out, color 0.4s ease-in-out;
    }

    .intro:hover {
      transform: scale(1.05);
      color: #0077B5;
    }

    h2 {
      font-size: 1.2em;
      margin-bottom: 10px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      margin-bottom: 10px;
    }

    .collaboration, .fun-fact {
      transition: background-color 0.4s ease, transform 0.3s ease;
    }

    .collaboration:hover, .fun-fact:hover {
      background-color: #e0f7fa;
      transform: translateY(-10px);
    }

    .contact a {
      display: inline-block;
      padding: 10px 20px;
      background-color: #0077B5;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    .contact a:hover {
      background-color: #005582;
    }

    .contact img {
      vertical-align: middle;
    }
  </style>
</head>
<body>

  <div class="container">
    <p class="intro">
      I'm Hussein Mohamed, a passionate learner and developer currently diving deep into the world of Web Development. I'm a student in the Computer Department at Cairo University, where I enjoy exploring new technologies, building projects, and collaborating with others to create innovative solutions.
    </p>

    <hr>

    <h2>🌱 What I’m Currently Learning</h2>
    <ul>
      <li><b>Node.js</b></li>
      <li><b>Express.js</b></li>
      <li><b>React.js</b></li>
    </ul>

    <hr>

    <div class="collaboration">
      <h2>👯 Collaboration</h2>
      <p>I'm looking to collaborate on open-source projects and web applications. If you have an interesting project, let’s connect!</p>
    </div>

    <hr>

    <div class="contact">
      <h2>📫 How to Reach Me</h2>
      <a href="https://www.linkedin.com/in/hussein-mohamed-b10b89283/" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn">
      </a>
    </div>

    <hr>

    <div class="fun-fact">
      <h2>⚡ Fun Fact</h2>
      <p>I’m always up for a challenge, whether it’s solving a coding problem or learning a new skill. Outside of tech, I love football.</p>
    </div>
  </div>

</body>
</html>
