<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
        integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

    <link rel="stylesheet" href="styles.css">

    <title>15-2020</title>


</head>

<body>

    <header class="header-container" style="text-align: center;">
        <div class="header-logo">
            <h1 style="font-weight: bold; display: inline-block; color:white; font-family: sans-serif;">Informacione tehnologije u senzorskim sistemima</h1>
            <blockquote style="font-style: italic; color: white; font-family: sans-serif;">
                "Senzorski sistemi su oči i uši modernog doba informacionih tehnologija, pretvarajući svijet oko nas u podatke koji oblikuju našu budućnost."
            </blockquote>
        </div>
    </header>
    
    
    
    

    
    
    
    <div class="container-fluid main-container">
        <!-- Naslov ITSENS -->
        <div class="row">
            <div class="col text-center" style="font-family: sans-serif;">
                <p align="justify" style="margin-left: 0.5cm; margin-right: 0.5cm; font-size: large;"> 
                    Senzori predstavljaju bitne komponente sistema koje detektuju i bilježe raznolike promene u okolini, transformišući ih u električne signale ili digitalne podatke. Ovi uređaji su esencijalni za prikupljanje informacija iz stvarnog sveta i omogućavaju elektronskim sistemima da adaptiraju svoje ponašanje u skladu sa promenama u okruženju.
                </p>
                <p align="justify" style="margin-left: 0.5cm; margin-right: 0.5cm; font-size: large;" ><b>
                    Tokom merenja koristio se Data logger za zabeležavanje različitih vrednosti, uključujući Temperaturu, Gravitacionu silu, Zvuk, Svetlost, Pritisak  i Vlažnost vazduha.</b>
                </p>
                <div class="image-container">
                    <img src="img/data.jpg" alt="EasySense" class="centered-and-resized">
                    <button class="button-below-image" onclick="window.location.href='https://store.data-harvest.co.uk/easysense';">Idi na link od EasySens-a</button>
                </div>
            </div>
       
        </div>
        
        <div class="container-fluid" style="padding-top: 60px;">
           
        <!-- Prikaz dijagrama -->
        <div class="row">
            <div class="col-sm-12"><canvas id="myChart"></canvas></div>
        </div>



        <!-- Opis podataka sa dijagrama -->
        <div class="container-fluid" style="font-family: sans-serif;">
            <p align="justify" style="margin-left: 0.5cm; margin-right: 0.5cm; font-size: large;">Tokom analize ovih merenja, pažljivo smo proučavali vrednosti senzora tokom različitih vremenskih perioda kako bismo identifikovali uzorke i trendove u promenama podataka. Posebna pažnja bila je usmerena na praćenje odnosa u promenama podataka, što nam je omogućilo dublje razumevanje kako se sistemi ponašaju tokom vremena.
            </p>
            <p align="justify" style="margin-left: 0.5cm; margin-right: 0.5cm; font-size: large;">Ova analiza nam je pružila uvid u ključne tačke u vremenu gde se vrednosti senzora značajno menjaju. Ove informacije su od suštinskog značaja za optimizaciju sistema, otkrivanje anomalija i donošenje informisanih odluka u vezi sa upravljanjem sistemima koji se oslanjaju na senzore.</p> 
        </div>
        
        
            <div class="row">
                <div class="col col-sm-12">
                    <nav aria-label="Data pagination">
                        <ul class="pagination justify-content-center mt-3" id="pagination"></ul>
                    </nav>
                </div>
            </div>
        
            <div class="row">
                <div class="col col-sm-12">
                    <div id="parsedData"></div>
                </div>
            </div>
        </div>

      
        <footer class="footer-container" style="text-align: center; font-size: larger;">
            <div class="footer-column" style="display: flex; justify-content: space-between; align-items: center; font-family: sans-serif;">
                <div>
                    <p><b>Student:</b> Veljko Jakovljević</p>
                    <p><b>Indeks:</b> 15/2020</p>
                </div>
            
                <button onclick="topFunction()" id="scrollToTopBtn" title="Vrati se na početak strane" class="btn btn-secondary">Vrati na početak strane</button>

                <div>
                    <p><b>Profesor:</b>Dr. Nebojša Mitrović</p>
                    <p><b>Asistent:</b>Jelena Orelj</p>
                </div>
                <div>
                    <a href="http://www.ftn.kg.ac.rs/" target="_blank"><img src="img/ftn.png" alt="Sajt Fakulteta" style="width: 100px; height: 100px;"></a>
                    <a href="https://www.instagram.com/ftn.cacak/" target="_blank"><img src="img/insta.png" alt="Instagram Fakulteta" style="width: 100px; height: 100px;"></a>
                    <a href="http://www.ftn.kg.ac.rs/akreditacija2021/KNJIGA%20PREDMETA/Informacione_tehnologije_u_senzorskim_sistemima.pdf" target="_blank"><img src="img/pdf.png" alt="Dokument predmeta" style="width: 100px; height: 100px;"></a>
                </div>
             
            </div>
        </footer>
    </div>
     
        
        

        
        

    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.9.4/Chart.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/papaparse@5.3.0/papaparse.min.js"></script>
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"
        integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0=" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
        integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
        integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6"
        crossorigin="anonymous"></script>
    <script src="script.js"></script>

</body>

</html>
