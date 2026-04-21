---
title: "Publications"
permalink: /publications/
layout: single
---

## Peer-Reviewed Publications

Below is a selected list of peer-reviewed publications. Full indexed profiles are available here:

- <a href="https://orcid.org/0000-0002-7873-8123" target="_blank">ORCID</a>
- <a href="https://www.scopus.com/authid/detail.uri?authorId=15130607200" target="_blank">Scopus</a>
- <a href="https://shorturl.at/eJRln" target="_blank">SLUpub (2022–2025)</a>
- <a href="https://scholar.google.com/citations?user=Hw6egegAAAAJ&hl=en" target="_blank">Google Scholar</a>
- <a href="https://www.webofscience.com/wos/author/record/AAV-4375-2021" target="_blank">Web of Science</a>

---

## Publications by Year

{% assign pubs = site.data.publications | sort: "year" | reverse %}

{% assign current_year = "" %}

{% for p in pubs %}

{% if p.year != current_year %}
{% assign current_year = p.year %}

## {{ current_year }}

{% endif %}
### <a href="{{ p.doi }}" target="_blank">{{ p.title }}</a>
{{ p.authors }} ({{ p.year }}).  
*{{ p.journal }}{% if p.volume != "" %}, {{ p.volume }}{% endif %}{% if p.pages != "" %}, {{ p.pages }}{% endif %}.*

{{ p.role }}
---
{% endfor %}

## Research Areas

- Population and evolutionary genomics  
- Functional genomics and transcriptomics  
- Disease resistance genetics  
- Genomic prediction and breeding  
- Multi-omics integration  
- Animal biotechnology  

---

## Ongoing Work

Current projects include transcriptomics, pan-genomics, structural variation, livestock resilience, and genome evolution.
