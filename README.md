<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - AI Automation & Web Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Arial', sans-serif;
        }
        .hero-bg {
            background: linear-gradient(135deg, #1e3a8a, #3b82f6);
        }
        .project-card {
            transition: transform 0.3s ease-in-out;
        }
        .project-card:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body class="bg-gray-100">
    <!-- Hero Section -->
    <section class="hero-bg text-white py-20 text-center">
        <div class="container mx-auto px-4">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">Your Name</h1>
            <p class="text-xl md:text-2xl mb-6">AI Automation Expert | Python & Django Developer</p>
            <a href="#contact" class="bg-white text-blue-600 px-6 py-3 rounded-full font-semibold hover:bg-blue-100">Get in Touch</a>
        </div>
    </section>

    <!-- About Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">About Me</h2>
            <p class="text-lg text-gray-700 max-w-3xl mx-auto">
                I'm a passionate AI Automation Expert and Full-Stack Web Developer with expertise in building efficient workflows using <strong>Make.com</strong>, <strong>Microsoft Power Automate</strong>, and <strong>n8n</strong>. I also specialize in creating secure, scalable web applications with <strong>Python</strong>, <strong>Django</strong>, and <strong>MySQL</strong>. My mission is to automate business processes and deliver user-friendly web solutions.
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Skills</h2>
            <div class="flex flex-wrap justify-center gap-4">
                <span class="bg-blue-600 text-white px-4 py-2 rounded-full">Make.com</span>
                <span class="bg-blue-600 text-white px-4 py-2 rounded-full">Microsoft Power Automate</span>
                <span class="bg-blue-600 text-white px-4 py-2 rounded-full">n8n</span>
                <span class="bg-green-600 text-white px-4 py-2 rounded-full">Python</span>
                <span class="bg-green-600 text-white px-4 py-2 rounded-full">Django</span>
                <span class="bg-green-600 text-white px-4 py-2 rounded-full">MySQL</span>
                <span class="bg-gray-600 text-white px-4 py-2 rounded-full">HTML/CSS</span>
                <span class="bg-gray-600 text-white px-4 py-2 rounded-full">JavaScript</span>
                <span class="bg-gray-600 text-white px-4 py-2 rounded-full">Git</span>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Featured Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="project-card bg-gray-100 p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold mb-2">n8n Workflow Automation</h3>
                    <p class="text-gray-700 mb-4">Built a multi-step automation syncing data between Google Sheets and Notion using n8n with 400+ integrations.</p>
                    <a href="https://github.com/yourusername/project1" class="text-blue-600 hover:underline">View Repository</a>
                </div>
                <!-- Project 2 -->
                <div class="project-card bg-gray-100 p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold mb-2">Django E-Commerce Platform</h3>
                    <p class="text-gray-700 mb-4">Developed a secure, scalable e-commerce site with Django and MySQL, featuring payment integration and user authentication.</p>
                    <a href="https://github.com/yourusername/project2" class="text-blue-600 hover:underline">View Repository</a>
                </div>
                <!-- Project 3 -->
                <div class="project-card bg-gray-100 p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold mb-2">Power Automate HR Dashboard</h3>
                    <p class="text-gray-700 mb-4">Automated HR analytics with Power Automate, integrating Microsoft Teams and Excel for real-time reporting.</p>
                    <a href="https://github.com/yourusername/project3" class="text-blue-600 hover:underline">View Repository</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-blue-600 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-8">Get in Touch</h2>
            <p class="text-lg mb-6">Interested in collaborating on automation or web development projects? Let's connect!</p>
            <div class="flex justify-center gap-4">
                <a href="https://linkedin.com/in/yourprofile" class="bg-white text-blue-600 px-4 py-2 rounded-full hover:bg-blue-100">LinkedIn</a>
                <a href="mailto:your.email@example.com" class="bg-white text-blue-600 px-4 py-2 rounded-full hover:bg-blue-100">Email</a>
                <a href="https://github.com/yourusername" class="bg-white text-blue-600 px-4 py-2 rounded-full hover:bg-blue-100">GitHub</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-4 text-center">
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
