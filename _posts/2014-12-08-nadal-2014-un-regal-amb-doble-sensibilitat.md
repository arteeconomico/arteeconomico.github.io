---
layout: post
og: true
og-type: article
title: "Nadal 2014, un regal amb doble sensibilitat" 
share: true
work: 3594
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

[Down Catalunya](http://sindromedown.cat/ca/) i **[Artinpocket](http://www.artinpocket.cat/)** uneixen esforços i creen la campanya **"Aquest Nadal sigues [#DoblementeSensible](https://twitter.com/hashtag/doblementesensible)"**, que té com a objectiu finançar les activitats que porta a terme la Coordinadora Síndrome de Down de Catalunya i, a la vegada, fomentar la compra d'art com a regal alternatiu i sensible amb la creació artística. En aquest sentit, han acordat que **el 10% de l’import de totes les vendes** que es facin durant tota la campanya de Nadal i Reis a través d’Artinpocket **es destinaran a Down Catalunya**.

Vols saber com ser #DoblementSensible? Aquest Nadal ho tens molt fàcil, amb una proposta exclusiva que et permet

1. Ajudar a finançar les accions de la Coordinadora Síndrome de Down de Catalunya
2. Fomentar la compra d’art com a regal alternatiu i sensible amb la creació artística.

Al mateix temps, el portal Artinpocket cedeix la seva plataforma per vendre i distribuir **[una obra]({{ work.permalink}} "{{ work.title }}") que el conegut ninotaire KAP ha creat per a l’ocasió i ha donat a Down Catalunya**. Aquesta obra tindrà una edició limitada de 100 exemplars a un preu de 40€ l’exemplar; el 90% d’aquest import es destinarà a Down Catalunya. Altres ninotaires podrien unir-se a aquesta campanya en les properes setmanes. 