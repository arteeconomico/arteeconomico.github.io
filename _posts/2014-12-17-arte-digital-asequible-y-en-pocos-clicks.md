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

La Iª Mostra simultània d’art digital de Barcelona es presenta com una exposició simultània en diferents espais i edificis de referència de la ciutat. L’objectiu d’aquesta mostra es oferir al públic la possibilitat de descobrir i gaudir de l’art digital fora dels circuits expositius tradicionals. Oci, cultura i patrimoni es fusionen per oferir una experiència entorn l’Art Digital.

La finalitat d’aquesta mostra es divulgar la disciplina artística digital alhora que projectar i promocionar el treball de diferents artistes. Per aquesta finalitat s’han escollit nous espais i formats expositius. Artinpocket conjuntament amb el Convent de Sant Agustí i amb la col·laboració de IDODI i Blanz, han reunit més de 20 creadors d’art digital per realitzar aquesta primera exhibició.
