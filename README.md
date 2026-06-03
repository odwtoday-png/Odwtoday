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
            font-size: 14px;
            font-family: inherit;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            padding: 15px 30px;
            border-radius: 5px;
            font-weight: 700;
            text-transform: uppercase;
            font-size: 14px;
            transition: all 0.3s;
            cursor: pointer;
            width: 100%;
            border: none;
        }

        .btn-green {
            background-color: var(--primary-green);
            color: white;
        }

        .btn-green:hover {
            background-color: var(--dark-green);
        }

        .btn-outline {
            background-color: transparent;
            color: white;
            border: 2px solid white;
        }

        /* --- WEBINAR CURRICULUM SECTION (1:1 Service Cards Map) --- */
        .curriculum-section {
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
        }

        .service-card p {
            font-size: 14px;
            color: #666;
            line-height: 1.5;
        }

        /* --- BOTTOM CALL TO ACTION --- */
        .cta-section {
            background: linear-gradient(rgba(68, 119, 10, 0.9), rgba(68, 119, 10, 0.9)), url('https://images.unsplash.com/photo-1558904541-efa8c3a30fc9?auto=format&fit=crop&w=1200&q=80') no-repeat center center/cover;
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
        }

        .cta-container .btn-outline {
            width: auto;
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
        </tr>

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
        }

        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid #222;
            font-size: 12px;
        }

        /* --- RESPONSIVE --- */
        @media (max-width: 992px) {
            .hero-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container nav-container">
            <div class="logo">ODW<span>.today</span></div>
            <nav>
                <ul>
                    <li><a href="#" class="active">Webinar Info</a></li>
                    <li><a href="#">What You'll Learn</a></li>
                    <li><a href="#">About Host</a></li>
                    <li><a href="#">Reviews</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container hero-grid">
            <div class="hero-content">
                <h1>You Relax.<br><span class="green">We Show You How</span> <span class="script">Today.</span></h1>
                <p>Join our exclusive online masterclass. Learn professional strategies, resource balancing, and how to scale your asset management with exceptional efficiency.</p>
            </div>
            
            <div class="registration-form">
                <h3>Save Your Free Spot</h3>
                <form action="#">
                    <div class="form-group">
                        <input type="text" placeholder="Your Name" required>
                    </div>
                    <div class="form-group">
                        <input type="email" placeholder="Your Email Address" required>
                    </div>
                    <button type="submit" class="btn btn-green">Secure My Ticket</button>
                </form>
            </div>
        </div>
    </section>

    <section class="curriculum-section">
        <div class="container">
            <span class="section-tag">— WEBINAR AGENDA —</span>
            <h2 class="section-title">What We Cover</h2>
            
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-bolt"></i></div>
                    <h3>Power Strategies</h3>
                    <p>Clean out outdated workflows and clear away standard operational inefficiencies instantly.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-seedling"></i></div>
                    <h3>Growth Nurturing</h3>
                    <p>Pruning excess overhead items and nurturing core pipelines to maximize value potential.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-layer-group"></i></div>
                    <h3>Layered Layering</h3>
                    <p>Establish a protective foundation of stable processes that enrich long-term growth retention.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-scissors"></i></div>
                    <h3>Precision Trimming</h3>
                    <p>Safely trim away hazardous operational bottlenecks keeping your workflow performance restricted.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-magnifying-glass"></i></div>
                    <h3>Clear Architecture</h3>
                    <p>Gain absolute clarity across all your projects with highly transparent analytics.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-dumpster-fire"></i></div>
                    <h3>System Sanitation</h3>
                    <p>Sanitize and wipe clean structural bloat so old systems run and feel brand new.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-truck-ramp-box"></i></div>
                    <h3>Debris Removal</h3>
                    <p>Haul away useless task backlogs and legacy clutter effortlessly without lifting a finger.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon"><i class="fa-solid fa-cubes"></i></div>
                    <h3>And Much More</h3>
                    <p>If it helps maximize efficiency or scales modern business, we handle it live. Just join!</p>
                </div>
            </div>
        </div>
    </section>

    <section class="cta-section">
        <div class="container cta-container">
            <div class="cta-text">
                <h2>Ready To Get Started?</h2>
                <p>Claim your spot before the registration timer runs out and event spaces close completely.</p>
            </div>
            <a href="#" class="btn btn-outline">Claim Free Spot</a>
        </div>
    </section>

    <footer>
        <div class="container footer-grid">
            <div class="footer-col">
                <h3><i class="fa-solid fa-users"></i> About Hosts</h3>
                <p>ODW.today provides leading professional mentorship frameworks. We treat every trainee's personal brand exactly like our own.</p>
                <p style="margin-top: 15px;">You relax. <span class="highlight">We get it done today.</span></p>
            </div>
            
            <div class="footer-col">
                <h3><i class="fa-solid fa-calendar-days"></i> Broadcast Times</h3>
                <table class="hours-table">
                    <tr>
                        <td>Session 1</td>
                        <td>9:00 AM – 11:00 AM</td>
                    </tr>
                    <tr>
                        <td>Session 2</td>
                        <td>5:00 PM – 7:00 PM</td>
                    </tr>
                    <tr>
                        <td>Replays</td>
                        <td>Unavailable</td>
                    </tr>
                </table>
            </div>

            <div class="footer-col">
                <h3><i class="fa-solid fa-headset"></i> Support Desk</h3>
                <ul class="contact-list">
                    <li><i class="fa-solid fa-phone"></i> (224) 401-2047</li>
                    <li><i class="fa-solid fa-envelope"></i> help@ODW.today</li>
                </ul>
            </div>
        </div>
        
        <div class="copyright">
            &copy; 2026 ODW.today. All rights reserved.
        </div>
    </footer>

</body>
</html>
