# Qorvo Intern Project - Query Automation for Bins

## Overview

This project, **Query Automation for Bins**, was developed during an internship at Qorvo. The goal of the project is to automate the querying and processing of data related to bins in the semiconductor manufacturing process. Automating this process significantly improves efficiency by reducing the manual effort previously required for data retrieval and analysis. The automation includes fetching relevant data, processing it, and providing meaningful insights to engineering teams.

The project leverages Python for automation and SQL for querying data from databases. By automating the querying of bin data, the project helps streamline the analysis of manufacturing processes, enabling quicker and more accurate decision-making.

## Table of Contents

- [Project Description](#project-description)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Automation Workflow](#automation-workflow)
- [Results](#results)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)

## Project Description

The **"Query Automation for Bins"** project focuses on automating the retrieval and processing of binning data used in semiconductor manufacturing. Bins categorize semiconductor chips based on various test parameters, and analyzing this data is crucial for yield optimization and quality control. Prior to automation, querying bins was a repetitive and time-consuming manual process prone to errors.

This project automates the querying of bin data using Python scripts combined with SQL queries. The script interacts with the database to retrieve relevant binning data and generates reports that can be further analyzed by engineering teams. This automation reduces manual effort and accelerates decision-making processes.

## Requirements

The project is implemented using Python and requires the following dependencies:

- Python 3.x
- pandas
- numpy
- sqlalchemy (for database interaction)
- pyodbc (if using ODBC connections)
- Jupyter Notebook (for running and testing the notebook)

### Installing the required libraries:

You can install the required dependencies using `pip`:

```bash
pip install pandas numpy sqlalchemy pyodbc
```

## Installation

1. **Clone the Repository**:

   Clone the GitHub repository to your local machine using the following command:

   ```bash
   git clone https://github.com/Fijuwat1032/Qorvo_Project_Query_Automation_for_Bins.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd Qorvo_Project_Query_Automation_for_Bins
   ```

3. **Install the Dependencies**:

   Ensure you install all required dependencies using `pip` as mentioned above.

4. **Open the Jupyter Notebook**:

   Launch Jupyter Notebook by running the following command:

   ```bash
   jupyter notebook
   ```

   Open the notebook titled **`Query Automation for bins.ipynb`** to explore the code and analysis.

## Usage

1. **Database Connection**:

   The project uses **SQLAlchemy** to connect to the database. You will need to set up the appropriate database connection string to enable the script to fetch data. Ensure that your credentials and connection settings are correctly configured in the notebook.

2. **Query Execution**:

   Once connected to the database, the automation script retrieves data using SQL queries. The script is designed to handle the selection of specific bins, which can be modified based on the requirements of the analysis.

3. **Data Processing**:

   After retrieving the bin data, the notebook processes it using **pandas**. It performs necessary cleaning, transformations, and aggregations to prepare the data for analysis.

4. **Reporting**:

   The script generates outputs that can be easily interpreted, such as data tables or summaries that highlight key trends in the bin data. The results can be saved as CSV or Excel files for further analysis.

## Automation Workflow

The automation workflow for querying bins is structured as follows:

1. **Connect to Database**: The script establishes a connection to the required database using SQLAlchemy.

2. **Execute SQL Query**: SQL queries are used to extract binning data relevant to the analysis.

3. **Process Data**: The raw data is processed and cleaned, removing any inconsistencies or missing values.

4. **Generate Reports**: The processed data is compiled into reports that can be shared with the engineering team for further analysis and decision-making.

5. **Automate Future Queries**: The script is designed to be reused for querying updated data in future runs, allowing seamless automation of the bin querying process.

## Results

The automation of the bin data querying process produced several significant results, including:

- **Reduction in Manual Effort**: The manual process that previously took hours was reduced to minutes with the automation script.

- **Increased Accuracy**: Eliminated the chances of human error during data retrieval, leading to more accurate data for analysis.

- **Efficiency Gains**: Allowed engineers to focus on critical analysis tasks rather than spending time on repetitive data querying.

## Conclusion

The **Qorvo Intern Project - Query Automation for Bins** successfully automates a crucial part of the semiconductor manufacturing analysis process. The automation reduces manual workload, speeds up decision-making, and improves the overall efficiency of the data analysis workflow. This project demonstrates how automation can effectively streamline data retrieval and processing in manufacturing environments.

## Acknowledgments

I would like to thank the Qorvo engineering team for their guidance and support throughout this project. Special thanks to **Jason** for his invaluable assistance and to Phuong-Thao Ton-Nu for her mentorship during the internship, which helped shape this project into a successful solution for the team.
