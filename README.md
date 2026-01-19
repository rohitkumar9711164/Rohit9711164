# Rohit9711164<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rohit</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Smooth scroll for navbar links */
    html { scroll-behavior: smooth; }
  </style>
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Navbar -->
  <nav class="bg-blue-600 text-white fixed w-full z-50 shadow-lg">
    <div class="container mx-auto flex justify-between items-center p-4">
      <div class="text-2xl font-bold">Rohit</div>
      <ul class="flex space-x-6">
        <li><a href="#home" class="hover:underline">Home</a></li>
        <li><a href="#about" class="hover:underline">About</a></li>
        <li><a href="#portfolio" class="hover:underline">Portfolio</a></li>
        <li><a href="#contact" class="hover:underline">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="flex flex-col justify-center items-center h-screen bg-gradient-to-r from-blue-200 to-blue-400 text-center px-4 animate-fadeIn">
    <h1 class="text-5xl md:text-6xl font-bold mb-4 animate-bounce">Hi, I'm Rohit</h1>
    <p class="text-lg md:text-xl max-w-2xl">Welcome to my personal website. Explore my projects, skills, and get in touch!</p>
    <a href="#contact" class="mt-6 px-6 py-3 bg-blue-600 text-white rounded-lg shadow-lg hover:bg-blue-700 transition">Contact Me</a>
  </section>

  <!-- About Section -->
  <section id="about" class="py-20 px-4 md:px-20 bg-white">
    <h2 class="text-4xl font-bold text-blue-600 text-center mb-8">About Me</h2>
    <p class="text-center max-w-3xl mx-auto text-lg md:text-xl leading-relaxed">I am Rohit, a passionate learner and explorer. I love coding, solving problems, and building cool projects. My goal is to continuously grow and create solutions that make a difference.</p>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="py-20 px-4 md:px-20 bg-gray-100">
    <h2 class="text-4xl font-bold text-blue-600 text-center mb-12">My Projects</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
      <!-- Project Card -->
      <div class="bg-white p-6 rounded-xl shadow-lg hover:scale-105 transform transition duration-300">
        <h3 class="text-xl font-bold text-blue-600 mb-2">Project 1</h3>
        <p class="text-gray-700">Short description of project 1. Technologies used: HTML, CSS, JS.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow-lg hover:scale-105 transform transition duration-300">
        <h3 class="text-xl font-bold text-blue-600 mb-2">Project 2</h3>
        <p class="text-gray-700">Short description of project 2. Technologies used: React, Tailwind.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow-lg hover:scale-105 transform transition duration-300">
        <h3 class="text-xl font-bold text-blue-600 mb-2">Project 3</h3>
        <p class="text-gray-700">Short description of project 3. Technologies used: Python, Flask.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20 px-4 md:px-20 bg-white text-center">
    <h2 class="text-4xl font-bold text-blue-600 mb-8">Contact Me</h2>
    <p class="text-lg mb-4">Email: <a href="mailto:rohitemail@example.com" class="text-blue-600 font-semibold hover:underline">rohitemail@example.com</a></p>
    <p class="text-lg">LinkedIn: <a href="https://www.linkedin.com/in/rohit/" target="_blank" class="text-blue-600 font-semibold hover:underline">linkedin.com/in/rohit</a></p>
  </section>

  <!-- Footer -->
  <footer class="bg-blue-600 text-white py-6 text-center">
    &copy; 2026 Rohit. All rights reserved.
  </footer>

  <!-- Optional Tailwind Animations -->
  <style>
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }
    .animate-fadeIn { animation: fadeIn 1.5s ease-in-out; }
  </style>

</body>
</html>
