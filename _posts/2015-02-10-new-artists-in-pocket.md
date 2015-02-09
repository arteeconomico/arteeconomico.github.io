---
layout: post
og: true
og-type: article
title: "New artists in pocket!" 
share: true
work: 4050
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

Navegamos horas y horas por la web, nos perdemos entre los entresijos de los blogs más influyentes en cultura, nos hundimos entre colores, dibujos y fotografias. Nos mareamos hasta naufragar y finalmente **después de un largo periplo logramos dar con aquellos artistas que más encajan en nuestra plataforma y los que creemos que más se pueden adaptar a tus gustos**. Aqui los tienes, hoy te los presentamos. Puedes conocerlos visitando **[Artinpocket](http://www.artinpocket.cat/)**  y clicando en el menú de **[novedades](http://www.artinpocket.cat/tienda/?orderby=date)**.  Seguro que las obras no te dejaran indiferente, a nosotros no lo han hecho, por eso estan aqui. Artinpocket, arte con alma para gente con alma.

Te presentamos la obra de la fotógrafa **[Mercedes Fittipladi](http://www.artinpocket.cat/etiqueta-producto/mercedes-fittipaldi/)**, una obra emotiva y sugerente que  dará un toque  único y especial a tu espacio.