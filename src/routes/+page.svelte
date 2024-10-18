<!-- <title>Calendario Escolar</title>
<link rel="icon" href="logoo.png" type="image/x-icon" sizes="32x32 32x32">
<link rel="stylesheet" href="style inicio.css"> -->
<script>
	import fondo from '$lib/images/fondo.jpg';
</script>
<div class="background" style="background-image: url({fondo});">
	<div class="content">
		<nav>
			<ul class="menu">
					<li><a href="/">Inicio</a></li>
					<li><a href="/">Contacto</a></li>

					<li class="dropdown">
						<a href="/" class="dropbtn">Actividades</a>
						<div class="dropdown-content">
							<a href="deportivas">Deportivas</a>
							<a href="escolares">Escolares</a>
						</div>
					</li>
					<li><a href="/">Novedades</a></li>
				</ul>
			</nav>
		<h1>¡Bienvenidos al Calendario Escolar de la institución educativa LOLA GONZÁLEZ</h1>
		<br>
		<br>
		<p>
			Aquí podras enterarte de todos los eventos institucionales programados durante
			 la semana y ver las novedades diarias dentro de nuestra institución
		</p>
	</div>
</div>

<style>
	.background {
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		display: flex;
		justify-content: center;
		align-items: flex-start;
		min-height: 120vh;
	}

	.content {
		text-align: center;
		padding: 80px;
		background-color: rgba(255, 255, 255, 0.9);
		border-radius: 10px;
		box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
		width: 80%;
		max-width: 1200px;
		margin: 50px auto;

		margin-top: 100px;
	}

	h1 {
		font-size: 2.5em;
		margin-bottom: 10px;
	}

	p {
		font-size: 1.2em;
	}

	nav {
		background-color: #fdfdfd;
		padding: 10px;
		display: flex;
		justify-content: center;
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
		z-index: 1000;
	}

	.menu {
		list-style-type: none;
		margin: 0;
		padding: 0;
		display: flex;
	}

	.menu li {
		margin: 0 10px;
	}

	.menu li a,
	.dropbtn {
		display: inline-block;
		color: rgb(0, 0, 0);
		text-align: center;
		padding: 14px 16px;
		text-decoration: none;
	}

	.menu li a:hover,
	.dropdown:hover .dropbtn {
		background-color: #f8f3f3;
	}

	.dropdown {
		position: relative;
		display: inline-block;
	}

	.dropdown-content {
		display: none;
		position: absolute;
		background-color: #f9f9f9;
		min-width: 160px;
		box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
		z-index: 1;
	}

	.dropdown-content a {
		color: rgb(0, 0, 0);
		padding: 12px 16px;
		text-decoration: none;
		display: block;
		text-align: left;
	}

	.dropdown-content a:hover {
		background-color: #ffffff;
	}

	.dropdown:hover .dropdown-content {
		display: block;
	}
</style>
