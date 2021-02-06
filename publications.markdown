---
title: Publications
permalink: /publications/
order: 1
---


{% comment %} Store the count of publication groups {% endcomment %}
{% capture book_count %}{% bibliography_count -q @book[author ~= Giuseppi] %}{% endcapture %}
{% capture incollection_count %}{% bibliography_count -q @incollection[author ~= Giuseppi] %}{% endcapture %}
{% capture article_count %}{% bibliography_count -q @article[author ~= Giuseppi] %}{% endcapture %}
{% capture inproceedings_count %}{% bibliography_count -q @inproceedings[author ~= Giuseppi] %}{% endcapture %}
{% capture other_count %}{% bibliography_count -q @techreport[author ~= Giuseppi] @unpublished[author ~= Giuseppi] %}{% endcapture %}

<script src="https://bibbase.org/show?bib=https%3A%2F%2Fraw.githubusercontent.com%2FAGiuseppi%2FAGiuseppi.github.io%2Fmaster%2Fpubs.bib&jsonp=1&group0=year&group1=document_type&theme=simple&hidemenu=true"></script>

