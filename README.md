<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Amazyng Enterprise</title>
    <style>
        body {
            font-family: Times New Roman, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #663399; /* Pewter background */
            color: #333; /* Dark text for contrast */
        }

        header {
            background-color: #FFD700; /* Bright yellow header */
            color: #333; /* Dark text to contrast the yellow */
            padding: 20px;
            text-align: center;
            position: relative; /* For positioning the cars */
        }

        header h1 {
            margin: 0;
            position: relative;
            z-index: 1; /* So the cars stay behind the text */
        }

        .car-left, .car-right {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            width: 105px; /* Adjust size as necessary */
            height: auto;
        }

        .car-left {
            left: 70px;
        }

        .car-right {
            right: 70px;
        }

        .container {
            width: 90%;
            margin: 0 auto;
            padding: 20px;
        }

        .about, .services, .contact {
            background-color: #EEE8AA; /* Pewter color for sections */
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #000000; /* Black section titles */
            margin-bottom: 10px;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            padding: 5px 0;
        }

        .contact-info {
            font-size: 1.2em;
            margin-top: 10px;
        }

        footer {
            background-color: #333; /* Dark grey footer */
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .vehicle-image {
            width: 100%;
            max-width: 400px;
            margin: 20px auto;
            display: block;
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <header>
        <img src="Schell Logo.png" alt="Yellow Car Left and Right" class="car-left car-right">
        <h1>Amazyng Enterprise</h1>
        <p>Your Reliable Transportation Solution</p>
        <img src="Schell Logo.png" alt="Yellow Car Left and Right" class="car-right">
    </header>

    <div class="container">
        <section class="about">
            <h2>About Us</h2>
            <p> Amazyng Enterprise LLC is dedicated to providing safe and dependable transportation for elderly individuals and others who need transport assistance. Our services include trips to doctor appointments, daycare, shopping, errands, and more. We ensure a stress-free transportation experience, whether you're booking for today or scheduling in advance.</p>
        </section>

        <section class="services">
            <h2>Our Transportation Services</h2>
            <ul style="list-style-type: disc; padding-left: 20px;">
                <li>Doctor's Appointments</li>
                <li>Errands</li>
                <li>Shopping</li>
                <li>School</li>
                <li>Daycare</li>
                <li>Airport Transfers</li>
                <li>Senior Citizens Transportation</li>
            </ul>
        </section>

        <img src="Yellow Whips.png" alt="Our Vehicles" class="vehicle-image">

        <section class="contact">
            <h2>Contact Us</h2>
            <p>Whether you need a ride immediately or want to schedule in advance, you can book through our website or give us a call!</p>
            <div class="contact-info">
                <p><strong>Phone:</strong> (708) 955-2134</p>
                <p><strong>Email:</strong> beamazyng@gmail.com</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Amazyng Enterprise LLC. All rights reserved.</p>
    </footer>

</body>
</html>
