---
title: "Publications"
permalink: /publications/
layout: single
---

## Peer-Reviewed Publications

Below is a selected list of my peer-reviewed publications. A full list is also available on external academic profiles.

---

### Full profiles
- Google Scholar: https://scholar.google.com
- SLUpub (Swedish University of Agricultural Sciences): https://publications.slu.se

---

## Selected Publications

{% assign pubs = site.data.publications | sort: "year" | reverse %}

{% for p in pubs %}

### {{ p.title }}

**{{ p.authors }}** ({{ p.year }})  
{{ p.journal }} {{ p.volume }} {{ p.pages }}

*{{ p.role }}*

---

{% endfor %}

---

## Research Topics Represented

- Evolutionary and population genomics  
- Transcriptomics and RNA-Seq  
- Genomic prediction and breeding  
- Multi-omics data integration  
- Transposable elements and genome evolution  

---

## Manuscripts & Ongoing Work

Several manuscripts related to transcriptomics, pan-genomics, and genome evolution are currently in preparation or under review.
