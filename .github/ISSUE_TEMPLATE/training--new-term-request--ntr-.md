---
name: 'Training: New Term Request (NTR)'
about: Describe this issue template's purpose here.
title: 'NTR: [term label]'
labels: new term request, training
assignees: ''

---

### New Term Request (NTR)

_Please fill in the appropriate fields with the desired information and delete unused fields. You may request multiple terms in a single issue. We cannot guarantee requests will be taken exactly as specified, changes may be made at the discretion of the curator._

## [Term Label]
**Ontology:** 

**Parent Class:**
**Parent Class ID:**

**Alternative Label:**
**Exact Synonym:**
**Narrow Synonym:**
**Broad Synonym:**
**Definition:**
**Definition Source:**
**Database Cross Reference:**

**Additional Comments (not an annotation):**

--- 
**Contributor Attribution:** _{Optional. [ORCiD](https://orcid.org/) is preferred - this is so we can list you as a contributor [[dc:contributor](http://purl.org/dc/elements/1.1/contributor)].}_

--- 
### _Annotation Guide:_

**Term Label:** _An [rdfs:label](https://www.w3.org/TR/rdf-schema/#ch_label) that provides a a human-readable description of a resource._
**Ontology:** _The ontology the term is being requested for - e.g., GenEpiO, FoodOn, ENVO, OBI... This guide is not an exact match for a term request at a specific [OBO Foundry ontology](https://obofoundry.org/), but will give you useful guidance and practice for common annotations._

**Parent Class:** _The class/term within the target ontology under which you think the term being request should placed. Depending on the ontology you are requesting this in, it isn't strictly required - but it is helpful in facilitating curation efficiency and in giving the curator a better impression of the term you're requesting. There can be multiple parent classes/terms for an ontology term._
**Parent Class ID**: _An ontology IRI (e.g., FOODON:00001002) or the PURL (e.g., http://purl.obolibrary.org/obo/FOODON_00001002) associated with the parent class/term._

**Alternative Label:** _"A label for a class or property that can be used to refer to the class or property instead of the preferred rdfs:label. Alternative labels should be used to indicate community- or context-specific labels, abbreviations, shorthand forms and the like." [[IAO:0000118](http://purl.obolibrary.org/obo/IAO_0000118)]_
**Exact Synonym:** _"An alternative label for a class or property which has the exact same meaning than the preferred name/primary label." [[hasExactSynonym](http://www.geneontology.org/formats/oboInOwl#hasExactSynonym)]_
**Narrow Synonym:** _"An alternative label for a class or property which has a more specific meaning than the preferred name/primary label." [[hasNarrowSynonym](http://www.geneontology.org/formats/oboInOwl#hasNarrowSynonym)]_
**Broad Synonym:** _"An alternative label for a class or property which has a more general meaning than the preferred name/primary label." [[hasBroadSynonym](http://www.geneontology.org/formats/oboInOwl#hasBroadSynonym)]_
**Definition:** _"The official definition, explaining the meaning of a class or property. Shall be Aristotelian, formalized and normalized. Can be augmented with colloquial definitions." [[IAO:0000115](http://purl.obolibrary.org/obo/IAO_0000115)] - if you aren't sure how to meet this requirements, don't fret - give a definition and the ontology curator will restructure it to meet the definition requirements._
**Definition Source:** _"Formal citation, e.g. identifier in external database to indicate / attribute source(s) for the definition. Free text indicate / attribute source(s) for the definition." [[IAO:0000119](http://purl.obolibrary.org/obo/IAO_0000119)]_
**Database Cross Reference:** _For when you want to cross reference with another database identifier (e.g., MIxS, MESH, etc.) [[hasDBXref](http://www.geneontology.org/formats/oboInOwl#hasDbXref)]_
**Additional Comments (not an annotation):** _Additional context is valuable to ontology curators to ensure the changes they make are appropriate for your need. If the curator deems it necessary, they may include it as a "comment" [[comment](comment)] or "editor note" [[IAO:0000116](http://purl.obolibrary.org/obo/IAO_0000116)] annotation._
