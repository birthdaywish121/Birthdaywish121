
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Riddhima 🎉</title>
    <style>
        body {
            background: linear-gradient(135deg, #ffb6c1, #ff69b4);
            /* Note: 'Poppins' font may not be available on all devices without linking it */
            font-family: sans-serif; 
            color: white;
            text-align: center;
            padding: 40px;
            margin: 0; /* Ensures no default margin */
            min-height: 100vh; /* Ensures background covers the whole viewport */
            display: flex; /* For centering the container */
            align-items: center; /* For centering the container */
            justify-content: center; /* For centering the container */
        }

        .container {
            background: rgba(255, 255, 255, 0.2);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.2);
            max-width: 600px;
            width: 90%;
            margin: auto;
        }

        h1 {
            font-size: 2.5em;
        }
        
        h3 {
             margin-top: 0;
             margin-bottom: 20px;
        }

        .cake {
            width: 200px;
            margin: 20px 0;
            animation: float 2s infinite ease-in-out;
        }

        .message {
            font-size: 1.2em;
            margin-bottom: 20px;
        }

        button {
            background-color: white;
            color: #ff69b4;
            border: none;
            padding: 12px 20px;
            font-size: 1em;
            border-radius: 8px;
            cursor: pointer;
            transition: 0.3s;
            font-weight: bold;
        }

        button:hover {
            background-color: #ffe6f0;
            transform: scale(1.05);
        }

        .hidden {
            display: none;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🎂 Happy Birthday, Riddhima! 🎉</h1>
        <h3>Wishing you a day filled with love, laughter, and joy!</h3>
        <img src="https://i.imgur.com/KxQ9NwG.png" alt="Birthday Cake" class="cake">
        <p class="message">
            You make everyone’s life brighter with your smile!  
            Have a magical birthday full of fun and surprises 💖
        </p>
        <button onclick="showSurprise()">Click for a Surprise 🎁</button>
        <div id="surprise" class="hidden">
            <h2>🎈 You are Amazing, Riddhima! 🎈</h2>
            <p>May your dreams come true today and always 🌟</p>
        </div>
    </div>
    <script>
        function showSurprise() {
            // This function toggles the 'hidden' class to show/hide the surprise
            document.getElementById("surprise").classList.toggle("hidden");
        }
    </script>
</body>
</html>
