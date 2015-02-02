---
layout: post
og: true
og-type: article
title: "Arte personalizado" 
share: true
work: 2022
---

{% assign work_data = site.data.works.artworks | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_3-4">
			<core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensiones: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

En **[Artinpocket](http://www.artinpocket.cat/)** te presentamos un amplio elenco de artistas, algunos de ellos tienen ya una trayectoria consolidada y otros emergente, pero seguro que daran de que hablar. Muchos de ellos suelen tratar siempre los mismos temas, acorde con su trayectoria, intereses o personalidad. Pero otros estan dispuestos a realitzarte aquella obra para aquella persona especial que quieres soprender. **Una forma muy original de hacer un regalo único y exclusivo es encargar una obra de arte a un artista que sea acorde a los intereses de la persona afortunada que va a recibir la obra**. No tiene porque ser una obra realista, puedes pedirle a un artista que plasme en una obra las sensaciones o emociones que tienes con una persona. No hay mejor regalo que aquel que está hecho desde el corazón, y si existen los artesanos de la emoción, estos son los artistas. Visita nuestra web donde podrás ver sus obras, informarte de su trayectoria y **compra arte, de puera a puerta**.