---
layout: post
og: true
og-type: article
title: "Llena tu casa de luz y creatividad" 
share: true
work: 2602
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

**¿Hace años que no has cambiado nada en tu salón? ¿Te aburre el aspecto de tu dormitorio? ¡Pues apuesta por el arte!** Es la manera ideal para darle un aire nuevo, personal y exclusivo a tú casa. Las obras de arte originales de **[Artinpocket](http://www.artinpocekt.cat/)** no dejaran indiferente a nadie. ¡Así de fácil es actualizar tu estilo!

>Una magnífica idea para dar un aire nuevo y personal a tu hogar y sin gastar mucho dinero

Introducir arte en tu hogar o en tu oficina ofrece un aspecto moderno y actual, además de ser original, exclusivo y propio. Un mundo mágico. Un espacio donde poder hacer volar la imaginación, así transforma una obra de arte tu salón. Calor reconfortante. El arte y la sensibilidad del artista pueden formar parte de tu hogar. Las obras de arte original que te ofrecemos en Artinpocket te ofrecen la posibilidad de **transformar tus espacios en lugares únicos y exclusivos**.