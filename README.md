<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minecraft Fanseite</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, nav, section, footer {
            padding: 20px;
        }
        header {
            background-color: #444;
            color: #fff;
            text-align: center;
        }
        nav {
            background-color: #555;
            color: #fff;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        #news {
            background-color: #d1c4e9;
            color: #000;
        }
        #bilder {
            background-color: #bbdefb;
            color: #000;
        }
        #info {
            background-color: #c8e6c9;
            color: #000;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .bilder-gallery img {
            max-width: 100%;
            height: auto;
            margin: 10px 0;
        }
        .gif-gallery img {
            max-width: 100%;
            height: auto;
            margin: 10px 0;
        }
        .news-post {
            margin-bottom: 20px;
        }
        footer {
            background-color: #444;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Minecraft Fanseite</h1>
    </header>
    <nav>
        <a href="#news">News</a>
        <a href="#bilder">Bilder & Gifs</a>
        <a href="#info">Infos</a>
    </nav>
    <section id="news" class="container">
        <h2>Neuigkeiten über Minecraft</h2>
        <div class="news-post">
            <h3>Update 1.20 ist da!</h3>
            <p>Das neue Update bringt viele spannende Features wie neue Biome, Mobs und mehr.</p>
        </div>
        <div class="news-post">
            <h3>Minecraft Live 2024</h3>
            <p>Erlebe die aufregendsten Ankündigungen und Neuigkeiten direkt von den Entwicklern.</p>
        </div>
    </section>
    <section id="bilder" class="container">
        <h2>Bilder & Gifs</h2>
        <div class="bilder-gallery">
            <h3>Bilder</h3>
            <img src="https://example.com/image1.jpg" alt="Minecraft Bild 1">
            <img src="https://example.com/image2.jpg" alt="Minecraft Bild 2">
            <img src="https://example.com/image3.jpg" alt="Minecraft Bild 3">
        </div>
        <div class="gif-gallery">
            <h3>Gifs</h3>
            <img src="https://example.com/animation1.gif" alt="Minecraft Gif 1">
            <img src="https://example.com/animation2.gif" alt="Minecraft Gif 2">
        </div>
    </section>
    <section id="info" class="container">
        <h2>Infos über Minecraft</h2>
        <p>Minecraft ist ein Sandbox-Videospiel, das von Mojang Studios entwickelt wurde. Das Spiel wurde von Markus "Notch" Persson in der Programmiersprache Java erstellt. Nach mehreren frühen Testversionen wurde es als bezahlte öffentliche Alpha für PCs im Jahr 2009 veröffentlicht, bevor es im November 2011 offiziell veröffentlicht wurde, mit Jens Bergensten, der die Entwicklung übernahm.</p>
        <p>In Minecraft erkunden die Spieler eine blockartige, prozedural generierte 3D-Welt mit unendlichen Geländetypen, entdecken und extrahieren Rohstoffe, fertigen Werkzeuge und Gegenstände und bauen Strukturen oder Erdwerke. Je nach Spielmodus können die Spieler auch gegen computergesteuerte "Mobs" kämpfen und mit anderen Spielern auf der Welt kooperieren oder gegeneinander antreten.</p>
    </section>
    <footer>
        <p>&copy; 2024 Minecraft Fanseite</p>
    </footer>
</body>
</html>
