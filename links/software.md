---
title: Wiki -> Links -> Software
description: Software related to Wii Modding.
redirect_from: "/links/software.md"
---

# Software for the Wii

  Various Software for the Wii, broken down into four categories:

## ***WARNING!***

  Some of the software on this page can damage your Wii. Please know what you are doing before you utilize it.

## Emulators

  Here you will find links to emulators for the Wii.

{% for link in site.data.links_software.emulators %}
  * [{{ link.name }}]({{ link.url }}) - {{ link.description }}
{% endfor %}

## Loaders

  This section is for software that loads images of game titles through external storage

{% for link in site.data.links_software.loaders %}
  * [{{ link.name }}]({{ link.url }}) - {{ link.description }}
{% endfor %}

## Modding/Utility

  This is software that either helps you mod your Wii or is not an emu/loader

{% for link in site.data.links_software.utility %}
  * [{{ link.name }}]({{ link.url }}) - {{ link.description }}
{% endfor %}

## Archive - *Work in progress*

  This section is for software that should not be used or is kept here for archival purposes
  
  {% for link in site.data.links_software.archive %}
  * [{{ link.name }}]({{ link.url }}) - {{ link.description }}
{% endfor %}

