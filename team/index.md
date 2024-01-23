---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## COSI Representative to Committee
Rafael Najmanovich, University of Montreal

## COSI Alternate Representative to Committee
Douglas Pires, University of Melbourne

## COSI Proceedings Liaison
Douglas Pires, University of Melbourne

## COSI Track Chair(s)
Rafael Najmanovich, University of Montreal
Douglas Pires, University of Melbourne

## ISCBacademy COSI Program Coordinator
Lam Su Datt, Universiti Kebangsaan Malaysia
Stephen Yi, The university of Texas at Austin

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.png" dark=false %}


{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
