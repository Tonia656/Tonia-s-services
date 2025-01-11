# Tonia-s-services
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tonia's Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            display: flex;
            justify-content: center;
            background: #555;
            padding: 10px 0;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: #007bff;
            color: #fff;
            text-align: center;
            padding: 50px 20px;
        }

        .hero h2 {
            margin: 0 0 10px;
        }

        .hero p {
            margin: 0 0 20px;
        }

        .hero a {
            background: #fff;
            color: #007bff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }

        .hero a:hover {
            background: #e0e0e0;
        }

        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: auto;
        }

        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-between;
        }

        .service {
            background: #f4f4f4;
            padding: 20px;
            border-radius: 5px;
            flex: 1 1 calc(33.333% - 20px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .service h3 {
            margin-top: 0;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        footer a {
            color: #fff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tonia's Services</h1>
        <p>Professional Hospitality and Facility Management Services</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">
        <h2>Welcome to Tonia's Services</h2>
        <p>Your trusted partner for efficient and reliable management solutions.</p>
        <a href="#services">Explore Services</a>
    </div>

    <section id="about">
        <h2>About Us</h2>
        <p>Tonia’s Services specializes in Night Audit Management, Facility Management, and Front Office/Night Receptionist roles. We pride ourselves on delivering exceptional service, ensuring smooth operations for your hospitality or facility needs.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service">
                <h3>Night Audit Manager</h3>
                <p>Ensure accurate financial reporting and smooth night operations with our experienced audit management services.</p>
            </div>
            <div class="service">
                <h3>Facility Management</h3>
                <p>Comprehensive facility solutions, from maintenance coordination to operational oversight.</p>
            </div>
            <div class="service">
                <h3>Front Office/Night Receptionist</h3>
                <p>Professional and welcoming reception services tailored to meet your business needs during nighttime hours.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Reach out today and let us assist you!</p>
        <p>Email: <a href="mailto:example@example.com">example@example.com</a></p>
        <p>Phone: <a href="tel:+1234567890">+1 234 567 890</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Tonia's Services. All rights reserved.</p>
    </footer>
</body>
</html>
