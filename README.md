# Odwtoday
Hey neighbors! I run ODW.today, a local outdoor services company serving homeowners in the area. We handle power washing, lawn care, mulch, tree trimming, window cleaning, junk removal, bin cleaning, car washing, and more. Fast turnaround, fair pricing, and free quotes. Check out our website and reach out anytime! 📞 (224) 401-2047 🌐 ODW.today
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ODW.today - Outdoor Work Today</title>
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
            display: flex;
            align-items: center;
            gap: 5px;
        }
        .logo span {
            color: #222;
        }
        .logo .subtext {
            font-size: 10px;
            display: block;
            font-weight: 600;
            letter-spacing: 1px;
            color: #666;
            margin-top: -5px;
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
            transition: color 0.3s;
        }

        nav ul li a:hover, nav ul li a.active {
            color: var(--primary-green);
        }

        /* --- HERO SECTION --- */
        .hero {
            /* Replace with an actual background image URL of a nice lawn/house */
            background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url('https://images.unsplash.com/photo-1558904541-efa8c3a30fc9?auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
            padding: 140px 0;
            color: var(--text-light);
        }

        .hero-content {
            max-width: 600px;
        }

        .hero h1 {
            font-size: 52px;
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
            margin-bottom: 35px;
            font-weight: 400;
            opacity: 0.9;
        }

        .hero-buttons {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            padding: 15px 30px;
            border-radius: 5px;
            font-weight: 700;
            text-transform: uppercase;
            font-size: 14px;
            transition: all 0.3s;
            cursor: pointer;
        }

        .btn-green {
            background-color: var(--primary-green);
            color: white;
            border: none;
        }

        .btn-green:hover {
            background-color: var(--dark-green);
        }

        .btn-outline {
            background-color: transparent;
            color: white;
            border: 2px solid white;
        }

        .btn-outline:hover {
            background-color: white;
            color: var(--text-dark);
        }

        /* --- SERVICES SECTION --- */
        .services-section {
            padding: 80px 0;
            background-color: #ffffff;
            text-align: center;
        }

        .section-tag {
            color: var(--primary-green);
            font-weight: 700;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 10px;
            display: block;
        }

        .section-title {
            font-size: 36px;
            font-weight: 800;
            text-transform: uppercase;
            margin-bottom: 40px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
            margin-bottom: 40px;
        }

        .service-card {
            background: #ffffff;
            padding: 35px 25px;
            border-radius: 8px;
            box-shadow: var(--card-shadow);
            border: 1px solid #f0f0f0;
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-icon {
            font-size: 40px;
            color: var(--primary-green);
            margin-bottom: 20px;
        }

        .service-card h3 {
            font-size: 16px;
            font-weight: 700;
            text-transform: uppercase;
            margin-bottom: 12px;
            letter-spacing: 0.5px;
        }

        .service-card p {
            font-size: 14px;
            color: #666;
            line-height: 1.5;
        }

        /* --- CALL TO ACTION (CTA) SECTION --- */
        .cta-section {
            /* Replace with an actual background image URL */
            background: linear-gradient(rgba(68, 119, 10, 0.85), rgba(68, 119, 10, 0.85)), url('https://images.unsplash.com/photo-1558904541-efa8c3a30fc9?auto=format&fit=crop&w=1200&q=80') no-repeat center center/cover;
            padding: 60px 0;
            color: white;
        }

        .cta-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 30px;
        }

        .cta-text h2 {
            font-size: 32px;
            font-weight: 800;
            text-transform: uppercase;
            margin-bottom: 10px;
        }

        .cta-text p {
            font-size: 16px;
            opacity: 0.9;
        }

        /* --- FOOTER --- */
        footer {
            background-color: var(--footer-bg);
            color: #bcbcbc;
            padding: 60px 0 20px 0;
            font-size: 14px;
        }

        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }

        .footer-col h3 {
            color: white;
            font-size: 16px;
            font-weight: 700;
            text-transform: uppercase;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .footer-col h3 i {
            color: var(--primary-green);
        }

        .footer-col p {
            line-height: 1.6;
        }

        .footer-col .highlight {
            color: var(--primary-green);
            font-weight: 600;
        }

        .hours-table {
            width: 100%;
            border-collapse: collapse;
        }

        .hours-table td {
            padding: 6px 0;
        }

        .hours-table td:last-child {
            text-align: right;
            color: white;
        }

        .contact-list {
            list-style: none;
        }

        .contact-list li {
            margin-bottom: 12px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .contact-list li i {
            color: var(--primary-green);
            width: 20px;
        }

        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid #222;
            font-size: 12px;
            color: #666;
        }

        /* --- RESPONSIVE DESIGN --- */
        @media (max-width: 768px) {
            nav {
                display: none; /* Simple implementation; can be upgraded to a hamburger menu */
            }
            .hero h1 {
                font-size: 36px;
            }
            .cta-container {
                flex-direction: column;
                text-align: center;
                justify-content: center;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container nav-container">
            <div class="logo">
                <div>ODW<span style="color:var(--primary-green);">.today</span></div>
                </div>
            <nav>
                <ul>
                    <li><a href="#" class="active">Home</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Gallery</a></li>
                    <li><a href="#">Free Quote</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <h1>You Relax.<br><span class="green">We Get It Done</span> <span class="script">Today.</span></h1>
                <p>Professional outdoor services you can count on. Quality work, fair pricing, and exceptional results.</p>
                <div class="hero-buttons">
                    <a href="tel:2244012047" class="btn btn-green">
                        <i class="fa-solid fa-phone"></i> (224) 401-2047
                    </a>
                    <a href="#" class="btn btn-outline">Get A Free Quote</a>
                </div>
            </div>
        </div>
    </section>

    <section class="services-section">
        <div class="container">
            <span class="section-tag">— Our Services —</span>
            <h2 class="section-title">We Do It All</h2>
            
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-噴霧器 fa-spray-can-sparkles"></i></div>
                    <h3>Power Washing</h3>
                    <p>Remove dirt, grime, and mold from driveways, siding, decks, and more.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-seedling"></i></div>
                    <h3>Lawn Care</h3>
                    <p>Mowing, edging, trimming, and seasonal cleanups to keep your lawn looking its best.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-cubes"></i></div>
                    <h3>Mulch Installation</h3>
                    <p>Fresh mulch that enhances your landscape and helps retain moisture.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-tree"></i></div>
                    <h3>Tree Trimming</h3>
                    <p>Safe and professional trimming to keep your trees healthy and your property safe.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-window-maximize"></i></div>
                    <h3>Window Cleaning</h3>
                    <p>Streak-free, spotless windows for a clearer view and a brighter home.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-trash-can"></i></div>
                    <h3>Garbage Bin Cleaning</h3>
                    <p>We clean and sanitize your bins so they smell fresh and look great.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-truck"></i></div>
                    <h3>Junk Removal</h3>
                    <p>We haul away unwanted junk, debris, and clutter so you don't have to.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-ellipsis"></i></div>
                    <h3>And More</h3>
                    <p>If it's outdoors, we can probably help. Just ask!</p>
                </div>
            </div>

            <button class="btn btn-green" style="padding: 12px 40px;">View All Services</button>
        </div>
    </section>

    <section class="cta-section">
        <div class="container cta-container">
            <div class="cta-text">
                <h2>Ready To Get Started?</h2>
                <p>Request your free quote today and let's get your outdoor project done right.</p>
            </div>
            <a href="#" class="btn btn-outline">Get Your Free Quote</a>
        </div>
    </section>

    <footer>
        <div class="container footer-grid">
            <div class="footer-col">
                <h3><i class="fa-solid fa-users"></i> About Us</h3>
                <p>ODW.today is a local, family-owned business dedicated to providing top-quality outdoor services. We take pride in our work and treat every property like it's our own.</p>
                <p style="margin-top: 15px;">You relax. <span class="highlight">We get it done today.</span></p>
            </div>
            
            <div class="footer-col">
                <h3><i class="fa-solid fa-clock"></i> Hours of Operation</h3>
                <table class="hours-table">
                    <tr>
                        <td>Monday – Friday</td>
                        <td>9:00 AM – 5:00 PM</td>
                    </tr>
                    <tr>
                        <td>Saturday</td>
                        <td>9:00 AM – 7:00 PM</td>
                    </tr>
                    <tr>
                        <td>Sunday</td>
                        <td>Closed</td>
                    </tr>
                </table>
            </div>

            <div class="footer-col">
                <h3><i class="fa-solid fa-phone"></i> Contact Us</h3>
                <ul class="contact-list">
                    <li><i class="fa-solid fa-phone"></i> (224) 401-2047</li>
                    <li><i class="fa-solid fa-envelope"></i> ODW.today@gmail.com</li>
                    <li><i class="fa-solid fa-globe"></i> ODW.today</li>
                </ul>
            </div>
        </div>
        
        <div class="copyright">
            &copy; 2026 ODW.today. All rights reserved.
        </div>
    </footer>

</body>
</html>
