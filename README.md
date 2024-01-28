# My-Portfolio-
This is my web development project !
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <title>Software Engineer Portfolio</title>
</head>
<body class="bg-gray-100 font-sans">

    <!-- Navigation -->
    <nav class="bg-blue-500 p-4">
        <div class="container mx-auto flex justify-between items-center">
            <a href="#" class="text-white text-xl font-bold">My Portfolio</a>
            <div class="space-x-4">
                <a href="#about" class="text-white">About</a>
                <a href="#projects" class="text-white">Projects</a>
                <a href="#contact" class="text-white">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-blue-700 text-white text-center py-20">
        <div class="container mx-auto">
            <h1 class="text-4xl font-bold mb-4">Hello, I'm [Vikash Kumar]</h1>
            <p class="text-lg">A passionate software engineer</p>
        </div>
    </header>

 
    
    <!-- About Section -->
    <section id="about" class="py-16">
        <div class="container mx-auto">
            <h2 class="text-3xl font-bold mb-8">About Me</h2>
            <p class="text-gray-800">
                Insert your introduction and details about your skills, experience, and passion for software engineering here.
            </p>
        </div>
    </section>
    <!-- Projects Section -->
<section id="projects" class="bg-gray-100 py-16">
    <div class="container mx-auto">
        <h2 class="text-3xl font-bold mb-8">Projects</h2>
        <!-- Add your projects here with appropriate HTML structure -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Project 1 -->
            <div class="bg-white p-6 rounded-lg shadow-md">
                <h3 class="text-xl font-bold mb-4">Project 1</h3>
                <p>My Portfolio
                <div class="mt-4">
                    <strong>Technologies:</strong> HTML, CSS, JavaScript
                </div>
            </div>
            <!-- Project 2 -->
            <div class="bg-white p-6 rounded-lg shadow-md">
                <h3 class="text-xl font-bold mb-4">Project 2</h3>
                <p>Contact Book is a GUI based project using Tkinter and a message module used for storing information about some person like name and contact number.</p>
                <div class="mt-4">
                    <strong>Technologies:</strong> Python , C
                </div>
            </div>
            <!-- Project 3 -->
            <div class="bg-white p-6 rounded-lg shadow-md">
                <h3 class="text-xl font-bold mb-4">Project 3</h3>
                <p> A To-Do List application is a useful project that helps users manage
                    and organize their tasks efficiently.</p>
                <div class="mt-4">
                    <strong>Technologies:</strong> Python, C
                </div>
            </div>
        </div>
    </div>
</section>


   

    
   
        <!-- Social Media Icons (you can replace the links and icons with your own) -->
        <div class="flex mt-8">
            <a href="#" target="_blank" class="text-2xl mr-4">
                <i class="fab fa-twitter"></i>
            </a>
            <a href="#" target="_blank" class="text-2xl mr-4">
                <i class="fab fa-linkedin-in"></i>
            </a>
            <a href="#" target="_blank" class="text-2xl">
                <i class="fab fa-github"></i>
            </a>
        </div>
    </div>
</section>
<!-- Contact Section -->
<section id="contact" class="py-16">
    <div class="container mx-auto">
        <h2 class="text-3xl font-bold mb-8">Contact Me</h2>
        <p class="text-gray-800 mb-4">Feel free to reach out to me through the following channels:</p>
        <ul class="list-disc pl-8">
            <li>Email: <a href="mailto:cutexvikash@gmail.com" class="text-blue-500">your.email@example.com</a></li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/vikash-kumar-103074282/" target="_blank" class="text-blue-500">linkedin.com/in/your-profile</a></li>
            <li>GitHub: <a href="https://github.com/VikashKumar0120" target="_blank" class="text-blue-500">github.com/your-username</a></li>
        </ul>

        <!-- Contact Form (Replace this with your actual contact form if needed) -->
        <div class="mt-8">
            <h3 class="text-xl font-bold mb-4">Send me a message:</h3>
            <form action="#" method="post" class="max-w-md">
                <div class="mb-4">
                    <label for="name" class="block text-sm font-medium text-gray-600">Name</label>
                    <input type="text" id="name" name="name" placeholder="Your Name" class="w-full px-4 py-2 border rounded-md">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-sm font-medium text-gray-600">Email</label>
                    <input type="email" id="email" name="email" placeholder="Your Email" class="w-full px-4 py-2 border rounded-md">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-sm font-medium text-gray-600">Message</label>
                    <textarea id="message" name="message" placeholder="Your Message" rows="4" class="w-full px-4 py-2 border rounded-md"></textarea>
                </div>
                <button type="submit" class="bg-blue-500 text-white px-4 py-2 rounded-md hover:bg-blue-600">Send Message</button>
            </form>
        </div>
    </div>
</section>


<!-- Footer -->
<footer class="bg-blue-500 text-white text-center py-4">
    <div class="container mx-auto">
        <p>&copy; 2024 Vikash Kumar. All rights reserved.</p>
        <div class="mt-2">
            <a href="#top" class="text-white hover:underline">Back to Top</a>
        </div>
    </div>
</footer>

