<template>

  <div class="container-responsive">

    <header style=" display: flex; align-items: center; justify-content: center;background-color: #CD68F7;border-bottom: 5px solid white;">

      <div>

        <nav class="navbar navbar-expand-lg navbar-dark" >
          <h1 class="navbar-brand" style=" font-size:200%;font-family: 'Shadows Into Light', cursive;">  Paul AKAR </h1>


          <button
            class="navbar-toggler"
                  type="button" data-toggle="collapse"
                  data-target="#Barnav"
                  aria-controls="Barnav"
                  aria-expanded="true"
                  aria-label="Toggle navigation">
            <span > <i style="color:white;width:30px;"class="fas fa-bars"></i> </span>
          </button>

          <div class="collapse navbar-collapse" id="Barnav">

            <ul class="navbar-nav">

              <li class="nav-item text-center">
                <router-link to="/" class="nav-link" href="index.html" style="font-family: 'Montserrat Medium';font-size:20px;color:white;"> Travaux </router-link>
              </li>

              <li class="nav-item text-center">
                <router-link to="/propos" class="nav-link" href="index.html" style="font-family: 'Montserrat Medium';font-size:20px;color:white;"> À propos de moi </router-link>
              </li>


            </ul>

          </div>



        </nav>
      </div>

    </header>





    <router-view/>





  </div>

</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
