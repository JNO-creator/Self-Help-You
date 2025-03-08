<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Self-Help-You</title>
    <title>Responsive Top Navigation</title>
    <style>
        /* Reset default margin and padding */
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        /* Styling the navigation bar */
        .navbar {
            color: #0e194d;
            overflow: hidden; /* Ensures the content is contained within the navbar */
            text-align: center; /* Centers the links */
        }

        /* Styling each link inside the navbar */
        .navbar a {
            display: inline-block; /* Display links horizontally */
            padding: 14px 20px; /* Padding inside each link */
            text-decoration: none; /* Removes underline from links */
            color: white; /* White text color */
            font-size: 18px; /* Font size for the links */
            transition: background-color 0.3s ease; /* Smooth transition for background color change */
        }

        /* Hover effect for the links */
        .navbar a:hover {
            background-color: #ddd; /* Light background when hovered */
            color: black; /* Change text color when hovered */
        }

        /* Active link styling (when a link is clicked or active) */
        .navbar a.active {
            background-color: #4CAF50; /* Green background for active link */
            color: white; /* Keep text white for active link */
        }

        /* Hamburger menu icon styling */
        .navbar .icon {
            z-index: 2;
            display: none;
            font-size: 30px;
            color: white;
            padding: 14px 20px;
            background-color: #333;
            cursor: pointer;
        }

        /* For small screens (mobile devices) */
        @media screen and (max-width: 768px) {
            .navbar a {
                display: none; /* Hide the links by default */
                width: 100%; /* Make the links take full width */
                text-align: left; /* Align links to the left */
                padding: 14px; /* Adjust padding for the links */
            }

            .navbar a.active {
                background-color: #4CAF50;
                color: white;
            }

            /* Display the hamburger icon */
            .navbar .icon {
                display: block;
            }

            /* When the hamburger icon is clicked, show the links */
            .navbar.responsive a {
                display: block;
            }

            .navbar.responsive .icon {
                position: absolute;
                right: 0;
                top: 0;
            }
        }
    </style>
</head>
<body>
    <!-- Top Navigation Bar -->
    <div class="navbar" id="myNavbar">
        <a href="#home" class="active">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
        <!-- Hamburger Icon -->
        <a href="javascript:void(0);" class="icon" onclick="toggleNavbar()">&#9776;</a>
    </div>
    <script>
        /* Function to toggle the navbar on small screens */
        function toggleNavbar()
            var navbar = document.getElementById("myNavbar");
            navbar.classList.toggle("responsive");
    </script>
</body>
</html>

    <!-- Inline CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #0e194d;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #004AAD;
            color: #0e194d;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 3.5rem;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
      }
        section {
            padding: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #0368D6;
            color: #e1705d;
        }
        /* Box Container */
        .box-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 10px;
            margin-top: 40px;
        }

        /* Box Styles */
        .box {
            background-color: #38B6FF;
  box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3), -2px -2px 5px rgba(92, 97, 102, 0.5);
            border: 1px solid #ddd;
            border-radius: 8px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            text-align: center;
            padding: 20px;
            transition: transform 0.3s ease;
        }

        .box h3 {
            margin: 20px 0 10px;
            font-size: 1.2rem;
            color: white;
        }

        .box p {
            font-size: 1rem;
            color: white;
        }

        .box:hover {
            transform: translateY(-10px);
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Self-Help-You</h1>
        <h3> - osana pienyrityksien tulevaisuuden suunnittelua</h3>
    </header>

    <!-- Main Content -->
    <section>
        <div class="box-container">
            <!-- Meistä Box -->
            <div class="box">
                <h3>Meistä</h3>
                <p>Lue lisää meistä ja referensseistämme.</p>
                 <a href="/" class="cta-btn">Lue lisää</a>
            </div>

            <!-- Yritys Box -->
            <div class="box">
                <h3>Yritys</h3>
                <p>Tutustu yritykseemme sekä henkilökuntaamme.</p>
                <a href="/Meista" class="cta-btn">Tutustu</a>
            </div>

            <!-- Palvelut Box -->
            <div class="box">
                <h3>Palvelut</h3>
                <p>Kuinka voimme auttaa Sinua ja yritystoimintaasi tulevaisuuden suunnittelussa.</p>
                 <a href="/Meista" class="cta-btn">Katso tästä</a>
            </div>

            <!-- Koulutus Box -->
            <div class="box">
                <h3>Koulutus</h3>
                <p>Monipuoliset ja monimuotoiset koulutukset räätälöity Sinun yritystarpeillesi.</p>
                 <a href="/Meista" class="cta-btn">Lue lisää</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Self-Help-You. Kaikki oikeudet pidätetään.</p>
    </footer>
