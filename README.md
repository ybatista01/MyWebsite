<!-- 
Author: Yanelis Batista
Date: 10/18/2024
File Name: Index
Description: The index is the home page of my website. It is a website for a party venue.
-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home | The Northside Venue</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        header img {
            height: 60px; /* Adjust logo height */
            margin-right: 15px; /* Space between logo and text */
        }
        nav {
            background-color: #444;
            text-align: center;
            padding: 10px 0;
        }
        nav ul {
            list-style-type: none; /* Removes bullets from list */
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline; /* Display list items inline */
            margin-right: 20px; /* Adds space between menu items */
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }
        nav ul li a:hover {
            text-decoration: underline;
        }
        .main-content {
            padding: 30px;
            background-color: white;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            position: absolute;
            width: 100%;
        }
    </style>
</head>
<body>

    <!-- Header with Logo and Title -->
    <header>
        <img src="TNVII.jpg" alt="The Northside Venue Logo">
        <h1>The Northside Venue</h1>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About Us</a></li>
            <li><a href="events.html">Events</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <!-- Main Content -->
    <div class="main-content">
        <h2>Welcome to The Northside Venue</h2>
        <p>Discover the perfect space for your special events, weddings, conferences, and more.</p>
    </div>

    <nav>
        <ul>
            <li><a href="privacy.html">Privacy Policy</a></li>
            <li><a href="terms.html">Terms and Conditions</a></li>
        </ul>
    </nav>

    <!-- Footer -->
    <footer>
        <p>© 2024 The Northside Venue | All Rights Reserved</p>
    </footer>

</body>
</html>

