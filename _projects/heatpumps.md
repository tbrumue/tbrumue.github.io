---
layout: page
title: Heat Pump Optimization
description: digital services for remote monitoring and optimization of energy efficiency of residential heat pumps
img: assets/img/project_profiles/hpexample.jpg
importance: 2
category: work
related_publications: BRUDERMUELLER/HPEfficiency, BRUDERMUELLER/2023121734, BRUDERMUELLER/10.1145/3600100.3623731, BRUDERMUELLER/9961055
---

Heat pumps play a crucial role in the decarbonization of the building sector. However, many heat pumps consume a considerable amount of electricity because they operate below the energy efficiency specified by the manufacturer. The majority of installed systems are not connected to the internet, and even the latest models lack an interface for standardized services.  This means that a high potential for energy and monetary optimization remains hidden and is lost, which leads to high operating costs for heat pump owners and puts a strain on the electricity grid due to increased total and peak electricity demand.

Therefore, as a PhD candidate in the [Bits to Energy Lab](https://www.bitstoenergy.com) at [ETH Zurich](https://www.im.ethz.ch), one area of focus for my work is analyzing data and developing machine learning algorithms to remotely monitor and optimize residential heat pumps in the field. In this context, I work with time series data from smart electricity meters (typically in 15-min resolution) and sensor data delivered by the heat pump directly (with typical resolutions in the range of a few seconds). 

For my research, I currently collaborate with multiple partners across industry and the public sector: [Swiss Federal Office of Energy](https://www.bfe.admin.ch/bfe/de/home.html), [Bosch](https://www.bosch-homecomfort.com/ch/de/wohngebaeude/home/), [EKZ](https://www.ekz.ch/de/privatkunden.html), [Enerlytica](https://www.enerlytica.com/), and [Hoval](https://www.hoval.ch/). Additionally, my algorithms are already being used in several digital energy consulting services to help Swiss households achieve higher levels of energy efficiency (e.g., [PERLAS](https://perlas.ch/de/)). For further information, please find a short interview in German language about the research project [here](https://www.ekz.ch/de/blue/innovation/2023/KI-zur-waermepumpenoptimierung.html) and a short science slam video (also in German language) [here](https://youtu.be/JFSeshpIkeE?feature=shared), in which I present my work to a non-scientific audience. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/heatmap_examples.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example: Heat maps showing patterns of electricity uptake of heat pumps identified as atypical and typical in terms of their on-off behavior.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/hpbenchmark.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example: Energy efficiency of a population of heat pumps benchmark against each other in terms of coefficient of performance.
</div>