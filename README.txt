Big Picture de HTML5 UP
html5up.net | @ajlkn
Gratis para uso personal y comercial bajo la licencia CCA 3.0 (html5up.net/license)


Esta es Big Picture, una plantilla de sitio simple y receptiva de una sola p�gina de HTML5 UP.

�ltimamente he estado en una sola p�gina, en parte porque soy vago, pero
sobre todo porque patean traseros para experimentar. En este caso, Big Picture
hace un uso intensivo de mi "desplazamiento progresivo" (provisionalmente nombrado y que pronto se lanzar�)
y los complementos jQuery de "scrollwatch" para lograr algunos efectos interesantes a medida que
desplazarse por la p�gina. Adem�s de dichos efectos interesantes, Big Picture
tambi�n incluye una bonita galer�a de estilo lightbox, estilo para elementos de p�gina b�sicos,
y c�digo completamente comentado para su placer de edici�n (�con instrucciones!
-- vea abajo).

Muchas gracias a mis buenas amigas Felicia Simion (ineedchemicalx.deviantart.com)
y Michael Domaradzki (md.photomerchant.net) por permitirme usar sus incre�bles
fotos en la demostraci�n de Big Picture *.

(* = �No incluido! Solo para usar con mi propia demostraci�n en el sitio, as� que NO
descargar y / o usar cualquiera de los trabajos de Felicia o Michael sin su expl�cito
�permiso!)

AJ
aj@lkn.io | @ajlkn

PD: �No est� seguro de c�mo hacer funcionar ese formulario de contacto? Prueba Formspree.io (es incre�ble).


Instructions:

	Overview:

		Being a single pager, Big Picture should be way simpler to work with than
		some of the heavier stuff I've released in the past. In fact, aside from
		a main page <header> and <footer>, it's pretty much just a stack of "main"
		<section> elements that follow the same basic pattern:

			<section id="foobar" class="main">
				<div class="content container">
					<header>
						<h2>Foobar</h2>
					</header>
					...
				</div>
			</section>

		The section can then be assigned a style class to determine its basic
		look (and, in some cases, its behavior):

			style1
				Centered content with an oversized <h2>. Works best when
				paired with a background image or color.

			style2 left
				Content in a box, anchored to the left side of the window. Works
				best when paired with a background image or color. If you have
				"useSectionTransitions" turned on in your settings, the box will
				slide into view from the left.

			style2 right
				Content in a box, anchored to the right side of the window. Works
				best when paired with a background image or color. If you have
				"useSectionTransitions" turned on in your settings, the box will
				slide into view from the right.

			style3 primary
				Used for generic content. Set against the primary background
				color (default is white).

			style3 secondary
				Used for generic content. Set against the secondary background
				color (default is a light gray).

		Oh, and there are a few (well, two) optional modifier classes you can
		tack on for additional effects:

			dark
				Flips the content's color scheme so it shows up better
				against darker background images and colors.

			fullscreen
				Makes the section fill the entire window (only if "useFullScreen"
				is enabled in your settings).


	Lightbox Gallery:

 		The actual gallery function is powered by my Poptrox plugin. For info on
 		how that works, go here: github.com/ajlkn/jquery.poptrox

		Each image (the '...' bit in the above examples) should look like this:

			<article class="from-(direction)">
				<a href="path/to/fullsize.jpg" class="image fit">
					<img src="path/to/thumbnail.jpg" title="This is the image caption." alt="" />
				</a>
			</article>

		The "from-(direction)" class indicates the direction from which the image should
		slide into view, and can be any of the following:

			from-left
			from-right
			from-bottom
			from-left

		You can also just remove the "from-(direction)" class if you don't want that particular
		image to slide into view (in which case it'll simply fade in).


	Contact Form:

		To get this working, place a script on your server to receive the form data, then
		point the "action" attribute to it (eg. action="http://mydomain.tld/mail.php").
		More on how it all works here: 1stwebdesigner.com/tutorials/custom-php-contact-forms


    Icons:

     	Powered by Font Awesome. Go here for a full listing of all the icons you can use:
     	fontawesome.io


	Other Stuff:

		- If you don't like the way images are tinted, either change "images/overlay.png"
		  to something else, or remove all references to it from css/style.css.


Credits:

	Demo Images:
		Felicia Simion (ineedchemicalx.deviantart.com)
			"The Swallow Song"
			"Mind is a clear stage"
			"The Anonymous Red"
			"The sparkling shell"
			"Carry on"

		Michael Domaradzki (md.photomerchant.net)
			"Vine Country"
			"Airchitecture II"
			"Bent IX"
			"Air Lounge"

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		Poptrox (github.com/ajlkn/jquery.poptrox)
		Scrollex (github.com/ajlkn/jquery.scrollex)
		Responsive Tools (github.com/ajlkn/responsive-tools)