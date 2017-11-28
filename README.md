En html armo estructura grid: genero un div row que contiene a la columna en la que irá el gatito
Colocar meta view <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
Creo 3 archivos ccs: media, main, grid.
En el html colocamos los estilos y enlazamos hojas de estilo:
	<link href="https://fonts.googleapis.com/css?family=Indie+Flower|Lobster|Montserrat" rel="stylesheet">
	<link rel="stylesheet" href="assets/css/main.css">
	<link rel="stylesheet" href="assets/css/grid.css">
	<link rel="stylesheet" href="assets/css/media.css">
En media.css coloco imagenes y con @media quires, para dar responsive design 
En grid.css coloco estilos de las columnas y filas, según grilla de 12[(n/12)*100]
En main.css personalizo estilos (estilos de imagenes, texto,etc.)
background-image: url(../images/sunny-day.jpg); imagen de fondo de la fila.
background-size: cover;
height: 100vh;(adecuar altura)
