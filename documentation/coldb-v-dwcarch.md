# ColDP vs Darwin Core Archive

## ColDP

The ColDP archive was downloaded from https://www.catalogueoflife.org/data/download as a zipfile called 6b9f4...88d4.zip. This was extracted to give the files and directory indicated below. The sources directory contains 168 .yaml files.

```console
total 2.1G
361M file 	6b9f4398-1968-42ac-bbce-640b77d288d4.zip
112M file 	Distribution.tsv
 72K file 	logo.png
 108 file 	Media.tsv
938K file 	metadata.yaml
 16M file 	NameRelation.tsv
1.1G file 	NameUsage.tsv
198M file 	reference.json
326M file 	Reference.tsv
4.0K directory	source
 37K file 	SpeciesEstimate.tsv
 112 file 	SpeciesInteraction.tsv
  81 file 	TaxonConceptRelation.tsv
 259 file 	TypeMaterial.tsv
 23M file 	VernacularName.tsv
```
The column headings in NameUsage.tsv (these are tab delimited and all on one line in the file but are shown below each on a separate line):

col:ID
col:alternativeID
col:nameAlternativeID
col:sourceID
col:parentID
col:basionymID
col:status
col:scientificName
col:authorship
col:rank
col:notho
col:uninomial
col:genericName
col:infragenericEpithet
col:specificEpithet
col:infraspecificEpithet
col:cultivarEpithet
col:namePhrase
col:nameReferenceID
col:publishedInYear
col:publishedInPage
col:publishedInPageLink
col:code
col:nameStatus
col:accordingToID
col:accordingToPage
col:accordingToPageLink
col:referenceID
col:scrutinizer
col:scrutinizerID
col:scrutinizerDate
col:extinct
col:temporalRangeStart
col:temporalRangeEnd
col:environment
col:species
col:section
col:subgenus
col:genus
col:subtribe
col:tribe
col:subfamilycol:family
col:superfamily
col:suborder
col:order
col:subclass
col:class
col:subphylum
col:phylum
col:kingdom
col:sequenceIndex
col:branchLength
col:link
col:nameRemarks
col:remarks

## Darwin Core Archive COL

The Darwin Core Archive formatted COL archive was also downloaded from https://www.catalogueoflife.org/data/download resulting in zip file 83f88...11d99.zip which when extracted gave the files adn directory indicated below. The dataset directory contains 168 .xml files

```
total 1.9G
381M file	83f88f40-e54a-4c01-b437-b34f9e211d99.zip
4.0K directory 	dataset
209M file	Distribution.tsv
247K file	eml.xml
 72K file	logo.png
3.8K file	meta.xml
 44M file	SpeciesProfile.tsv
1.3G file	Taxon.tsv
 12M file	VernacularName.tsv

The column headings in Taxon.tsv (these are tab delimited and all on one line in the file but are shown below each on a separate line):

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
