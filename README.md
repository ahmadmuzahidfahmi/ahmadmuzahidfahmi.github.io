<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital Portfolio - Ahmad Muzahid Fahmi</title>
  <style>
    /* General Styles */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      color: #333;
      background: #f9f9f9;
    }
    header {
      background: #0d253f;
      color: #fff;
      padding: 2rem 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.2rem;
    }
    header p {
      margin: 0.5rem 0;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 1.5rem;
      color: #0d253f;
    }
    .projects, .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background: #fff;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
    }
    .skills-list {
      list-style: none;
      padding: 0;
    }
    .skills-list li {
      background: #e6f0ff;
      margin: 0.3rem 0;
      padding: 0.5rem;
      border-radius: 5px;
    }
    footer {
      background: #0d253f;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    footer a {
      color: #ffda79;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Ahmad Muzahid Fahmi</h1>
    <p>E-commerce & Technology Management Student</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- About Me -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I am an E-commerce and Technology Management student at YPC International College with 
      a strong interest in digital transformation and business development. I enjoy exploring how 
      technology drives innovation, improves efficiency, and creates value for businesses. My goal 
      is to apply my knowledge and skills to contribute to organizations while continuously learning 
      and gaining new experiences.
    </p>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Website Development</h3>
        <p>
          Developed a dynamic website using HTML, CSS, Java, and PHP scripting. 
          The project showcased smartphone product information and was completed 
          independently in under two months.
        </p>
      </div>
      <div class="card">
        <h3>Community Project</h3>
        <p>
          Led a team of 13 students in organizing a community project with both local 
          and international students. This project enhanced my leadership, problem-solving, 
          and teamwork skills.
        </p>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card">
        <h3>Hard Skills</h3>
        <ul class="skills-list">
          <li>Microsoft Word, Excel, PowerPoint</li>
          <li>C++, HTML, PHP, Java</li>
          <li>Web Development</li>
          <li>Project Management</li>
          <li>Research Skills</li>
        </ul>
      </div>
      <div class="card">
        <h3>Soft Skills</h3>
        <ul class="skills-list">
          <li>Team Collaboration</li>
          <li>Independent Work</li>
          <li>Time Management</li>
          <li>Problem-Solving</li>
          <li>Decision-Making</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:ahmad.muzahidfahmi@ypccollege.edu.my">ahmad.muzahidfahmi@ypccollege.edu.my</a></p>
    <p>Phone: +60 017-644 0667</p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/ahmad-muzahid-fahmi" target="_blank">linkedin.com/in/ahmad-muzahid-fahmi</a></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Ahmad Muzahid Fahmi. Built with HTML & CSS.</p>
  </footer>
</body>
</html>
