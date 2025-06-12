---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

## Plant Gene Discovery Platform

<p align="justify">
    The Plant Gene Discovery Platform is an open-source initiative focused on integrating genomic, transcriptomic, and regulatory data to accelerate the identification of biotechnologically relevant genes in non-model agricultural species. Designed for biotechnologists and bioinformaticians, the platform combines network analyses (such as gene co-expression networks and regulatory networks), providing a unified view of complex biological mechanisms, such as stress response. Its modular design allows continuous incorporation of public data (e.g., genomic annotations, SRA datasets) and computational tools, while APIs ensure interoperability between services, such as pipeline execution and database queries. With a focus on accessibility and reproducibility, the platform aims to overcome existing resource fragmentation, democratizing access to integrative analyses for agronomically significant species, such as soybean and eucalyptus. 
</p>

## Projects

{% for post in site.posts %}

  <h3>{{ post.title }}</h3>
  <p>{{ post.excerpt }}</p>
{% endfor %}

## Publications

<p align="justify">
FLORES, Lorrana Verdi et al.. TITLE. In: X-Meeting presentations. Anais...João Pessoa(PB) Local, 2025. Available in: <a href="" target="_blank">xmeeting-2025-number</a>. Access in: 00/00/2025.
</p>

<p align="justify">
FLORES, Lorrana Verdi et al.. TITLE. In: X-Meeting presentations. Anais...João Pessoa(PB) Local, 2025. Available in: <a href="" target="_blank">xmeeting-2025-number</a>. Access in: 00/00/2025.
</p>
