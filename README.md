# bleau.info statistics — ML Model Prototypes

This repository contains the development and testing ground for machine learning models used in the **bleau.info statistics** project.

## 🧠 Purpose

This is an exploration-focused repository, aimed at:

- Designing and iterating on ML models  
- Evaluating performance: accuracy, speed, and memory usage  
- Comparing modeling approaches  
- Preparing models for integration into production

## 🔁 Integration Flow

Once validated, models are integrated into the **bleau.info statistics** web application, at either:

- The **scraper stage** — to enrich or filter data at ingestion  
- The **API stage** — to provide fast recommendations or predictions


## ⚙️ Technical Notes

- Models are designed to work efficiently with **sparse, large-scale data**
- Data inputs are pulled from the core bleau.info pipeline
- Code is in active development — expect rapid changes and experiments

## 🔍 Status

Experimental — not production-ready. Stable models are migrated to the main app repository when finalized.