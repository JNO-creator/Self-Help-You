# Kotisivu
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homepage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
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
body, html {
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: Arial, sans-serif;
}

.container {
    display: flex;
    flex-wrap: wrap;
    width: 80%;
    height: 80%;
}

.box {
    flex: 1 1 50%;
    height: 50%;
    position: relative;
    background-size: cover;
    background-position: center;
}

#meista {
    background-image: url('images/meista.jpg');
}

#yritys {
    background-image: url('images/yritys.jpg');
}

#palvelut {
    background-image: url('images/palvelut.jpg');
}

#koulutus {
    background-image: url('images/koulutus.jpg');
}

.box-content {
    position: absolute;
    bottom: 20px;
    left: 20px;
    color: white;
    background-color: rgba(0, 0, 0, 0.5);
    padding: 10px;
    border-radius: 5px;
}

h2 {
    margin: 0;
}
