# Life Explorer

This website will enable users to record their identifications of living organisms. The site helps people to organize their efforts to identify organisms with the aim being to arrive at the full, correct taxonomic description for each record.

The site will also attach the time and location to each observation to be recorded. It will enable any number of files, for example, images and observations to be attached to any given recording.

The approach taken will, to the maximum possible extent, be based on evolutionary relationships between organisms.

## The Data

### Catalogue of Life

[COL](https://www.catalogueoflife.org/) maintains a checklist of over two million of the world's species. The number of published scientific species names is far higher as there are many synonyms. COL indicates which names are **accepted**. This is achieved through COL's participation with taxonomic communities to develop **consensus-based** species lists for each taxonomic group which are then merged to complete a list for all life. New information and revision of old information result in new versions of COL being released monthly with major versions released annually.

The latest COL checklist can be downloaded from https://www.catalogueoflife.org/data/download. COL recommends the COL Data Package Archive (ColDP) format although other formats for example Darwin Core are available. The ColDP schema and information relating to it can be found at https://github.com/CatalogueOfLife/coldp. The specification not only describes the schema of the ColDP archive made available by COL but is also intended to specify what constitutes a valid ColDP format for people who want to construct a species list using their own data. Therefore the specification for the format is broader than that actually used by the ColDP archive itself. For example comma separated files as well as tab separated files are acceptable for the format but the archive only actually uses tab separated files (suffixed with the *.csv* file extension). 

Downloading ColDP archive file and extracting it gives the following files and (one) directory:

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

The files above are for the simpler version of ColDP (see https://github.com/CatalogueOfLife/coldp) in which the *Taxon*, *Synonym* and *Name* entities have been merged into *NameUsage*. Note that I am lacking  *Treatment* file which is shown on the schema.

#### Glossary

- Catalogue of Life (COL)

  https://www.catalogueoflife.org/

  https://en.wikipedia.org/wiki/Catalogue_of_Life

- Catalogue of Life Plus (COL+)

  https://www.catalogueoflife.org/ 

- COL Checklist

  https://www.catalogueoflife.org/about/colusage

#### Glossary of related terms

- Digital Object Identifier (DOI)
