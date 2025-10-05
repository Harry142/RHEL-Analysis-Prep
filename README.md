# RHEL-Analysis-Prep
RHEL Security Vulnerability Analysis
This project analyzes Red Hat Enterprise Linux (RHEL) security vulnerabilities using publicly available data from Red Hat's security data API. The analysis covers:

- CVE Data Collection: Gathering RHEL CVEs over a specified time period.
- ASB v3 Domain Mapping: Categorizing vulnerabilities based on the Azure Security Benchmark v3 control domains using keyword matching.
- Security Trend Analysis: Visualizing trends in CVE disclosures over time, by severity, and by affected package families.
- Vulnerable Asset Identification: Comparing a sample asset package inventory against known vulnerabilities to identify at-risk systems.
- Anomaly Detection: Using time series analysis to identify periods with unusual spikes in CVE disclosures.
- Investigation of Anomalies: Examining the characteristics of vulnerabilities in anomalous periods, including those with potentially incomplete package information ('Unknown Package').
- Comprehensive Reporting: Utilizing AI (Gemini) to generate a structured report summarizing the key findings and recommendations.

This project provides insights into the RHEL vulnerability landscape, helps identify potentially vulnerable assets within an environment, and highlights unusual patterns in vulnerability disclosures.

<img width="4767" height="3539" alt="4cc2f75b-7c3f-4343-8f69-730b719db40e" src="https://github.com/user-attachments/assets/fadfa74a-31a6-4607-867c-cc8f0d7456bf" />
