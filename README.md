

#### *Capstone Project: August 2023*

![](https://github.com/jvenncpe/QR-Code-Marketing/blob/main/images/ezgif.com-gif-maker.gif)

# QR Code Marketing Dashboard

Capstone project output from "SP401  Dashboards and Drill-Down Analytics" facilitated by Project SPARTA from Development Academy of the Philippines. The course aims to teach us skills for creating reports and dashboards that display risks and opportunities in businesses, explaining trends in key indicators. Additionally, we'll grasp creating interactive and automated reports, saving significant time.

## Activity
This dashboard should visually represent data about risks and opportunities in businesses. We had to design it so that it shows why certain trends happen in important indicators. The goal was to make it easy for users to interact with the dashboard, allowing them to explore the data.

## Dataset Context
The QR Code Marketing has three (3) dataset tables. 
- The first dataset cover metrics related to scanning activities, impressions, scan-through rates, and conversions from QR landing pages within specific time periods. 
- The second dataset contains information on the number of scans and the location of the advertisements where these scans occurred within different periods.
- The third dataset record the number of conversions and the landing pages where these conversions took place during different periods.

These datasets focus on tracking scanning activities, conversions, and associated metrics over time, providing insights into the performance of QR code campaigns, advertisement locations, and landing pages.

## Methodology
The methodology involved creating several pivot tables for the interactive dashboard as follows:
- "Performance Metrics Overview" was designed to display columns for "No. of Impressions," "No. of Scans (Actual)," and "No. of Conversions from QR Landing (Actual)." This table provides an overall snapshot of key metrics.

- "Number of Scans Comparison: Actual vs Goal" was structured to compare "No. of Scans (Goal)" against "No. of Scans (Actual)." This comparison helps in assessing performance against set targets.

- "Scan Through Rate Comparison: Actual vs Goal" included columns labeled "Scan Through Rate (Actual)," and "Scan Through Rate (Goal)." This table compares the achieved scan-through rates against the expected or targeted rates.

- "Scan Distribution Across Ad Locations" likely contains data related to the distribution of scans across different advertisement locations, with columns showing the count of scans for each location.

- "Distribution of Conversions by Landing Page" was designed to represent the distribution of conversions across various landing pages.

This methodology indicates the creation of pivot tables tailored to present specific insights regarding impressions, scans, conversions, scan-through rates, ad locations, and landing pages within the interactive dashboard.


## Visualization:

![](https://github.com/jvenncpe/QR-Code-Marketing/blob/main/images/1.PNG)

After creating the pivot tables, the visualization plan includes:
- Combo Chart: It comprises a Comparison Column Chart for "No. of Impressions" and "No. of Scans" with a secondary axis showcasing a line chart for "No. of Conversions from QR Landing." This chart aims to depict the relationship between impressions, scans, and conversions over time.

- Bullet Column Chart: This chart visualizes the comparison between the actual and goal of the number of scans. It helps in quickly assessing performance against the set targets.

- Stack Column Chart: It's intended to display the percentage differences between the goal and actual scan-through rates. This chart helps in understanding the variance between targeted and achieved rates.

- Bar Chart: This chart represents the distribution of scans across different advertisement locations, providing insights into which locations are more popular for scanning.

- Pie Chart: It's used to showcase the composition of scans based on landing pages. There's an added feature to change the display to a column chart if the slicer selections are less than three, enabling a clearer representation for smaller selections.

These visualizations aim to present insights into impressions, scans, conversions, scan-through rates, ad locations, and landing page compositions within the interactive dashboard, facilitating easy interpretation and analysis of the data.


## The Slicers:

![](https://github.com/jvenncpe/QR-Code-Marketing/blob/main/images/12.PNG)

- Time Period Slicer: This slicer allows the selection of specific months or a range of months within a year. It helps in focusing the charts on particular time periods to analyze performance trends over selected durations.
- Ad Location Slicer: This slicer is dedicated to selecting specific advertisement locations. It enables users to assess and compare the performance of individual or multiple ad locations, aiding in understanding which locations are more effective.
- Landing Page Slicer: Similar to the Ad Location slicer, this one facilitates the selection of specific landing pages. It's aimed at evaluating and comparing the performance of different landing pages, providing insights into the effectiveness of each page in driving conversions or interactions.

These slicers allows users to customize their analysis by choosing specific time frames, advertisement locations, and landing pages, enabling a more detailed and targeted examination of the data within the interactive dashboard.


## Results and Discussion

![](https://github.com/jvenncpe/QR-Code-Marketing/blob/main/images/11.PNG)

The insight above cover the whole year with the default slicer values. Since the dashboard is interactive, these insight also changes based on slicer selections for time periods, ad locations, and landing pages as shown below:

![](https://github.com/jvenncpe/QR-Code-Marketing/blob/main/images/3.PNG)

And to illustrate the trick we used at the 5th pivot table wherein the default chart is a pie chart, if only one or two landing pages are selected, the default pie chart transforms into a column chart with an interactive insight as shown below:

![](https://github.com/jvenncpe/QR-Code-Marketing/blob/main/images/6.PNG)

![](https://github.com/jvenncpe/QR-Code-Marketing/blob/main/images/7.PNG)

---
### Overall, this project provided a comprehensive framework for analyzing QR code marketing data, empowering users to glean actionable insights, make informed decisions, and refine marketing strategies.
# Thank you!
