# Once Analytics: AI Job Market Analytics Dashboard 📊

**Author**: Rendi Dwi Andika  
**Tools Used**: Power BI, Power Query, DAX, SVG UI Design  
**Portfolio Link**: [Insert Web Link Here]

## 📌 Project Overview
Once Analytics is a professional data analytics agency focusing on workforce intelligence and labor market trends. With thousands of global job openings, salary records, and applicant data points spanning 2025–2026, management and job seekers required a unified, high-precision analytics platform. 

This project provides an interactive **Executive Dashboard** acting as a single source of truth to empower stakeholders with actionable, data-driven insights into the evolving global AI job market.

## 📸 Dashboard Previews
<video src="https://github.com/user-attachments/assets/e6d92deb-1c0d-4932-a8ad-6f6b8472d720" muted playsinline width="100%" controls></video>

## 🗄️ Data Architecture & Modeling
To ensure efficient processing and accurate metric calculations, the data was structured cleanly using a relational model approach.

<img width="1076" height="382" alt="Screenshot 2026-10-03 002015" src="https://github.com/user-attachments/assets/f8d2c883-a2bd-483e-abea-c864106032bd" />

*   **Fact Table**: `Fact_JobPostings` (Core transactional table containing job postings, posting dates, and application deadlines).
*   **Dimension Tables**: `Dim_Date` (for temporal analysis) and `Dim_JobSkills` (for technical skill granularities).
*   **Measure Table**: Dedicated container for organized DAX calculations.
  
*   **Executive Summary Page**: High-level KPIs and multi-dimensional charts tracking monthly trends, salary distribution by experience, work models, top skills, and competitive roles.
*   **Detailed Records Page**: Granular grid view providing full record-level transparency with optimized column visibility, data bars, and metadata footnotes.

## 🛠️ Technical Highlights
This project highlights several key data transformation, UI/UX, and modeling techniques:
1.  **Custom Agency Branding & UI/UX**: Designed a custom dark-mode minimalist sidebar featuring a bespoke SVG logo and structured "Control Panel" layout.
2.  **ETL & Power Query**: Cleaned raw datasets, standardized global currencies, and optimized performance for smooth cross-filtering.
3.  **DAX Implementations**: 
    *   Created dynamic measures for total job volumes, average compensation in USD, applicant metrics, and competition ratios.
    *   Implemented robust filter contexts to power synchronized global slicers (*Year, Month, Employment Type, Experience Level*).

## 📈 Key Business Insights
*   **Market Demand & Volume:** The market tracks significant job openings with high applicant pressure, peaking across strategic operational months.
*   **Compensation Tiers:** Executive and Lead roles command substantial salary premiums, while Mid and Entry levels form the broad foundational hiring volume.
*   **Work Model Preferences:** Hybrid and On-Site structures dominate the distribution, flanked by strong remote opportunities.
*   **Skill Requirements:** Core programming languages (Python, SQL) and technical specializations (PyTorch, RAG) remain the most critical in-demand competencies.

## 💡 Actionable Recommendations
1.  **Job Seekers & Professionals:** Focus skill development on high-demand technical stacks (Python, RAG, PyTorch) to navigate high competition ratios effectively.
2.  **Recruiters & HR Leaders:** Calibrate compensation benchmarks according to experience tier distributions to attract top-tier talent in specialized AI roles.
3.  **Strategic Planning:** Monitor monthly hiring fluctuations to optimize recruitment campaign timings and budget allocations.

## 📁 Repository Contents
*   `Once_Analytics_Dashboard.pbix`: The main Power BI file containing the dashboard and data model.
*   `AI Job Market Analysis BRD.pdf`: Formal Business Requirements Document.
*   `Icon Used/`: Folder containing custom SVG logos and interface icons.
*   `dataset_ai_jobs_2026.csv`: Source dataset used for the analysis.
