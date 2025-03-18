<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>عيد ميلاد سعيد ملكتي!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
            text-align: center;
            padding: 50px;
            margin: 0;
            overflow: hidden;
        }
        h1 {
            color: #fff;
            font-size: 3em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
            animation: glow 2s infinite alternate;
        }
        p {
            font-size: 1.5em;
            color: #fff;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3);
        }
        @keyframes glow {
            0% { text-shadow: 0 0 10px #fff, 0 0 20px #ff69b4, 0 0 30px #ff69b4; }
            100% { text-shadow: 0 0 20px #fff, 0 0 30px #ff1493, 0 0 40px #ff1493; }
        }
        .balloon {
            position: absolute;
            bottom: -10%;
            font-size: 2em;
            animation: float 6s ease-in infinite;
        }
        @keyframes float {
            0% { transform: translateY(0) rotate(0deg); }
            50% { transform: translateY(-100vh) rotate(360deg); }
            100% { transform: translateY(0) rotate(720deg); }
        }
        .confetti {
            position: absolute;
            width: 10px;
            height: 10px;
            background-color: #ff69b4;
            animation: confetti-fall 5s linear infinite;
        }
        @keyframes confetti-fall {
            0% { transform: translateY(-10vh) rotate(0deg); }
            100% { transform: translateY(100vh) rotate(720deg); }
        }
    </style>
</head>
<body>
    <h1>🎉🎂 كل عام ونتي بحير يا ملكة! 🎂🎉</h1>
    <p>أتمنى لك يومًا مليئًا بالفرح والحب والضحكات! 🌸✨</p>

    <!-- بالونات -->
    <div class="balloon" style="left: 10%; animation-delay: 0s;">🎈</div>
    <div class="balloon" style="left: 20%; animation-delay: 2s;">🎈</div>
    <div class="balloon" style="left: 30%; animation-delay: 4s;">🎈</div>
    <div class="balloon" style="left: 40%; animation-delay: 1s;">🎈</div>
    <div class="balloon" style="left: 50%; animation-delay: 3s;">🎈</div>
    <div class="balloon" style="left: 60%; animation-delay: 5s;">🎈</div>
    <div class="balloon" style="left: 70%; animation-delay: 2s;">🎈</div>
    <div class="balloon" style="left: 80%; animation-delay: 4s;">🎈</div>
    <div class="balloon" style="left: 90%; animation-delay: 1s;">🎈</div>

    <!-- كونفيتي -->
    <div class="confetti" style="left: 5%; animation-delay: 0s;"></div>
    <div class="confetti" style="left: 15%; animation-delay: 1s;"></div>
    <div class="confetti" style="left: 25%; animation-delay: 2s;"></div>
    <div class="confetti" style="left: 35%; animation-delay: 3s;"></div>
    <div class="confetti" style="left: 45%; animation-delay: 4s;"></div>
    <div class="confetti" style="left: 55%; animation-delay: 5s;"></div>
    <div class="confetti" style="left: 65%; animation-delay: 6s;"></div>
    <div class="confetti" style="left: 75%; animation-delay: 7s;"></div>
    <div class="confetti" style="left: 85%; animation-delay: 8s;"></div>
    <div class="confetti" style="left: 95%; animation-delay: 9s;"></div>
</body>
</html>
