<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gamer Rewards - Earn while you play</title>
    <style>
        :root {
            --bg-color: #0d1117;
            --card-bg: #161b22;
            --accent-color: #00ff7f; /* Vert style Freecash */
            --text-color: #ffffff;
            --secondary-text: #8b949e;
        }
        body { font-family: 'Inter', sans-serif; background-color: var(--bg-color); color: var(--text-color); margin: 0; padding: 20px; text-align: center; }
        .container { max-width: 800px; margin: auto; }
        .header { margin-bottom: 40px; }
        h1 { font-size: 2.5rem; margin-bottom: 10px; color: var(--accent-color); }
        .live-feed { background: rgba(0, 255, 127, 0.1); border: 1px solid var(--accent-color); padding: 10px; border-radius: 8px; margin-bottom: 30px; font-size: 0.9rem; }
        .offer-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .offer-card { background: var(--card-bg); padding: 20px; border-radius: 12px; border: 1px solid #30363d; transition: transform 0.2s; text-align: left; }
        .offer-card:hover { transform: translateY(-5px); border-color: var(--accent-color); }
        .offer-card h3 { margin: 0 0 10px 0; color: var(--accent-color); }
        .offer-card p { color: var(--secondary-text); font-size: 0.9rem; }
        .badge { display: inline-block; background: var(--accent-color); color: #000; padding: 4px 8px; border-radius: 4px; font-size: 0.8rem; font-weight: bold; margin-bottom: 10px; }
        .btn { display: block; width: 100%; padding: 12px; background: var(--accent-color); color: #000; text-decoration: none; border-radius: 6px; font-weight: bold; margin-top: 15px; text-align: center; }
        .footer { margin-top: 50px; color: var(--secondary-text); font-size: 0.8rem; }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>GAMER REWARDS HUB</h1>
            <p>Complete simple tasks and unlock premium gaming content.</p>
        </div>

        <div class="live-feed">
            🔥 <strong>Live:</strong> User <em>Saad_DZ</em> just claimed a <strong>$10 Gift Card</strong> (1 min ago)
        </div>

        <div class="offer-grid">
            <div class="offer-card">
                <span class="badge">POPULAR</span>
                <h3>Fortnite V-Bucks</h3>
                <p>Complete a quick verification to receive your 1000 V-Bucks pack.</p>
                <a href="#" class="btn">CLAIM NOW</a>
            </div>

            <div class="offer-card">
                <span class="badge">NEW</span>
                <h3>Free Fire Diamonds</h3>
                <p>Unlock the latest skins and diamonds for your account instantly.</p>
                <a href="#" class="btn">UNLOCK ACCESS</a>
            </div>

            <div class="offer-card">
                <span class="badge">HOT</span>
                <h3>PlayStation / Xbox</h3>
                <p>Get exclusive digital codes for your favorite console games.</p>
                <a href="#" class="btn">GET CODES</a>
            </div>
        </div>

        <div class="footer">
            © 2026 Gamer Rewards Platform. Not affiliated with Epic Games or Garena.
        </div>
    </div>
</body>
</html>
