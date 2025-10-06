---
title: 'Variant representation in RDF'
title_short: 'Variants in RDF'
tags:
  - Variant representation
  - Ontology alignment
  - RDF
  - Data interoperability
authors:
  - name: Núria Queralt-Rosinach
    orcid: 0000-0003-0169-8159
    affiliation: 1
  - name: Alexander Jonathan Kellmann
    orcid: 0000-0001-6108-5552
    affiliation: 2
affiliations:
  - name: Leiden University Medical Center
    index: 1
  - name: University Medical Center Groningen
    index: 2
date: 27 February 2025
cito-bibliography: paper.bib
event: BH25JP
biohackathon_name: "SWAT4HCLS BioHackathon 2025"
biohackathon_url:   "https://www.swat4ls.org/workshops/barcelona2025/programme/swat4hcls-2025-biohackathon/"
biohackathon_location: "Barcelona, Spain, 2025"
group: variant-rdf
git_url: https://github.com/NuriaQueralt/SWAT4HCLS-BH25-variant-representation-in-rdf
authors_short: Queralt-Rosinach \emph{et al.}
---

# Introduction
While variant representation is a cornerstone for understanding the molecular mechanisms underlying disease biology, there is no standard to represent this variation in RDF. During the International SWAT4HCLS conference held on 24-27th February 2025 in Barcelona (Spain), we detected an emerging number of novel RDF models to represent variant information in datasets. This challenges interoperability with existing Semantic Web based research infrastructures and hinders data reuse for example for variant interpretation. As part of the SWAT4HCLS BioHackathon 2025, we here report that we worked on the mapping and merging of different ontology models about genetic variants identified during the conference.

# Results
## Identifying variant RDF models
From talks and posters presented during the event, we identified several projects devoted to representing genetic variants.  according to divers driving use cases, from human health to plant sciences. 

## Aligning existing RDF models 
At the SWAT4HCL

Outcome: https://docs.google.com/spreadsheets/d/1JCVV3GB7t4cp4GrKcfn0OG4dJjJHI9dp5BEHEl-3xN8/edit?usp=sharing

## Converting alignments into SSSOM standard 
At the SWAT4HCL

Outcome: xxx

# Discussion
At the SWAT4HCL conference, we detected the proliferation of different RDF models to represent variant information, identified their commonalities and disjointnesses, and defined a strategy to enable their interoperability. Our agreed strategy was to align all models to a common core model that acts as a reference and collects all shared features. As a best practice in the field, we utilised existing standards to map and share our manually derived mappings. Even though every model is driven by a particular use case that confers unique terms and features, we observed that all models have overlap with the GA4GH VRS RDF model. Therefore, we selected this model as our core model since GA4GH VRS is a global standard and, moreover, its design is modular and is based on object-oriented engineering to enable granularity and flexibility in representing molecular variation from basic to specific concepts. Another outcome was that we created a Python tool publicly available on Github [link] to describe and share with the community our curated mappings with the SSSOM standard. Finally, we want to highlight that the BioHackathon along the conference set an ideal opportunity for multiple groups to discuss how they had represented variation data in RDF and to define together a solution to enable interoperability.

## Acknowledgements
We thank the SWAT4HCLS BioHackathon 2025 organizers for hosting the event and providing support. We acknowledge the contributions of all team members and collaborators who participated in discussions and testing.

## References
