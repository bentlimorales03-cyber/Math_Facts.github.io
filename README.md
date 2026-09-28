# Math_Facts.github.io<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Math Fact Practice Portal</title>
    <style>
        /* The main background has been changed to red */
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: #8B0000; color: #ffffff; margin: 0; padding: 0; text-align: center; }
        /* The top banner bar background is a matching dark red */
        .navbar { background: #5c0000; padding: 20px; box-shadow: 0 4px 15px rgba(0,0,0,0.5); position: sticky; top: 0; z-index: 100; }
        /* The main title text color has been changed to a vibrant blue */
        h1 { margin: 0 0 15px 0; font-size: 24px; color: #00bfff; text-shadow: 0 0 10px rgba(0,191,255,0.6); }
        .menu { display: flex; justify-content: center; flex-wrap: wrap; gap: 10px; max-width: 800px; margin: 0 auto; }
        /* The buttons are styled to match the new look */
        .menu button { background: #3a0000; color: #fff; border: 2px solid #5c0000; padding: 12px 24px; font-size: 15px; font-weight: bold; cursor: pointer; border-radius: 6px; transition: all 0.2s ease; min-width: 130px; }
        /* When you hover over a button, it turns blue */
        .menu button:hover { background: #00bfff; color: #121212; border-color: #00bfff; box-shadow: 0 0 15px rgba(0,191,255,0.7); transform: translateY(-2px); }
        .game-area { max-width: 960px; margin: 30px auto; padding: 0 15px; }
        .iframe-container { position: relative; width: 100%; height: 0; padding-bottom: 56.25%; background: #000; border: 4px solid #3a0000; border-radius: 12px; overflow: hidden; box-shadow: 0 10px 30px rgba(0,0,0,0.7); }
        .iframe-container iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none; }
    </style>
</head>
<body>

    <div class="navbar">
        <h1>MATH FACT PORTAL</h1>
        <div class="menu">
            <button onclick="playGame('https://y8.com')">Slope</button>
            <button onclick="playGame('https://retrobowl.me')">Retro Bowl</button>
            <button onclick="playGame('https://eaglercraft.ru')">Minecraft</button>
            <button onclick="playGame('https://bkcore.com')">HexGL Racing</button>
            <button onclick="playGame('https://tetris.com')">Tetris</button>
            <button onclick="playGame('https://dashnet.org')">Cookie Clicker</button>
        </div>
    </div>

    <div class="game-area">
        <div class="iframe-container">
            <iframe id="arcadeFrame" src="https://y8.com" allowfullscreen></iframe>
        </div>
    </div>

    <script>
        function playGame(gameUrl) {
            document.getElementById('arcadeFrame').src = gameUrl;
        }
    </script>

</body>
</html>
