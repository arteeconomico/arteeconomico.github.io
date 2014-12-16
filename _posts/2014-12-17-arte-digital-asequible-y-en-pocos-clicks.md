---
layout: post
og: true
og-type: article
title: "Arte Digital, Asequible Y En Pocos Clicks" 
share: true
work: 1793
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

La tecnología avanza a pasos agigantados, de forma exponencial, dicen los expertos, y son los usuarios los que se adaptan a estas nuevas utilidades tecnológicas. ¿Y el arte? El arte es reflejo de la sociedad en la cual vivimos. Pero, ¿la sociedad está preparada y concienciada con el arte actual? Difícil pregunta y complicada respuesta. Muchas veces nos aproximamos al arte con una visión anclada en el **siglo XIX**, con la concepción romántica del **artista excéntrico y la obra única e irrepetible**.

Avancemos dos siglos. Estamos en el **siglo XXI** y se puede comprar arte adaptado a este tiempo, el denominado **arte digital**. ¿Y como se consume? Muy fácil, el arte ya no hace falta que sólo esté colgado en una pared, en un soporte o en un museo, lo puedes tener al alcance de tu bolsillo, en los dispositivos más utilizados hoy en día: **en el móvil y en la tablet**... en definitiva, **en cualquier pantalla**. Es arte hecho y pensado para ser consumido en píxeles.

¿Cómo comprar este tipo de arte? **[Artinpocket](http://www.artinpocket.cat/) es la respuesta**. Te puedes convertir en coleccionista de arte a muy bajo coste, ya que puedes seleccionar entre más de 100 obras de arte digital. 

Así de sencillo: arte actual asequible en unos pocos clicks.