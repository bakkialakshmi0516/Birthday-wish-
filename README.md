# Birthday-wish
#Wish card
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Happiest Birthday Gorgeous</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            overflow: hidden;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #ff99cc, #ff66aa, #ff3385);
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            color: white;
        }
        h1 {
            font-size: 3rem;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.3);
            animation: pop 2s ease-in-out infinite;
        }
        @keyframes pop {
            0% { transform: scale(1); }
            50% { transform: scale(1.08); }
            100% { transform: scale(1); }
        }
        .confetti {
            position: absolute;
            width: 10px;
            height: 10px;
            background: yellow;
            top: -10px;
            animation: fall linear infinite;
        }
        @keyframes fall {
            to { transform: translateY(110vh) rotate(360deg); }
        }
    </style>
</head>
<body>

    <h1>🎉 Happiest Birthday Gorgeous 🎂</h1>

    <script>
        function createConfetti() {
