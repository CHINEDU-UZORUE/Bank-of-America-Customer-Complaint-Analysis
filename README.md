# Bank-of-America-Customer-Complaint-Analysis
BANK OF AMERCIA CUSTOMER COMPLAINTS ANALYSIS WITH PYTHON

This repository contains a Python-based analysis of consumer complaints data from Bank of America (BoA) from 2017 to 2023. The analysis focuses on uncovering complaint patterns by state, product type, and response timeliness, providing actionable insights to enhance customer service and operational efficiency.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Usage](#usage)
- [Analysis Sections](#analysis-sections)


## Project Overview

The objective of this analysis is to:
- Identify high-complaint products and regions.
- Examine timeliness in response across various complaint types and submission channels.
- Uncover seasonal trends in complaints.
- Develop data-driven recommendations to help BoA reduce complaint volumes and improve customer satisfaction.

## Dataset

The dataset includes the following key fields:
- **Complaint ID**: Unique identifier for each complaint.
- **Date submitted** and **Date received**: Dates when complaints were submitted and received.
- **State**: State of the complainant (in 2-letter abbreviations).
- **Product** and **Issue**: Categories for the product and specific complaint issue.
- **Submitted via**: Channel used to submit the complaint (e.g., web, phone, referral).
- **Company public response**: Public response type from BoA.
- **Timely response?**: Indicator if the complaint was responded to in a timely manner.

The dataset is included in this repository. Please check the dataset file (`Consumer_Complaints.xlsx`) 


## Analysis Sections

The analysis is divided into several key sections:

1. **Data Cleaning and Preparation**:
   - Handling missing values, standardizing date formats, mapping state abbreviations to full names, and adding calculated columns like complaint duration.

2. **Exploratory Data Analysis (EDA)**:
   - **Complaints by Product**: Analyzing the volume and types of complaints for each product.
   - **State-Based Analysis**: Identifying states with high complaint volumes, common issues per state, and variations in timely response rates by state.
   - **Channel-Based Analysis**: Examining complaint distributions across submission channels and their associated response times.
   - **Seasonal Trends**: Analyzing monthly and seasonal trends in complaint volumes to identify peak times.

3. **Timely Response Analysis**:
   - Studying timely response distributions across complaint types, submission channels, and states, with an aim to identify patterns and areas for improvement.

4. **Recommendations**:
   - Based on the findings, a set of actionable business recommendations is provided to guide BoA in reducing complaint volumes and enhancing customer service.
