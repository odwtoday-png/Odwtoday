# Odwtoday
Hey neighbors! I run ODW.today, a local outdoor services company serving homeowners in the area. We handle power washing, lawn care, mulch, tree trimming, window cleaning, junk removal, bin cleaning, car washing, and more. Fast turnaround, fair pricing, and free quotes. Check out our website and reach out anytime! 📞 (224) 401-2047 🌐 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ODW.today - Exclusive Business Webinar</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        /* --- CSS VARIABLES & RESET --- */
        :root {
            --primary-green: #60a611;
            --dark-green: #44770a;
            --text-dark: #1a1a1a;
            --text-light: #ffffff;
            --bg-light: #f8f9fa;
            --footer-bg: #0b0c0e;
            --card-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Montserrat', sans-serif;
        }

        body {
            color: var(--text-dark);
            background-color: #ffffff;
            overflow-x: hidden;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* --- HEADER & NAVIGATION --- */
        header {
            background: #ffffff;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 28px;
            font-weight: 800;
            color: var(--primary-green);
        }
        .logo span {
            color: #222;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        nav ul li a {
            font-weight: 700;
            font-size: 14px;
            text-transform: uppercase;
            color: #222;
        }

        nav ul li a:hover, nav ul li a.active {
            color: var(--primary-green);
        }

        /* --- HERO SECTION --- */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.55), rgba(0, 0, 0, 0.55)), url('https://images.unsplash.com/photo-1558904541-efa8c3a30fc9?auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
            padding: 120px 0;
            color: var(--text-light);
        }

        .hero-grid {
            display: grid;
            grid-template-columns: 1.2fr 0.8fr;
            gap: 40px;
            align-items: center;
        }

        .hero h1 {
            font-size: 48px;
            font-weight: 800;
            line-height: 1.1;
            text-transform: uppercase;
            margin-bottom: 15px;
        }

        .hero h1 span.green {
            color: var(--primary-green);
        }

        .hero h1 span.script {
            font-style: italic;
            text-transform: none;
            font-weight: 400;
            display: block;
            margin-top: 5px;
        }

        .hero p {
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 25px;
            opacity: 0.9;
        }

        /* Hero Registration Form */
        .registration-form {
            background: rgba(255, 255, 255, 0.98);
            padding: 30px;
            border-radius: 8px;
            color: var(--text-dark);
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
        }

        .registration-form h3 {
            font-size: 20px;
            font-weight: 800;
            text-transform: uppercase;
            margin-bottom: 15px;
            text-align: center;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group input {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font
