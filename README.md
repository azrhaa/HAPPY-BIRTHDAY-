# HAPPY-BIRTHDAY-
yeah
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Ulang Tahun!</title>
    <style>
        body {
            background-color: #ffe6f0;
            text-align: center;
            font-family: 'Comic Sans MS', cursive, sans-serif;
            padding-top: 50px;
        }

        h1 {
            color: #ff3399;
            font-size: 48px;
            margin-bottom: 20px;
        }

        .cupcake {
            position: relative;
            width: 150px;
            height: 200px;
            margin: 0 auto;
        }

        .cake-bottom {
            width: 100px;
            height: 80px;
            background: #cc6699;
            position: absolute;
            bottom: 0;
            left: 25px;
            border-radius: 10px 10px 20px 20px;
        }

        .cake-top {
            width: 150px;
            height: 100px;
            background: pink;
            position: absolute;
            top: 20px;
            left: 0;
            border-radius: 75px 75px 0 0;
        }

        .candle {
            width: 10px;
            height: 40px;
            background: #ffff66;
            position: absolute;
            top: -30px;
            left: 70px;
            border-radius: 5px;
        }

        .flame {
            width: 15px;
            height: 20px;
            background: orange;
            position: absolute;
            top: -40px;
            left: 67px;
            border-radius: 50% 50% 50% 50%;
            animation: flicker 1s infinite alternate;
        }

        @keyframes flicker {
            from { transform: scale(1); opacity: 1; }
            to { transform: scale(1.2); opacity: 0.8; }
        }
    </style>
</head>
<body>
    <h1>Selamat Ulang Tahun!</h1>
    <div class="cupcake">
        <div class="cake-top"></div>
        <div class="cake-bottom"></div>
        <div class="candle"></div>
        <div class="flame"></div>
    </div>
</body>
</html>
