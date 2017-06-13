<!doctype html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.98.2/css/materialize.min.css">
<script src="https://code.jquery.com/jquery-3.2.1.js" integrity="sha256-DZAnKJ/6XZ9si04Hgrsxu/8s717jcIzLy3oi35EouyE=" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.98.2/js/materialize.min.js"></script>
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
<meta charset="UTF-8">
<title>FORMA DE REGISTRO PARA PONENTES</title>
<style>
 .container{
		display:block;
		margin-left: auto;
		margin-right: auto;
	 	margin-bottom: auto
	}
	.page-footer{
		background-color: #1B76BA;
	}
	.peso {
		font: normal 400 1em/1em "reef", sans-serif;
		font-size: 500%;
		font-weight: bold;
		color: #364A8B;
			
	}	
	.parrafo {
		font-weight: 300;
	}
	.titulitos{ 
		font: normal 400 1em/1em "reef", sans-serif;
		font-size: 300%;
		color:#EC6726;
	}
	label {
		font: normal 400 1em/1em "Montserrat", sans-serif;
	}
	p{
		font: normal 400 1em/1em "Montserrat", sans-serif;
	}
	input {
		font: normal 400 1em/1em "Montserrat", sans-serif;
	}
	span{
		font: normal 400 1em/1em "Montserrat", sans-serif;
	}
	button{
		font: normal 400 1em/1em "Montserrat", sans-serif;
		color: #364A8B;
	}
	.parrafovuelo{
		text-align: center;
		font-weight: 300
	}
	.fondo{
		background-color:#F2F3F5;
		padding: 20px;
	}
	.borde{
		margin-right: 100px;
		margin-left: 100px;
		padding:70px;
		background-color: #82B040;
	}
	img{
		align-content: left;
		margin: 20px;
	}
	.title{
		color: #364A8B;
		font:  normal 400 1em/1em "reef", sans-serif;
		font-size: 500%;
	}
	.hide-on-small-and-down{
		margin: 40px;
		font-size: 150%;
		text-align: left;

}
	.lista li{ display: inline;
		 padding: 0px 20px;	}
	.input-field input[type=text]:focus + label {
     color: #364A8B;
}
	.input-field input[type=text].valid {
     border-bottom: 1px solid #364A8B;
     box-shadow: 0 1px 0 0 #364A8B;
	}
	.input-field input[type=text]:focus {
     border-bottom: 1px solid #364A8B;
     box-shadow: 0 1px 0 0 #364A8B;
   }
	.input-field .prefix.active {
     color: #364A8B;
   }
	.input-field input[type=email]:focus + label {
     color: #364A8B;
}
	.input-field input[type=email].valid {
     border-bottom: 1px solid #364A8B;
     box-shadow: 0 1px 0 0 #364A8B;
	}
	.input-field input[type=email]:focus {
     border-bottom: 1px solid #364A8B;
     box-shadow: 0 1px 0 0 #364A8B;
   }
	.input-field input[type=date]:focus + label {
     color: #364A8B;
}
	.input-field input[type=date].valid {
     border-bottom: 1px solid #364A8B;
     box-shadow: 0 1px 0 0 #364A8B;
	}
	.input-field input[type=date]:focus {
     border-bottom: 1px solid #364A8B;
     box-shadow: 0 1px 0 0 #364A8B;
   }
	.input-field input[type=time]:focus + label {
     color: #364A8B;
}
	.input-field input[type=time].valid {
     border-bottom: 1px solid #364A8B;
     box-shadow: 0 1px 0 0 #364A8B;
	}
	.input-field input[type=time]:focus {
     border-bottom: 1px solid #364A8B;
     box-shadow: 0 1px 0 0 #364A8B;
   }

	</style>
	
</head>

<body>

<div class="header nav-extended">
	 <img src="5toencuentrologo-01.png" height="200px">
 
       <ul class="right hide-on-small-and-down lista">
        <li><a href="http://www.uacj.mx">UACJ</a></li>
        <li><a href="http://www.uacj.mx/DGVI/Encuentro/Paginas/default.aspx">5to Encuentro</a></li>
		  </ul>
      <h1 class="title" align="center">FORMATO DE REGISTRO</h1>
</div>
	<div class="borde">
<div class="fondo">
<h3 class="titulitos" align="center">INFORMACIÓN PERSONAL</h3>
<p class="parrafo" align="center">Datos personales para las gestiones de esta participación.</p>

	<div class="container">
	<form action="/action_page.php">
  <div class="row">
      <div class="row">
       
        <div class="input-field col s6">
      <i class="material-icons prefix">perm_identity</i>
	  <input id="nombre" type="text" class="validate">
	  <label for="nombre">Nombre</label>
		  </div>
		
	   
	<div class="input-field col s6">
	  <input id="apellido" type="text" class="validate">
	  <label for="apellido">Apellido</label>
		  </div>
		  </div>
		</div>
	  
		</form>
		<form>
	<div class="row">
        <div class="input-field col s12">
        
      <p>Fecha de nacimiento:</p>  
	  <input type="date" class="validate"><br>
	   </div>
      </div>
	 <div class="row">
        <div class="input-field col s12">
       <i class="material-icons prefix">email</i>
	  <input id="correo" type="email" class="validate">
	  <label for="correo">Correo electrónico</label>
	   </div>
      </div>
      <div class="row">
        <div class="input-field col s12">
      <i class="material-icons prefix">phone</i>
	  <input id="telefono" type="text" class="validate">
	  <label for="telefono">Teléfono</label>
			</div>
		  </div>
      <div class="row">
        <div class="input-field col s12">
      	<i class="material-icons prefix">business</i>
	  <input id="institucion" type="text" class="validate">
	  <label for="institucion">Institución/Organismo</label>
		  </div>
		  </div>
      <div class="row">
        <div class="input-field col s12">
      <i class="material-icons prefix">class</i>		  
	  <input id="grado" type="text" class="validate">
	  <label for="grado">Grado</label>
		  </div>
		  </div>
	 <div class="row">
        <div class="input-field col s12">
      <i class="material-icons prefix">room</i>
	  <input id="pais" type="text" class="validate">
	  <label for="pais">País</label>
		 </div>
		  </div>
	<div class="row">
        <div class="input-field col s12">
       <i class="material-icons prefix">my_location</i>
	  <input id="ciudad" type="text" class="validate">
	  <label for="ciudad">Ciudad</label>
		</div>
		  </div>
	<div class="row">
        <div class="input-field col s12">
       <i class="material-icons prefix">assignment_ind</i>	  
	  <input id="pasaporte" type="text" class="validate">
	  <label for="pasaporte">Número de Pasaporte</label>
		</div>
		  </div>
	<div class="row">
        <div class="input-field col s12">
        <i class="material-icons prefix">today</i>
	  <input id="expiracion" type="text" class="validate">
	  <label for="expiracion">Fecha de expiración</label>
		</div>
		  </div>
	<div class="row">
	<div class="input-field col s12">
		<p>Currículum Vitae:</p>	  
	<div class="file-field input-field">
      <div class="btn">
        <span>Archivo</span>
        <input type="file" multiple>
      </div>
      <div class="file-path-wrapper">
        <input class="file-path validate" type="text" placeholder="Favor de adjuntar su CV con fotografía">
      </div>
    </div>
  </div>
		  </div>
  <div class="row">
	<div class="input-field col s12">
  <h3 class="titulitos" align="center">ACERCA DE SU PARTICIPACIÓN</h3><br>
	  </div>
		  </div>
  	<div class="row">
	<div class="input-field col s12">
     <i class="material-icons prefix">speaker_notes</i>
	  <input id="tema" type="text" class="validate">
	  <label for="tema">Tema de su ponencia:</label>
		</div>
		  </div>
	<div class="row">
	<div class="input-field col s12">
	<p>Abstract de su ponencia:</p>	  
	<div class="file-field input-field">
      <div class="btn">
        <span>Archivo</span>
        <input type="file" multiple>
      </div>
      <div class="file-path-wrapper">
        <input class="file-path validate" type="text" placeholder="Adjuntar uno o más archivos">
      </div>
    </div>
  </div>
		  </div>


	  <div class="row">
	<div class="input-field col s12">
	 	  <h3 class="titulitos" align="center">ITINERARIO DE VUELO</h3>
	 	  <p class="parrafovuelo">La siguiente información es necesaria para formular su itinerario de una manera accesible.</p>
		  </div>
		</div>
	  <div class="row">
	<div class="input-field col s12">
     <i class="material-icons prefix">call_made</i>
	  <input id="lugarpartida" type="text" class="validate">
	  <label for="lugarpartida">Lugar de origen</label>
		  </div>
		</div>
	<div class="row">
		<div class="input-field col s12">
		<i class="material-icons prefix">grade</i>
	  <input id="aerolineapreferencia" type="text" class="validate">
	  <label for="aerolineapreferencia">Aerolínea de preferencia</label>
		</div>
		</div> 
	  <div class="row">
	<div class="input-field col s12">
		<p>Preferencia de vuelo:</p>
		<input class="with-gap" name="preferenciavuelo" type="radio" id="1">
			  <label for="1">Mañana</label><br>
		<input class="with-gap" name="preferenciavuelo" type="radio" id="2">
			  <label for="2">Tarde</label><br>
		<input class="with-gap" name="preferenciavuelo" type="radio" id="3">
			  <label for="3">Noche</label><br>
		  </div>
		</div>
   	  <div class="row">
	<div class="input-field col s12">
	<p class="parrafo">En caso de contar ya con el vuelo:</p>	
  <p>Fecha de partida:</p>
	  <input type="date" name="fechapartida">
		  </div>
		</div>
   <div class="row">
	<div class="input-field col s12">
     <i class="material-icons prefix">call_made</i>
	  <input id="lugarorigen" type="text" class="validate">
			  <label>Lugar de origen</label>
				  </div>
		</div>
	<div class="row">
	<div class="input-field col s12">
		<p>Hora de partida</p>
	  <input id="Hora de partida" type="time" class="validate">
		</div>
		</div>
	<div class="row">
	<div class="input-field col s12">
  <i class="material-icons prefix">call_received</i>
	  <input id="destino" type="text" class="validate">
	  <label for="destino">Lugar de destino</label>
		</div>
		</div>
	  <div class="row">
	<div class="input-field col s12">
		<p>Hora de llegada:</p>
	  <input id="llegada" type="time" class="validate">
		  </div>
		</div>
	  <div class="row">
	<div class="input-field col s12">
  <i class="material-icons prefix">navigation</i>
	  <input id="aerolinea" type="text" class="validate">
		<label for="aerolinea">Aerolínea</label>
		</div>
		</div>
	  <div class="row">
	<div class="input-field col s12">
  <i class="material-icons prefix">info</i>
	  <input id="numerovuelo" type="text" class="validate">
	  <label for="numerovuelo">Número de vuelo</label>
		  </div>
		</div>
 	  
  	  <div class="row">
	<div class="input-field col s12">
  <h3 class="titulitos" align="center">HOSPEDAJE Y ALIMENTACIÓN</h3>
		  </div>
		</div>
		
	  <div class="row">
	<div class="input-field col s12">		
		<p>¿Tiene alguna preferencia respecto a su hospedaje?</p>
  	<input class="with-gap" name="preferenciahotel" type="radio" id="4">
			  <label for="4">Si</label><br>
	<input class="with-gap" name="preferenciahotel" type="radio" id="5">
			  <label for="5">No</label><br>
		  </div>
		</div>
		<br>
<div class="row">
	<div class="input-field col s12">
	<i class="material-icons prefix">note_add</i>
	<input id="cualhospedaje" type="text" class="validate">
	<label>En caso de que su respuesta sea afirmativa favor de especificar</label>
	  </div>
		</div>
		
<p class="parrafo">En caso de contar ya con el hospedaje:</p>
 
   <div class="row">
	<div class="input-field col s12">
  <i class="material-icons prefix">store</i>
	  <input id="hospedaje" type="text" class="validate">
	  <label for="hospedaje">Dirección del hotel</label>
		  </div>
		</div>
<div class="row">
	<div class="input-field col s12">
	<i class="material-icons prefix">phone</i>
	<input id="telefonohotel" type="text" class="validate">
	<label for="telefonohotel">Teléfono del hotel</label>	
	</div>
			</div>
<div class="row">
	<div class="input-field col s12">
		<p>Check-in</p>
	<input id="checkin" type="date" class="validate">
	</div>
			</div>
<div class="row">
	<div class="input-field col s12">
		<p>Check-Out</p>
	<input id="checkout" type="date" class="validate">
	</div>
	</div>
				
  
	  <div class="row">
	<div class="input-field col s12">
		<p>¿Tiene alguna preferencia respecto a su alimentación?</p>
	<input class="with-gap" name="preferenciacomida" type="radio" id="6">
			  <label for="6">Si</label><br>
	<input class="with-gap" name="preferenciacomida" type="radio" id="7">
			  <label for="7">No</label><br>
		  </div>
		</div>
	  <div class="row">
	<div class="input-field col s12">
	<i class="material-icons prefix">note_add</i>
	<input id="comida" type="text" class="validate"><br>
	  <label for="comida"> En caso de que su respuesta sea afirmativa favor de especificar</label>
		  </div>
		</div>
	  <div class="row">
	<div class="input-field col s12">	
		<p>¿Tiene alergias a algun alimento?</p>
	<input class="with-gap" name="alergias" type="radio" id="8">
			  <label for="8">Si</label><br>
	<input class="with-gap" name="alergias" type="radio" id="9">
			  <label for="9">No</label><br>
		  </div>
		</div>
		  <div class="row">
	<div class="input-field col s12">
	<i class="material-icons prefix">note_add</i>		
	<input id="quealergia" type="text" class="validate">
	<label for="quealergias">En caso de que su respuesta sea afirmativa favor de especificar</label>
			  </div>
		</div>
		  <div class="row">
	<div class="input-field col s12">
	<i class="material-icons prefix">forum</i>
 <textarea id="textarea1" class="materialize-textarea"></textarea>
          <label for="textarea1">Comentarios</label>
			  </div>
		</div>
	
	
<div align="center">	
  <button  class="btn waves-effect waves-light" type="submit" name="action">Enviar
    <i class="material-icons right">send</i>
  </button>
  </div>	
		</form>
		<br>
		<h5 class="parrafo" align="center">Gracias por su atención, le esperamos en el 5to. Encuentro de Jóvenes Investigadores en el Estado de Chihuahua, el próximo 7 y 8 de septiembre del 2017 en la Universidad Autónoma de Ciudad Juárez.</h5>
	</div> 
	</div>
	</div>
	<br>
	<br>	
<footer class="page-footer">
          <div class="container">
            <div class="row">
              <div class="col s12">
                <h4 align="center" class="white-text">Universidad Autónoma de Ciudad Juárez</h4>
                <h5 align="center" class="grey-text text-lighten-4">Dirección General de Vinculación e Intercambio</h5>
                <p align="center" class="grey-text text-lighten-4">Subdirección de Cooperación e Internacionalización</p>
				</div>
            </div>
          </div>
          <div class="footer-copyright">
            <div class="container">
            <p align="center"> © 2017</p>
            </div>
          </div>
        </footer>
            				
</body>
</html>
