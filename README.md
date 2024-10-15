<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Progetto 2B - Audio Guida</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        main {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .section {
            background-color: white;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .section h2 {
            margin-top: 0;
        }
        .audio-guide {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Progetto 2B</h1>
        <p>Audio Guida per la Mostra</p>
    </header>

    <main>
        <!-- Prima sezione dell'esposizione -->
        <div class="section">
            <h2>Esposizione 1: La Storia della Scuola</h2>
            <p>In questa sezione scopriamo la storia della nostra scuola, dalle sue origini fino ad oggi.</p>
            <div class="audio-guide">
                <audio controls>
                    <source src="https://drive.google.com/file/d/1OZffDoXMl2kIZE-afoBMKApKIj62uU24/view?usp=sharing" type="audio/mpeg">
                    Il tuo browser non supporta l'elemento audio.
                </audio>
                <span>Ascolta la spiegazione</span>
            </div>
        </div>

        <!-- Seconda sezione dell'esposizione -->
        <div class="section">
            <h2>Esposizione 2: Le Opere d'Arte degli Studenti</h2>
            <p>Questa sezione raccoglie le opere realizzate dagli studenti negli ultimi anni.</p>
            <div class="audio-guide">
                <audio controls>
                    <source src="audio/opere_studenti.mp3" type="audio/mpeg">
                    Il tuo browser non supporta l'elemento audio.
                </audio>
                <span>Ascolta la spiegazione</span>
            </div>
        </div>

        <!-- Altre sezioni -->
        <div class="section">
            <h2>Esposizione 3: Gli Antichi Documenti</h2>
            <p>Qui puoi esplorare alcuni documenti antichi appartenenti alla nostra storia.</p>
            <div class="audio-guide">
                <audio controls>
                    <source src="audio/antichi_documenti.mp3" type="audio/mpeg">
                    Il tuo browser non supporta l'elemento audio.
                </audio>
                <span>Ascolta la spiegazione</span>
            </div>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Museo Scolastico - Tutti i diritti riservati</p>
    </footer>

</body>
</html>

