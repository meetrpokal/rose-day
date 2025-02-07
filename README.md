<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Rose Day 🌹</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(135deg, #ff758c, #ff7eb3);
            color: white;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        .container {
            background: rgba(255, 255, 255, 0.2);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            width: 90%;
            max-width: 400px;
        }
        button {
            padding: 10px 15px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            margin: 10px;
            cursor: pointer;
            color: white;
        }
        .yes-btn { background: #28a745; }
        .no-btn { background: #007bff; }
        button:hover {
            opacity: 0.8;
        }
        #message {
            margin-top: 15px;
            font-size: 18px;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>🌹 Happy Rose Day! 🌹</h2>
        <p>Are you single?</p>
        <button class="yes-btn" onclick="wishSingle()">Yes</button>
        <button class="no-btn" onclick="wishTaken()">No</button>
        <p id="message"></p>
    </div>

    <script>
        function wishSingle() {
            document.getElementById("message").innerHTML = "🌹 Roses are red, violets are blue,<br> You're single and awesome too! 💖";
        }
        function wishTaken() {
            document.getElementById("message").innerHTML = "💑 Enjoy your Rose Day with your special one!";
        }
    </script>

</body>
</html>

