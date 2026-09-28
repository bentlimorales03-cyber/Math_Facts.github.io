<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Math Fact Practice Portal</title>
    <style>
        /* Main background color changed to vibrant orange */
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: #FF4500; color: #ffffff; margin: 0; padding: 0; text-align: center; }
        /* Navigation banner set to a dark, contrasting orange-red */
        .navbar { background: #D32F2F; padding: 25px; box-shadow: 0 4px 15px rgba(0,0,0,0.3); position: sticky; top: 0; z-index: 100; }
        /* Main title text remains bright blue */
        h1 { margin: 0 0 20px 0; font-size: 28px; color: #00bfff; text-shadow: 0 0 10px rgba(0,191,255,0.6); }
        
        /* Grid system for your visual game cards */
        .game-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 20px; max-width: 900px; margin: 40px auto; padding: 0 20px; }
        
        /* Interactive image cards that open games in a new window */
        .game-card { background: #3a0000; border: 3px solid #ffffff; border-radius: 12px; overflow: hidden; text-decoration: none; color: white; display: flex; flex-direction: column; align-items: center; transition: all 0.2s ease; box-shadow: 0 6px 15px rgba(0,0,0,0.4); }
        .game-card:hover { transform: translateY(-5px); border-color: #00bfff; box-shadow: 0 10px 20px rgba(0,191,255,0.4); }
        
        /* Fixed-size image display for consistency */
        .game-card img { width: 100%; height: 120px; object-fit: cover; background: #000; }
        .game-card span { font-weight: bold; font-size: 16px; padding: 12px 5px; text-transform: uppercase; }
    </style>
</head>
<body>

    <div class="navbar">
        <h1>MATH FACT PORTAL</h1>
    </div>

    <!-- Clickable card layout. target="_blank" opens each game link securely in a new tab -->
    <div class="game-grid">
        <a class="game-card" href="https://github.io" target="_blank">
            <img src="https://unsplash.com" alt="Slope">
            <span>Slope</span>
        </a>

        <a class="game-card" href="https://retrobowl.me" target="_blank">
            <img src="https://unsplash.com" alt="Retro Bowl">
            <span>Retro Bowl</span>
        </a>

        <a class="game-card" href="https://eaglercraft.ru" target="_blank">
            <img src="https://unsplash.com" alt="Minecraft">
            <span>Minecraft</span>
        </a>

        <a class="game-card" href="https://bkcore.com" target="_blank">
            <img src="https://unsplash.com" alt="HexGL Racing">
            <span>HexGL Racing</span>
        </a>

        <a class="game-card" href="https://tetris.com" target="_blank">
            <img src="https://unsplash.com" alt="Tetris">
            <span>Tetris</span>
        </a>

        <a class="game-card" href="https://dashnet.org" target="_blank">
            <img src="https://unsplash.com" alt="Cookie Clicker">
            <span>Cookie Clicker</span>
        </a>
    </div>

</body>
</html>

