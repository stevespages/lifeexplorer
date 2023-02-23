# Life Explorer

This website will enable users to record their identification of living organisms. The site helps people to organize their efforts to identify organisms with the aim being to arrive at the full, correct taxonomic description for each record.

The site will also attach the time and location to each observation to be recorded. It will enable any number of files, for example, images and observations to be attached to any given recording.

The approach taken will, to the maximum possible extent, be based on evolutionary relationships between organisms.

## The Data

### Catalogue of Life

[COL] (https://www.catalogueoflife.org/) maintains a checklist of over two million of the world's species. The number of published scientific species names is far higher as there are many synonyms.

The latest COL checklist can be downloaded from https://www.catalogueoflife.org/data/download. There are several different formats available. COL recommends the ColDP Archive. However I found something which looked easier to work with by downloading the Darwin Core Archive format of the COL checklist.

Darwin Core Archive Col's taxon.tsv file had these headings:

- dwc:taxonID
- dwc:parentNameUsageID
- dwc:acceptedNameUsageID
- dwc:originalNameUsageID
- dwc:scientificNameID
- dwc:datasetID
- dwc:taxonomicStatus
- dwc:taxonRank
- dwc:scientificName
- dwc:scientificNameAuthorship
- col:notho
- dwc:genericName
- dwc:infragenericEpithet
- dwc:specificEpithet
- dwc:infraspecificEpithet
- dwc:cultivarEpithet
- dwc:nameAccordingTo
- dwc:namePublishedIn
- dwc:nomenclaturalCode
- dwc:nomenclaturalStatus
- dwc:taxonRemarks
- dcterms:references
