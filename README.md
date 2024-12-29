<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Message</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
        }
        .message {
            text-align: center;
        }
        .message h1 {
            font-size: 4rem;
            animation: colorChange 3s infinite;
        }
        .message p {
            font-size: 2rem;
            color: #ff6347;
        }
        @keyframes colorChange {
            0% { color: #ff4500; }
            25% { color: #ff6347; }
            50% { color: #ffd700; }
            75% { color: #32cd32; }
            100% { color: #1e90ff; }
        }
    </style>
</head>
<body>
    <div class="message">
        <h1>I LOVE YOU</h1>
        <p>Do You Love ME</p>
    </div>
</body>
</html>
