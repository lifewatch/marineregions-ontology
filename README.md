# marineregions-ontology

This repository contains the source files of the Marine Regions ontology.
The hosted version of this ontology can be accessed through `http://marineregions.org/ns/ontology#`, where it is available in Turtle and HTML formats.

The ontology makes light use of OWL to define the different ways objects in the Marine Regions dataset may be related to each other. A secondary resource, `http://marineregions.org/ns/placetypes#`, describes a SKOS concept scheme with all the place types each object may belong to. 

## Project structure

Only one file, `ontology.ttl` should be updated manually. The other file, `ontology.html`, is to be generated through an ontology documentation tool - such as [pyLODE](https://github.com/RDFLib/pyLODE). The ontology contains definitions in both English and Dutch. The desired language can be specified as follows (assuming a local pyLODE installation):

```
pylode -i ontology.ttl -o ontology.html -l en
```

or 

```
pylode -i ontology.ttl -o ontology.html -l nl
```

## Marine Regions

Marine Regions is a standard list of marine georeferenced place names and areas. It integrates and serves geographic information from the VLIMAR Gazetteer and the MARBOUND database and proposes a standard of marine georeferenced locations, boundaries and regions.

Read more at https://marineregions.org/

