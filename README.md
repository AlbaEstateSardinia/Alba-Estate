<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alba Estate - Your Perfect Escape</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F4EDE4;
            color: #5A4A42;
        }
        .navbar {
            display: flex;
            justify-content: center;
            background-color: #5A4A42;
            padding: 15px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .hero {
            background: url('main-image.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            font-size: 2rem;
            padding: 20px;
            box-shadow: inset 0 0 0 1000px rgba(0, 0, 0, 0.3);
        }
        .content {
            padding: 40px;
            text-align: center;
        }
        .btn {
            background-color: #C19A6B;
            padding: 15px 25px;
            text-decoration: none;
            color: white;
            border-radius: 8px;
            font-size: 1.2rem;
            display: inline-block;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #A07750;
        }
        .properties {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 40px;
        }
        .property {
            text-align: center;
        }
        .property img {
            width: 250px;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
        }
        .footer {
            background-color: #5A4A42;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <a href="#">Home</a>
        <a href="#">Location</a>
        <a href="#">Activities</a>
        <a href="#">Testimonials</a>
        <a href="#">Contacts</a>
    </div>
    <div class="hero">
        <h1>Discover your perfect escape where elegance meets tranquillity in the beautiful northeast Sardinia.</h1>
    </div>
    <div class="content">
        <h2>Welcome to Alba Estate</h2>
        <p>Experience the ultimate retreat in San Pantaleo, where elegance and serenity blend seamlessly.</p>
    </div>
    <div class="properties">
        <div class="property">
            <img src="villa-alba.jpg" alt="Villa Alba">
            <p><a href="#" class="btn">Check Availability</a></p>
        </div>
        <div class="property">
            <img src="farmhouse.jpg" alt="Farmhouse">
            <p><a href="#" class="btn">Check Availability</a></p>
        </div>
        <div class="property">
            <img src="stazzu.jpg" alt="Stazzu">
            <p><a href="#" class="btn">Check Availability</a></p>
        </div>
        <div class="property">
            <img src="villa-olivo.jpg" alt="Villa Olivo">
            <p><a href="#" class="btn">Check Availability</a></p>
        </div>
    </div>
    <div class="footer">
        <p>&copy; 2025 Alba Estate. All Rights Reserved.</p>
    </div>
</body>
</html>
