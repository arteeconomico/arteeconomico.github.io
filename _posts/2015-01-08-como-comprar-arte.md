---
layout: post
og: true
og-type: article
title: "¿Cómo comprar arte?" 
share: true
work: 3746
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

¿Cómo saber que una obra de arte vale la pena más allá de su valor estético? ¿Merece realmente el precio que estoy pagando por ella? **A la mayoría de personas nos cuesta invertir en una obra** ya que la propia atmósfera elitista que rodea al mundo del Arte se ha encargado de hacernos sentir incultos ante una obra. Parece que la ciudadanía no pueda llegar a entender el arte contemporáneo. Todos hemos oído la frase “Yo, de Arte no entiendo” o la mítica : “¿Esto es Arte?, ¡Esto también lo hago yo!”

Y sí, digamos que desde que Duchamp se inventó el readymade y se plantó con su Fontaine en el Salón de los artistas independientes de Nueva York en 1917, las cosas para los artistas se han puesto mucho más complicadas.

¿Cómo saber lo que es Arte y lo que no? ¿Lo que vale la pena comprar o lo que no si hoy en día todo puede ser considerado Arte? Es cierto, todo depende del concepto que se le dé pero **[en Artinpocket te damos algunas pistas](http://www.artinpocket.cat/guia-para-comprar-arte/)** para saber si lo que estás comprando realmente puede estar bien valorado en un futuro.

Digamos lo que te digamos, ten en cuenta que lo primero que tiene que hacer una obra es gustarte, por muy obvio que te parezca. Sigue tu intuición. Ya te podemos decir quién será el próximo artista más valorado, que si no lo puedes ni ver, mejor que lo dejes dónde está.

**Las obras que perduran, son las que mueven y hacen vibrar, las que te dicen alguna cosa o por algo llaman tu atención**. Y para diferenciarlas, lo que tienes que hacer es comparar. **Mira, investiga, navega y pregunta**. Aunque a veces te parezca imposible, toda obra por muy abstracta que sea, tiene una explicación. Y si alguien sabe de dar largas explicaciones sobre el concepto de una obra éstos son los críticos, así que, aunque no te creas todo lo que dicen, sígueles la pista. 

Y por último, fija un presupuesto a tu compra. Aunque te parezca increíble, **no hace falta ser millonario para empezar a comprar obras**. Puedes invertir en obra de artistas consagrados mediante la compra de serigrafías o grabados. Si lo que te va es la compra de arte emergente, único y original, entonces **[Artinpocket](http://www.artinpocket.cat/)** te puede ayudar. En la web encontrarás obras de más de cincuenta artistas emergentes con un gran potencial. ¿Tienes alguna duda? [Pregúntanos](http://www.artinpocket.cat/contacto/), ¡estaremos encantados de asesorarte!