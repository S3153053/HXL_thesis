This repository contains the ontology, datasets, and serialization scripts developed for the master’s thesis:
mapping the HXL to an ontology

The project explores how the Humanitarian Exchange Language (HXL) can be formally modeled into an ontology to improve semantic interoperability, data sharing, and integration across humanitarian organizations.

🗂️ Datasets (Synthetic Workbooks)

1- ACTED-Workbook.xlsx – Simulated organizational workbook for ACTED, structured according to the sheet divisions discussed in the thesis (Beneficiaries, Distributions, Needs Assessments, etc.).

2- NRC-Data.xlsx – Simulated organizational workbook for NRC, prepared following the same structure.

3- Organization X - workbook –the first synthetic dataset demonstrating how sheets were divided- basically its also a syntehtic workbook data and follows the same structure. 

🧩 Ontology

1- HONT ontology in turtle– The ontology file in Turtle format, created and refined in Protégé.
  Models humanitarian concepts such as Beneficiary, Aid Item, Distribution, Project, and their relationships.
  Integrates HXL tags as annotation properties to data properties


⚙️ Serialization & Queries

Serialization code for triples – Scripts used to transform HXL-tagged Excel data into RDF triples for uploading into GraphDB.

for the code to work:
1-  the Excel workbook sheet names must match the names in the code
2-  the main idenifier for each sheet must be present like for beneficiary contract its: #beneficiary +code 
3

📊 Visual Modeling

hxl final draft.vpp – Visual Paradigm project file containing the final ontology diagrams and modeling decisions.
