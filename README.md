This repository contains the ontology, datasets, and serialization scripts developed for the master’s thesis:
mapping the HXL to an ontology

The project explores how the Humanitarian Exchange Language (HXL) can be formally modeled into an ontology to improve semantic interoperability, data sharing, and integration across humanitarian organizations.

🗂️ Datasets (Synthetic Workbooks)

1- ACTED-Workbook.xlsx – Simulated organizational workbook for ACTED, structured according to the sheet divisions discussed in the thesis (Beneficiaries, Distributions, Needs Assessments, etc.).

2- NRC-Data.xlsx – Simulated organizational workbook for NRC, prepared following the same structure.

3- serialisationsheetdivision.xlsx – Consolidated synthetic dataset demonstrating how sheets were divided and serialized for RDF conversion.

🧩 Ontology

1- HXLOntologyPrtoegeEdit.ttl – The ontology file in Turtle format, created and refined in Protégé.
  Models humanitarian concepts such as Beneficiary, Aid Item, Distribution, Project, and their relationships.
  Integrates HXL tags as annotation properties to data properties


⚙️ Serialization & Queries

Serialization code for triples – Scripts used to transform HXL-tagged Excel data into RDF triples for uploading into GraphDB.

📊 Visual Modeling

hxl final draft.vpp – Visual Paradigm project file containing the final ontology diagrams and modeling decisions.
