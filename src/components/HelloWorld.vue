<template>
  <div class="hello">

    <body style="background: black; ">

    <h2 class="text-center paul" style="padding-top:5%">JE SUIS PAUL AKAR, ÉTUDIANT EN 2ÈME ANNÉE
      DE MMI À MONTBÉLIARD.</h2>

    <h3 class="text-center" style=""> Mes compétences </h3>

    <div class="compt">


      <h4  style="color:#00EDFF; margin-top:5%; font-family: 'DotGothic16'"> CSS </h4>

      <div class="progress" style="margin-top:5%;font-family: 'DotGothic16'">
        <div class="progress-bar barre1" role="progressbar" style="background-color : #8259D4;width: 90%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
      </div>

      <h4 style="color:#87D9F5; margin-top:5%;font-family: 'DotGothic16'"> HTML </h4>

      <div class="progress" style="margin-top:5%">
        <div class="progress-bar barre2" role="progressbar" style="background-color : #8259D4;width: 90%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
      </div>

      <h4 style="color:#87D9F5; margin-top:5%;font-family: 'DotGothic16'"> JS </h4>

      <div class="progress" style="margin-top:5%">
        <div class="progress-bar barre3" role="progressbar" style="background-color : #8259D4;width: 50%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
      </div>

      <h4 style="color:#87D9F5; margin-top:5%;font-family: 'DotGothic16'"> PHP </h4>

      <div class="progress" style="margin-top:5%">
        <div class="progress-bar barre4" role="progressbar" style="background-color : #8259D4;width: 60%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
      </div>

      <h4 style="color:#87D9F5; margin-top:5%;font-family: 'DotGothic16'"> DESIGN </h4>

      <div class="progress" style="margin-top:5%">
        <div class="progress-bar barre5" role="progressbar" style="background-color : #8259D4;width: 80%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
      </div>

    </div>






    <h3 class="text-center" style="color:white; margin-top:5%;font-family: 'Anton', sans-serif;">Mes projets </h3>

    <div class="vignettes">

      <img id="wdp" class="wdp" style=" " src="@/assets/img/Vignettes.png" alt="wordpress">

      <img id="ill" class="ill" style=" " src="@/assets/img/Vignette_illustrations.png" alt="illustrations">


      <img id="ind" class="ind" style=" " src="@/assets/img/Vignette_indiglu.png" alt="indiglu">


      <img id="lynch" class="lynch" style=" " src="@/assets/img/Vignette_lynch.png" alt="site_lynch">


      <img id="taupe" class="taupe" style=" " src="@/assets/img/Vignette_taupe.png" alt="taupe">

      <img id="loca" class="loca" style=" " src="@/assets/img/Vignette_locaterra.png" alt="locaterra">

      <img id="pulp" class="pulp" style=" " src="@/assets/img/Vignette_pulp.png" alt="pulp_fiction">


    </div>

    <h3 class="text-center" style="margin-top:5%"> Me contacter </h3>


    <div class="inscri container-fluid" >


      <div class="shadow col-lg-3" style="border-radius: 5%;margin-right: auto; margin-left:auto; ">


        <div class=" form d-flex" style="margin-top:8%;padding-bottom:20%">
          <fieldset class="m-auto col-lg-12 ">

            <div class="form-group">
              <label style="color:white;" for="prenom"> PRÉNOM :</label>
              <input type="text" name="prenom_utilisateur" id="prenom" class="form-control" style="border-radius:18px">
            </div>

            <div class="form-group">
              <label style="color:white;" for="nom"> NOM :</label>
              <input type="text" name="nom_utilisateur" id="nom" class="form-control " style="border-radius:18px">
            </div>

            <div class="form-group">
              <label style="color:white;" for="mail"> MAIL :</label>
              <input type="email" name="mail_utilisateur" id="mail" class="form-control " style="border-radius:18px">
            </div>

            <div class="form-group">
              <label style="color:white;" for="mess"> MESSAGE :</label>
              <textarea name="mess_utilisateur" id="mess" class="form-control " style="border-radius:18px"></textarea>
            </div>


            <div class="form-group">
              <label style="color:white;" for="envoyer"></label>
              <input class="envoyer" type="submit" name="envoyer_utilisateur" id="envoyer" style="">
            </div>



          </fieldset>


        </div>

      </div>

    </div>

    <!-- Footer -->
    <footer class="bg-light text-center text-lg-start" style=" color:#8259D4;border-top: 5px solid #CD68F7;">
      <!-- Grid container -->
      <div class="container p-4">
        <!--Grid row-->
        <div class="row">
          <!--Grid column-->
          <div class="col-lg-6 col-md-12 mb-4 mb-md-0">
            <h5 class="text-uppercase" style="font-family: 'Anton', sans-serif;"> CV </h5>
            <a style="display:block; text-align:center;font-family: 'Montserrat Medium';color:blue" href="<%= BASE_URL %>CV.pdf" download> Télécharger</a>
          </div>
          <!--Grid column-->



          <!--Grid column-->
          <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
            <h5 class="text-uppercase" style="font-family: 'Anton', sans-serif;">CONTACT</h5>

            <ul class="list-unstyled mb-0">
              <li>
                <a href="mailto:paul.akar2019@gmail.com" style="font-family: 'Montserrat Medium';color:blue">paul.akar2019@gmail.com</a>
              </li>
            </ul>
          </div>
          <!--Grid column-->





          <!--Grid column-->
          <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
            <h5 class="text-uppercase mb-0" style="font-family: 'Anton', sans-serif;">Réseaux sociaux </h5>

            <ul class="list-unstyled">
              <li>
                <a href="https://www.linkedin.com/in/paul-akar-92a286197/" class="text-dark"> <i style="width:30px; height:50%; margin-top:7%; color:#8259D4;"  class="fab fa-linkedin"></i> </a>
              </li>

              <li>
                <a href="https://www.instagram.com/illustration_pakar/" class="text-dark"> <i style="width:30px; height:50%; margin-top:7%; color:#8259D4;" class="fab fa-instagram"></i> </a>
              </li>

            </ul>
          </div>
          <!--Grid column-->
        </div>
        <!--Grid row-->
      </div>
      <!-- Grid container -->

      <!-- Copyright -->
      <!-- Copyright -->
      <div class="text-center p-3" style="background-color:#CD68F7;color:white">
        © 2020 Copyright:
        <a style="color:white" href="http://paulakar.fr/">paulakar.fr</a>
      </div>
      <!-- Copyright -->
    </footer>
    <!-- Footer -->

    <!-- Modal Section -->

    <div class="modal-wdp">
      <div class="modal-content-wdp">
        <div class="close-wdp">+</div>
        <h4 style = "text-align: center; margin-top:5%;font-family: 'Anton', sans-serif;font-size:35px; "> Wordpress </h4>
        <p style="margin:5%;text-align: center;font-family: 'Montserrat Light'"> Page d'accueil d'un site Wordpress sur la marche en montagne. Page d'accueil réalisée à l'aide d'une maquette graphique fournie en amont.</p>
        <p style="margin:5%;text-align: center;font-family: 'Montserrat Light'"> Thème utilisé: Avada </p>
        <p style="margin:5%;text-align: center;font-family: 'Montserrat Light'"> Année : 2021 </p>
        <a class="decouvrir" style="color:white;" href="https://maquettetp.fr.paulakar.fr/"> Découvrir </a>
      </div>
    </div>


    <div class="modal-ill">
      <div class="modal-content-ill">
        <div class="close-ill">+</div>

        <h4 style = "text-align: center; margin-top:5%;font-family: 'Anton', sans-serif; font-size:35px;"> Illustrations </h4>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Différents portraits que j'ai dessiné et coloriés à partir de photos, et cela directement sur ordinateur à l'aide de la souris. </p>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Logiciel utilisé : Adobe Illustrator </p>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Année : 2020 / 2021 </p>


        <div id="myCarousel" class="carousel slide" data-ride="carousel">

          <ol class="carousel-indicators">
            <li data-target="#myCarousel" data-slide-to="0" class="active" ></li>
            <li data-target="#myCarousel" data-slide-to="1"></li>
            <li data-target="#myCarousel" data-slide-to="2"></li>
            <li data-target="#myCarousel" data-slide-to="3"></li>
            <li data-target="#myCarousel" data-slide-to="4"></li>
          </ol>

          <div class="carousel-inner">

            <div class="carousel-item active">
              <div class="container">
                <img src="@/assets/img/ill1.png" style="width:100%" alt="portrait1">
              </div>
            </div>

            <div class="carousel-item">
              <div class="container">
                <img src="@/assets/img/ill2.png" style="width:100%" alt="portrait2">
              </div>
            </div>

            <div class="carousel-item">
              <div class="container">
                <img src="@/assets/img/ill3.png" style="width:100%" alt="portrait3">
              </div>
            </div>

            <div class="carousel-item">
              <div class="container">
                <img src="@/assets/img/ill4.png" style="width:100%" alt="portrait4">
              </div>
            </div>

            <div class="carousel-item">
              <div class="container">
                <img src="@/assets/img/ill5.png" style="width:100%" alt="portrait5">
              </div>
            </div>

          </div>

          <a href="#myCarousel" class="carousel-control-prev"  role="button" data-slide="prev">

            <span class="sr-only"> Previous </span>

            <span class="carousel-control-prev-icon" aria-hidden="true">  </span>

          </a>

          <a href="#myCarousel" class="carousel-control-next"  role="button" data-slide="next">

            <span class="sr-only"> Previous </span>

            <span class="carousel-control-next-icon" aria-hidden="true">  </span>

          </a>

        </div>


      </div>
    </div>


    <div class="modal-ind">
      <div class="modal-content-ind">
        <div class="close-ind">+</div>
        <h4 style = "text-align: center; margin-top:5%;font-family: 'Anton', sans-serif; font-size:35px; "> Charte Graphique </h4>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Charte graphique d'un site web d'une association permettant aux malades du diabète de manger le plus sainement possible.  </p>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Logiciels utilisés : Canva / Adobe Illustrator  </p>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Année : 2020 </p>
        <a class="decouvrir" style="display:block; text-align:center;color:white;"  href="<%= BASE_URL %>charte.pdf" download>Découvrir</a>

      </div>
    </div>


    <div class="modal-lynch">
      <div class="modal-content-lynch">
        <div class="close-lynch">+</div>
        <h4 style = "text-align: center; margin-top:5%;font-family: 'Anton', sans-serif; font-size:35px; "> Site web VueJS </h4>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Site web responsive que j'ai réalisé en VueJS au cours d'un examen d'une durée d'une journée. </p>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Technologies utilisées : HTML / CSS / Boostrap / VueJS </p>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Année : 2021 </p>
        <a class="decouvrir" style="display:block; text-align:center;color:white;" href="http://boss.paulakar.fr/"> Découvrir </a>
      </div>
    </div>

    <div class="modal-taupe">
      <div class="modal-content-taupe">
        <div class="close-taupe">+</div>
        <h4 style = "text-align: center; margin-top:5%;font-family: 'Anton', sans-serif; font-size:35px;"> Court métrage </h4>
        <p style="text-align: center;margin-top:2%; font-family: 'Montserrat Light'"> Court métrage réalisé avec 2 camarades, l'objectif était de réaliser une courte vidéo interactive avec différents supports. </p>
        <p style="text-align: center; font-family: 'Montserrat Light'"> Logiciels utilisés : Adobe After Effects / Adobe Première Pro / Adobe Audition  </p>
        <p style="text-align: center; font-family: 'Montserrat Light'">  Année : 2020 </p>
        <video style="width:100%" controls src="@/assets/video/taupe.mp4">Court métrage La taupe</video>

      </div>
    </div>

    <div class="modal-loca">
      <div class="modal-content-loca">
        <div class="close-loca">+</div>
        <h4 style = "text-align: center; margin-top:5%;font-family: 'Anton', sans-serif; font-size:35px;"> Site web </h4>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Locaterra est un site web responsive que j'ai  réalisé avec 2 camarades. L'objectif du site est de regrouper tous les évènements écologiques près de chez soi sur une carte interactive sous forme de marqueurs . </p>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Technologies utilisées :  HTML / CSS / JS</p>
        <p style="margin:5%;text-align: center; font-family: 'Montserrat Light'"> Année : 2020 </p>
        <a class="decouvrir" style="display:block; text-align:center;color:white;" href="http://locaterra.paulakar.fr/"> Découvrir </a>

      </div>
    </div>

    <div class="modal-pulp">
      <div class="modal-content-pulp">
        <div class="close-pulp">+</div>
        <h4 style = "text-align: center; margin-top:5%;font-family: 'Anton', sans-serif; font-size:35px; "> Motion desgin </h4>
        <p style="margin:2%;text-align: center; font-family: 'Montserrat Light'">Projet Motion design réalisé en cours visant à présenter le film "Pulp Fiction" dans une vidéo courte d'environ 1min30. Avant de passer directement à la réalisation j'ai d'abord réalisé un script vidéo ainsi qu'un storyboard.</p>
        <p style="margin:2%;text-align: center; font-family: 'Montserrat Light'">Logiciels utilisés : Adobe After Effects </p>
        <p style="margin:2%;text-align: center; font-family: 'Montserrat Light'">Année : 2020 </p>
        <video style="width:100%" controls src="@/assets/video/pulp.mp4">Présentation du film Pulp Fiction </video>

      </div>
    </div>

    </body>

  </div>


</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'helloworld',
      publicPath: process.env.BASE_URL,
    }
  },

  mounted() {

    /*wdp */

    document.getElementById('wdp').addEventListener('click', function (event) {
      document.querySelector('.modal-wdp').style.visibility = 'visible';
      document.querySelector('body').style.overflow = 'hidden';
    });

    document.querySelector('.close-wdp').addEventListener('click', function (){
      document.querySelector('.modal-wdp').style.visibility = 'hidden';
      document.querySelector('body').style.overflow = 'scroll';
    })



    /*ill*/

    document.getElementById('ill').addEventListener('click', function (event) {
      document.querySelector('.modal-ill').style.visibility = 'visible';
      document.querySelector('body').style.overflow = 'hidden';
    });

    document.querySelector('.close-ill').addEventListener('click', function (){
      document.querySelector('.modal-ill').style.visibility = 'hidden';
      document.querySelector('body').style.overflow = 'scroll';
    })

    /*ind*/

    document.getElementById('ind').addEventListener('click', function (event) {
      document.querySelector('.modal-ind').style.visibility = 'visible';
      document.querySelector('body').style.overflow = 'hidden';
    });

    document.querySelector('.close-ind').addEventListener('click', function (){
      document.querySelector('.modal-ind').style.visibility = 'hidden';
      document.querySelector('body').style.overflow = 'scroll';
    })


    /*lynch*/

    document.getElementById('lynch').addEventListener('click', function (event) {
      document.querySelector('.modal-lynch').style.visibility = 'visible';
      document.querySelector('body').style.overflow = 'hidden';
    });

    document.querySelector('.close-lynch').addEventListener('click', function (){
      document.querySelector('.modal-lynch').style.visibility = 'hidden';
      document.querySelector('body').style.overflow = 'scroll';
    })

    /*taupe*/

    document.getElementById('taupe').addEventListener('click', function (event) {
      document.querySelector('.modal-taupe').style.visibility = 'visible';
      document.querySelector('body').style.overflow = 'hidden';
    });

    document.querySelector('.close-taupe').addEventListener('click', function (){
      document.querySelector('.modal-taupe').style.visibility = 'hidden';
      document.querySelector('body').style.overflow = 'scroll';
    })

    /*loca*/

    document.getElementById('loca').addEventListener('click', function (event) {
      document.querySelector('.modal-loca').style.visibility = 'visible';
      document.querySelector('body').style.overflow = 'hidden';
    });

    document.querySelector('.close-loca').addEventListener('click', function (){
      document.querySelector('.modal-loca').style.visibility = 'hidden';
      document.querySelector('body').style.overflow = 'scroll';
    })

    /*pulp*/

    document.getElementById('pulp').addEventListener('click', function (event) {
      document.querySelector('.modal-pulp').style.visibility = 'visible';
      document.querySelector('body').style.overflow = 'hidden';
    });

    document.querySelector('.close-pulp').addEventListener('click', function (){
      document.querySelector('.modal-pulp').style.visibility = 'hidden';
      document.querySelector('body').style.overflow = 'scroll';
    })





  }

}
</script>


