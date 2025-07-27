<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lucky Marange - Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e0f7ff; /* Light blue background */
            color: #333;
            display: flex;
        }

        .sidebar {
            width: 220px;
            background-color: #cceeff;
            padding: 20px;
            position: fixed;
            height: 100vh;
            overflow-y: auto;
            box-shadow: 2px 0 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .sidebar img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid #66ccff;
            margin-bottom: 15px;
        }

        .sidebar ul {
            list-style-type: none;
            padding: 0;
        }

        .sidebar li {
            margin: 15px 0;
        }

        .sidebar a {
            text-decoration: none;
            color: #007acc;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .sidebar a:hover {
            color: #ff6600;
        }

        .content {
            margin-left: 240px;
            padding: 30px;
            flex: 1;
        }

        h2 {
            color: #336699;
        }

        h3 {
            color: #009999;
        }

        ul {
            color: #333366;
        }

        p {
            color: #444;
        }

        .section {
            margin-bottom: 40px;
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

    <div class="content">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Hi there! I'm <strong style="color: #cc3399;">Lucky Marange</strong>, an aspiring IT Professional and dedicated educator with a passion for problem-solving and continuous learning. Currently pursuing a BSc in Information Technology at North-West University (expected completion 2026), I'm eager to apply my strong analytical skills and foundational knowledge in software engineering, cybersecurity, and web development to innovative projects. My background in STEM education has honed my ability to simplify complex concepts and communicate effectively, making me a valuable asset to any technical team.</p>
        </section>

        <section id="interests" class="section">
            <h2>Interests</h2>
            <ul>
                <li>Software Engineering</li>
                <li>Cybersecurity</li>
                <li>Mathematics & Physics</li>
                <li>Artificial Intelligence</li>
                <li>Data Science</li>
                <li>Web Development</li>
            </ul>
        </section>

        <section id="education" class="section">
            <h2>Education</h2>
            <div>
                <h3>BSc Information Technology (In Progress)</h3>
                <p><strong style="color: #0099cc;">North-West University</strong><br>January 2023 – Present (Final Year)</p>
                <ul>
                    <li>Specializing in Software Development and Cybersecurity.</li>
                    <li>Relevant coursework includes: Database Systems, OOP (Java, C++, C#), Web Development, Network Security, Info Systems.</li>
                    <li>Engaged in practical projects applying theoretical knowledge to real-world IT challenges.</li>
                </ul>
            </div>

            <div>
                <h3>BSc Degree in Mathematics and Physics</h3>
                <p><strong style="color: #0099cc;">University of South Africa (UNISA)</strong><br>January 2019 - December 2023</p>
                <ul>
                    <li>Advanced mathematical concepts and physical principles.</li>
                    <li>Strong analytical, problem-solving, and critical thinking skills.</li>
                    <li>Prepared for research, data analysis, and technical careers.</li>
                </ul>
            </div>

            <div>
                <h3>Bachelor of Science in Education (B.Sc.Ed)</h3>
                <p><strong style="color: #0099cc;">University of South Africa (UNISA)</strong><br>January 2014 – December 2017</p>
                <ul>
                    <li>Majored in Physical Sciences and Mathematics.</li>
                    <li>Curriculum design, assessment, student engagement.</li>
                    <li>Extensive experience in explaining complex topics clearly.</li>
                </ul>
            </div>

            <div>
                <h3>Charlton Vos College</h3>
                <p><strong style="color: #0099cc;">January 2008 – Present</strong></p>
                <ul>
                    <li>Consistent 100% pass rates in Physical Sciences and Mathematics for over 15 years.</li>
                    <li>Engaging lesson plans fostering critical thinking and problem-solving.</li>
                    <li>Individualized mentoring, enhancing academic performance.</li>
                    <li>Used tech tools to simplify learning and concepts.</li>
                    <li>Fostered a positive and inclusive learning environment.</li>
                </ul>
            </div>
        </section>

        <section id="skills" class="section">
            <h2>Skills</h2>
            <ul>
                <li><strong>Languages:</strong> Java, Python, C++, JavaScript</li>
                <li><strong>Frameworks:</strong> Spring, Django, React</li>
                <li><strong>Databases:</strong> MySQL, MongoDB</li>
                <li><strong>OS:</strong> Windows, Linux, macOS</li>
                <li><strong>Core Competencies:</strong> Software engineering, problem-solving, teamwork, communication</li>
            </ul>
        </section>

        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:marangelucky@gmail.com" style="color: #ff6600;">marangelucky@gmail.com</a></p>
            <p>LinkedIn: <a href="https://linkedin.com/in/luckymarange" style="color: #ff6600;">linkedin.com/in/luckymarange</a></p>
            <p>GitHub: <a href="https://github.com/luckymarange" style="color: #ff6600;">github.com/luckymarange</a></p>
        </section>
    </div>
</body>
</html>

