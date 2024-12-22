<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vuokatti Villas - Stay & Explore</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background: url('path/to/your-image.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 60px 20px;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
        }
        header p {
            font-size: 1.2rem;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .packages {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .package {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            flex: 1 1 calc(33% - 20px);
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .package img {
            width: 100%;
            height: auto;
        }
        .package-content {
            padding: 15px;
        }
        .package h3 {
            margin: 0 0 10px;
        }
        .package p {
            margin: 0 0 15px;
        }
        .cta {
            background-color: #007BFF;
            color: white;
            text-align: center;
            padding: 20px;
            border-radius: 8px;
            text-decoration: none;
            display: inline-block;
            margin-top: 10px;
        }
        .cta:hover {
            background-color: #0056b3;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #f8f9fa;
            color: #6c757d;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Vuokatti Villas</h1>
        <p>Discover stunning villas and adventure-packed experiences</p>
    </header>
    <section>
        <h2>Exclusive Packages</h2>
        <div class="packages">
            <div class="package">
                <img src="path/to/package1-image.jpg" alt="Package 1">
                <div class="package-content">
                    <h3>Relax & Rejuvenate</h3>
                    <p>Stay in luxury villas and enjoy serene surroundings.</p>
                    <a href="#" class="cta">Book Now</a>
                </div>
            </div>
            <div class="package">
                <img src="path/to/package2-image.jpg" alt="Package 2">
                <div class="package-content">
                    <h3>Adventure Awaits</h3>
                    <p>Thrilling activities including skiing, hiking, and more.</p>
                    <a href="#" class="cta">Explore More</a>
                </div>
            </div>
            <div class="package">
                <img src="path/to/package3-image.jpg" alt="Package 3">
                <div class="package-content">
                    <h3>Family Fun</h3>
                    <p>Perfect for families with activities for all ages.</p>
                    <a href="#" class="cta">Learn More</a>
                </div>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Vuokatti Villas. All Rights Reserved.</p>
    </footer>
</body>
</html>
