
# 🎓 openEHR Fellowship Project

Welcome to the official documentation of the Somayeh Abedian's openEHR Fellowship.

# Project main goal
Develop conceptual models for core Patient-Generated Health Data (PGHD) using openEHR’s archetype-based modeling framework, and to assess the feasibility of semantic mapping to existing structures in HL7 FHIR and OMOP CDM — identifying gaps and proposing standard extensions where necessary.

# Project background
Patient-Generated Health Data (PGHD), such as data from wearable devices, mobile health apps, and home care sensors, is increasingly recognized as a key contributor to personalized and preventive healthcare. These data provide valuable, real-time insights into a person’s lifestyle, behaviors, and physiological patterns, supporting early detection, remote monitoring, and more informed clinical decision-making. Despite this, most PGHD remains isolated in vendor-specific silos and is not semantically integrated into clinical workflows or EHRs.
Examples of such silos include Garmin Connect, Fitbit Cloud, Apple Health Kit, Samsung Health, and Google Fit. Each of these platforms captures data using proprietary formats and data models that differ not only in structure but also in clinical relevance and interoperability capabilities. As a result, integrating PGHD into health systems for primary or secondary purposes is challenging due to the lack of semantic consistency, structural standardization, and interoperability support.

Different health information systems tend to prioritize different data standards based on their goals:
*openEHR: suited for detailed clinical modeling and longitudinal storage,
*FHIR: focuses on real-time data exchange and interoperability,
*OMOP: tailored for harmonized secondary data analysis and research.

However, a significant gap exists: there is no common approach to model PGHD once, and then use that model intelligently across multiple standards and use cases.
This project seeks to address this gap by using openEHR as the foundation for conceptual modeling of core PGHD elements (e.g., activity, sleep, heart rate, steps). The modeled concepts will then be semantically transformed into FHIR and OMOP using AI-assisted mapping techniques. This transformation enables meaningful reuse and integration of PGHD, whether for clinical care, personal health tracking, or population-level analysis.

A joint initiative grounded in openEHR efforts aims to foster collaboration between standards such as FHIR or OMOP. Ultimately, beyond publishing a finalized model for integrating PGHD into the openEHR framework, this work seeks to improve the usability of PGHD across healthcare systems, reduce duplication in modeling efforts across standards, and enhance clinical decision support, continuity of care, and secondary data use. As a prototyping effort, the method developed may also be adapted for other concepts in the future.

