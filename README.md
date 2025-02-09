# Valentine
Valentine site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Love</title>
    <style>
        body { text-align: center; background: pink; font-family: Arial, sans-serif; }
        h1 { color: red; font-size: 36px; margin-top: 100px; }
        .buttons a { padding: 15px 25px; font-size: 24px; text-decoration: none; border-radius: 5px; }
        .yes { background: red; color: white; }
        .no { background: gray; color: white; position: absolute; }
    </style>
    <script>
        function moveNoButton() {
            let x = Math.random() * (window.innerWidth - 100);
            let y = Math.random() * (window.innerHeight - 50);
            document.getElementById("noBtn").style.left = x + "px";
            document.getElementById("noBtn").style.top = y + "px";
        }
    </script>
</head>
<body>
    <h1>Will You Be My Valentine? 💖</h1>
    <div class="buttons">
        <a href="yes.html" class="yes">YES ❤️</a>
        <a href="#" id="noBtn" class="no" onmouseover="moveNoButton()">NO 💔</a>
    </div>
</body>
</html> 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yay! ❤️</title>
    <style>
        body { text-align: center; background: red; color: white; font-family: Arial; }
        h1 { font-size: 48px; }
        .heart { font-size: 100px; }
    </style>
</head>
<body>
    <h1>Yay! You Said Yes! ❤️</h1>
    <div class="heart">💘💞💖</div>
    <p>Happy Valentine's Day! 🎉</p>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yay! ❤️</title>
    <style>
        body { text-align: center; background: red; color: white; font-family: Arial; }
        h1 { font-size: 48px; }
        .heart { font-size: 100px; }
    </style>
</head>
<body>
    <h1>Yay! You Said Yes! ❤️</h1>
    <div class="heart">💘💞💖</div>
    <p>Happy Valentine's Day! 🎉</p>
</body>
</html>
