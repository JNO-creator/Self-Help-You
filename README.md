<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Self-Help-You</title>

    <!-- Inline CSS -->
    <style>
        body {
            font-family: TT Interphases;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #24292f;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        section {
            padding: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #24292f;
            color: white;
        }

        /* Box Container */
        .box-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }

        /* Box Styles */
        .box {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 20px;
            transition: transform 0.3s ease;
        }

        .box img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }

        .box h3 {
            margin: 20px 0 10px;
            font-size: 1.5rem;
            color: #24292f;
        }

        .box p {
            font-size: 1rem;
            color: #666;
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
    </header>

    <!-- Main Content -->
    <section>
        <div class="box-container">
            <!-- Meistä Box -->
            <div class="box">
                <img src="https://github.com/user-attachments/assets/d1117b4d-31ca-432f-89c1-76b7eadd4e92/400x200" alt="Meistä">
                <h3>Meistä</h3>
                <p>Tutustu tästä tarinaamme ja referensseihin palveluistamme.</p>
            </div>

            <!-- Yritys Box -->
            <div class="box">
                <img src="https://via.placeholder.com/400x200" alt="Yritys">
                <h3>Yritys</h3>
                <p>Discover what we do and the services we offer.</p>
            </div>

            <!-- Palvelut Box -->
            <div class="box">
                <img src="https://via.placeholder.com/400x200" alt="Palvelut">
                <h3>Palvelut</h3>
                <p>Explore the variety of services we provide to our clients.</p>
            </div>

            <!-- Koulutus Box -->
            <div class="box">
                <img src="https://via.placeholder.com/400x200" alt="Koulutus">
                <h3>Koulutus</h3>
                <p>Check out the training programs we offer to help you grow.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Self-help-you. Kaikki oikeudet pidätetään.</p>
    </footer>

</body>
</html>
