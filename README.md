# 🏗️ Concrete Strength Analytics & Six Sigma Intelligence Platform

An enterprise-grade analytics platform for Concrete Cube Compressive Strength Evaluation, ACI Acceptance Verification, and Six Sigma Quality Intelligence.

This dashboard transforms routine concrete cube test data into actionable engineering insights through advanced statistical analysis, compliance monitoring, risk assessment, abnormality detection, and executive reporting.

---

## Overview

The Concrete Strength Analytics & Six Sigma Intelligence Platform enables quality engineers, construction managers, QA/QC professionals, consultants, and project leadership teams to evaluate concrete strength performance using:

- ACI-style acceptance criteria
- Six Sigma process capability analysis
- Statistical quality control
- Risk intelligence analytics
- Supplier and mix performance benchmarking
- Executive dashboards and reporting

The system automatically processes uploaded Excel files and generates a complete quality intelligence dashboard for decision-making.

---

## Features

### Data Management

- Excel file upload
- Automatic column mapping and validation
- Data preview and cleansing
- Support for standard concrete cube strength logs
- Handles formatted cube testing registers

### Concrete Strength Analytics

- Cube strength calculation
- Test average strength evaluation
- Characteristic strength determination
- 28-day strength filtering
- Grade-aware analysis (M20, M25, M30, M35, M40, etc.)
- Supplier-wise performance review
- Structure-wise quality tracking

### ACI Compliance Verification

The dashboard evaluates concrete acceptance using ACI-style criteria:

#### Rule 1

Moving average of any 3 consecutive strength tests shall be:

    ≥ Specified Strength (f'c)

#### Rule 2

For:

    f'c ≤ 35 MPa

No individual test average shall fall below:

    f'c − 3.5 MPa

#### Rule 3

For:

    f'c > 35 MPa

No individual test average shall fall below:

    0.90 × f'c

The system automatically identifies non-compliance and highlights risk areas.

---

## Six Sigma Quality Intelligence

The platform calculates:

- Mean
- Standard Deviation
- Coefficient of Variation (CV)
- Cp
- Cpk
- Sigma Level
- Defect Percentage
- Process Capability

---

## Risk Intelligence Engine

### Green

- Fully compliant
- Stable process
- Low variation

### Amber

- Trend concern
- Marginal capability
- Requires monitoring

### Red

- Non-compliant
- High variation
- Immediate action required

---

## Abnormality Detection

Automatically detects:

- Statistical outliers
- Sudden strength drops
- Repeated low-strength trends
- Excessive variation
- Process instability
- Potential quality risks

---

## Positive Opportunity Analytics

The system identifies:

- Best-performing supplier
- Best mix design
- Strongest concrete grade
- Most consistent structure
- High-performing project zones
- Process improvement opportunities

---

## Interactive Dashboards

Built using Plotly interactive visualizations.

### Strength Trend Analysis

- Strength progression
- Target strength comparison
- Historical trend monitoring

### Control Charts

- Statistical process control
- Process stability evaluation

### Histograms

- Strength distribution analysis
- Variation assessment

### Supplier Performance

- Vendor benchmarking
- Comparative strength evaluation

### Mix Design Performance

- Mix optimization analysis
- Design consistency review

---

## Executive KPI Dashboard

The dashboard provides real-time KPI cards:

- Total Cubes Tested
- Average Strength (MPa)
- Characteristic Strength (MPa)
- Six Sigma Level
- Cp
- Cpk
- Defect Percentage
- ACI Compliance Score

---

## Export & Reporting

Generate:

- Excel analysis reports
- Compliance summaries
- Quality intelligence reports
- Executive dashboards
- Printable PDF-ready reports

---

## Technology Stack

| Technology | Purpose |
|------------|----------|
| Python | Core Application |
| Streamlit | Dashboard Framework |
| Pandas | Data Processing |
| NumPy | Numerical Analytics |
| Plotly | Interactive Visualizations |
| OpenPyXL | Excel Import & Export |

---

## Project Structure

Concrete-Strength-Analytics/
│
├── app.py
├── analytics.py
├── requirements.txt
├── README.md
│
├── reports/
│   └── exported_reports.xlsx
│
└── sample_data/
    └── concrete_cube_log.xlsx

---

## Installation

### Clone Repository

git clone https://github.com/YOUR-USERNAME/concrete-strength-analytics.git

cd concrete-strength-analytics

### Install Dependencies

pip install -r requirements.txt

### Run Application

streamlit run app.py

Open your browser:

http://localhost:8501

---

## Requirements

streamlit
pandas
numpy
plotly
openpyxl

Or install directly:

pip install streamlit pandas numpy plotly openpyxl

---

## Excel Input Format

The application accepts:

- Concrete Cube Strength Registers
- Cube Compression Test Logs
- QC Laboratory Reports
- Clean Excel Tables

### Required Fields

| Column | Description |
|----------|------------|
| test_date | Date of cube test |
| specified_strength | Required design strength (MPa) |
| test_average | Average cube strength |

### Recommended Fields

| Column | Description |
|----------|------------|
| cube_1 | Cube 1 strength |
| cube_2 | Cube 2 strength |
| cube_3 | Cube 3 strength |
| age_days | Age of cube |
| grade | Concrete grade |
| supplier | Supplier name |
| mix_id | Mix design identifier |
| structure | Structure / Location |

### Supported Aliases

| Standard Name | Alternative Names |
|--------------|-------------------|
| test_date | date |
| specified_strength | fc |
| supplier | vendor |
| mix_id | mix design |
| structure | location |

---

## Dashboard Outputs

The platform generates:

✔ Executive KPI Dashboard

✔ ACI Compliance Assessment

✔ Six Sigma Capability Metrics

✔ Risk Classification

✔ Abnormality Detection Alerts

✔ Positive Opportunity Insights

✔ Interactive Plotly Visualizations

✔ Downloadable Excel Reports

✔ Printable Management Reports

---

## Example Use Case

For an M30 concrete project, the platform:

1. Identifies all 28-day cube test results.
2. Calculates test average strengths.
3. Verifies ACI acceptance criteria.
4. Computes Six Sigma capability metrics.
5. Detects abnormal trends and risks.
6. Identifies top-performing suppliers and mix designs.
7. Produces an executive-quality dashboard for project leadership.

---

## Target Users

- QA/QC Engineers
- Construction Managers
- Project Managers
- EPC Contractors
- Consultants
- Quality Heads
- Ready Mix Concrete Suppliers
- Infrastructure Project Teams

---

## License

This project is intended for:

- Engineering analytics
- Construction quality management
- Educational and research purposes
- Six Sigma process improvement studies

Users are responsible for verifying compliance requirements with applicable project specifications, standards, and contractual obligations.

---

## Built for Data-Driven Construction Quality Excellence

Transform concrete test data into actionable quality intelligence through ACI compliance analytics, Six Sigma methodology, and AI-powered engineering insights.
