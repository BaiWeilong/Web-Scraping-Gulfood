# Web Scraping for Gulfood Exhibitors

## Project Overview

This project focuses on scraping exhibitor data from the Gulfood website. The goal is to extract comprehensive information about companies, including their names, locations, countries, and websites, for further analysis and insights.
![website](https://github.com/user-attachments/assets/1fab3480-1da4-4ae6-ae01-908b45f94ac0)

---

## Tech Stack

- **Python**: For web scraping and data processing.
- **BeautifulSoup**: For parsing HTML content.
- **Pandas**: For organizing and processing data.
- **Matplotlib & Seaborn**: For data visualization.
- **Requests**: For fetching webpage content.

---

## Logic and Solution Approach

### 1. Data Extraction
- Defined the target URL structure for paginated requests.
- Used `requests` to fetch HTML content of exhibitor pages.
- Extracted the following details for each exhibitor:
  - `Name`: Name of the exhibitor.
  - `Hall`: Location hall.
  - `Stand`: Stand number.
  - `Country`: Country of the exhibitor.
  - `WWW`: Official website URL.

### 2. Data Cleaning and Storage
- Cleaned extracted data to handle missing or invalid fields.
- Converted lists of data into a structured Pandas DataFrame.
- Exported the final dataset to an Excel file (`gulfood.xlsx`) for easy access and analysis.

### 3. Data Analysis and Visualization
- Aggregated exhibitor data by country.
- Visualized the top 10 countries with the highest number of exhibitors using a bar chart.

---

## Results

- **Total Exhibitors Scraped**: 3,837 exhibitors.
- **Key Insights**:
  - Identified top exhibiting countries and their representation.
  - Extracted website links for exhibitor outreach.

### Example Visualization

- **Top 10 Countries by Exhibitor Count**:
  A bar chart showing the distribution of exhibitors among the top 10 countries.

---

## Recommendations

- **Business Development**:
  - Utilize extracted contact and location data for targeted marketing campaigns.
  - Focus on countries with high exhibitor counts for strategic partnerships.

- **Future Improvements**:
  - Automate the scraping process to handle real-time data updates.
  - Expand scraping to include product categories and descriptions.
