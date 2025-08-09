<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mijn Muziekpagina</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .music-card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 300px;
            padding: 20px;
            text-align: center;
        }
        .music-card img {
            max-width: 100%;
            border-radius: 10px;
        }
        .music-card audio {
            width: 100%;
            margin-top: 10px;
        }
        .music-card p {
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <h1>Mijn Muziekpagina</h1>
    <div class="container">
        <div class="music-card">
            <img src="afbeelding1.jpg" alt="Afbeelding 1">
            <h2>Nummer 1</h2>
            <audio controls>
                <source src="muziek1.mp3" type="audio/mpeg">
                Je browser ondersteunt het audio-element niet.
            </audio>
            <p>Dit is een toelichting bij nummer 1. Hier kun je meer informatie geven over het nummer.</p>
        </div>
        <div class="music-card">
            <img src="afbeelding2.jpg" alt="Afbeelding 2">
            <h2>Nummer 2</h2>
            <audio controls>
                <source src="muziek2.mp3" type="audio/mpeg">
                Je browser ondersteunt het audio-element niet.
            </audio>
            <p>Dit is een toelichting bij nummer 2. Hier kun je meer informatie geven over het nummer.</p>
        </div>
        <!-- Voeg meer muziekkaarten toe zoals hierboven -->
    </div>
</body>
</html>



> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDM1NTU2MDkzXX0=
-->