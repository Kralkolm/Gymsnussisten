<!DOCTYPE html>
<html>
    <head>
        <meta charset = "UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href ="style.css" rel = "stylesheet">
        <title> Hemsida</title>

        <link href="https://fonts.googleapis.com/css2?family=Inter:wght@600&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Ramabhadra&display=swap" rel="stylesheet">

    </head>

    <body>
        <header>
            <div class = "Rubrik"> 

                <a id="GymSnussisten" onclick="changeText()" href = "index.html"> GymSnussisten</a>

                <input type= "search" id = "site-search" name = "q"placeholder="Search">

                <div id="account_bag">

                    <a href="Acoount.html" id = "account">Account </a>


                    <div class = "Bag">

                        <a><img src="Bilder/Bag.png"></a>
                        <p>Bag</p>
                        <a><img src="Bilder/Hamburger.png" id = "Ham_Menu"></a>
                    </div>
                </div>
            </div>
                e
          
            <ul class="Products">
                <li><a href  ="Pre-Snus.html?product=preSnus">Pre-Snus</a></li>
                <li><a href = "Pre-Snus.html?product=gainer">Meth gainer</a></li>
                <li><a href = "Pre-Snus.html?product=creatine">Crystal Cratine</a></li>
                <li><a href = "Pre-Snus.html?product=shrooms">Keto shrooms</a></li>
                <li><a href = "Pre-Snus.html?product=tren">Tren</a></li>
            </ul>
        

            <ul class="Leverans">
                <li>Leverans från EU</li>
                <li>5-7 dagar leverans</li>
                <li>Fri frakt över 33kr</li>
            </ul>
         
        </header>

        <main>

            <section id = "Gymsnussist_bild">
                
                <div id = "Main_text">
                    <img src = "Bilder/Barbelll.png" id="Barbell_img">
                    <ul>
                        <li>Gymsnussisten</li>
                        <li id = "Snus_is_Future"> Snus is Future</li>
                    </ul>
                </div>
                <div id = "text">
                    <h2> Text </h2>
                </div>
            </section>

            <section class = "trender">
                <h1>Trender</h1>
                <div class = "karussell">
                    <button id = "knapp"></button>
                    
                    <ul id = "karrusell__spar">
                        <li>
                            <img src = "Bilder/Snus.jpeg">
                            <p>Pre-Snus</p>
                            <p>199 :-</p>
                            <p>Använd rabattkod: 34567lol för 20 % av</p>
                            
                        </li>

                        <li>
                            <img src = "Bilder/Crystal_creatine.jpg">
                            <p>Crystal Creatine</p>
                            <p>499 :-</p>
                            <p>Använd rabattkod: 34567lol för 20 % av</p>
                        </li>

                        <li>
                            <img src = "Bilder/Shrooms.png">
                            <p>Shrooms</p>
                            <p>349 :-</p>
                            <p>Använd rabattkod: 34567lol för 20 % av</p>
                        </li>

                        <li>
                            <img src = "Bilder/Wife_beater.png">
                            <p>Wife beater</p>
                            <p>999 :-</p>
                            <p>Använd rabattkod: 34567lol för 20 % av</p>
                        </li>
                    </ul>

                    <button id = "knapp"></button>
                </div>
            </section>

            <section class = "pundargymmet">

                <h1> Logo </h1>
                <ul>
                    <li><img src="Bilder/Gym.jpg" alt="Gym"></li>
                    <li><img src="Bilder/Gym2.png" alt=""></li>
                </ul>

                <h1 id = "TräningsGuide">Pundar gymmet</h1>
                
                <a href=""></a>
            </section>

        </main>


        <footer>
            <ul>
                <li>________________________________________________</li>
                <li>________________________________________________</li>
                <li>________________________________________________</li>
                <li>________________________________________________</li>
            </ul>    
                
            <ul>    
                <div id="Footer_Div">
                    <img src="Bilder/Flagga.png" id="Sverige_flagga">
                    <li>Gymsnussuisten Swe AB</li>
                </div>

                <p>+46-762164939</p>

            </ul>
            
            <ul id="Social_Media">
                <li><img src="Bilder/Insta_logo.png" alt=""></li>
                <li><img src="Bilder/twitter.png" alt=""></li>
                <li><img src="Bilder/Youtube.png" id="Youtube_image"></li>
                <li><p>@GymsnussistenSE</p></li>
            </ul>
        </footer>



        <script src="action.js"></script>
    </body>
</html>
