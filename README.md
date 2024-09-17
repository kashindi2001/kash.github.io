<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Real Estate Wholesaling</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header Section -->
    <header class="header">
        <div class="container">
            <h1>Sell Your Home Fast. No Fees. No Hassle.</h1>
            <p>We buy homes in any condition. Get a fair cash offer and close in as little as 7 days.</p>
            <a href="#get-offer" class="cta-btn">Get My Cash Offer</a>
        </div>
    </header>

    <!-- How It Works Section -->
    <section class="how-it-works" id="how-it-works">
        <div class="container">
            <h2>Our Simple 3-Step Process</h2>
            <div class="steps">
                <div class="step">
                    <h3>Step 1: Contact Us</h3>
                    <p>Fill out our quick form or call us, and we’ll ask for some basic details about your property.</p>
                </div>
                <div class="step">
                    <h3>Step 2: Get a Cash Offer</h3>
                    <p>We’ll review your property and make you a no-obligation cash offer.</p>
                </div>
                <div class="step">
                    <h3>Step 3: Close on Your Terms</h3>
                    <p>Pick your closing date, and we’ll handle all the paperwork. No repairs or fees required!</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section class="about-us" id="about-us">
        <div class="container">
            <h2>Who We Are</h2>
            <p>At [Your Company Name], we specialize in providing fast, stress-free home-selling solutions. We buy homes as-is, with no repairs or fees required.</p>
            <p>Founded by real estate investor Abednego Kashindi, [Your Company Name] has helped many homeowners sell their homes quickly and easily.</p>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="services-list">
                <div class="service">
                    <h3>Cash Offers on Homes</h3>
                    <p>We make fair, all-cash offers for homes in any condition.</p>
                </div>
                <div class="service">
                    <h3>Fast Closings</h3>
                    <p>We can close on your property in as little as 7-14 days.</p>
                </div>
                <div class="service">
                    <h3>No Repairs Needed</h3>
                    <p>We buy homes as-is, no need for repairs or cleaning.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Get a Cash Offer Section -->
    <section class="get-offer" id="get-offer">
        <div class="container">
            <h2>Get Your Cash Offer Today!</h2>
            <form action="submit_offer.php" method="POST">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>

                <label for="address">Property Address</label>
                <input type="text" id="address" name="address" required>

                <label for="phone">Phone Number</label>
                <input type="tel" id="phone" name="phone" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="condition">Property Condition</label>
                <select id="condition" name="condition">
                    <option value="excellent">Excellent</option>
                    <option value="good">Good</option>
                    <option value="fair">Fair</option>
                    <option value="poor">Poor</option>
                </select>

                <button type="submit" class="cta-btn">Submit for a Free Cash Offer</button>
            </form>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 [Your Company Name]. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
