<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Asya Öztürk | Portfolio</title>
    <style>
        /* Renk Paleti */
        :root {
            --bg-color: #1a1a24; /* Koyu Gece Mavisi/Antrasit */
            --text-main: #eef2f5; /* Buz Beyazı */
            --accent-color: #8a1c31; /* Bordo/Koyu Kırmızı */
            --text-muted: #9ba4b5; /* Gümüş Grisi */
        }
        
        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Ekranı ortalamak için */
        }

        .container {
            max-width: 600px;
            padding: 30px;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 5px;
        }

        h1 span {
            color: var(--accent-color); /* 'Asya' yazısını bordo yapar */
        }

        .subtitle {
            color: var(--text-muted);
            font-size: 1.2em;
            margin-bottom: 40px;
            letter-spacing: 1px;
        }

        .section {
            background-color: rgba(255, 255, 255, 0.03);
            padding: 20px 25px;
            border-radius: 8px;
            margin-bottom: 25px;
            border-left: 4px solid var(--accent-color);
        }

        .section h2 {
            margin-top: 0;
            font-size: 1.4em;
        }

        a {
            color: var(--accent-color);
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            color: #a8253e;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Hi, I'm <span>Asya.</span></h1>
        <p class="subtitle">International Relations Student & Data Analyst in Training</p>
        
        <div class="section">
            <h2>📊 Data & Skills</h2>
            <p>Successfully completed the <b>Introduction to SQL</b> track on DataCamp. Combining global politics with data analytics.</p>
            <p><i>Next stop: Data Literacy!</i></p>
        </div>

        <div class="section">
            <h2>🎬 Beyond the Desk</h2>
            <p>Analyzing global affairs by day, exploring Christopher Nolan & Jake Gyllenhaal mind-benders by night.</p>
            <p>Find me playing 1-minute bullet games on Chess.com: <a href="https://www.chess.com/member/asyawinchester" target="_blank">asyawinchester</a></p>
        </div>
    </div>

</body>
</html>
