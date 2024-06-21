# Políticas de privacidad

Para publicar una app en google play se requiere disponer de una política de privacidad para tu aplicación, el siguiente ejemplo en html me sirvió para concretar la publicación:

```html
<html>
	<head>
		<meta charset='utf-8'>
		<meta name='viewport' content='width=device-width'>
		<title>Politicas de privacidad</title>
		<style> body { font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; padding:1em; } </style>
	</head>
	<body>
		<div id="contentWrapper">
			<div class="page-title title-1">
				<div class="container">
					<div class="row">
						<div class="cell-12">
							<h1 class="fx" data-animate="fadeInLeft"><span> Política de privacidad</span></h1>
						</div>
					</div>
				</div>
			</div>				
			<div class="padd-top-50">
				<div class="container">
					<div class="row">
						<p>Esta política de privacidad establece cómo TRANSPORTES GEMINIS usa y protege toda la información que usted proporciona al utilizar nuestra aplicación Gecof. TRANSPORTES GEMINIS está comprometido en la protección de su privacidad. Si le pedimos que nos proporcione cierta información por la cual usted puede ser identificado al usar este sitio web, puede estar seguro de que sólo se utilizará de acuerdo con esta declaración de privacidad. TRANSPORTES GEMINIS puede cambiar esta política en cualquier momento actualizando esta página. Usted debe visitar esta página periódicamente para asegurarse de que está de acuerdo con los cambios.</p>
						
						<h3><strong>Qué recogemos</strong></h3>
						<p>Su ubicación GPS</p>

						<h3><strong>Qué hacemos con la información recogida</strong></h3>
						<p>Necesitamos esta información para poder desplegar su ubicación en el mapa</p>
 
						<h3><strong>Seguridad</strong></h3>
						<p>Estamos comprometidos en garantizar que su información está segura. Para prevenir accesos no autorizados o revelación de datos utilizamos los sistemas más avanzados, actualizados y fiables disponibles.</p>

						<h3><strong>Uso de cookies</strong></h3>
						<p>Una cookie es un pequeño fichero que solicita permiso para almacenarse en su ordenador. Cuando usted acepta, el fichero se crea y la cookie ayuda a analizar el tráfico web o le facilita la visita a una web específica. Las cookies permiten a las aplicaciones web reconocerle individualmente. La aplicación web puede ajustar las operaciones a sus necesidades y preferencias recordando la información necesaria.
						Nuestra aplicación no utliza cookies.

						<h3><strong>Enlaces a otros sitios web</strong></h3>
						<p>Nuestra web puede contener enlaces a otros sitios de interés. Sin embargo, una vez utilice estos enlaces para abandonar nuestra web no tenemos control del sitio al que usted se dirige. Por tanto no somos responsables de su privacidad ni de la protección de los datos que usted proporcione mientras visita estos sitios web ya que éstos no están sujetos a esta política de privacidad. Le sugerimos operar con precaución y consulte la política de privacidad aplicable al sitio en cuestión.</p>

						<h3><strong>Control de su información personal</strong></h3>
						<p>Nuestra aplicación no recopila ninguna información personal de nuestros usuarios.</p>
					</div>
				</div>
			</div>
		</div>
	</body>
</html>
```
Una vez alojado en algún servidor, se debe indicar la url en la app mediante google play console.