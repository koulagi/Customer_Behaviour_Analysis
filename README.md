# Customer_Behaviour_Analysis
📊 Data analytics project exploring customer behavior patterns, purchasing habits, and segmentation using Power BI to uncover actionable business insights.

# End-to-End Data Analytics Project: [Customer Behavior & Sales Performance]

## 📌 Project Overview
This project delivers an end-to-end data analytics solution designed to ingest, clean, model, and visualize business data to uncover actionable strategic insights. By integrating Python for exploratory analysis, SQL Server for structured relational queries, and Power BI for interactive business intelligence, the pipeline transforms messy raw data into a narrative-driven presentation for stakeholders.

**Key Objective:** To identify hidden performance trends, optimize operational decision-making, and deliver data-backed recommendations directly to executive stakeholders.

---

## 📊 Dataset Description
* **Source:** [CSV File]
* **Size:** [e.g., 4000+ rows, 15 columns]
* **Core Variables:** Includes unique customer identifiers, transaction dates, product categories, regional demographics, purchase counts, and financial values.

---

## 🛠️ Tools & Technologies Used
* **Data Extraction & EDA:** Python (Pandas, NumPy, Matplotlib, Seaborn)
* **Database Management:** Microsoft SQL Server (T-SQL)
* **Business Intelligence & ETL:** Power BI Desktop (Power Query, DAX)
* **Stakeholder Presentation:** Gamma App (AI-Assisted Presentation Design)

---

## 🚀 Execution Steps & Project Workflow

### 1. Ingestion & Exploratory Data Analysis (Python)
* Imported raw messy datasets into a Jupyter Notebook environment.
* Conducted structured EDA to assess distribution patterns, identify missing rows, and flag statistical outliers.
* Generated target visualizations (histograms and correlation matrices) to map out key data relationships.

### 2. Data Cleaning & Transformation (Python)
* Standardized text inputs, handled null values systematically, and corrected mismatched structural data types.
* Removed duplicate fields to preserve data entity integrity.
* Exported the clean, staging-ready structured files as `.csv` formatted outputs.

### 3. Relational Database Queries (SQL Server)
* Ingested clean data tables directly into a custom Microsoft SQL Server database.
* Executed advanced T-SQL queries utilizing Aggregations, Window Functions, and Common Table Expressions (CTEs).
* Validated core Key Performance Indicators (KPIs) to establish a baseline of truth prior to the visualization stage.

### 4. Interactive BI Modeling & Dashboarding (Power BI)
* Connected Power BI to the active SQL Server database instances.
* Built a relational Star-Schema data model mapping out explicit dimension-to-fact table relationships.
* Formulated scalable DAX measures (e.g., Year-over-Year Growth, Rolling Averages, Customer Lifetime Value).

### 5. Stakeholder Report & Executive Slide Deck (Gamma)
* Compiled core findings into a highly structured, readable analytic brief.
* Utilized Gamma App to convert structural metrics into an interactive, visually stunning slide deck tailored for non-technical leadership.

---

## 📈 Dashboard Previews & Live Insights
*(Tip: Take a screenshot of your Power BI dashboard and save it in your repository folder to link it below!)*

![Power BI Dashboard View](path-to-your-screenshot-image.png)

### Core Views Created:
* **Executive Summary View:** High-level metrics monitoring active dynamic growth KPIs.
* **Granular Breakdown View:** Drill-down slicers segmenting performance across varying demographic groups.

---

## 💡 Key Results & Business Impact
* **Discovered Optimization Opportunity:** Identified a specific operational bottleneck that accounts for an estimated [X%] drop in performance.
* **Customer Segment Value:** Pinpointed the highest-performing customer persona, uncovering actionable expansion targets.
* **Data-Driven Retention:** Formulated a distinct churn risk profile, allowing retention teams to proactively intervene.

---

## 💻 How to Run This Project

### Prerequisites
Ensure you have the following installed locally on your desktop machine:
* Python 3.8+ (with Anaconda or Jupyter Notebooks setup)
* Microsoft SQL Server Management Studio (SSMS)
* Power BI Desktop

### Local Installation Steps
1. **Clone this repository:**
   ```bash
   git clone https://github.com
   ```
2. **Execute Python scripts:** Navigate to the `/scripts` directory and open `eda_cleaning.ipynb` to review or run the initial processing pipeline.
3. **Database Population:** Execute the initialization scripts located within `/sql/schema_setup.sql` inside SQL Server to construct the required tables. Run `analysis_queries.sql` to generate analytical snapshots.
4. **Launch Power BI Dashboard:** Open the main desktop file `/dashboards/final_report.pbix` to explore the interactive components.
5. **Review Stakeholder Deck:** Access the web-ready slide presentation via the provided [Gamma Presentation URL Key](https://gamma.app).
