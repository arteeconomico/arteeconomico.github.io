---
layout: post
og: true
og-type: article
title: "Artinpocket para dar un aire nuevo y personal a tu hogar y sin gastar mucho dinero" 
share: true
work: 2989
---

{% assign work_data = site.data.works.artworks | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_4-3">
			<core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensiones: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

Comprar arte es una forma de expresarse, **pásate a las obras de arte y decora tus paredes según tu forma de ser**. Conseguirás personalizar tu casa y le darás el toque que necesita para que sea cien por cien tu hogar. Nuestra oferta de obras de arte originales es amplia y exclusiva. ¡Ecuentra tu estilo y exprésate! !Escoge ARTE en [Artinpocket](http://www.artinpocket.cat/), no dejará a nadie indiferente!

Creatividad al poder, ya no tienes excusa para dejar tu espacio sin vestir y personalizar, utiliza piezas de arte originales y marca la diferencia. En Artinpocket tenemos el detalle personal que te falta; **un cuadro, una foto o un grabado. El complemento perfecto para tu salón, dormitorio o estudio**. 