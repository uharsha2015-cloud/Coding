<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harsha's Radio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f3f4f6;
        }
        .container {
            text-align: center;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #4a90e2;
        }
        p {
            color: #333;
        }
        audio {
            width: 100%;
            margin-top: 20px;
        }
        footer {
            margin-top: 20px;
            font-size: 0.9em;
            color: #666;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to Harsha's Radio</h1>
        <p>Enjoy live Telugu songs!</p>
        <!-- Replace the src URL with the actual streaming URL of Harsha's Radio -->
        <audio controls autoplay>
            <source src="https://your-radio-stream-url.com/stream" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        <footer>
            © 2025 Harsha's Radio
        </footer>
    </div>
</body>
</html>