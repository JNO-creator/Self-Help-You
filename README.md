<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <style>
        .box {
            border: 2px solid #000;
            padding: 20px;
            margin: 10px;
            background-color: #f0f0f0;
            border-radius: 10px;
        }
        .background-person {
            background-image: url('path-to-person-image.jpg');
            background-size: cover;
            background-position: center;
            width: 100%;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            font-size: 24px;
        }
    </style>
</head>
<body>
    <div class="background-person">
        Explaining to the audience
    </div>
    <div class="container">
        <div class="box" id="meista">
            <div class="box-content">
                <h2>Meistä</h2>
            </div>
        </div>
        <div class="box" id="yritys">
            <div class="box-content">
                <h2>Yritys</h2>
            </div>
        </div>
        <div class="box" id="palvelut">
            <div class="box-content">
                <h2>Palvelut</h2>
            </div>
        </div>
        <div class="box" id="koulutus">
            <div class="box-content">
                <h2>Koulutus</h2>
            </div>
        </div>
    </div>
</body>
</html>
