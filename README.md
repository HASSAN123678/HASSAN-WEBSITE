# HASSAN-WEBSITE
MY FIRST WEBSITE IN GOOGLE
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A luxurious website designed to showcase elegance and sophistication.">
    <title>Hassan's Luxury Website</title>
    <!-- Linking Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- AOS for Animations -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css">
    <script defer src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
</head>

<body class="bg-gray-100 text-gray-800 font-roboto">
    <!-- Header -->
    <header class="bg-gradient-to-r from-gray-900 to-gray-700 text-white py-6 px-10">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-4xl font-playfair">Hassan's Luxury Space</h1>
            <nav>
                <ul class="flex space-x-6">
                    <li><a href="index.html" class="hover:underline">Home</a></li>
                    <li><a href="portfolio.html" class="hover:underline">Portfolio</a></li>
                    <li><a href="blog.html" class="hover:underline">Blog</a></li>
                    <li><a href="shop.html" class="hover:underline">Shop</a></li>
                    <li><a href="contact.html" class="hover:underline">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="relative h-screen bg-cover bg-center" style="background-image: url('images/hero-bg.jpg');">
        <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center">
            <div class="text-center text-white">
                <h2 class="text-5xl font-playfair" data-aos="fade-up">Welcome to Luxury</h2>
                <p class="mt-4 text-lg" data-aos="fade-up" data-aos-delay="200">Where elegance meets functionality.</p>
                <button class="mt-6 px-6 py-3 bg-white text-gray-900 rounded-lg shadow-lg" data-aos="fade-up" data-aos-delay="400">Explore Now</button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-6">
        <div class="container mx-auto text-center">
            <p>&copy; 2024 Hassan's Luxury Website. All rights reserved.</p>
        </div>
    </footer>

    <!-- Initialize AOS -->
    <script>
        AOS.init();
    </script>
</body>

</html>
