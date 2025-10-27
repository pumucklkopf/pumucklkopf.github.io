---
title: "GANDR - Georelating Dataset, Metrics, and Evaluation"
collection: publications
category: manuscripts
permalink: /publication/2025-GANDR
excerpt: 'We generate a new dataset, propose metrics, and perform an extensive evaluation for the novel Georelating task.'
date: 2025-11-03
venue: 'The 8th ACM SIGSPATIAL International Workshop on AI for Geographic Knowledge Discovery (GeoAI ’25)'
citation: 'Kai Moltzen and Ricardo Usbeck. 2025. GANDR - Georelating Dataset, Metrics, and Evaluation. In The 8th ACM SIGSPATIAL International Workshop on AI for Geographic Knowledge Discovery (GeoAI ’25), November 3–6, 2025, Minneapolis, MN, USA. ACM, New York, NY, USA, 11 pages. https://doi.org/ 10.1145/3764912.3770819'
---
Georelating has been introduced to learn geospatial representations of events from textual reports, which requires the interpretation  of spatial relations. To foster the development and evaluation of Georelating systems, we construct the silver-standard Georelating
Annotated Natural Disaster Reports dataset GANDR and benchmark our LLM agent architecture as a baseline (areal F1 = 0.609, fuzzy cell match score = 0.833) for this new task.

GANDR comprises synthetic disaster reports referencing 1,000 US and 1,000 EU cities, annotated with Discrete Global Grid System (DGGS) cells for efficient geospatial integration.We propose a set of
five complementary metrics capitalizing on the DGGS annotations for efficient and comprehensive evaluation.

Analysis reveals the potential of reasoning LLMs integrated with  geographical knowledge bases to address variation across spatial  relations such as (inter-)cardinal directions. We highlight the estimation  of the impact area’s size as a key challenge of Georelating.