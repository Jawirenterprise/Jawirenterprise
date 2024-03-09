<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Expressing Love</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 20%;
        }
        #loveMessage {
            display: none;
            font-size: 1.5em;
            color: red;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Express Your Love</h1>
    <button onclick="showLoveMessage()">Click to Express Love</button>
    <p id="loveMessage">I love you more than anything!</p>

    <script>
        function showLoveMessage() {
            var loveMessage = document.getElementById("loveMessage");
            loveMessage.style.display = "block";
        }
    </script>
</body>
</html>
