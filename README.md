# Crowdfunding Data Analysis Project

## Project Overview
This project involves analyzing a dataset of 1,000 sample crowdfunding projects to uncover trends and insights in the crowdfunding market. The analysis includes various aspects such as project outcomes, funding goals, backers, categories, launch dates, and more.

## Project Structure
The project is structured into the following components:

- **Data Cleaning and Formatting**:
  - Applied conditional formatting to the Outcome column to differentiate between successful, failed, canceled, and live campaigns.
  - Calculated the Percent Funded for each campaign and applied conditional formatting based on a three-color scale.
  - Calculated the Average Donation per backer.
  - Categorized projects into Parent Category and Sub-Category columns for better analysis.

- **Category and Subcategory Analysis**:
  - Utilized pivot tables and pivot charts to analyze campaign outcomes per category and sub-category.
  - Created a stacked-column pivot chart filtered by country and parent category for deeper insights.

- **Date Conversion**:
  - Converted Unix timestamps in the launched_at and deadline columns into Excel's date format for easier analysis.

- **Outcomes Based on Launch Date**:
  - Conducted analysis on campaign outcomes based on their launch dates using pivot tables and pivot-chart line graphs.

- **Crowdfunding Goal Analysis**:
  - Created a table and graph showing the percentage of successful, failed, and canceled projects based on different crowdfunding goal ranges.
  - Utilized the COUNTIFS() formula for goal range analysis and visualization.

- **Statistical Analysis**:
  - Evaluated the number of backers for successful and unsuccessful campaigns, calculating summary statistics like mean, median, minimum, maximum, variance, and standard deviation.

- **Comprehensive Report**:
  - A comprehensive report answering key questions and drawing conclusions from the analysis is provided in a separate Microsoft Word document within this repository.

## Repository Structure
- `CrowdfundingBook.xlsx`: Excel workbook containing the dataset and analysis results.
- `Crowfunding Analysis.docx`: Microsoft Word document containing a brief analysis of the results.
- `README.md`: This README file providing an overview of the project.

## Tools Used
- Microsoft Excel
- Pivot tables and pivot charts

## Conclusion

This project showcases my proficiency in utilizing Excel for data analysis and visualization to derive meaningful insights from a dataset of 1,000 sample crowdfunding projects. By employing data cleaning, conditional formatting, pivot tables, statistical analysis, and data visualization techniques, I was able to:

- Identify trends and patterns related to crowdfunding campaign outcomes, funding goals, backer engagement, and temporal factors.
- Create informative visualizations such as pivot charts, line graphs, and conditional formatting to present data trends effectively.
- Derive actionable insights and recommendations for optimizing crowdfunding campaign success rates based on the analysis results.
