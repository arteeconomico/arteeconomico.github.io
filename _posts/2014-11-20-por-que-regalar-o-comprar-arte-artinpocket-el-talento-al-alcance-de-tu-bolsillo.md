---
layout: post
og: true
og-type: article
title: "¿Por qué regalar o comprar arte? Artinpocket el talento al alcance de tu bolsillo" 
share: true
work: 3444
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

En **[Artinpocket](http://www.artinpocket.cat/)** lanzamos la campaña **[#Emocionart](http://www.emocio-nart.com/)** para promocionar la venta de obras de arte. Os podéis preguntar, ¿por qué comprar arte? No hablamos de comprar arte de miles y miles de euros, hablamos de comprar un grabado o una pequeña pieza en vez de salir una noche a cenar y de copas o comprarnos unos zapatos que nos gustan mucho. Hablamos de **comprar una obra de arte original en vez de regalar, estas navidades, el típico perfume o una joya**. Y por supuesto, hablamos de comprar **un objeto único y exclusivo** en vez de entrar en unos grandes almacenes a comprar una pieza sin alma. 

En Artinpocket os ofrecemos la posibilidad de acceder a obras de arte originales de jóvenes creadores a un precio accesible y unas condiciones únicas. Más de 60 creadores y cerca de 500 obras te esperan en Artinpocket. Seguramente alguna de ellas se adapte a tu gusto y a tu bolsillo. Artinpocket **el talento al alcance de tu bolsillo**.