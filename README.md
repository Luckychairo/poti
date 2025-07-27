<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lucky Marange - Portfolio</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css">
  <style>
    html {
      scroll-behavior: smooth;
    }
    h2[id] {
      scroll-margin-top: 100px;
    }
  </style>
</head>
<body class="bg-gray-100 font-sans">
  <div class="flex">
    <!-- Sidebar -->
    <div class="w-1/4 min-h-screen bg-white p-4 shadow-md flex flex-col items-center">
      <img src="img.jpg" alt="Lucky Marange" class="w-24 h-24 rounded-full object-cover border mb-4">
      <nav class="space-y-2 text-left w-full">
        <a href="#about" class="block text-blue-600 hover:underline">About</a>
        <a href="#interests" class="block text-blue-600 hover:underline">Interests</a>
        <a href="#education" class="block text-blue-600 hover:underline">Education</a>
        <a href="#skills" class="block text-blue-600 hover:underline">Skills</a>
        <a href="#contact" class="block text-blue-600 hover:underline">Contact</a>
      </nav>
    </div>

    <!-- Main Content -->
    <div class="w-3/4 p-8 space-y-10">
      <section id="about">
        <h2 class="text-2xl font-bold mb-2">About Me</h2>
        <p class="text-gray-700">Hi there! I'm Lucky Marange, an aspiring IT Professional and dedicated educator with a passion for problem-solving and continuous learning. Currently pursuing a BSc in Information Technology at North-West University (expected completion 2026), I'm eager to apply my strong analytical skills and foundational knowledge in software engineering, cybersecurity, and web development to innovative projects. My background in STEM education has honed my ability to simplify complex concepts and communicate effectively, making me a valuable asset to any technical team.</p>
      </section>

      <section id="interests">
        <h2 class="text-2xl font-bold mb-2">Interests</h2>
        <ul class="list-disc list-inside text-gray-700">
          <li>Software Engineering</li>
          <li>Cybersecurity</li>
          <li>Mathematics & Physics</li>
          <li>Artificial Intelligence</li>
          <li>Data Science</li>
          <li>Web Development</li>
        </ul>
      </section>

      <section id="education">
        <h2 class="text-2xl font-bold mb-2">Education</h2>

        <div class="bg-white p-6 rounded-lg shadow-lg border border-blue-200 mb-4">
          <h3 class="text-xl font-semibold text-blue-700">BSc Information Technology (In Progress)</h3>
          <p class="text-gray-600">North-West University | January 2023 – Present</p>
          <ul class="list-disc list-inside text-gray-700 mt-2">
            <li>Specializing in Software Development and Cybersecurity</li>
            <li>Relevant coursework: Database Systems, OOP, Java, C++, C#, Web Dev, Network Security</li>
            <li>Real-world practical projects</li>
          </ul>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-lg border border-green-200 mb-4">
          <h3 class="text-xl font-semibold text-green-700">BSc Mathematics and Physics</h3>
          <p class="text-gray-600">UNISA | January 2019 – December 2023</p>
          <ul class="list-disc list-inside text-gray-700 mt-2">
            <li>Advanced mathematical concepts and physical principles</li>
            <li>Critical thinking and scientific problem-solving</li>
          </ul>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-lg border border-purple-200 mb-4">
          <h3 class="text-xl font-semibold text-purple-700">Bachelor of Science in Education (B.Ed)</h3>
          <p class="text-gray-600">UNISA | January 2014 – December 2017</p>
          <ul class="list-disc list-inside text-gray-700 mt-2">
            <li>Majored in Physical Sciences and Mathematics</li>
            <li>Curriculum design, assessment, and pedagogical strategies</li>
          </ul>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-lg border border-yellow-200">
          <h3 class="text-xl font-semibold text-yellow-700">Charlton Vos College</h3>
          <p class="text-gray-600">January 2008 – Present</p>
          <ul class="list-disc list-inside text-gray-700 mt-2">
            <li>100% pass rates in Physical Sciences and Mathematics for 15+ years</li>
            <li>Mentorship, individualized support, and dynamic classroom management</li>
            <li>Applied educational technologies to enhance learning</li>
            <li>Participated in simulated software development lifecycle</li>
            <li>Contributed to Java/SQL web app projects, Git collaboration, agile workflow</li>
          </ul>
        </div>
      </section>

      <section id="skills">
        <h2 class="text-2xl font-bold mb-2">Skills</h2>
        <ul class="list-disc list-inside text-gray-700">
          <li>Languages: Java, Python, C++, JavaScript</li>
          <li>Frameworks: Spring, Django, React</li>
          <li>Databases: MySQL, MongoDB</li>
          <li>Operating Systems: Windows, Linux, macOS</li>
          <li>Core Skills: Problem-solving, communication, collaboration</li>
        </ul>
      </section>

      <section id="contact">
        <h2 class="text-2xl font-bold mb-2">Contact</h2>
        <p class="text-gray-700">Email: <a href="mailto:marangelucky@gmail.com" class="text-blue-600 hover:underline">marangelucky@gmail.com</a></p>
        <p class="text-gray-700">LinkedIn: <a href="https://linkedin.com/in/luckymarange" class="text-blue-600 hover:underline">linkedin.com/in/luckymarange</a></p>
        <p class="text-gray-700">GitHub: <a href="https://github.com/luckymarange" class="text-blue-600 hover:underline">github.com/luckymarange</a></p>
      </section>
    </div>
  </div>
</body>
</html>
