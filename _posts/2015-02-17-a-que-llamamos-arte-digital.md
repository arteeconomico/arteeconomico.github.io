---
layout: post
og: true
og-type: article
title: "¿A qué llamamos Arte Digital?" 
share: true
work: 2078
---

{% assign work_data = site.data.works.artworks | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_4-4">
			<core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensiones: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

La innovación en los métodos de producción, la desmaterialización de la obra artística y sus nuevos medios de difusión hacen que nos enfrentemos a un cambio de paradigma en el modo de acercarnos a la obra artística. **El arte ha dejado de ser algo palpable y físico para convertirse an algo inmaterial, pura imagen**. Ha dejado de estar dentro de los museos y las galerías físicas para colarse en nuestros dispositivos digitales y para invadir nuestra vida cotidiana. Pero, ¿cómo consumimos éste tipo de Arte? Estamos preparados para absorber tal cantidad de información visual que nos llega de forma immediata? Y quizás lo más importante, ¿cómo hacer que perdure a lo largo del tiempo algo inmaterial y que depende tanto de la tecnologia? ¿Qué pasará con las obras de arte digital? ¿Las podemos considerar Arte?

**[Artinpocket](http://www.artinpocket.cat/)** nace precisamente de la necesidad de dar respuesta a todas estas preguntas y al creciente interés social y cultural que  despiertan los últimos movimientos artísticos que relacionan el ámbito del arte con la tecnologia y las nuevas corrientes de pensamiento.

Tenemos el objetivo de **impulsar la creación digital y promover y reformular su consumo**. Si cada vez más los artistas tienden a trabajar de forma digital , que sentido tiene esperar a tener la obra física si ha sido concebida para consumirse de forma tecnológica? El interés de los artistas y agentes culturales  por adaptar  el clásico modelo de comercialización del arte al arte digital ha dado lugar a nuestra plataforma, donde aceptamos diferentes soportes y formatos digitales para facilitar su venta y difusión.

**Comprar arte nunca había sido tan fácil**, ¿todavía tienes dudas? Date un paseo por nuestra galeria y descubre la opinión de nuestro clientes y las nuevas obras que hemos incluido en la plataforma. Esperamos que te gusten!