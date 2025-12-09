# Introduction de Projet
Une Ontologie pour un Système Médical de Prédiagnostic.
Problèmes visés :
1. Identiffer les affections potentielles dont ils pourraient souffrir.
2. Les orienter vers le service médical le plus adéquat pour une consultation.
3. Suggérer les médicaments usuels pouvant être indiqués pour leur pathologie présumée.

# Dataset comme référence
- Human Phenotype Ontology (HPO) : https://hpo.jax.org/app/download/ontology
- Human Disease Ontology (DOID) : https://github.com/DiseaseOntology/HumanDiseaseOntology
- Medical Subject Headings (MeSH) : https://nlmpubs.nlm.nih.gov/projects/
mesh/MESH_FILES/asciimesh/
- DrugBank Online : https://go.drugbank.com/releases/latest

# Structure Global
```text
├── Patient
├── SymptomTotal
│   ├── Symptom
│   └── SymptomAttribut
├── BodySystem
├── Disease
├── MedicalDepartment
└── Drug
```



