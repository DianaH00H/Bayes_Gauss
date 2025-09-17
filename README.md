# Articulo_2

Modelado de la contaminacion ambiental y la salud en México con redes bayesianas gaussianas

Abstract— Air pollution is a major and persistent public-health concern in Mexico. This study aims to evaluate how ambient contami-
nants influence blood-based biomarkers by applying Gaussian Bayesian Networks (GBNs), which capture multivariate dependencies and
enable predictive inference under uncertainty. We integrate 2022 ENSANUT records (sociodemographics and laboratory assays) with 2025
SEMARNAT air-quality data at the municipality level, assuming 2025 levels are reasonable proxies for 2022 exposure. After data cleaning
and MICE imputation, three expert-elicited DAGs were constructed with the guidance of Samantha Nevarez Soto (medical student), Ángel
David Hernández Almeida (biomedical engineer), and Estefanía Parra Esparza (medical student), and fitted with maximum likelihood.
Model fit was assessed with BIC and AIC. A conditional-Gaussian (hybrid) network that includes Sex as a categorical parent achieved
the best fit (BIC = −1,537,689; AIC = −1,537,248), outperforming purely Gaussian alternatives. As illustrative queries, we examined:
(i) the probability that an adult older than 40 has Glucose > 110 mg/dL given LDL > 130 mg/dL, which was estimated at 0.672; (ii) the
probability that an adult woman of the third age has a high level of Glucose given their level of exposition to contaminants in the air, which
was estimated at 0.71875 for having low exposure and 0.7416974 for having high exposure; and (iii) age and exposure to air contaminants
influences biomarkers such as glucose, indicating a relationship between them that reflects on the metabolic status and health of the person,
which was estimated at around 0.01. These results suggest that pollutant exposure has modest but measurable associations with biomarker
alterations at the population level. This research helps to understand the relationship between environmental contaminants and health
biomarkers, which can support the design of preventive strategies and public-policy design in Mexico
