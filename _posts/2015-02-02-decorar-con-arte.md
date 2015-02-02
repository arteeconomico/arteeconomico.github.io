---
layout: post
og: true
og-type: article
title: "¿Decorar con Arte?" 
share: true
work: 1831
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

En **[Artinpocket](http://www.artinpocket.cat/)** encontrarás un amplio catálogo de obras de arte especialmente escogidas para ayudar a crear un entorno más apacible en tu hogar. Nacemos con la voluntad de acercarte **la creación artística más contemporánea al precio más asequible**. Porque las obras de arte no son sólo de uso exclusivo. En Artinpocket trabajamos para que el arte esté al alcance de todos. El Arte te ayuda a crear espacios con más carácter y es un elemento decorativo que va muy acorde con tu personalidad. En nuestra página puedes escoger las categorias que más te apetezcan acorde con tu estado emocional. Quieres obras que te aporten serenidad, alegria... visita nuestra página!