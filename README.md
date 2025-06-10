# My-shop
E commerce 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Store</title>
    <!-- Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Link to your custom stylesheet -->
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* Using Inter font as the default */
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-50">

    <!-- Header Section -->
    <header class="bg-white shadow-sm">
        <div class="container mx-auto px-4 py-6">
            <h1 class="text-3xl font-bold text-gray-800 text-center">My Awesome Store</h1>
            <p class="text-center text-gray-500 mt-1">High-Quality Products, Just a Message Away</p>
        </div>
    </header>

    <!-- Main Content: Product Grid -->
    <main class="container mx-auto px-4 py-8">
        <div id="product-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Products will be dynamically inserted here by JavaScript -->
            <div class="text-center col-span-full py-16 text-gray-500">
                <p>Loading products...</p>
            </div>
        </div>
    </main>

    <!-- Footer Section -->
    <footer class="bg-white mt-12 py-6">
        <div class="container mx-auto px-4 text-center text-gray-500">
            <p>&copy; 2024 My Awesome Store. All rights reserved.</p>
        </div>
    </footer>


    <!-- Link to your JavaScript file -->
    <script src="script.js"></script>
</body>
</html>

