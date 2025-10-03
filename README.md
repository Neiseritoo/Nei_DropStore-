<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nei_DroopShop - Ropa Vintage y Retro</title>
    <style>
        /* Estilos generales */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Courier New', monospace;
        }

        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Estilos vintage/retro */
        .vintage-border {
            border: 2px solid #8B0000;
            box-shadow: 5px 5px 0px rgba(139, 0, 0, 0.3);
        }

        .retro-pattern {
            background-image: repeating-linear-gradient(
                45deg,
                transparent,
                transparent 10px,
                rgba(139, 0, 0, 0.05) 10px,
                rgba(139, 0, 0, 0.05) 20px
            );
        }

        /* Header */
        header {
            background-color: #8B0000;
            color: #fff;
            padding: 20px 0;
            border-bottom: 5px solid #5a0000;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 2.5rem;
            font-weight: bold;
            letter-spacing: 2px;
            text-shadow: 2px 2px 0px #5a0000;
        }

        .logo span {
            color: #FFD700;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            transition: all 0.3s;
        }

        nav ul li a:hover {
            background-color: #FFD700;
            color: #8B0000;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1558769132-cb25e5c8c5b3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 500px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #fff;
            margin-bottom: 40px;
        }

        .hero-content {
            max-width: 800px;
            padding: 20px;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 0px #8B0000;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            background-color: #8B0000;
            color: #fff;
            padding: 12px 30px;
            text-decoration: none;
            font-weight: bold;
            border: 2px solid #fff;
            transition: all 0.3s;
        }

        .btn:hover {
            background-color: #FFD700;
            color: #8B0000;
        }

        /* Productos */
        .products {
            padding: 40px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 40px;
            position: relative;
        }

        .section-title h2 {
            display: inline-block;
            background-color: #fff;
            padding: 0 20px;
            font-size: 2rem;
            color: #8B0000;
            position: relative;
            z-index: 1;
        }

        .section-title::after {
            content: "";
