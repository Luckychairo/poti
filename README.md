<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lucky Marange Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .gradient-text {
      background: linear-gradient(to right, #4f46e5, #9333ea);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .card-hover:hover {
      transform: scale(1.02);
      transition: transform 0.3s;
    }
    .animate-fade-in {
      animation: fadeIn 1s ease-in;
    }
    .animate-slide-in-left {
      animation: slideInLeft 1s ease-out;
    }
    .animate-slide-in-right {
      animation: slideInRight 1s ease-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes slideInLeft {
      from { transform: translateX(-100px); opacity: 0; }
      to { transform: translateX(0); opacity: 1; }
    }
    @keyframes slideInRight {
      from { transform: translateX(100px); opacity: 0; }
      to { transform: translateX(0); opacity: 1; }
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans">
  <div class="flex min-h-screen">
    <!-- Sidebar Navigation -->
    <nav class="w-64 bg-white p-6 shadow-lg sticky top-0 h-screen">
      <h1 class="text-2xl font-bold text-indigo-600 mb-6">Lucky Marange</h1>
      <ul class="space-y-4 text-indigo-800 font-medium">
        <li><a href="#about" class="hover:text-purple-600">About</a></li>
        <li><a href="#interests" class="hover:text-purple-600">Interests</a></li>
        <li><a href="#education" class="hover:text-purple-600">Education</a></li>
        <li><a href="#skills" class="hover:text-purple-600">Skills</a></li>
        <li><a href="#contact" class="hover:text-purple-600">Contact</a></li>
      </ul>
    </nav>

    <!-- Main Content -->
    <main class="flex-1 p-8 space-y-12">

      <!-- About Section -->
      <section id="about" class="animate-fade-in">
        <h2 class="text-3xl font-bold gradient-text mb-4">About Me</h2>
        <p class="text-lg text-slate-700 max-w-3xl">I am a passionate educator and future software developer with a strong background in STEM and Information Technology. With over 15 years of teaching experience and ongoing studies in IT, I bring a blend of instructional expertise and technical acumen.</p>
      </section>

      <!-- Interests Section -->
      <section id="interests" class="animate-fade-in">
        <h2 class="text-3xl font-bold gradient-text mb-4">Interests</h2>
        <p class="text-lg text-slate-700 max-w-3xl">My interests include software development, cybersecurity, educational technology, artificial intelligence, and mentoring learners to excel in technical subjects.</p>
      </section>

      <!-- Education Section -->
      <section id="education" class="space-y-10">
        <h2 class="text-3xl font-bold gradient-text mb-4">Education</h2>

        <div class="bg-white p-6 rounded-lg shadow-lg border-2 border-blue-200 card-hover animate-slide-in-left">
          <h3 class="text-xl font-semibold gradient-text mb-2">BSc Information Technology (In Progress)</h3>
          <p class="text-slate-700 font-medium mb-1">North-West University</p>
          <p class="text-slate-500 text-sm mb-4">January 2023 – Present (Final Year)</p>
          <ul class="list-disc list-inside space-y-2 text-slate-700">
            <li>Specializing in Software Development and Cybersecurity.</li>
            <li>Relevant coursework includes: Database Systems, OOP, Web Dev, Network Security.</li>
            <li>Engaged in practical projects applying theory to real-world IT challenges.</li>
          </ul>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-lg border-2 border-green-200 card-hover animate-slide-in-right">
          <h3 class="text-xl font-semibold gradient-text mb-2">BSc Mathematics and Physics</h3>
          <p class="text-slate-700 font-medium mb-1">University of South Africa (UNISA)</p>
          <p class="text-slate-500 text-sm mb-4">January 2019 – December 2023</p>
          <ul class="list-disc list-inside space-y-2 text-slate-700">
            <li>Studied advanced mathematical concepts and physical principles.</li>
            <li>Built strong analytical and critical thinking skills.</li>
          </ul>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-lg border-2 border-purple-200 card-hover animate-slide-in-right">
          <h3 class="text-xl font-semibold gradient-text mb-2">Bachelor of Science in Education (B.Sc.Ed)</h3>
          <p class="text-slate-700 font-medium mb-1">University of South Africa (UNISA)</p>
          <p class="text-slate-500 text-sm mb-4">January 2014 – December 2017</p>
          <ul class="list-disc list-inside space-y-2 text-slate-700">
            <li>Majored in Physical Sciences and Mathematics.</li>
            <li>Gained strong curriculum design and student engagement skills.</li>
          </ul>
        </div>
      </section>

      <!-- Experience Section -->
      <section id="experience" class="space-y-10">
        <h2 class="text-3xl font-bold gradient-text mb-4">Experience</h2>

        <div class="bg-white p-6 rounded-lg shadow-lg border-2 border-indigo-200 card-hover animate-fade-in">
          <h3 class="text-xl font-semibold gradient-text mb-2">Teaching Experience: Charlton Vos College</h3>
          <p class="text-slate-700 font-medium mb-1">Charlton Vos College</p>
          <p class="text-slate-500 text-sm mb-4">January 2008 – Present</p>
          <ul class="list-disc list-inside space-y-2 text-slate-700">
            <li>Consistent 100% pass rate in Physical Sciences and Mathematics.</li>
            <li>Developed engaging lesson plans and critical thinking activities.</li>
            <li>Mentored students and improved academic performance.</li>
            <li>Utilized EdTech for effective content delivery.</li>
            <li>Created a positive and inclusive classroom environment.</li>
          </ul>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-lg border-2 border-yellow-200 card-hover animate-fade-in">
          <h3 class="text-xl font-semibold gradient-text mb-2">Software Development Internship (Simulated)</h3>
          <ul class="list-disc list-inside space-y-2 text-slate-700">
            <li>Participated in software development lifecycle: from requirements to deployment.</li>
            <li>Worked with Java, SQL, Git, Agile methodologies.</li>
            <li>Applied cybersecurity best practices in coding.</li>
          </ul>
        </div>
      </section>

      <!-- Skills Section -->
      <section id="skills" class="animate-fade-in">
        <h2 class="text-3xl font-bold gradient-text mb-4">Skills</h2>
        <ul class="list-disc list-inside space-y-2 text-slate-700">
          <li>Programming: Java, Python, C++, JavaScript</li>
          <li>Web Development: HTML, CSS, Tailwind, React</li>
          <li>Database Systems: SQL, MySQL</li>
          <li>Cybersecurity Principles</li>
          <li>Curriculum Design & Instruction</li>
        </ul>
      </section>

      <!-- Contact Section -->
      <section id="contact" class="animate-fade-in">
        <h2 class="text-3xl font-bold gradient-text mb-4">Contact</h2>
        <p>Email: <a href="mailto:marangelucky@gmail.com" class="text-indigo-600 hover:underline">marangelucky@gmail.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/luckymarange" class="text-indigo-600 hover:underline">linkedin.com/in/luckymarange</a></p>
      </section>

      <footer class="mt-16 text-center text-sm text-slate-500">&copy; 2025 Lucky Marange. All rights reserved.</footer>

    </main>
  </div>
</body>
</html>

