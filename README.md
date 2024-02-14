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
            <h1 style="font-weight: bold; display: inline-block;">Informacione tehnologije u senzorskim sistemima-15/2020</h1>
        </div>
    </header>
    
    

    
    
    
    <div class="container-fluid main-container">
        <!-- Naslov ITSENS -->
            
   
            <div class="col text-center" style="font-family: 'Times New Roman', Times, serif;">
                <p align="justify" style="margin-left: 0.5cm; margin-right: 0.5cm; font-size: large;"> Senzori su uređaji ili komponente sistema koji osećaju i registruju fizičke, hemijske, mehaničke ili biološke promene u okolini i pretvaraju ih u električne signale ili digitalne podatke. Ovi uređaji su ključni za prikupljanje podataka iz stvarnog sveta i omogućavaju elektronskim sistemima da reaguju na okolnosti u njihovoj okolini.<br> Merenja su vršena data loggerom i merene su vrednosti: <br> <b>temperature, pritiska 1, zvuka, svetlosti, pritiska 2 i vlažnosti vazduha.</b> </p>
            </div>
     
        
        

        <!-- Prikaz dijagrama -->
        <div class="row">
            <div class="col-sm-12"><canvas id="myChart"></canvas></div>
        </div>
        <br>


        <!-- Opis podataka sa dijagrama -->
        <div class="container-fluid">
            <div class="row mt-4">
                
           
                

                <div class="col col-md-6">
                    <div class="table-data"><br><br>
                        
                            <p align="justify" style="margin-left: 0.5cm; margin-right: 0.5cm; font-size: large;"><br>Kroz analizu ovih merenja, uspoređivali smo vrednosti senzora tokom različitih vremenskih perioda kako bismo identifikovali trendove i obrasce u promenama podataka. Fokusirali smo se na praćenje odnosa u promenama podataka, čime smo dobili dublje razumevanje o tome kako se sistemi ponašaju tokom vremena.
        
                                Ova analiza nam je omogućila da identifikujemo ključne tačke u vremenu gde se vrednosti senzora značajno menjaju. Ove informacije su dragocene za optimizaciju sistema, detekciju anomalija i donošenje informisanih odluka u vezi sa upravljanjem sistemima koji se baziraju na senzorima.</p>
                        </div><br>
                    </div>
                    <br>
                    <br>
             
                </div>
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
                <br>
            </div>
            
            <br>

        </div>

        <footer class="footer-container" style="text-align: center;">
            <div class="footer-column" style="display: inline-block;">
                <button onclick="topFunction()" id="scrollToTopBtn" title="Vrati se na pocetak strane" class="btn btn-secondary">Vrati na pocetak strane</button>
                <p><b>Student:</b> Veljko Jakovljevic</p>
                <p><b>Indeks:</b>15/2020</p>
            </div>
        </footer>
        
        

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
