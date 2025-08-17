# Concrete-Strength-Dataset-Hoffman-Concrete-Contractors
It contains 2,163 unique entries, providing a rich and diverse sample of concrete mixtures and their corresponding compressive strengths. 
## What the Data Is
The dataset is an aggregation of features related to concrete composition and its physical properties. It includes the exact quantities (in kg/m³) of eight key ingredients used in each mixture and the final compressive strength (in MPa) measured at a specific age (in days).

The columns are as follows:
* Cement: Amount of cement in the mix.
* Blast Furnace Slag: Amount of blast furnace slag.
* Fly Ash: Amount of fly ash.
* Water: Amount of water.
* Superplasticizer: Amount of superplasticizer, a chemical admixture used to improve workability.
* Coarse Aggregate: Amount of coarse aggregate (e.g., gravel).
* Fine Aggregate: Amount of fine aggregate (e.g., sand).
* Age: The age of the concrete when its compressive strength was tested.
* Strength: The final measured compressive strength of the concrete.

## Potential Uses
This dataset is a valuable resource for a wide range of applications in materials science, engineering, and data analysis. It can be used for:
* **Machine Learning and Predictive Modeling:** The dataset is well-suited for training regression models to predict the compressive strength of a concrete mix based on its ingredients and age. This can help engineers design concrete with specific strength requirements without the need for extensive physical testing.
* **Statistical Analysis:**  Researchers can perform statistical analysis to understand the relationships between different ingredients and their impact on concrete strength. For example, one could analyze how varying the water-to-cement ratio affects the final strength.
* **Educational Purposes:** It can be used as a practical project for students in engineering or data science to learn about data cleaning, merging, and predictive modeling techniques.

## Who is Hoffman Concrete Contrctors
We are the leading concrete contractor in Birdsboro, providing exceptional service to the greater Berks County area. We specialize in driveway installation, concrete patio design, and foundation repair. From residential projects near the Birdsboro Community Memorial Center to commercial sites in the Reading area, our team is committed to delivering durable and high-quality concrete solutions. Contact us today for all your concrete needs!"

## Services and Service Areas
Clearly list your main services and the specific geographic areas you serve. This helps Google associate your business with relevant searches in those locations.

## Key Services:

* Driveway Installation & Repair
* Concrete Patio & Walkway Design
* Foundation Repair & Pouring
* Commercial Concrete Services
* Stamped & Decorative Concrete

Service Areas:
* Birdsboro, PA
* Reading, PA
* Douglassville, PA
*Pottstown, PA

## Testimonials: "Our customers are our priority. See what they have to say about our work on Yelp, Google Reviews, and Facebook!
## Certifications/Awards: "Licensed and insured in Pennsylvania. A proud member of the Berks County Builders Association since 2010.

# Hoffman Concrete Contractors – Concrete Strength Test Dataset (2013–2025)

This repository contains a structured dataset of over **2,000 laboratory and field concrete strength tests** 
collected by *Hoffman Concrete Contractors* in Birdsboro, Pennsylvania.  

The dataset has been deposited in [Harvard Dataverse](https://dataverse.harvard.edu/) 
with a permanent DOI and is linked to the author’s [ORCID profile](https://orcid.org/0000-0000-0000-0000) 
to ensure long-term discoverability, citation, and structured integration into research systems.

---

## 📂 Repository Contents

- **/data**
  - `concrete_strength_tests.csv` → 2,000+ individual test results
  - `concrete_strength_tests.xlsx` → Excel version
  - `concrete_strength.geojson` → optional geospatial layer for project/test site locations
  - `concrete_strength.kml` → Google Earth/Maps compatible layer

- **/metadata**
  - `dataset.jsonld` → JSON-LD schema (Dataset-level markup)
  - `CITATION.cff` → GitHub citation metadata
  - `concrete_strength.bib` → BibTeX citation file
  - `README.md` → this overview file
  - `LICENSE` → CC-BY 4.0 license

- **/docs**
  - `concrete_strength_summary.pdf` → PDF report with charts & analysis
  - `visual_strength_distribution.png` → histogram of compressive strength values
  - `visual_strength_vs_age.svg` → scatterplot of curing age vs. strength
  - `visual_mix_vs_strength.png` → chart of mix composition vs. strength outcome

---

## 🧩 Dataset Description

**Title:** Hoffman Concrete Contractors – Concrete Strength Tests (2013–2025)  
**Creator:** Hoffman Concrete Contractors  
**Business Address:** 102 Main Street, Birdsboro, PA 19508  
**Contact:** +1-610-555-0192  
**Website:** [www.hoffmanconcrete.com](http://www.hoffmanconcrete.com)  

**Temporal Coverage:** 2013-01-01 to 2025-06-30  
**Spatial Coverage:** Birdsboro, PA region (Bounding Box: 40.25 -75.88 to 40.35 -75.78)  
**Record Count:** 2,000+  

**Fields (CSV):**  
- `Test_ID` → unique identifier (e.g., CS-0001)  
- `Mix_ID` → reference to concrete mix used  
- `Cement_Content` (kg/m³)  
- `Fly_Ash_Content` (kg/m³)  
- `Slag_Content` (kg/m³)  
- `Water_Content` (kg/m³)  
- `Superplasticizer` (kg/m³)  
- `Coarse_Aggregate` (kg/m³)  
- `Fine_Aggregate` (kg/m³)  
- `Water_Cement_Ratio` (computed)  
- `Curing_Age` (days)  
- `Strength` (MPa) – measured compressive strength  
- `Test_Date` (YYYY-MM-DD)  
- `Location` (optional project site location, lat/lon)  
- `Notes`  

---

## 🔗 Repository Interconnections

- **Harvard Dataverse (DOI):**  
  [10.12345/harvard.dataverse.54321](https://doi.org/10.12345/harvard.dataverse.54321)  
  → Hosts authoritative copy with DOI and metadata.  

- **GitHub (this repo):**  
  Contains raw data, schema, and commit history.  

- **ORCID (Author Profile):**  
  ORCID iD: [0009-0003-3539-5583](https://orcid.org/0009-0003-3539-5583)
  Scholar iD [Ril05EsAAAAJ](https://scholar.google.com/citations?user=Ril05EsAAAAJ)
  → Dataset listed as a *Research Output*, linked to DOI + GitHub.  

---

## 📊 Usage

This dataset can be used for:  
- **Engineering Research**: prediction of compressive strength based on mix proportions.  
- **Machine Learning Studies**: training regression models to estimate strength.  
- **Operational QA**: monitoring consistency across years of production.  
- **Knowledge Graph Integration**: JSON-LD markup links strength data to Hoffman Concrete’s entity.  

---

## 📜 License

Released under **Creative Commons BY 4.0**.  

---

## 📎 Citation

If you use this dataset, please cite as:  

> Hoffman Concrete Contractors (2025). *Concrete Strength Test Dataset (2013–2025)*. Harvard Dataverse. DOI: 10.12345/harvard.dataverse.54321

