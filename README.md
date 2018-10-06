<!DOCTYPE html>
<html lang="fr">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="css/style.css" >
    <link rel="stylesheet" href="css/animate.css" >
    <!--link rel="stylesheet"  media="screen and (max-width: 400px)" href="css/petite-résolution.css"-->
    <script src="JS/jquer.js"></script>
    <script src="JS/jquery.lettering.js"></script>
    <script src="JS/jquery.textillate.js"></script>
    <title>INSTANT T PHOTO</title>
    
       
  
    
  </head>
  
  <body>
  <div class="welcome-section content-hidden" id="enter">
    <div class="content-wrap">
      <ul class="fly-in-text">
        <li>I</li>
        <li>N</li>
        <li>S</li>
        <li>T</li>
        <li>A</li>
        <li>N</li>
        <li>T</li>
        
        <li id="t">T</li>
      </ul>
      <a href="#enter" class="enter-button"><span class="top">ENTRER</span></a>
    </div>
  </div>
  <script type="text/javascript">
  
  $(function() {
    var welcomeSection = $('.welcome-section'),
    enterButton = welcomeSection.find('.enter-button');

    setTimeout(function() {
      welcomeSection.removeClass('content-hidden');
    },800);

    enterButton.on('click', function(e){
    e.preventDefault();
    welcomeSection.addClass('content-hidden').fadeOut();
    });
  });

  </script>

<nav class="navbar" id="nav">
    <span class="open-slide">
      <a href="#a" onclick="openSlideMenu()">
        <svg width="40" height="40">
            <path d="M0,5 40,5" stroke="#fff" stroke-width="5"/>
            <path d="M0,14 40,14" stroke="#fff" stroke-width="5"/>
            <path d="M0,23 40,23" stroke="#fff" stroke-width="5"/>
            <path d="M0,32 40,32" stroke="#fff" stroke-width="5"/>
        </svg>
      </a>
    </span>

    <ul class="navbar-nav">
      <li><a href="#enter">Acceuil</a></li>
      <li><a href="Page 2/Galerie2.html">Galerie</a></li>
      <li><a href="#tarif">Tarifs</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <div id="side-menu" class="side-nav">
    <a href="#a" class="btn-close" onclick="closeSlideMenu()">&times;</a>
    <a href="#enter"  onclick="closeSlideMenu()">Acceuil</a>
    <a href="Page 2/Galerie2.html" onclick="closeSlideMenu()">Galerie</a>
    <a href="#tarif" onclick="closeSlideMenu()">Tarifs</a>
    <a href="#contact" onclick="closeSlideMenu()">Contact</a>
  </div>



  <script>
    function openSlideMenu(){
      document.getElementById('side-menu').style.width = '160px';
      document.getElementById('main').style.marginLeft = '160px';
    }

    function closeSlideMenu(){
      document.getElementById('side-menu').style.width = '0';
      document.getElementById('main').style.marginLeft = '0';
    }
  </script>

<script type="text/javascript">

  

  // Scrolling Effect

  $(window).on("scroll", function() {
        if($(window).scrollTop()) {
              $('nav').addClass('black');
        }

        else {
              $('nav').removeClass('black');
        }
  })


  </script>

    <main>
      <!-- Landing Area -->
      <div id="landing">
        <div id="landing-text">
          <div id="landing-text-inner">
            <h1 class='elegantshadow'><span class="bold">INSTANT T Photographie</span></h1>
            <h2 class="souligne">Photographe Professionnel</h2>
            <a class="btn"  id="z" id="view-work" href="#images">
             <span class="bold">Mes Images</span> 
            </a>
          </div>
        </div>
        <div>
          <img alt="" src="david.jpg" id="landing-image">
        </div>
      </div>
  
      <div id="images">
        <div id="header">
          <h2 ><strong class="lu2">MON TRAVAIL</strong></h2>
        </div>
    
        <img alt="" src="famille.jpg">
        <div class="caption">
          <h3><strong class="lu1" id="tarif">PHOTO DE FAMILLE</strong></h3>
          <p><strong>_____________________</strong></p>
          <br>
          <p> Seul, en couple ou en famille, le portrait révèle la personnalité profonde du ou des modèles. A l'issue d'une séance, on obtient de belles images très différentes des photos de tous les jours. C'est aussi l'occasion de passer un bon moment à jouer à être la star du jour. Un cadeau à offrir ou à s'offrir à l'occasion d'un anniversaire, d'une St Valentin ou des fêtes de fin d'année.</p>
          <br>
          <p class="p3">TARIFS :</p>
          <p class="p"> séance de prise de vue d'une demi-heure, à domicile ou dans un lieu choisis en commun. Vous obtiendrez 8 Photos sur un CD ou un tirage 15x20 cm.</p>
          <p class="p">Tarif: 80€ + les frais de déplacement. </p>
        </div>
        <img  src="nos petits.jpg"/>
        <div class="caption">
          <h3><strong class="lu1">Naissances & Bâtemes:</strong></h3>
          <p><strong>_____________________</strong></p>
          <br>
          <p>Les Souvenirs pour nos tout petits.</p>
          <br>
          <p class="p3">TARIFS :</p>
          <p class="p"> séance de prise de vue d'une demi-heure, à domicile ou dans un lieu choisis en commun. Vous obtiendrez 8 Photos sur clé USB ou un tirage 15x20 cm.</p>
          <p class="p">Tarif: 80€ + les frais de déplacement. </p>
        </div>
        <img alt="" src="ariel.jpg">
        <div class="caption">
          <h3><strong class="lu1">Portrait de couple, en extérieur ou à domicile:</strong></h3>
          <p><strong>_______________________________________________</strong></p>
          <br>
          <p> Une séance de prise de vue d'une à deux heures selon la motivation des modèles, dans des lieux choisis en commun. Utiliser l'environement naturel ou urbain permet des situations bien plus variées qu'en studio. Le jeux aidera les Modèles à se sentir à l'aise pour obtenir plus de naturel dans les attitudes.</p>
          <br>
          <p class="p3">TARIFS :</p>
          <p class="p"> Vous obtiendrez 25 Photos sur un CD ou 5 tirages 20x30 cm et 5 tirages 15x20 cm.
          Tarif : 250€ + les frais de déplacement </p>
        </div>
        <img alt="" src="mode.jpg">
        <div class="caption">
          <h3><strong class="lu1">Photos de mode & Book professionnel :</strong></h3>
          <p><strong>________________________________________</strong></p>
          <br>
          <p> Vos Photos de mode pour votre Book professionnel , agence et autres prestations promotionnelles artistique. Sur un site définit en commun et décors de mise en valeur, nous réaliserons les plus belles photos que vous pourrez présenter à vos futurs clients et employeurs.</p>
          <br> 
          <p class="p"> Pour une séances d'une heure minimum </p>
        </div>
        <img alt="" src="maraige.jpg">
        <div class="caption">
          <h3><strong class="lu1">MARIAGE :</strong></h3>
          <p><strong>_____________</strong></p>
          <br>
          <p class="p"> Nous proposons le reportage photo de votre mariage.
           À partir d'un forfait de base à 350€, hors frais de déplacement, incluant :
          </p>
          <br>
          <p>Portrait de couple,
            Reportage de la cérémonie à la mairie,
             les fichiers-photo sur DVD et les droits de retirage des images chez le prestataire de votre choix,
               Vous pourrez choisir les étapes en plus dont vous souhaitez garder une trace en images, 
               de la préparation dès le matin jusqu'à la pièce montée..</p>
        </div>
        <img alt="" src="evenements.jpg">
        <div class="caption">
          <h3><strong class="lu1">Sites et Évenements :</strong></h3>
          <p><strong>________________________</strong></p>
          <br>
          <p>Vous souhaitez promouvoir un site, événements sportifs, associations, ou tout simplement garder les plus belles images de ces lieux et instants Nous vous proposons la formule forfait et tous types de tirages décritent ci-dessus, mais aussi la réalisation de Poster de différentes tailles et qualités papier ainsi que des tee-shirts, gobelets, agenda et une multitude de support aux meilleurs prix du marché et qui vous seront livrés directement dans les meilleurs délais grace a notre partenaire de production.</p>
          <br>   
          <p class="p">Tarifs et frais d'envois informé sur demande de devis</p>
        </div>
        <img alt="" src="pack-shot.jpg">
        <div class="caption">
          <h3><strong class="lu1">Pack-shot et Étude en studio :</strong></h3>
          <p><strong>________________________________</strong></p>
          <br>
          <p class="p">Photo technique pour des catalogues et modes d'emploi ou étude artistique pour des tirages de grande taille.</p>
        </div>
        <div id="images">
          <img src="Instant T 36.gif">
        </div>
      </div>
    </main>

    <footer>
        <h1>Me Contacter</h1>
        <h3>Cliquez ci-dessous</h3>
        <button class="btnA" id="contact"> </button>
      <!--div class="footerdiv" id="contact">
        <button class="footerbutton"></button>
        
      </div-->
      <!--h2><strong>ME CONTACTER</strong></h2>
      <p>Email:
        <strong>contact@instant-t36.com</strong>
      </p>
      <p>Téléphone:
        <strong>07.81.95.56.45</strong>
      </p-->
      <br>
      <!--modal-->
      <button class="btnA" id="myBtn"></button>

      <div id="myModal" class="modal">

      <div class="modal-content">
        <span class="close">&times;</span>
        <form action="" method="get">
          <p>
            <label class="aa" for="Noms">Votre nom :</label><br>
            <input class="saisie" type="text" name="name"id="name" placeholder="Ex: Dupont" size="30" 
            maxlength="20"/>
            <p>
            <label class="aa" for="Noms">Votre prénom :</label><br>
            <input class="saisie" type="text" name="name"id="name" placeholder="Ex: Nicolas" size="30" 
            maxlength="20"/>
          </p>
          <p>
          <label class="aa" for="Noms">Votre Numéro :</label><br>
          <input class="saisie" type="text" name="name"id="name" placeholder="N°:" size="30" 
          maxlength="10"/>
          <p>
        </p>
        <label class="aa" for="Noms">Votre Email :</label><br>
        <input  class="saisie" type="text" name="name"id="name" placeholder="Email:" size="30" 
        maxlength="40"/>
      </p>
      <p>
        <label class="aa" for="Noms">Votre Message :</label><br>
        <textarea class="saisie" type="text" name="name"id="name" placeholder="Message:"></textarea>
      </p>

        </form>
      </div>

    </div>
    <script>
    var modal= document.getElementById('myModal'); 
    
    var btn = document.getElementById("myBtn");
    
    var span = document.getElementsByClassName("close")[0];
    
    btn.onclick = function(){
      modal.style.display = "block";
    }
    
    span.onclick = function(){
      modal.style.display = "none"
    }

    window.onclick = function(event) {
      if (event.target == modal){
        modal.style.display = "none";
      }
    }
     </script>
    </footer>
    
      <script>
        $('.lu1').textillate({
        in: { effect: 'rollIn', delay:100},
        out: { effect: 'rollOut', sync: true, delay:10 },
        loop: true   
        });
        </script>
  
  <script>
    $('.lu2').textillate({
    in: { effect: 'bounce', delay:100},
    out: { effect: 'flash', delay:10 },
    loop: true   
    });
    </script>
  
  
  
  
  </body></html>
