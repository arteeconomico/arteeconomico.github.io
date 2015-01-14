---
layout: post
og: true
og-type: article
title: "¿El futuro del arte será el arte digital?" 
share: true
work: 2118
---

{% assign work_data = site.data.works.artworks | where:"id", page.work %}
{% assign work = work_data | first %}
<figure class="text-center">
	<div class="padding-artwork-container">
		<div class="embed-container embed-container_4-4">
			<core-image sizing="cover" class="core-image-size" preload fade src="{{ work.featured_src }}"></core-image>	
		</div>
	</div>
	<figcaption>
		<p><small><strong>{{ work.title }}</strong> | {% if work.downloadable == true %} digital art{% else if %} dimensiones: {{ work.dimensions.length }}x{{ work.dimensions.height }} {{ work.dimensions.unit }}{% endif %}</small></p>
		<p><a href="{{ work.permalink }}" class="btn btn-primary btn-lg">¡{% if sale_date > site.sale-end %}{{ work.regular_price }}{% else if %}{{ work.price_html }}{% endif %}! ¡comprar! <i class="fa fa-credit-card"></i></a></p>
	</figcaption>
</figure>

Mucho se habla sobre el sentido del arte en la época actual. **Oímos frases que sentencian que el “Arte está muerto”**, discursos que especulan sobre su función social, se critica y infravalora el trabajo de los artistas, y se les considera como integrantes de una extraña raza humana que tiende a moverse entre guetos elitistas.

¿Será cierto? ¿No puede existir futuro para un medio de expresión plástica en la era digital? **En [Artinpocket](http://www.artinpocket.cat/) discrepamos**. Creemos que es cierto que el Arte no tiene futuro, pero precisamente porque **es un medio que se construye y retroalimenta del presente y para el presente**, el Arte nace con una clara función social, es un espejo que refleja lo mismo que nuestra sociedad proyecta. Si vamos a toda velocidad, el arte irá a toda velocidad. Por eso creemos que afirmar que el Arte está muerto hoy en día, es tener los ojos cerrados a nuestra sociedad.

El Arte se transforma, vive del presente y si alguna vez en toda la historia podemos decir que ha existido arte, es en la actualidad. Nunca antes hemos estado tan rodeados de imágenes como hoy en dia. La creatividad y la innovación empiezan a tener un papel importantísimo en el desarrollo de las empresas, y de eso los artistas, saben un poco.

Quizás si que es cierto que el mercado del arte “tradicional” como tal está en caída libre pero eso no quiere decir que debamos asistir a su entierro, sinó todo lo contrario. **Asistimos a una cambio radical en como el arte se produce y se consume**, además de una democratización total de los medios de producción, que ha provocado que un adolescente con tan sólo un iphone pueda arrasar en las redes sociales con sus fotos.

Claramente el arte digital està ganando mucha fuerza en los circuitos artísticos por ser facilmente consumido en dispositivos portátiles. **De [nuevos artistas digitales](http://www.artinpocket.cat/categoria-producto/digital/) y de nuevas corrientes artísticas en Artinpocket, sabemos un rato**, así que navega por nuestra web, descubre, y pregunta. ¿Alguna duda? ¡Aqui estamos!