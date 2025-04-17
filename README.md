<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            background: #000;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .jumping-text {
            font-size: 50px;
            font-weight: bold;
            animation: jump 1s infinite, colorChange 3s infinite;
            text-shadow: 0 0 10px rgba(255,0,0,0.5);
        }

        @keyframes jump {
            0%   { transform: translateY(0) scale(1); }
            25%  { transform: translateY(-30px) scale(1.2); }
            50%  { transform: translateY(0) scale(0.9); }
            75%  { transform: translateY(-15px) scale(1.1); }
            100% { transform: translateY(0) scale(1); }
        }

        @keyframes colorChange {
            0%   { color: #ff0000; }
            25%  { color: #00ff00; }
            50%  { color: #0000ff; }
            75%  { color: #ff00ff; }
            100% { color: #ff0000; }
        }
    </style>
</head>
<body>
    <div class="jumping-text">梁师图南通第一渣男</div>
</body>
</html>
