---
layout: post
og: true
og-type: article
title: "¡Conviértete en un coleccionista de arte sin salir de casa!" 
share: true
work: 1888
---

{% assign work_data = site.data.works.artworks | where:"id", page.work %}
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

**[Artinpocket](http://www.artinpocket.cat/)** es una galeria virtual que te ofrece la posibilidad de **ver y compar arte online**. El hecho de que sea una galería online tiene varias ventajas que debes de considerar si estás interesado en comprar arte. De entrada, nos permite tenir unos **precios mucho más económicos** que las galerías físicas y por otro lado, al sólo necesitar espacio virtual, tenemos **más cabida para artistas**. Esto quiere decir que gracias a Internet y desde el salón de tu casa puedes descubrir un sinfin de nuevos artistas emergentes con nuestra selección creada especialmente para que puedas acceder a poder tenir una pequeña colección de arte de pequeño formato en tu casa  que seguro que aumentará su valor con los años. Nuestro equipo está muy pendiente de todo aquello que se mueve en el mercado del arte contemporáneo emergente para podertelo llevar a casa.

Además en Artinpocket, apostamos por el arte digital, así que si eres de los minimalistas que prefieren no decorar las paredes de su salón pero no quieren renunciar a poder disfrutar de obras de arte, ahora te damos **la oportunidad de poder comprar obras de arte exclusivamente digitales con certificado de autenticidad** para que puedas tenerlas en tus dispositivos y contemplarlas las veces que quieras.