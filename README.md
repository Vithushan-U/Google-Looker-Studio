# Google Looker Studio: Tool Assessment & Data Analysis on Housing Prices and Labour Market Trends in Canada
This report provides a comprehensive analysis on the practical application of Google Looker Studio, evaluating its features, benefits, limitations, and user interface. It includes a step-by-step walkthrough of how the tool was used for analysis, concluding with a comparison to Microsoft Power BI and an assessment of Looker Studio’s ideal target audience.

## Analysis Overview
Using housing price data from Statista and labour characteristics data from Statistics Canada, Looker Studio was utilized to explore potential correlations between housing prices and labour force metrics across Canadian provinces in 2023.

## Key Insights
- **Which provinces have the highest housing prices?**
  - British Columbia, Ontario, and Quebec recorded the highest housing prices in 2023, with the Canadian average at $678,282.

    <img width="896" alt="Looker 1" src="https://github.com/user-attachments/assets/8f1209e0-1edd-4120-81aa-bec89691c7e1" />
  

- **Is there a correlation between the labour force and housing prices?**
  - No direct correlation was observed between provinces with high housing prices and their respective labour force size.
 
    <img width="801" alt="Looker 2" src="https://github.com/user-attachments/assets/8965f26e-86c6-4939-a501-33b29d575256" />


- **Does the job vacancy rate impact housing prices?**
  - Most provinces clustered around the median housing price with similar job vacancy rates, but Ontario, British Columbia, Saskatchewan, and Newfoundland and Labrador stood out as outliers.
 
    <img width="884" alt="Looker 3" src="https://github.com/user-attachments/assets/cdd3996c-4026-42b9-bb9d-6766ed7e8eb9" />
  

## Looker Studio Features & Limitations
- **Strengths:**
  - User-friendly interface with intuitive filtering and formatting options
  - Data blending feature enabled merging values from multiple datasets
  - Ideal for quick visualizations and seamless sharing

- **Limitations:**
  - Limited custom visuals compared to Power BI
  - Row limit and occasional connectivity issues with data uploads

## Looker Studio vs. Power BI
- Power BI is better suited for advanced data modeling, machine learning, and complex analyses.
- Looker Studio excels in quick, user-friendly visualizations for smaller datasets.

## Target Audience
**Looker Studio is best suited for:**
  - Students learning and getting started with business intelligence and visualizations.
  - Professionals working with small datasets who need easy collaboration and sharing capabilities without advanced modeling.

Despite some limitations, Looker Studio is a strong choice for users focused on simple, interactive data visualizations.

## Procedure of Analysis in Looker Studio
### 1️⃣ Data Preparation: Cleaning Up Datasets

**Three datasets were used:**

  - Housing Prices (Statista, 2023) – No cleanup was required.
  - Labour Force Data (Statistics Canada, 2023) – Headers, footers, and irrelevant columns were removed.
  - Job Vacancy Rates (Statistics Canada, 2023) – Unnecessary fields were removed for relevance.

These datasets were then stored in Google Sheets for structured data preparation.

### 2️⃣ Uploading Datasets & Understanding the UI

Looker Studio allows multiple data sources, including Google Sheets. The right-side panel provides controls to adjust dataset settings, while the visualization toolbar enables different chart types.

   <img width="809" alt="2 pro" src="https://github.com/user-attachments/assets/0eff9b04-378c-4f2e-aef1-be406774fe56" />
    

### 3️⃣ Creating Visualizations

**Looker Studio provides two main customization tabs:**

  - Setup Tab:  Assigns categories, metrics, and filters.
  - Style Tab: Adjusts formatting, fonts, and layouts.

<img width="822" alt="3 pro" src="https://github.com/user-attachments/assets/838d576e-5b06-47f5-aa2b-09d6f3cc139a" />
    

### 4️⃣ Applying Filters

**Filters allow dynamic exploration of data. Looker Studio provides:**

  - AND/OR logic to combine multiple conditions.
  - Saved filters for reuse across multiple visuals.

<img width="784" alt="4 pro" src="https://github.com/user-attachments/assets/d56d2260-2467-47a3-8b0e-5af423d4ad9a" />
    

### 5️⃣ Mixing Datasets Using Data Blend

**Since the datasets were separate, the Data Blend feature was used to merge them. The steps include:**

  1. Select data sources for blending.
  2. Define a common key (e.g., province name) to link datasets.
  3. Add relevant fields to the blended dataset.
  4. Set a join condition to establish the relationship.

<img width="746" alt="5 pro" src="https://github.com/user-attachments/assets/e6424855-5c5d-447f-aeb1-e8cc2c9ea86c" />
     

## View the Full Report
For a detailed breakdown of the analysis please refer to the written report, that is attached in the files section of this repository. This report provides deeper insights into the analysis, tool assessment, and key insights. 
