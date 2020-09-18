---
layout: page
title: Appraising
description: "Guidance for curators during the data appraisal stage."
lang: en
ref: appraising
---

*(data assessment, evaluation, review)*

In this stage of the lifecycle, a data deposit is reviewed for completeness and compliance with a repository’s terms of use, and the overall FAIRness of the deposit may be assessed. A curator may work with the research team to enhance the usability and accessibility of the dataset. The Data Curation Network's [CURATED checklist](https://datacurationnetwork.org/resources/) is one framework that will guide a curator through the curation process. Steps include checking and understanding the data files and associated documentation, requesting missing information, augmenting metadata for findability, transforming files if necessary, evaluating the FAIRness of a deposit, and documenting all curation activities.

Some of the tasks a curator may perform:
- Check datasets for compliance with the repository terms of service
- Perform quality assurance through file audit and code review
- Assess files for disclosure risk or intellectual property concerns
- Review, enhance, or create documentation
- Help select an appropriate license for the data
- Make recommendations on file formats for accessibility in the short and long term
- Verify metadata quality and augment or restructure to facilitate discoverability and interoperability
- Request missing or ambiguous information or changes from data creators

Relevant tools and resources:

<ul>
  {% assign postlang = site.data.navigation.languages %}
  {% for item in postlang %}
  {% for post in site.posts %}
      {% if item.language == page.lang %}
      {% if post.lang == page.lang %}
      {% if post.categories contains "appraising" %}
          <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
      {% endif %}
      {% endif %}
  {% endfor %}
  {% endfor %}
</ul>
