<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Medewerkersenquête: Verlofregeling</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .question {
            margin-bottom: 20px;
        }
        .question label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .submit-button {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            font-size: 16px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .submit-button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Medewerkersenquête: Verlofregeling</h1>
        <form action="" method="POST">
            <div class="question">
                <label>1. Hoe tevreden ben je momenteel over de verlofregeling?</label>
                <input type="radio" name="tevredenheid" value="Zeer tevreden"> Zeer tevreden<br>
                <input type="radio" name="tevredenheid" value="Tevreden"> Tevreden<br>
                <input type="radio" name="tevredenheid" value="Neutraal"> Neutraal<br>
                <input type="radio" name="tevredenheid" value="Ontevreden"> Ontevreden<br>
                <input type="radio" name="tevredenheid" value="Zeer ontevreden"> Zeer ontevreden
            </div>

            <div class="question">
                <label>2. Vind je dat de verlofregeling eerder moet starten?</label>
                <input type="radio" name="startdatum" value="Ja"> Ja<br>
                <input type="radio" name="startdatum" value="Nee"> Nee<br>
                <input type="radio" name="startdatum" value="Geen mening"> Geen mening
            </div>

            <div class="question">
                <label>3. Vind je dat de inleverdatum van het verlof later mag zijn?</label>
                <input type="radio" name="inleverdatum" value="Ja"> Ja<br>
                <input type="radio" name="inleverdatum" value="Nee"> Nee<br>
                <input type="radio" name="inleverdatum" value="Geen mening"> Geen mening
            </div>

            <div class="question">
                <label>4. Welke van de volgende aspecten vind jij het belangrijkst bij het bepalen van de verlofregeling?</label>
                <input type="checkbox" name="aspecten" value="Flexibiliteit"> Flexibiliteit voor medewerkers<br>
                <input type="checkbox" name="aspecten" value="Communicatie"> Tijdige communicatie over goedgekeurd verlof<br>
                <input type="checkbox" name="aspecten" value="Eerlijke verdeling"> Eerlijke verdeling van vakantiedagen<br>
                <input type="checkbox" name="aspecten" value="Wijziging"> Mogelijkheid om verlof te wijzigen na indiening<br>
                <input type="checkbox" name="aspecten" value="Anders"> Anders: <input type="text" name="anders" placeholder="Toelichting">
            </div>

            <div class="question">
                <label>5. Heb je suggesties of opmerkingen over de huidige verlofregeling?</label>
                <textarea name="opmerkingen" rows="4" cols="50" placeholder="Schrijf hier je opmerkingen..."></textarea>
            </div>

            <button type="submit" class="submit-button">Verstuur</button>
        </form>
    </div>
</body>
</html>
Kun je dit in een site zetten of uitleggen hoe het moet 
