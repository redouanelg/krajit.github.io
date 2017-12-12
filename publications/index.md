---
layout: page
title: Publications
permalink: /publications/
---

# Submitted/Working on..

<img align="left" src="https://raw.githubusercontent.com/redouanelg/redouanelg.github.io/master/images/eddynet.jpg" width="350" height="200"> Redouane Lguensat, Miao Sun, Ronan Fablet, Evan Mason, Pierre Tandeo, Ge Chen. **EddyNet: A Deep Neural Network For Pixel-Wise Classification of Oceanic Eddies** [pdf](https://arxiv.org/abs/1711.03954){:target="_blank"}

<br><br>
<br><br>
<br><br>

<img align="left" src="https://raw.githubusercontent.com/redouanelg/redouanelg.github.io/master/images/slainterp.png" width="350" height="200"> Redouane Lguensat, Phi Huynh Viet, Miao Sun, Ge Chen, Tian Fenglin, Bertrand Chapron, Ronan Fablet 
**Data-driven Interpolation of Sea Level Anomalies using Analog Data Assimilations**. [pdf](https://hal.archives-ouvertes.fr/hal-01609851){:target="_blank"}

<br><br>
<br><br>
<br><br>

# Selected journal papers

<img align="left" src="https://raw.githubusercontent.com/redouanelg/redouanelg.github.io/master/images/anda.png" width="350" height="100"> LGUENSAT Redouane, TANDEO Pierre, AILLIOT Pierre, PULIDO Manuel and FABLET Ronan. **The Analog Data Assimilation**. Monthly Weather Review, 2017, vol. 145, no 10, p. 4093-4107. [journal webpage](http://journals.ametsoc.org/doi/abs/10.1175/MWR-D-16-0441.1){:target="_blank"}

<br><br>
<br><br>
<br><br>

<img align="left" src="https://raw.githubusercontent.com/redouanelg/redouanelg.github.io/master/images/ieeeTCI.png" width="350" height="200"> Ronan Fablet, Phi Huynh Viet, and Redouane Lguensat. (2017) **Data-Driven Models for the Spatio-Temporal Interpolation of Satellite-Derived SST Fields**. IEEE Transactions on Computational Imaging 3:4, 647-657. [journal webpage](http://ieeexplore.ieee.org/document/8025578/){:target="_blank"}, [pdf](https://www.researchgate.net/publication/319474901_Data-driven_Models_for_the_Spatio-Temporal_Interpolation_of_satellite-derived_SST_Fields){:target="_blank"}

<br><br>
<br><br>
<br><br>

# Selected conference papers (still updating..)

<img align="left" src="https://raw.githubusercontent.com/redouanelg/redouanelg.github.io/master/images/oceans2016.PNG" width="350" height="80"> LGUENSAT Redouane, TANDEO Pierre, AILLIOT Pierre, FABLET Ronan, CHAPRON Bertrand
**Using archived datasets for missing data interpolation in ocean remote sensing observation series**. OCEANS 2016 - Shanghai : MTS/IEEE international conference, IEEE/MTS, 10-13 april 2016, Shanghai, China, 2016, pp. 1-6. [IEEExplore link](http://ieeexplore.ieee.org/document/7485433/){:target="_blank"}, [pdf](https://portail.telecom-bretagne.eu/publi/public/fic_download.jsp?id=65287){:target="_blank"}




{% comment %}
### Journal
{% for paper in site.data.publications.journal %}
 * {{paper.author}}. [{{paper.title}}]({{paper.url}}). *{{paper.journal}}*. Volume {{paper.volume}}-{{paper.number}}. Pages {{paper.pages}}. {{paper.year}}
{% endfor %}
### Conference
{% for paper in site.data.publications.conference %}
 * {{paper.author}}. [{{paper.title}}]({{paper.url}}). *{{paper.conference}}*. {{paper.year}}
{% endfor %}
{% endcomment %}
