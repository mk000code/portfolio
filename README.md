<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Your Name - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="port.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="container">
      <h1>MD KAIF</h1>
      <p>Web Developer | Designer | Lifelong Learner</p>
    </div>
  </header>

  <!-- About Section -->
  <section class="about" id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>Hello! I'm MD KAIF, a passionate web developer with a love for design and creating interactive web experiences. I specialize in front-end development and have a background in computer science.</p>

      <h3>Educational Background</h3>
      <p>Bachelor's in Computer Science, KIET Institute Ghaziabad</p>

      <h3>Interests</h3>
      <ul>
        <li>Web Development</li>
        <li>UI/UX Design</li>
        <li>Technology Innovations</li>
      </ul>

      <h3>Expertise</h3>
      <p>I have hands-on experience in:</p>
      <ul>
        <li>HTML, CSS, JavaScript</li>
        <li>React, Node.js</li>
        <li>Responsive Web Design</li>
      </ul>
    </div>
  </section>

  <!-- Skills Section -->
  <section class="skills" id="skills">
    <div class="container">
      <h2>Skills</h2>
      <div class="skill-card">
        <h3>HTML & CSS</h3>
        <p>Expert in HTML5 and CSS3 for creating responsive layouts.</p>
      </div>
      <div class="skill-card">
        <h3>JavaScript</h3>
        <p>Advanced knowledge of JavaScript for interactivity and dynamic content.</p>
      </div>
      <div class="skill-card">
        <h3>React.js</h3>
        <p>Experienced in building interactive UIs using React.</p>
      </div>
    </div>
  </section>

  <!-- Footer Section -->
  <footer>
    <div class="container">
      <p>Contact: mdkaif4530@gmail.com | <a href="https://www.linkedin.com/in/md-kaif-66950427a/" target="_blank">LinkedIn</a></p>
    </div>
  </footer>
</body>
</html>



* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: 'Poppins', sans-serif;
    background-color: #f4f4f9;
    color: #333;
  }
  
  .container {
    width: 80%;
    margin: 0 auto;
  }
  
  header {
    background: linear-gradient(to right, #6a11cb, #2575fc);
    color: white;
    padding: 60px 0;
    text-align: center;
  }
  
  header h1 {
    font-size: 3em;
    font-weight: 600;
  }
  
  header p {
    font-size: 1.2em;
    font-weight: 400;
  }
  
  section {
    padding: 60px 0;
  }
  
  h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
  }
  
  h3 {
    font-size: 1.8em;
    margin-bottom: 10px;
    color: #2575fc;
  }
  
  ul {
    list-style: none;
  }
  
  ul li {
    font-size: 1.1em;
    margin: 5px 0;
  }
  
  .about p {
    font-size: 1.2em;
    margin-bottom: 20px;
  }
  
  .skills .skill-card {
    background-color: #ffffff;
    padding: 20px;
    margin: 20px 0;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }
  
  .skills .skill-card h3 {
    font-size: 1.6em;
    color: #2575fc;
  }
  
  footer {
    background-color: #2575fc;
    color: white;
    padding: 20px 0;
    text-align: center;
  }
  
  footer a {
    color: white;
    text-decoration: none;
  }
  
  footer a:hover {
    text-decoration: underline;
  }
  



