<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mema's Food Bar | Alotau, Milne Bay</title>
    <style>
        :root {
            --primary: #d9534f;
            --dark: #222;
            --light: #f8f9fa;
        }
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: var(--dark);
            background-color: #fff;
            line-height: 1.6;
        }
        header {
            background-color: var(--primary);
            color: white;
            text-align: center;
            padding: 3rem 1rem;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 0.5rem;
        }
        nav {
            background: var(--dark);
            text-align: center;
            padding: 0.8rem;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 2rem 1rem;
        }
        .section-title {
            text-align: center;
            border-bottom: 2px solid var(--primary);
            padding-bottom: 0.5rem;
            margin-bottom: 1.5rem;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }
        .card {
            background: var(--light);
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .card h3 {
            margin-top: 0;
            color: var(--primary);
        }
        footer {
            text-align: center;
            background: var(--dark);
            color: white;
            padding: 1.5rem 0;
            margin-top: 2rem;
        }
        .btn {
            display: inline-block;
            background: var(--primary);
            color: white;
            padding: 0.6rem 1.2rem;
            border-radius: 4px;
            text-decoration: none;
            margin-top: 1rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Mema's Food Bar</h1>
        <p>Authentic Local Flavors & International Cuisine in Alotau</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#menu">Highlights</a>
        <a href="#hours">Hours & Contact</a>
    </nav>

    <div class="container">
        <section id="about">
            <h2 class="section-title">Welcome to Mema's</h2>
            <p style="text-align: center;">Fun for all! Come visit us in Alotau for delicious meals, cool drinks, and a warm, welcoming atmosphere.</p>
        </section>

        <section id="menu" style="margin-top: 3rem;">
            <h2 class="section-title">What We Offer</h2>
            <div class="grid">
                <div class="card">
                    <h3>Local & International Dishes</h3>
                    <p>Enjoy a wide variety of freshly prepared meals, from local PNG favorites to classic steaks and buffet options.</p>
                </div>
                <div class="card">
                    <h3>Licensed Bar</h3>
                    <p>Relax after a long day with a cool ale, wine, or soft drink in a comfortable atmosphere.</p>
                </div>
                <div class="card">
                    <h3>Great Location</h3>
                    <p>Conveniently located in Alotau near Island Plaza and the Massim Museum, just a short walk from the dock.</p>
                </div>
            </div>
        </section>

        <section id="hours" style="margin-top: 3rem;">
            <h2 class="section-title">Visit Us</h2>
            <div class="grid">
                <div class="card">
                    <h3>Location</h3>
                    <p>Allotment 39, Section 2<br>Alotau, Milne Bay Province<br>Papua New Guinea</p>
                </div>
                <div class="card">
                    <h3>Opening Hours</h3>
                    <p><strong>Monday – Saturday:</strong> 10:00 AM – 10:00 PM<br>
                    <strong>Sunday:</strong> Closed</p>
                </div>
                <div class="card">
                    <h3>Contact Us</h3>
                    <p>Phone: +675 7955 8054</p>
                    <a href="tel:+67579558054" class="btn">Call Now</a>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; Mema's Food Bar. All rights reserved.</p>
    </footer>

</body>
</html>
