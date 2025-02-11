<head>
    <link rel="stylesheet" href="assets/index.css">
    <link rel="icon" type="image/x-icon" href="https://play-lh.googleusercontent.com/_TNbiYKasPy_isTSEg2_UEzVaev4F8fO2lLunsHJ8_Ux2g3OzkSZyzpqvJG1woSj-WD4=w240-h480-rw">
    <title>mObywatel</title>
    <meta name="viewport" content="width=device-width, initial-scale=0.8, user-scalable=no">
</head>
<body>
    <img src="https://play-lh.googleusercontent.com/_TNbiYKasPy_isTSEg2_UEzVaev4F8fO2lLunsHJ8_Ux2g3OzkSZyzpqvJG1woSj-WD4" class="logo">
    <p class="logo_text">Obywatel 2.0</p>

    <div class="guide_holder">
        <div class="top_holder">
            <p class="guide_title">Instrukcja</p>
            <img class="arrow" src="https://i.imgur.com/aUZmu0W.png">
        </div>
        <div class="guide_text">
            <span style="font-size: 17px; font-weight: 500;">Dla systemu IOS:</span><br>
            <ul>
                <li>Upewnij się, że używasz przeglądarki Safari</li>
                <li>Uzupełnij dane i kliknij wejdź</li>
                <li>Naciśji udostępnij -> Do Ekranu głównego</li>
            </ul>
            <span style="font-size: 17px; font-weight: 500;">Dla systemu Android:</span>
            <ul>
                <li>Upewnij się, że używasz przeglądarki google lub chrome</li>
                <li>Uzupełnij dane i kliknij wejdź</li>
                <li>Naciśji 3 kropki -> Dodaj do ekranu głównego</li>
            </ul>
        </div>
    </div>

    <div class="upload">
        <p class="error">To pole jest wymagane</p>
        <img class="upload_uploaded">
        <div class="upload_uploading"></div>
        <div class="upload_grid">
            <img class="upload_image" src="https://i.imgur.com/vwIQErh.png">
            <p class="upload_text">Dodaj zdjęcie</p>
        </div>
    </div>

    <div class="input_holder">
        <input type="text" id="name" class="input" placeholder="">
        <span class="placeholder">Imię (imiona)</span>
        <p class="error">To pole jest wymagane</p>
    </div>
 
    <div class="input_holder">
        <input type="text" id="surname" class="input" placeholder="">
        <span class="placeholder">Nazwisko</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="sex" class="input" placeholder="">
        <span class="placeholder">Płeć</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="nationality" class="input" placeholder="">
        <span class="placeholder">Obywatelstwo</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="birthday" class="input" placeholder="">
        <span class="placeholder">Data urodzenia (DD.MM.YYYY)</span>
        <p class="error">To pole jest wymagane</p>
    </div>
  
    <div class="input_holder">
        <input type="text" id="Kod" class="input" placeholder="">
        <span class="placeholder">PESEL</span>
        <p class="error">To pole jest wymagane</p>
    </div>
   
    <div class="input_holder">
        <input type="text" id="familyName" class="input" placeholder="">
        <span class="placeholder">Nazwisko rodowe</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="fathersFamilyName" class="input" placeholder="">
        <span class="placeholder">Nazwisko rodowe ojca</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="mothersFamilyName" class="input" placeholder="">
        <span class="placeholder">Nazwisko rodowe matki</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <p class="subtext">Miejsce zamieszkania</p>

    <div class="input_holder">
        <input type="text" id="birthPlace" class="input" placeholder="">
        <span class="placeholder">Miejsce urodzenia</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="countryOfBirth" class="input" placeholder="">
        <span class="placeholder">Kraj urodzenia</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="adress1" class="input" placeholder="">
        <span class="placeholder">Ulica i numer domu</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="adress2" class="input" placeholder="">
        <span class="placeholder">Kod pocztowy</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="city" class="input" placeholder="">
        <span class="placeholder">Miasto</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <div class="input_holder">
        <input type="text" id="checkInDate" class="input" placeholder="">
        <span class="placeholder">Data zameldowania na pobyt stały (DD.MM.YYYY)</span>
        <p class="error">To pole jest wymagane</p>
    </div>

    <a class="go">wejdź</a>

    <div class="discord" onclick="location.href = 'https://discord.gg/CSQcXcQTsq'">
        <div class="inner_grid">
            <img class="discord_image" src="https://i.imgur.com/7fQLd9v.png">
            <p class="discord_text">Dołącz na naszego discorda</p>
        </div>
    </div>

    <script src="index.js"></script>
</body>
