<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta Tags -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Title -->
    <title>DD Motors | Heavy Vehicles Industry</title>

    <!-- Favicon -->
    <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/1995/1995506.png">

    <!-- Internal CSS -->
    <style>
        /* Smooth Scrolling */
        html {
            scroll-behavior: smooth;
        }

        /* Reset Default Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body Styling */
        body {
            font-family: "Times New Roman", Times, serif;
            background-color: #f4f4f4;
            line-height: 1.6;
        }

        /* Header */
        header {
            background-color: #1f2933;
            color: white;
            padding: 15px 0;
            text-align: center;
        }

        /* Navigation Bar */
        nav {
            background-color: #f39c12;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            font-size: 16px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.65),
                        rgba(0, 0, 0, 0.65)),
                        url("https://images.unsplash.com/photo-1601584115197-04ecc0da31d7?auto=format&fit=crop&w=1600&q=80")
                        no-repeat center center/cover;
            color: #ffffff;
            padding: 120px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 15px;
            letter-spacing: 1px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 25px;
        }

        .hero .btn {
            display: inline-block;
            background-color: #f39c12;
            color: #ffffff;
            padding: 12px 25px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
            font-weight: bold;
            transition: 0.3s ease;
        }

        .hero .btn:hover {
            background-color: #d68910;
            transform: scale(1.05);
        }

        /* Sections */
        .container {
            padding: 30px;
            max-width: 1000px;
            margin: 20px auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #1f2933;
            margin-bottom: 15px;
            border-bottom: 3px solid #f39c12;
            display: inline-block;
            padding-bottom: 5px;
        }

        ul {
            margin-left: 20px;
        }

        /* Products Section */
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: space-between;
        }

        .card {
            flex: 1 1 30%;
            background: #f9f9f9;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }

        .card h3 {
            margin-top: 10px;
        }

        /* Contact Form */
        form input,
        form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-family: "Times New Roman", Times, serif;
        }

        form button {
            background-color: #f39c12;
            color: white;
            border: none;
            padding: 10px 15px;
            margin-top: 10px;
            cursor: pointer;
            border-radius: 5px;
            font-size: 16px;
        }

        form button:hover {
            background-color: #d68910;
        }

        /* Footer */
        footer {
            background-color: #1f2933;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .products {
                flex-direction: column;
            }

            .hero {
                padding: 80px 20px;
            }

            .hero h1 {
                font-size: 30px;
            }

            .hero p {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>DD Motors</h1>
        <p>Powering the Future of Heavy Vehicles</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <h1>Welcome to DD Motors</h1>
        <p>Your Trusted Partner in Heavy Vehicle Solutions</p>
        <a href="#products" class="btn">Explore Our Products</a>
    </section>

    <!-- About Section -->
    <section class="container" id="about">
        <h2>About Us</h2>
        <p>
            DD Motors is a leading heavy vehicles industry specializing in the manufacturing,
            sales, and servicing of high-performance commercial vehicles. We are committed to
            delivering quality, reliability, and innovation to meet modern transportation needs.
        </p>
    </section>

    <!-- Services Section -->
    <section class="container" id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Heavy Vehicle Manufacturing</li>
            <li>Truck Sales and Distribution</li>
            <li>Vehicle Maintenance and Repair</li>
            <li>Spare Parts Supply</li>
            <li>Fleet Management Solutions</li>
        </ul>
    </section>

    <!-- Products Section -->
    <section class="container" id="products">
        <h2>Our Products</h2>
        <div class="products">
            <div class="card">
                <img src="images/Heavy Duty Trucks.jpg" alt="Heavy Duty Truck">
                <h3>Heavy Duty Truck</h3>
                <p>Reliable and powerful for long-distance transport.</p>
            </div>  

            <div class="card">
                <img src="images/Cargo Trailers.jpg" alt="Cargo Trailer">
                <h3>Cargo Trailer</h3>
                <p>Designed for efficient and secure goods transport.</p>
            </div>

            <div class="card">
                <img src="images/Construction Vehicles.jpg" alt="Construction Vehicle">
                <h3>Construction Vehicle</h3>
                <p>Built for durability in demanding environments.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="container" id="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> Anna Nagar East,Chennai, Tamil Nadu, India</p>
        <p><strong>Phone:</strong> +91 98765 43210</p>
        <p><strong>Email:</strong> info@ddmotors.com</p>

        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="4" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 DD Motors. All Rights Reserved.</p>
        <p>Designed by Deepika Sivagurunathan</p>
    </footer>

</body>
</html>
