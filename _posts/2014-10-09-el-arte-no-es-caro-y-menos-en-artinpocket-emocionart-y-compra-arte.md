---
layout: post
title: El arte no es caro y menos en Artinpocket, "#Emocionart" y compra arte 
share: true
work: 3310
---

{% assign work_data = site.data.works.jordimitja | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_9-16">
			<core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensiones: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

[Artinpocket](http://www.artinpocket.cat/) te abre las puertas y te propone descubrir su colectivo de artistas y te ofrece sus obras de arte a muy buen precio. [#Emocionart](http://www.artinpocket.cat/product-category/emocionart/) es una acción para promocionar e impulsar la compra de arte a precios asequibles, esta semana y de forma exclusiva os presentamos Veure les estrelles un Fotograbado sobre papel Arches manipulado a mano. Edición de 50 ejemplares numerados y firmados. 28x38 cm.

Edición realizada por Jordi Mitjà con motivo de la campaña de [crowdfunding](http://www.verkami.com/projects/8133-tipografia-artinpocket-regular) para desarrollar la tipografía constructivista diseñada para títulos y destacados [Artinpocket](http://www.artinpocketregular.com/download/). Esta obra está vinculada a un código QR que incluye el poema: [veure les estrelles](http://www.artinpocketregular.com/general/home/2014/07/19/veure-les-estrelles/). Edita: Artinpocket.

-----------

<p><small><strong>Oferta sólo de este mes de octubre</strong> por la compra del fotograbado te ofrecemos una lámina con las letras de la nueva tipografía de edición limitada (150 ejemplares) y la postal con el logo de la campaña. Valorados en 15 €.</small></p>

-----------

##Jordi Mitjà

Des de múltiples registros de presentación - la escultura o la fotografía pasando por la publicación o el video- la obra de [Jordi Mitjà](http://www.jordimitja.com/?cat=30) plantea la apropiación de diversos contextos, situaciones, medios o producciones externas que el artista lleva hábilmente a su terreno, en base de una alta complicidad emocional con los referentes y puntos de partida que escoge.  Una dinámica de trabajo compleja y obsesiva que, que más allá de su formalización expositiva, concentra su intensidad en el proceso de producción y en el tiempo de negociación entre la idea inicial y la resolución final; hecho que incorpora de manera voluntaria aspectos flexibles y libres como la intuición, el ensayo, el error o el accidente.

Ha presentado sus proyectos en numerosas exposiciones, tanto individuales como colectivas. Participa también en proyectos editoriales y crea juntamente con Jesús Novillo y Carolina Trebol la editorial Crani. Estos últimos años ha consolidado su presencia dentro la escena artística nacional y también ha realizado residencias en Ciudad de México y en Sâo Paulo. Ha participado en las exposiciones inaugurales del Bòlit, Centre d’Art Contemporani de Girona y del Canòdrom de Barcelona; y su obra se encuentra en colecciones públicas, como el Museu de l’Empordà, la Mediateca de la Fundación “La Caixa”, o en el Centro Galego de Arte Contemporánea (CGAC), entre otros.