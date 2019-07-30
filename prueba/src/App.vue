<template> <!--inicia el HTML para la pagina de inicio -->
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
	<a class="navbar-brand" href="#"> <img  id="log" class="logo" width="50px" height="50px" src="https://upload.wikimedia.org/wikipedia/commons/b/b5/Logo-UIP-jpg.jpg" > LOGO UIP</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar1" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbar1">
    <ul class="navbar-nav ml-auto"> 
<li class="nav-item active">
<a class="nav-link" href="#">INICIO <span class="sr-only">(current)</span></a>
</li>
<li class="nav-item">
<a class="btn ml-2 btn-warning" href="#">LOGIN</a></li> <!--Aqui se abrira un Js PopUp para abrir el login -->
    </ul>
  </div>
</nav>
<div class="container-center">
        <br> 
        <p>Bienvenido al sistema de seleccion de cubiculos/ computadores para la biblioteca de la UIP.</p>
    <p>Seleccione uno de los recuadros si desea apartar un COMPUTADOR o un CUBICULO.</p>

<br><br><br>
<!-- Aqui se seleccionara en los reacuadros si el usuario desea PC o Cubiculo. -->
<div class="container">
                                                                                        <!--PONER LOS LINKS PARA EL DIRECCIONAMIENTO DE LA PAGINA -->
<button class="btn btn-primary align-left" href="Pagina de cubiculo">Computador</button>
<br> <br> <br>
<button class="btn btn-success alingn-rigth" href="pagina de pc">Cubiculo</button>
</div>
</div>

<br><br>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Bienvenido al sistema de seleccion de cubiculos/ computadores para la biblioteca de la UIP.'
    }
  }
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

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

</style>
