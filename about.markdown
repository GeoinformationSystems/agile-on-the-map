---
layout: page
title: About
permalink: /about/
---

## Motivation

Efficient discovery of scholarly outputs is crucial for conducting research.
Today, the discovery often relies on text searches using keywords, ontologies, or full texts.
**Geospatial metadata** is a powerful but underused dimension of scholarly discovery, enabling place- and time-based exploration of research outputs.
In this [AGILE initiative](https://agile-gi.eu/proposing-activities/proposing-an-initiative), a student research assistant conducts an iterative geospatial mapping or georeferencing of publications published as part of the [AGILE conference series](https://agile-gi.eu/past-conferences).
This work puts all research published through AGILE literally “on the map” across disciplines.

## Approach

The georeferencing begins with the most recent year (2025) and proceeds backwards until funds are exhausted.
Open Access publications are prioritized, including early self-hosted proceedings before 2008, followed by commercially published volumes (Springer LNGC, 2008-2019).
All contribution types (full papers, short papers, and poster abstracts) are included to ensure comprehensive coverage of research outcomes.
Each publication is reviewed manually to extract geographic regions, time periods, and [concepts](https://eo4geo-bok.firebaseio.com/.json) of the latest [EO4GEO Body of Knowledge](http://www.eo4geo.eu/bok/) (BoK).
After each year's manual georeferencing, two weeks (one development sprint) are dedicated to integrating automation techniques (e.g., NLP, LLMs, or metadata extraction from linked data) and applying them to the mapped (reference) and unreviewed publications.
The priority remains on maximizing coverage, even if manual work is required.

The mapping is conducted based on the projects [OPTIMAP](https://github.com/GeoinformationSystems/optimap) by the Chair of Geoinformatics, TUD Dresden University of Technology, and [geoextent](https://github.com/nuest/geoextent/).
OPTIMAP features harvesting and manual curation of publication metadata.
geoextent automatically extracts geospatial metadata for data files.
The initiative extends (a) OPTIMAP to showcase the AGILE publications as a collection at <https://optimap.geo.tu-dresden.de/agile-gi> and to model BoK metadata, and (b) geoextent to integrate existing approaches for georeferencing textual publications.
All project outcomes, including an end of project report, are published with DOIs under open licenses.

## Expected benefit

The initiative creates a comprehensive, openly available geospatial index of AGILE conference publications to improve discovery and interdisciplinary reuse by enabling place- and time-based exploration of publications and by supporting meta-analyses.
It thereby benefits AGILE members, because their work is highlighted and discoverable in a novel fashion, spanning across disciplinary and topical boundaries.
Exploiting the integration with OPTIMAP, publications could eventually become part of open knowledge graphs such as [Wikidata](http://www.wikidata.org/) or the [NFDI4Earth Knowledge Hub](https://knowledgehub.nfdi4earth.de/).
Furthermore, AGILE takes a leading role in new ways to discover, present, and monitor research works using the integrative power of space and time.
The methods, tools, and outcomes of the project may also serve as the basis to acquire further funding to map research outputs beyond the field of GIScience, or to develop an location-enhanced Open Science Observatory for GIScience beyond the AGILE conference.
This observatory can build a network with diverse research contributions, i.e., linking publications, datasets, software, projects, institutions, and people.

## Team

- Daniel Nüst (PI, <daniel.nuest@tu-dresden.de>)
- Tom Niers (<tom.niers@tu-dresden.de>)
- NN (student developer)
