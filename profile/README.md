# Azahar Data Insights

**Biostatistics & Data Science for Healthcare & Life Sciences**

We help research teams, healthcare organisations, life-science companies and international organisations turn complex health data into results that can be **understood, verified and used**.

Azahar Data Insights was founded in 2025 by [Julia M. Sánchez-Tormo](https://github.com/jsancheztorm) and [Rubén Palomo-Llinares](https://github.com/palomorub), each bringing more than **15 years of experience in research and healthcare**.

Our work spans **clinical research, public health and epidemiology, biopharma and clinical evaluation, and nutrition and food health**.

## What we do

We usually enter a project because there is a question to answer or a decision to support, not because a particular statistical technique needs to be applied.

Depending on the problem, our work may involve:

- **Study design and biostatistics** — defining research questions, outcomes, sample size and analytical strategies before data collection begins.
- **Data preparation and quality** — structuring, validating, documenting and protecting data so that subsequent analysis is reliable and traceable.
- **Statistical modelling and machine learning** — from classical inference and survival analysis to predictive modelling, explainability and simulation.
- **Impact evaluation** — estimating whether an intervention worked, understanding why, and modelling what could happen under alternative scenarios.
- **Population and epidemiological analysis** — identifying temporal, geographic and population-level patterns that can support surveillance and planning.
- **Scientific communication and decision-support tools** — reproducible reports, Quarto websites, interactive Shiny applications and visualisations designed around the people who need to use the results.

[Explore what we do](https://azahardata.com/tus-necesidades/)

## How we work

Our projects follow **D²I — Data to Insights**, the framework we use to keep the research question, available data, methodological decisions and final use of the results connected throughout the project.

We do not start with the most sophisticated method available. We start by asking what the data can actually support.

That means:

- putting the **question before the technique**;
- using complexity only when it adds value;
- checking assumptions, robustness and uncertainty;
- preserving traceability and reproducibility;
- and reviewing findings with the teams who understand the scientific and clinical context.

**Understand · Model · Communicate** are three complementary dimensions of the same process, not separate services.

[Read about our D²I methodology](https://azahardata.com/sobre-nosotros/metodologia-d2i/)

## Featured project: Biofortified Maize Impact Assessment Framework for Guatemala

For [New Seed](https://newseed.org/), we developed a national-scale analytical framework to estimate how biofortified maize adoption could affect nutrition, childhood stunting and agricultural outcomes in Guatemala.

The framework combines national and official data sources including **ENCOVI, SIVESNU and MAGA**, together with nutritional reference data and New Seed's production and economic information.

Rather than relying on a single analytical pathway, the nutritional impact on stunting is estimated independently from observational population data and from published evidence. Both approaches converged on an estimated **5.8 percentage-point reduction in stunting under 100% coverage**.

These are modelled projections, not measured effects of a deployed intervention, and that distinction is explicit throughout the analysis.

The project was developed by Azahar Data Insights for New Seed, with nutritional methodology advisory from FINUT.

### Open and reproducible by design

The public repository includes:

- the modular **R analytical pipeline**;
- configuration files defining analytical scenarios;
- reproducible dependency management with **renv**;
- the complete source of the **Quarto methodological website**;
- data provenance and methodological documentation;
- citation metadata and an open-source licence.

Raw national microdata are not redistributed because access is controlled by their original providers. The analytical code, parameters and methodological sources document the complete process so that it can be audited and reproduced when the corresponding source data are available.

[View the repository](https://github.com/Azahar-Data-Insights/newseed-biofortification-guatemala-public) · [Methodological documentation](https://newseed.azahardata.com/web-guatemala/) · [Interactive results](https://newseed.azahardata.com/app-guatemala/) · [Case study](https://azahardata.com/casos-exito/impacto-biofortificacion-desnutricion-infantil/)

## Selected work

### Anonymisation and traceability of population health data

For the **Servicio Navarro de Salud-Osasunbidea (SNS-O)**, we designed a reproducible framework to replace a manual anonymisation process with standardised, verifiable rules and add reverse traceability to distributed datasets. The study forms part of Spain's **National Health Data Space**, under Component 18 of the Recovery, Transformation and Resilience Plan, funded by **Next Generation EU**.

The work combined formal privacy models—including k-anonymity, l-diversity and differential privacy—with pseudonymisation and recipient-specific forensic marking.

Because real health data could not be shared for development, we generated a synthetic population to validate the complete workflow. The final prototype—provided beyond the originally requested deliverables—was implemented in **R with four functional modules, 410 automated tests and 17 documented validation scenarios**.

The project also delivered decision protocols and an implementation roadmap designed around the infrastructure already available within the Service.

[Read the case study](https://azahardata.com/casos-exito/anonimizacion-trazabilidad-sns-osasunbidea/)

### Machine learning for community pharmacy triage

Our team worked on the **Indica+PRO programme**, led by the University of Granada in collaboration with the University of Technology Sydney, using data from more than **14,000 consultations across 500+ community pharmacies in Spain**.

Nine families of predictive algorithms were evaluated to identify patients who required referral to primary care, dealing explicitly with class imbalance and heterogeneous clinical profiles.

The final radial SVM reached an accuracy of **0.934** and an AUC of **0.897**, with later analytical work incorporating SHAP to examine how patient, pharmacist and pharmacy characteristics contributed to predictions.

[Read the case study](https://azahardata.com/casos-exito/ml-triaje-farmaceutico-indicapro/)

[Explore all case studies](https://azahardata.com/insights/casos-exito/)

## Research and scientific background

Our work combines applied data science with experience in biomedical, clinical and public-health research.

**Both founders are published authors in indexed scientific journals**, with work spanning biomedical research, machine learning in healthcare, nutritional and digital epidemiology, occupational health and other areas of applied health research.

Both hold doctoral degrees and have worked across universities, hospitals, research institutes and international organisations.

[Scientific publications](https://azahardata.com/sobre-nosotros/publicaciones/)

## Team

### [Julia M. Sánchez-Tormo, PhD](https://github.com/jsancheztorm)

**Biostatistician & Data Scientist**

PhD in Clinical-Medical Biochemistry and Immunology and MSc in Bioinformatics and Biostatistics. Her background combines biomedical research, biostatistics, statistical modelling, machine learning and scientific communication.

[Profile](https://azahardata.com/sobre-nosotros/equipo/julia-sanchez/)

### [Rubén Palomo-Llinares, PhD](https://github.com/palomorub)

**Data Scientist & Medical Physicist**

PhD in Public Health, MSc in Bioinformatics and Biostatistics, Telecommunications Engineer and Medical Physics Specialist. His background combines hospital-based medical physics, public health, clinical context and applied data science.

[Profile](https://azahardata.com/sobre-nosotros/equipo/ruben-palomo/)

## Tools

Our analytical work is primarily developed in **R**, with **Python** and **SQL** where appropriate.

We use tools including **tidymodels, XGBoost, SHAP, Quarto, Shiny and Git** to build statistical models, reproducible analytical pipelines and tools for communicating and exploring results.

The method and technology always follow the question, not the other way around.

## 🌸 About our name

**Azahar** is the Spanish word for orange blossom, part of the Mediterranean landscape around **Alicante**, where we are based.

We wanted a name rooted in where we come from rather than another abstract technology brand: local in origin, but built to work on health and research problems well beyond it.

## Contact

**Alicante, Spain · Remote-first**

[Website](https://azahardata.com/) · [LinkedIn](https://www.linkedin.com/company/azahar-data-insights/) · [info@azahardata.com](mailto:info@azahardata.com)
