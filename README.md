<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frezer Eshetu | Professional Artist</title>
    <!-- Modern Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root { --primary: #2c3e50; --accent: #3498db; --bg: #ffffff; }
        body { font-family: 'Inter', sans-serif; margin: 0; color: #333; line-height: 1.6; }
        
        /* Navigation (Strikingly Style) */
        nav { display: flex; justify-content: space-between; align-items: center; padding: 20px 5%; background: #fff; position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 10px rgba(0,0,0,0.05); }
        .logo { font-weight: 700; font-size: 1.5rem; letter-spacing: 2px; }
        .nav-links a { margin-left: 25px; text-decoration: none; color: #666; font-size: 0.9rem; transition: 0.3s; }
        .nav-links a:hover { color: var(--accent); }
        .btn-contact { background: var(--primary); color: white !important; padding: 10px 20px; border-radius: 5px; }

        /* Hero Section */
        .hero { height: 60vh; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; background: #f4f7f6; padding: 0 20px; }
        .hero h1 { font-size: 3.5rem; margin-bottom: 10px; }
        .hero p { font-size: 1.2rem; color: #777; max-width: 600px; }

        /* Gallery Grid */
        .container { padding: 50px 5%; }
        .gallery { display: grid; grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); gap: 20px; }
        .art-item { background: #eee; height: 350px; border-radius: 8px; overflow: hidden; position: relative; cursor: pointer; }
        .art-item img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.5s; }
        .art-item:hover img { transform: scale(1.05); }

        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .nav-links { display: none; } /* Mobile menu simplified */
        }
    </style>
</head>
<body>

<nav>
    <div class="logo">FREZER ESHETU</div>
    <div class="nav-links">
        <a href="#">Home</a>
        <a href="#">Gallery</a>
        <a href="#">About</a>
        <a href="#" class="btn-contact">Contact Me</a>
    </div>
</nav>

<section class="hero">
    <h1>Artistic Vision</h1>
    <p>Exploring the boundaries of color and form. Welcome to my official digital portfolio.</p>
</section>

<div class="container">
    <div class="gallery">
        <div class="art-item"><img src="https://via.placeholder.com/600x800" alt="Art 1"></div>
        <div class="art-item"><img src="https://via.placeholder.com/600x800" alt="Art 2"></div>
        <div class="art-item"><img src="https://via.placeholder.com/600x800" alt="Art 3"></div>
        <div class="art-item"><img src="https://via.placeholder.com/600x800" alt="Art 4"></div>
    </div>
</div>

<footer style="text-align: center; padding: 50px; color: #999;">
    <p>&copy; 2024 Frezer Eshetu. Built for GitHub Pages.</p>
</footer>

</body>
</html>
