---
layout: post
title: 'Col·leccionar art: per on començo?'
share: true
work: 3342
---

{% assign work_data = site.data.works.juanoles | where:'id', page.work %}
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

T'agradaria convertir-te en un col·leccionista d'art? Doncs és possible amb **Artinpocket**, la nostra plataforma et permet accedir a desenes d'obres sense moure't de casa. Tothom té dret a gaudir d'obres d'art originals i úniques no cal ser un expert en aquest sector. Podem anar aprenent les tendències, els estils i descobrir quines són les peces que més t'emocionen. Amb la compra d'art ajudes a que els artistes puguin continuar creant i evolucionant. 

Visita [www.artinpocket.cat](http://www.artinpocket.cat/) i aprofita les nostres promocions dins la campanya [#emocionart](http://www.emocio-nart.com/ofertes/).
