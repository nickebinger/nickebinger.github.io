<html>
   <body>
      <script>
         var password = "wiler1";
         (function passcodeprotect() {
            var passcode = prompt("Passwort eingeben");
            while (passcode !== password) {
               alert("Falsches Passwort :(");
               return passcodeprotect();
            }
         }());
      </script>
      <script async src="https://www.googletagmanager.com/gtag/js?id=G-5ZZ6G9W6TD"></script>
      <script>
         window.dataLayer = window.dataLayer || [];
         function gtag(){dataLayer.push(arguments);}
         gtag('js', new Date());
         gtag('config', 'G-5ZZ6G9W6TD');
      </script>
   </body>
</html>

## Ferien im Lötschental 

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.

<html>
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <style>
      body {
      font-family: Arial;
      margin: 0;
      }
      * {
      box-sizing: border-box;
      }
      img {
      vertical-align: middle;
      }
      /* Position the image container (needed to position the left and right arrows) */
      .container {
      position: relative;
      }
      /* Hide the images by default */
      .mySlides {
      display: none;
      }
      /* Add a pointer when hovering over the thumbnail images */
      .cursor {
      cursor: pointer;
      }
      /* Next & previous buttons */
      .prev,
      .next {
      cursor: pointer;
      position: absolute;
      top: 40%;
      width: auto;
      padding: 16px;
      margin-top: -50px;
      color: white;
      font-weight: bold;
      font-size: 20px;
      border-radius: 0 3px 3px 0;
      user-select: none;
      -webkit-user-select: none;
      }
      /* Position the "next button" to the right */
      .next {
      right: 0;
      border-radius: 3px 0 0 3px;
      }
      /* On hover, add a black background color with a little bit see-through */
      .prev:hover,
      .next:hover {
      background-color: rgba(0, 0, 0, 0.8);
      }
      /* Number text (1/3 etc) */
      .numbertext {
      color: #f2f2f2;
      font-size: 12px;
      padding: 8px 12px;
      position: absolute;
      top: 0;
      }
      /* Container for image text */
      .caption-container {
      text-align: center;
      background-color: #222;
      padding: 2px 16px;
      color: white;
      }
      .row:after {
      content: "";
      display: table;
      clear: both;
      }
      /* Six columns side by side */
      .column {
      float: left;
      width: 16.66%;
      }
      /* Add a transparency effect for thumnbail images */
      .demo {
      opacity: 0.6;
      }
      .active,
      .demo:hover {
      opacity: 1;
      }
   </style>
   <body>
      <div class="container">
         <div class="mySlides">
            <div class="numbertext">1 / 6</div>
            <img src="wohnzimmer.JPG" style="width:100%">
         </div>
         <div class="mySlides">
            <div class="numbertext">2 / 6</div>
            <img src="wohnzimmer2.JPG" style="width:100%">
         </div>
         <div class="mySlides">
            <div class="numbertext">3 / 6</div>
            <img src="wohnzimmer3.JPG" style="width:100%">
         </div>
         <div class="mySlides">
            <div class="numbertext">4 / 6</div>
            <img src="kueche.JPG" style="width:100%">
         </div>
         <div class="mySlides">
            <div class="numbertext">5 / 6</div>
            <img src="bad.JPG" style="width:100%">
         </div>
         <div class="mySlides">
            <div class="numbertext">6 / 6</div>
            <img src="logo.JPG" style="width:100%">
         </div>
         <a class="prev" onclick="plusSlides(-1)">❮</a>
         <a class="next" onclick="plusSlides(1)">❯</a>
         <div class="caption-container">
            <p id="caption"></p>
         </div>
         <div class="row">
            <div class="column">
               <img class="demo cursor" src="wohnzimmer.JPG" style="width:100%" onclick="currentSlide(1)" alt="Wohnzimmer">
            </div>
            <div class="column">
               <img class="demo cursor" src="wohnzimmer2.JPG" style="width:100%" onclick="currentSlide(2)" alt="Aufenthaltsraum">
            </div>
            <div class="column">
               <img class="demo cursor" src="wohnzimmer3.JPG" style="width:100%" onclick="currentSlide(3)" alt="Warmes Cheminée fürs Aufwärmen nach einem langen Skitag">
            </div>
            <div class="column">
               <img class="demo cursor" src="kueche.JPG" style="width:100%" onclick="currentSlide(4)" alt="Grosszügige Küche">
            </div>
            <div class="column">
               <img class="demo cursor" src="bad.JPG" style="width:100%" onclick="currentSlide(5)" alt="Badezimmer">
            </div>
            <div class="column">
               <img class="demo cursor" src="logo.JPG" style="width:100%" onclick="currentSlide(6)" alt="Haus">
            </div>
         </div>
      </div>
      <script>
         let slideIndex = 1;
         showSlides(slideIndex);
         
         function plusSlides(n) {
           showSlides(slideIndex += n);
         }
         
         function currentSlide(n) {
           showSlides(slideIndex = n);
         }
         
         function showSlides(n) {
           let i;
           let slides = document.getElementsByClassName("mySlides");
           let dots = document.getElementsByClassName("demo");
           let captionText = document.getElementById("caption");
           if (n > slides.length) {slideIndex = 1}
           if (n < 1) {slideIndex = slides.length}
           for (i = 0; i < slides.length; i++) {
             slides[i].style.display = "none";
           }
           for (i = 0; i < dots.length; i++) {
             dots[i].className = dots[i].className.replace(" active", "");
           }
           slides[slideIndex-1].style.display = "block";
           dots[slideIndex-1].className += " active";
           captionText.innerHTML = dots[slideIndex-1].alt;
         }
      </script>
      <br>   
   </body>
</html>

## Ausstattung 

*   8 Betten, für bis zu 10 Personen
*   Grosszügige Küche
*   WIFI
*   Skiraum
*   etc..

*   
## Preise

| Übernachtungen | Preis / Nacht     | 
|:---------------|:------------------|
| 1-3            | 120 CHF           |
| 4,5            | 110 CHF           | 
| 6              | 100 CHF           |
| >7             | 80 CHF            |

## Flyer zum Download 

<html>
   <a href="Ferienwohnung Wiler Flyer 2025 Winter.pdf" download>
  <button>PDF herunterladen</button>
</a>
</html>

## Verfügbarkeit

<html>

<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=Europe%2FZurich&bgcolor=%23ffffff&showPrint=0&src=MDNhNjcxZWE2NmQ0ZTVkYzJlOTJhMzRiYzUxN2QwNjVhMDljZDA1OWNlNzQ5MDMwYWJiZThhZmY1NzRlYmVkNEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%23F09300"  style="overflow:hidden;height:450;width:100%" height="450" width="100%"></iframe>
   
</html>
