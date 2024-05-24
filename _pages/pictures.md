---
title: "Zanne Lab - Pictures"
layout: piclay
excerpt: "Zanne Lab -- Pictures"
permalink: /pictures/
---

# Pictures
Jump to: [Gallery](#gallery), [Art from Donna](#art-from-donna), [Brazil Fieldwork December 2019](#brazil-fieldwork-december-2019), [Australia Fieldwork June 2019](#australia-fieldwork-june-2019)


#### Australia Fieldwork June 2019
{% assign number_printed = 0 %}
{% for pic in site.data.aus %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>

#### Gallery
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>

#### Art from Donna
##### Check out some of Donna's artwork on the decomposition process, captured in video form!

##### [DE-CAY-dence](https://vimeo.com/538499033)
Donna's statement on‘DE-CAY-dence’: My work explores ecological relationships in an effort to try and understand the complex dichotomy between humans and nature with respect to climate change. In reality without a healthy ecosystem, humans and life could not exist, we are intrinsically linked and therefore share the same fate.

This work explores inter-species relationships using 'hidden players' to consider the complex issue of the carbon economy and climate change; the currency of the work is drawn from a scientific research project that investigates tropical deadwood decomposition.

Hidden players essential for this process, such as termites, microbes and fungi are quietly hard at work cycling nutrients, which support the ecological health of our planet. In contrast, humans are consuming resources to fuel our unsustainable, and often-decadent lifestyles.

Through subtle reflections of the viewer is each screen, these ecological portraits simultaneously present these players alongside the human inviting contemplation about roles and accountability within the biosphere.

Playing with the concept of Who IS the fairest' the work challenges our unconscious bias with respect to terms such as pest, germ, decay, versus notions of beauty, value and status; to explore how these beliefs inform our ecological understanding and action.

With the health of ourselves and our planet, both impending concerns at the moment, reflecting on these theme endeavors to provide a platform to consider imagined futures wherein relationships with multi-species kin are respects, understood and equally valued; inviting the viewer to reflect on their own multi-species perspective and personal contribution to the interconnected ecological sphere of life.

##### [DE-Compose](https://vimeo.com/644593938)
Donna's statement on 'DE-Compose': Single channel projection installation that explores hidden ecological players alongside the human in an effort to try and understand the complex dichotomy between humans and nature with respect to the ecological health of our planet.

Hidden players such as termites, fungi and microbes play an intrinsic role the ecological health of our planet, however are often met with unfavorable connotations such as pest, germ and decay. This work seeks to challenge unconscious bias with respect to such notions to explore how our beliefs inform our ecological understanding and actions; inviting contemplation about inter-species relationships, roles and accountability within the biosphere.

This work was created in response to the 'Wood, Termite, Fungi Project' led by George Washington University, a project that is investigating tropical deadwood decomposition. Special thanks to Rebecca Clement for supplying micro imagery of the termites featured in this work.

{% assign number_printed = 0 %}
{% for pic in site.data.donna %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>

#### Brazil Fieldwork December 2019
{% assign number_printed = 0 %}
{% for pic in site.data.brazil %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>

#### Australia Fieldwork June 2019
{% assign number_printed = 0 %}
{% for pic in site.data.aus %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>
