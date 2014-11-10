---
layout: post
title: '¿Te has planteado hacer un regalo muy especial?... ¿Regalar arte?'
share: true
work: 3334
---

{% assign work_data = site.data.works.juanoles | where:'id', page.work %}
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

El arte nos hace ser más sensibles al mundo que nos rodea. ¿Te has planteado hacer un regalo muy especial? Un regalo original y único, algo que puede hacer dibujar una sonrisa en su rostro. **Regalar arte** ¿Qué aporta el arte nuestras vidas?

**Artinpocket es arte al alcance de todos los bolsillos** ¿Arte? seguramente a todos nos vienen a la cabeza, Dalí, Barceló, Picasso o van gogh  ergo obras de arte fuera de nuestro alcance, pero el arte no acaba en las grandes figuras la oferta actual es muy grande y con variedad de precios asequibles como los que ofrecemos en Artinpocket dónde puedes  conseguir obras de gran calidad al alcance de tu bolsillo.

**Tú puedes ser un mecenas**. Muchos de los grandes maestros de la historia del arte  fueron apoyados y pudieron destacar  y llegar tan lejos porque hubo  alguien que, en un momento determinado, confió en ellos, vio su potencial y apostó por su talento. Comprando una obra, participas y das apoyo a los artistas para que puedan seguir creando y que de esta forma el Arte siga vivo.

**Un nuevo mundo a tus pies**. Regalar arte dice mucho de ti, de tu sensibilidad, de tu buen gusto y de tu inquietud cultural. El regalo es siempre una tarjeta de visita de la persona que lo aporta, por eso si regalas arte también tú obtienes algo a cambio.
