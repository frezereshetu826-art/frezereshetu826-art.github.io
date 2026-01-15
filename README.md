<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gemini Design - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #2563eb;
            --dark: #0f172a;
            --light: #f8fafc;
            --accent: #3b82f6;
        }

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            background-color: var(--light);
            color: var(--dark);
        }

        /* --- HEADER & NAVIGATION BAR --- */
        header {
            background: white;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 15px 5%;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary);
            text-decoration: none;
        }

        .menu-links {
            display: flex;
            gap: 25px;
        }

        .menu-links a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 500;
            transition: 0.3s;
        }

        .menu-links a:hover {
            color: var(--primary);
        }

        .search-bar {
            background: #f1f5f9;
            padding: 8px 15px;
            border-radius: 30px;
            display: flex;
            align-items: center;
        }

        .search-bar input {
            border: none;
            background: transparent;
            outline: none;
            margin-left: 10px;
            width: 150px;
        }

        /* --- MAIN LAYOUT --- */
        .container {
            display: grid;
            grid-template-columns: 1fr 300px;
            gap: 40px;
            padding: 40px 5%;
        }

        /* --- IMAGE GALLERY (4 Big Images) --- */
        .gallery-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 30px;
        }

        .hero-image-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 15px -3px rgba(0,0,0,0.1);
        }

        .hero-image-card img {
            width: 100%;
            height: 500px; /* Big sized images */
            object-fit: cover;
            display: block;
        }

        .image-info {
            padding: 20px;
        }

        /* --- SIDEBAR --- */
        .sidebar-bar {
            background: white;
            padding: 25px;
            border-radius: 15px;
            height: fit-content;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        .sidebar-bar h3 {
            border-bottom: 2px solid var(--primary);
            padding-bottom: 10px;
        }

        /* --- FOOTER --- */
        footer {
            background: var(--dark);
            color: white;
            padding: 50px 5% 20px;
            text-align: center;
            margin-top: 50px;
        }

        @media (max-width: 900px) {
            .container { grid-template-columns: 1fr; }
            header { flex-direction: column; gap: 15px; }
            .hero-image-card img { height: 300px; }
        }
    </style>
</head>
<body>
