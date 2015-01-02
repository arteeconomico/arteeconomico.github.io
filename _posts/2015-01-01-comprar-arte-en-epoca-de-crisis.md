---
layout: post
og: true
og-type: article
title: "Comprar arte en época de crisis" 
share: true
work: 2598
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


Probablemente en más de una ocasión hayas visto alguna obra de arte en alguno de sus múltiples formatos que te ha atrapado de tal forma que has pensado en llevártela contigo en ese mismo instante, comprarla para tenerla de forma permanente y para poder contemplar día tras día su imperecedera belleza. Pero cuando ha llegado el momento de decidir si la compras o no, de repente te ha invadido la duda, un sudor frío te ha recorrido la espalda y te ha parecido la idea más tonta que hayas tenido en los últimos años. **¿Comprar una obra de arte? ¿Ahora? ¿Para qué?** 

Si bien en los tiempos que corren, en los que la cultura está pasando por un momento trágico, podríamos pensar que comprar arte es una acto inútil, todos los estudios afirman que es precisamente en los tiempos de crisis cuánto más se revaloriza el mercado artístico. No lo decimos nosotros, lo afirma **Belén Herrera Ottino**, sales director de la **[galería Marlborough](http://www.galeriamarlborough.com/)** de Madrid, la filial española de la galería más importante del mundo: "*A lo largo del siglo XX y en el presente siglo hay una sorprendente correlación entre los debacles económicos y el boom artístico; en estos momentos, el coleccionista prefiere ampliar su colección que invertir en volátiles valores bursátiles. Comprando arte encuentra la oportunidad de realizar una inversión rentable en un contexto de incertidumbre económica*".

Ah, o sea que el arte resulta que es un bien económico que está considerado una fuente de riqueza continua porque a diferencia de otros activos, nunca perderá su valor sinó que tiende a revalorizarse con los años? Pues sí.

O sea que comprando arte, por un lado sacias tu sed cultural y sentido estético y por el otro **inviertes en un valor económico que lo único que puede hacer es ir a la alza**.

En **[Artinpocket](http://www.artinpocket.cat/)** defendemos que el arte debe de ser accesible a todos los bolsillos, por ése motivo te ofrecemos una selección de artistas emergentes con gran talento que no te dejaran indiferente y que seguro están a tu alcance.

Nunca es tarde para empezar una colección, y menos si es de arte. Hoy te invitamos a conocer la inquietante y crítica obra de **[Mateu Targa](http://www.artinpocket.cat/etiqueta-producto/mateu-targa-agusti/)**.