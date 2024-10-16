# ETL Mini Project - Crowdfunding Data Processing

### Collaborators:
- Daphine Nyangena
- Gerald Dixon
- Latifah Jones

### Project Overview:
This project is an ETL (Extract, Transform, Load) pipeline that focuses on analyzing crowdfunding campaign data. The goal of the project was to extract, transform, and analyze campaign information, creating structured DataFrames for further analysis. The project culminated in generating reports on categories and subcategories, which were exported into CSV files.

### Key Objectives:
1. Extract relevant data from a raw crowdfunding dataset.
2. Create structured DataFrames for categories and subcategories.
3. Clean and transform data to prepare it for analysis.
4. Export transformed data to CSV for future use.

### Dataset Description:
The dataset consists of various crowdfunding campaign metrics, including:
- **cf_id**: Campaign ID
- **company_name**: Name of the company
- **goal**: Target fundraising amount
- **pledged**: Amount raised
- **outcome**: Campaign success or failure
- **backers_count**: Number of backers
- **country and currency**: Information about campaign geography
- **category and subcategory**: Campaign's business type and focus area.

### Steps Performed:
1. **Data Extraction**: 
   - Loaded the dataset from an Excel file into a pandas DataFrame.
2. **Data Transformation**:
   - Separated the `category` and `subcategory` from combined fields.
   - Created two new DataFrames: one for **Category** and one for **Subcategory**.
   - Ensured sequential numbering for both categories and subcategories.
3. **Data Export**:
   - The final DataFrames were exported into two CSV files:
     - `category.csv`
     - `subcategory.csv`

### References:
- **Pandas**: Used extensively for data manipulation and cleaning.
- **NumPy**: Employed for efficient data handling.
- **Jupyter Notebook**: For interactive development and testing.
- **Excel**: The initial data source was in `.xlsx` format.
- **Boot Camp Spot**: Xpert Learning Assistant


### Conclusion:
In summary, we were able to streamline and categorize a large crowdfunding dataset, preparing it for deeper analysis. The use of Python's pandas library allowed for effective data manipulation, ensuring the data was in a format ready for further use. The exported files can be used in subsequent analysis or integrated into larger systems.
