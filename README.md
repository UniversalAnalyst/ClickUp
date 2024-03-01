# R Markdown Automation for ClickUp Data Retrieval

This R markdown file automates the retrieval of data from ClickUp, a web-based productivity tool (https://clickup.com/), for creating plots of Quality metrics over time. The script runs weekly, processing and visualizing values recorded in ClickUp to present data trends for leadership to monitor Quality KPIs and take necessary actions.

**Note:** For privacy reasons, the authorization token "pk_" has been omitted. Running the script in a notebook may not work properly due to specific list locations in private ClickUp space folders.

The code utilizes ClickRUp by Peter Solymos (https://github.com/psolymos/clickrup) and the tidyverse package to extract data from ClickUp, automating the creation of weekly data visualizations and eliminating manual manipulation.

## Script Sections

- **Setup**
- **Data/Task Extraction**
- **Looping Function**
  - Requests data page-by-page to accommodate data packet size limitations
- **Output Data**
  - Converts data into JSON format
- **Data Conversion**
  - Transforms JSON to a dataframe
- **Data Formatting**
- **Data Processing**
  - Detailed extraction of quality data of interest
  - Filtering, grouping, and mutating data into monthly metrics
- **Data Visualization**
  - Generates time series plots
- **Data Export**
  - Creates a CSV file of the cumulative dataset
  - Produces an HTML file of plots

Thank you for your interest. Please reach out if you have any questions or feedback!

