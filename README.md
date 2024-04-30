# DataStage Project: Retail Sales Analysis

## Overview
This project demonstrates the implementation of a star-schema data warehousing flow using IBM InfoSphere DataStage within the context of a retail industry scenario. The goal is to build a sales analysis data warehouse with dimensions including customer, store, and product. This README provides an overview of the project structure, modeling process, and implementation details.

## Scenario
In our fictitious scenario, a national department store decides to construct a star-schema sales analysis data warehouse to gain insights into its business operations. The warehouse is fed data from an OLTP system and is designed to handle changing dimension attributes while preserving versions for accurate historical analysis.

## Modeling Process
1. **Logical Data Model:** Define the entities, attributes, and relationships relevant to the retail sales analysis.
2. **Physical Data Model:** Translate the logical model into a physical representation suitable for implementation.
3. **Data Mart Design:** Design data marts such as RETAIL_DATA_MART and ACTIVATION_SALES_DATA_MART to meet specific business needs.

## Implementation
### Steps:
1. **Data Preparation:**
   - Prepare sample data files containing information on customers, stores, products, and transactions.
2. **ETL Process:**
   - Utilize DataStage to create ETL solutions for loading data into files or databases.
   - Read source data, and apply necessary transformations to meet business requirements.
3. **Data Mart Creation:**
   - Design and implement data marts based on business needs.
   - Example: Create RETAIL_DATA_MART to display transaction details for each customer, differentiated by customer type (citizen or foreign).
4. **Analysis and Bonus Calculation:**
   - Analyze data in the created data marts to fulfill specific business queries.
   - Calculate bonuses for customers based on profit using defined equations.

### DataStage Pipeline:
- **Joining Data:** Use DataStage's sequential files and join jobs to combine data from multiple tables.
- **Transformation:** Apply transformations, such as aggregation functions using aggregator jobs, for analysis purposes.
- **Sorting and Filtering:** Employ sorting and head jobs to manage data flow efficiently.

  ![joinner](https://github.com/emadeldinadel2022/RetailETL_DataStageProject/assets/62083769/919c807b-1dd1-45fe-bddd-fe952f87fc92)
  ![aggregators](https://github.com/emadeldinadel2022/RetailETL_DataStageProject/assets/62083769/214d1b8d-ab30-4cba-ad55-887a23ac8e12)
  ![final_annual_income](https://github.com/emadeldinadel2022/RetailETL_DataStageProject/assets/62083769/490d597e-a438-40c8-bc0d-108ba5719fe7)


## Usage
1. Clone the repository.
2. Ensure IBM InfoSphere DataStage is installed and configured.
3. Follow the provided documentation to set up and execute the DataStage jobs.
4. Explore the generated data marts for retail sales analysis.
5. Refer to the README files within each job directory for detailed instructions on job execution and configuration.

