football-game/
├── index.html
├── about.html
├── download.html
├── teams.html
├── tournaments.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── app.js
├── images/
├── assets/
└── README.md
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ultimate Football</title>

    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
    <h1>Ultimate Football</h1>
</header>

<main>

<button id="playButton">
Play Match
</button>

<canvas id="gameCanvas" width="1200" height="700"></canvas>

</main>

<script src="js/game.js"></script>

</body>
</html>
