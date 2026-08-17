# Ben Lewis

Founder of **The Open Inference Initiative** which is developing open spatial reasoning systems for climate, health, sustainable development, historical research, and other public-interest applications.

From 2007 to 2026, I worked at Harvard University's **Center for Geographic Analysis (CGA)**, where I led of development of systems for collaborative mapping, spatial search, geospatial data discovery, and various forms of analysis. My work has increasingly focused on making messy collections of evidence accessible through spatial and conversational interfaces.

I am an Affiliate of Harvard's **Institute for Quantitative Social Science (IQSS)** and an Associate of Harvard's **Hutchins Center for African and African-American Research**

---

## Current work

### Open Inference Initiative

The Open Inference Initiative explores how spatial structure can make AI systems more **auditable, deterministic, efficient, and useful for reasoning about the physical and social world**.

A central research direction is a spatial inference substrate built around explicit provenance, deterministic operations, and AI-assisted interfaces.

Current applications include environmental health, climate and land systems, historical data, and spatial evidence synthesis.

### Habitable Air

I am developing a conversational spatial evidence system for **The Atmosphere as a Social Problem**, a University of Bergen-linked research and teaching project led by anthropologist Kerry Chance.

The system brings together environmental measurements, modeled atmospheric data, land cover, facilities, population, place information, and documentary evidence for comparative study of industrial communities in the United States, South Africa, and Germany.

The goal is to enable natural-language questions to return **bounded, inspectable spatial operations over documented evidence**.

### Trans-Atlantic Slave Trade Database / SlaveVoyages

I have been developing an **AI-readiness and MCP-based evidence layer** for the Trans-Atlantic Slave Trade Database.

The work explores how natural-language questions can be translated into auditable operations over a mature scholarly database while preserving distinctions among source evidence, derived results, uncertainty, and scholarly interpretation.

---

## Selected Harvard CGA projects

During nineteen years at Harvard CGA, I led or helped develop a series of open spatial platforms and research infrastructures. My role was generally **project leadership, system architecture, research collaboration, product design, and management of software development, not code authorship**.

### AfricaMap / Harvard WorldMap

AfricaMap began as an effort with Harvard art historian Suzanne Blier to bring geographically scattered scholarly materials together through a common map interface. It grew into **[Harvard WorldMap](https://gis.harvard.edu/projects/worldmap)**, a collaborative platform for publishing, combining, annotating, and sharing spatial information across disciplines.  WorldMap was integrated into Harvard Dataverse via GeoConnect.

**My role:** Co-founded AfricaMap/Harvard WorldMap and led its technical and product development as it grew into a broadly used scholarly mapping platform.

Repositories:
- [worldmap](https://github.com/cga-harvard/worldmap)
- [dataverse-integration](https://github.com/IQSS/geoconnect)
- [geoexplorer-worldmap-client](https://github.com/cga-harvard/geoexplorer-worldmap-client)
- [ansible-worldmap](https://github.com/cga-harvard/ansible-worldmap)
- [worldmapXBlock](https://github.com/cga-harvard/worldmapXBlock)
- [worldmap-migration](https://github.com/cga-harvard/worldmap-migration)

### Hypermap Registry

[Hypermap Registry](https://link.springer.com/article/10.1186/s40965-018-0051-x) addressed a different problem: **how to discover useful geospatial information distributed across thousands of remote web services**.

It provided open infrastructure for harvesting, indexing, searching, and monitoring OGC, Esri REST, and related map services.

**My role:** Co-developed Hypermap Registry and helped define its approach to scalable discovery and search of distributed geospatial web services.

Repository:
- [Hypermap-Registry](https://github.com/cga-harvard/Hypermap-Registry)

### Geotweet Archive / GEOPS / TweetMap

Beginning in the early 2010s, CGA collected a global archive of geolocated social-media records and experimented with ways to interact with billions of spatial observations in real time.

Working with Todd Mostak, we developed **GEOPS**, an early GPU-accelerated spatial database. That work powered [TweetMap](https://gis.harvard.edu/geotweets-archive-v20) and contributed to the technical lineage that became MapD and later OmniSci.

**My role:** Co-created the Harvard Geotweet Archive and worked with Todd Mostak on the original GEOPS GPU spatial-database effort and its application to interactive geospatial analysis.

Repositories:
- [GeoTweets](https://github.com/cga-harvard/GeoTweets)
- [MapD](https://github.com/cga-harvard/MapD)

### Billion Object Platform

The **[Billion Object Platform (BOP)](https://gis.harvard.edu/billion-object-platform-bop)** explored another route to extremely large spatial collections: indexing space, time, and text with Apache Solr/Lucene and making the resulting collections interactively searchable and mappable.

The project included work on spatial and temporal faceting and on interfaces for exploring very large spatiotemporal datasets.

**My role:** Co-led the conception and development of BOP as an open platform for interactive search and visualization of billion-scale spatial and temporal records.

Repositories:
- [bop-ui](https://github.com/cga-harvard/bop-ui)
- [Data_Science_Big_Data_Projects](https://github.com/cga-harvard/Data_Science_Big_Data_Projects)

### Geospatial big data and high-performance computing

CGA also explored how GPU databases, distributed search, high-performance computing, and cloud infrastructure could make very large spatial datasets useful to researchers without requiring them to become systems engineers.

This work included experiments with MapD/OmniSci, Solr, PostGIS, Harvard's research-computing infrastructure, large hydrological datasets, and other spatial-data visualization and processing challenges.

**My role:** Helped establish and manage CGA's geospatial big-data program, connecting research problems with scalable computing and emerging database technologies.

Repositories:
- [Evaluating_OmniSci_NWM](https://github.com/cga-harvard/Evaluating_OmniSci_NWM)
- [Data_Science_Big_Data_Projects](https://github.com/cga-harvard/Data_Science_Big_Data_Projects)

### Chinese Academic Mapping Platform (CAMP)

CAMP was a Harvard–Zhejiang collaboration to adapt the WorldMap/GeoNode approach for academic mapping, research, teaching, and spatial-data sharing in China.

**My role:** Managed CGA's platform-development contribution and helped adapt the WorldMap architecture to the needs of the collaboration.

Repository:
- [CAMP](https://github.com/cga-harvard/CAMP)

### GeoNode and open geospatial infrastructure

Much of WorldMap and related CGA work depended on the wider open-source geospatial ecosystem: GeoNode, GeoServer, GeoExplorer, Django, OpenLayers, and associated libraries and services.

Rather than treating these as separate projects of mine, I regard them as the **technical substrate that CGA adapted and extended to support scholarly spatial collaboration**.

Selected repositories:
- [geonode](https://github.com/cga-harvard/geonode)
- [geonode-project](https://github.com/cga-harvard/geonode-project)
- [geonode-suite-sdk](https://github.com/cga-harvard/geonode-suite-sdk)
- [geonode-client](https://github.com/cga-harvard/geonode-client)
- [geoserver-geonode-ext](https://github.com/cga-harvard/geoserver-geonode-ext)
- [django-geoexplorer](https://github.com/cga-harvard/django-geoexplorer)

---

## Earlier and related tools

CGA's work also included historical-map georeferencing, digital-humanities infrastructure, deployment automation, and experimental spatial applications. Some of the repositories associated with that work include:

- [mapwarper](https://github.com/cga-harvard/mapwarper)
- [ansible-omeka](https://github.com/cga-harvard/ansible-omeka)
- [edmap](https://github.com/cga-harvard/edmap)

---

## What I am interested in now

I am particularly interested in systems that combine:

**spatial and temporal indexing · natural-language interfaces · deterministic computation · provenance and audit trails · environmental and historical evidence · large search systems · AI-assisted scientific and scholarly reasoning**

The broader question behind much of this work is **Can we use the structure of the physical and historical world to make AI more useful and trustworthy?**

---

**Open Inference Initiative**  
Cambridge, Massachusetts / Minneapolis–St. Paul  
Harvard IQSS Associate
