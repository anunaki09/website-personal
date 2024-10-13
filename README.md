<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="icariya" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0e68c;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #ff6347;
            font-size: 3em;
        }
        .video-container {
            margin: 20px 0;
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
            max-width: 100%;
            background: #000;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        .message {
            font-size: 1.2em;
            margin: 20px 0;
            line-height: 1.6;
        }
        .footer {
            margin-top: 30px;
            font-size: 0.9em;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Birthday, [Name]!</h1>
        
        <div class="video-container">
            <iframe src="kucing.mp4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        
        <div class="message">
            <p>Selamat ulang tahun yang ke-[umur]! Semoga hari ini penuh dengan kebahagiaan dan cinta.</p>
            <p>Semoga semua harapan dan impianmu menjadi kenyataan. Tetap sehat, bahagia, dan penuh semangat selalu!</p>
        </div>

        <div class="footer">
            <p>Best Wishes, [Your Name]</p>
        </div>
    </div>
</body>
</html> p
