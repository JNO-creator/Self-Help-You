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
            background-color: #0368D6;
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
            background-color: #0368D6;
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
        <h3>- osana pienyrityksien tulevaisuuden suunnittelua</h3>
    </header>

    <!-- Main Content -->
    <section>
        <div class="box-container">
           <section>
    <div class="box-container">
        <!-- Meistä Box -->
        <div class="box">
            <h3>Meistä</h3>
            <p>Tutustu tästä tarinaamme ja referensseihin palveluistamme.</p>
        </div>
    </div>
</section>
            <!-- Yritys Box -->
          <div class="box">
            <h3>Yritys</h3>
            <p>Lue lisää yrityksestämme ja tutustu henkilökuntaamme.</p>
    </div>
            <!-- Palvelut Box -->
          <div class="box">
            <h3>Palvelut</h3>
            <p>Kuinka voimme olla avuksi Sinulle ja yrityksellesi.</p>
    </div>
            <!-- Koulutus Box -->
            <div class="box">
            <h3>Koulutus</h3>
            <p>Tutustu monimuotoisiin ja monipuolisiin koulutuksiimme.</p>
    </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Self-help-you. Kaikki oikeudet pidätetään.</p>
    </footer>

</body>
</html>
