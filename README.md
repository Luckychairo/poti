<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lucky Marange - Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #e0f2ff; /* light blue background */
      color: #333;
      display: flex;
      min-height: 100vh;
    }
    .sidebar {
      width: 250px;
      background-color: #b3e5fc;
      padding: 20px;
      position: fixed;
      top: 0;
      bottom: 0;
      left: 0;
      overflow-y: auto;
      box-shadow: 2px 0 5px rgba(0, 0, 0, 0.1);
    }
    .sidebar img {
      width: 100px;
      height: 100px;
      object-fit: cover;
      border-radius: 50%;
      border: 2px solid #0288d1;
      margin-bottom: 15px;
    }
    .sidebar ul {
      list-style: none;
      padding: 0;
    }
    .sidebar ul li {
      margin: 10px 0;
    }
    .sidebar ul li a {
      text-decoration: none;
      color: #01579b;
      font-weight: bold;
      transition: color 0.3s;
    }
    .sidebar ul li a:hover {
      color: #ff4081;
    }
    .main-content {
      margin-left: 270px;
      padding: 30px;
      flex: 1;
    }
    h2 {
      color: #0277bd;
      border-bottom: 2px solid #81d4fa;
      padding-bottom: 5px;
    }
    h3 {
      color: #f06292;
    }
    ul li {
      color: #444;
    }
    p {
      color: #37474f;
    }
    .card {
      background-color: #ffffff;
      border: 2px solid #81d4fa;
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
  </style>
</head>
<body>
  <div class="sidebar">
    <img src="img.jpg" alt="Lucky Marange">
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#interests">Interests</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </div>
  <div class="main-content">
    <h2 id="about">About Me</h2>
    <p>Hi there! I'm <span style="color:#0288d1; font-weight:bold;">Lucky Marange</span>, an aspiring IT Professional and educator passionate about solving problems and learning continuously. I'm studying BSc IT at North-West University (expected 2026). I bring strong analytical skills, experience in STEM education, and a drive for innovation.</p>

    <h2 id="interests">Interests</h2>
    <ul>
      <li>Software Engineering</li>
      <li>Cybersecurity</li>
      <li>Mathematics & Physics</li>
      <li>Artificial Intelligence</li>
      <li>Data Science</li>
      <li>Web Development</li>
    </ul>

    <h2 id="education">Education</h2>
    <div class="card">
      <h3>BSc Information Technology (In Progress)</h3>
      <p><strong>North-West University</strong></p>
      <p>January 2023 – Present</p>
      <ul>
        <li>Specializing in Software Development and Cybersecurity.</li>
        <li>Relevant courses: DBMS, Java, Web Dev, Networks, Info Systems.</li>
        <li>Practical project experience applying theory to real-world IT.</li>
      </ul>
    </div>

    <div class="card">
      <h3>BSc Mathematics and Physics</h3>
      <p><strong>University of South Africa (UNISA)</strong></p>
      <p>January 2019 – December 2023</p>
      <ul>
        <li>Advanced mathematics and physical science studies.</li>
        <li>Built problem-solving, research, and analytical skills.</li>
      </ul>
    </div>

    <div class="card">
      <h3>Bachelor of Education (B.Sc.Ed)</h3>
      <p><strong>University of South Africa (UNISA)</strong></p>
      <p>January 2014 – December 2017</p>
      <ul>
        <li>Majored in Physical Sciences and Mathematics.</li>
        <li>Experience in curriculum design and student engagement.</li>
      </ul>
    </div>

    <div class="card">
      <h3>Charlton Vos College</h3>
      <p>January 2008 – Present</p>
      <ul>
        <li>Achieved 100% pass rates in Physics and Math for 15+ years.</li>
        <li>Created engaging lesson plans, improved academic performance.</li>
        <li>Led software development simulation projects in Java and SQL.</li>
        <li>Applied cybersecurity best practices in IT training.</li>
      </ul>
    </div>

    <h2 id="skills">Skills</h2>
    <ul>
      <li>Languages: Java, Python, C++, JavaScript</li>
      <li>Frameworks: Spring, Django, React</li>
      <li>Databases: MySQL, MongoDB</li>
      <li>OS: Windows, Linux, macOS</li>
      <li>Soft Skills: Problem-solving, communication, teamwork</li>
    </ul>

    <h2 id="contact">Contact</h2>
    <p>Email: <a href="mailto:marangelucky@gmail.com">marangelucky@gmail.com</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/luckymarange">linkedin.com/in/luckymarange</a></p>
    <p>GitHub: <a href="https://github.com/luckymarange">github.com/luckymarange</a></p>
  </div>
</body>
</html>
