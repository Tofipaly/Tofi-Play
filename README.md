<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع مسلسلات</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            direction: rtl;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        .showcase {
            min-height: 400px;
            background: url('https://www.tuktukcima.com/wp-content/uploads/2024/05/MV5BMzkwODZjYjAtZDQ0Yy00YWM0LThmZTMtM2FiMzE1OWU2OGViXkEyXkFqcGdeQXVyMjQzNzIzMTA@.jpg_V1_SX700.jpg') no-repeat 0 -400px;
            text-align: center;
            color: #fff;
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .showcase p {
            font-size: 20px;
        }
        section {
            padding: 20px;
            margin: 20px 0;
            background: #fff;
        }
        .box {
            width: 30%;
            float: left;
            margin: 1.66%;
            background: #fff;
            border: 1px solid #ccc;
            border-radius: 5px;
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        .box:hover {
            transform: scale(1.05);
        }
        .box img {
            width: 100%;
        }
        .box h3 {
            text-align: center;
            padding: 10px;
            background: #333;
            color: #fff;
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>موقع المسلسلات</h1>
            <ul>
                <li><a href="#">الرئيسية</a></li>
                <li><a href="#">المسلسلات</a></li>
                <li><a href="#">الأفلام</a></li>
                <li><a href="#">التواصل</a></li>
            </ul>
        </div>
    </header>
    <section class="showcase">
        <div class="container">
            <h1>مرحبًا بكم في موقع المسلسلات</h1>
            <p>شاهد أحدث المسلسلات والأفلام هنا</p>
        </div>
    </section>
    <div class="container">
        <section>
            <div class="box">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2024/05/MV5BMzkwODZjYjAtZDQ0Yy00YWM0LThmZTMtM2FiMzE1OWU2OGViXkEyXkFqcGdeQXVyMjQzNzIzMTA@.jpg_V1_SX700.jpg" alt="مسلسل 1">
                <h3>مسلسل 1</h3>
            </div>
            <div class="box">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2024/05/MV5BMzkwODZjYjAtZDQ0Yy00YWM0LThmZTMtM2FiMzE1OWU2OGViXkEyXkFqcGdeQXVyMjQzNzIzMTA@.jpg_V1_SX700.jpg" alt="مسلسل 2">
                <h3>مسلسل 2</h3>
            </div>
            <div class="box">
                <img src="https://www.tuktukcima.com/wp-content/uploads/2024/05/MV5BMzkwODZjYjAtZDQ0Yy00YWM0LThmZTMtM2FiMzE1OWU2OGViXkEyXkFqcGdeQXVyMjQzNzIzMTA@.jpg_V1_SX700.jpg" alt="مسلسل 3">
                <h3>مسلسل 3</h3>
            </div>
        </section>
    </div>
</body>
</html>
