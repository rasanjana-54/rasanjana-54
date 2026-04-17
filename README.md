<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(to right, #ff7e5f, #feb47b);
            color: transparent;
            font-size: 48px;
            animation: gradient 3s ease infinite;
            overflow: hidden;
        }

        @keyframes gradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .text {
            animation: typewriter 4s steps(30, end);
            border-right: 3px solid;
            white-space: nowrap;
            overflow: hidden;
        }

        @keyframes typewriter {
            from { width: 0; }
            to { width: 100%; }
        }

        .wave {
            display: inline-block;
            animation: wave-animation 1s infinite;
        }

        @keyframes wave-animation {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
    </style>
    <title>Animated Greeting</title>
</head>
<body>
    <div class="text">
        <span class="wave">Hey, I'm Rasanjana</span>
    </div>
</body>
</html>