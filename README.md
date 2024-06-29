<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FitLife Gym</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <script src="scripts.js" defer></script>
</head>
<body>
    <header>
        <div class="logo">
            <img src="C:\Users\sanga\OneDrive\Pictures\logo.png.jpg" alt="FitLife Gym Logo">
            <span>FitLife Gym</span>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#packages">Packages</a></li>
                <li><a href="#timings">Timings</a></li>
                <li><a href="#offers">Offers</a></li>
                <li><a href="#gears">Gym Gears</a></li>
                <li><a href="#nutrition">Nutrition & Supplements</a></li>
                <li><a href="#registration">Register</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="banner" id="home">
        <h1>Welcome to FitLife Gym</h1>
        <p>Your Fitness Journey Begins Here</p>
    </section>

    <section class="packages" id="packages">
        <h2>Our Packages</h2>
        <div class="package">
            <h3>Basic</h3>
            <p>$30/month</p>
            <ul>
                <li>Access to all equipment</li>
                <li>1 personal training session</li>
                <li>Free Wi-Fi</li>
            </ul>
        </div>
        <div class="package">
            <h3>Standard</h3>
            <p>$50/month</p>
            <ul>
                <li>All Basic features</li>
                <li>5 personal training sessions</li>
                <li>Access to group classes</li>
            </ul>
        </div>
        <div class="package">
            <h3>Premium</h3>
            <p>$80/month</p>
            <ul>
                <li>All Standard features</li>
                <li>Unlimited personal training</li>
                <li>Nutrition plan</li>
            </ul>
        </div>
    </section>

    <section class="timings" id="timings">
        <h2>Gym Timings</h2>
        <ul>
            <li>Monday - Friday: 6 AM - 10 PM</li>
            <li>Saturday: 8 AM - 8 PM</li>
            <li>Sunday: 10 AM - 6 PM</li>
        </ul>
    </section>

    <section class="offers" id="offers">
        <h2>Special Offers</h2>
        <p>Sign up now and get 20% off your first month!</p>
        <p>Refer a friend and get a free month!</p>
    </section>

    <section class="gears" id="gears">
        <h2>Gym Gears</h2>
        <ul>
            <li>Dumbbells</li>
            <li>Treadmills</li>
            <li>Exercise Bikes</li>
            <li>Kettlebells</li>
            <li>Yoga Mats</li>
        </ul>
    </section>

    <section class="nutrition" id="nutrition">
        <h2>Nutrition & Supplements</h2>
        <ul>
            <li>Protein Powders</li>
            <li>Vitamins</li>
            <li>Energy Bars</li>
            <li>Hydration Drinks</li>
        </ul>
    </section>

    <section class="registration" id="registration">
        <h2>Register Now</h2>
        <form id="registration-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="phone">Phone:</label>
            <input type="tel" id="phone" name="phone" required>
            
            <label for="package">Package:</label>
            <select id="package" name="package" required>
                <option value="basic">Basic</option>
                <option value="standard">Standard</option>
                <option value="premium">Premium</option>
            </select>
            
            <button type="submit">Register</button>
        </form>
        <div id="form-result"></div>
    </section>
<section class="hero">
    <div class="hero-content">
        <h1>Welcome to FitLife Gym</h1>
        <p>Your Fitness Journey Begins Here</p>
        <a href="#registration" class="cta-button">Join Now</a>
    </div>
</section>


    <footer>
        <p>© 2024 FitLife Gym. All rights reserved.</p>
        <ul class="social-media">
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">Instagram</a></li>
        </ul>
    </footer>
</body>
</html>
