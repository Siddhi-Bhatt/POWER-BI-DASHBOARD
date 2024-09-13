# Student Performance Dashboard
## Project Overview
This Power BI dashboard visualizes the academic performance of students across various subjects. It provides a detailed breakdown of marks, pass/fail statuses, and total scores by student USN (University Seat Number). The dashboard is designed to help educators and administrators quickly assess the performance of individual students and entire classes at a glance.

## Database Creation
The dataset used in this project was created from scratch using Excel. Leveraging functions such as `RANDBETWEEN()` and `IF()`, I generated realistic student marks and pass/fail statuses to simulate academic performance data. This approach allowed for the creation of a dynamic dataset to power the visualizations.

## Dashboard Features:
* Pass/Fail Analysis: A pie chart and small multiples highlight overall pass/fail statuses across different subjects.
* Total Marks by USN: A bar chart shows the total marks scored by each student identified by their USN.
* Detailed Student Scores: A table lists individual scores for each student across multiple subjects, offering a granular view of performance.
* Subject-wise Pass/Fail Overview: Individual grids show the pass/fail status of students for subjects like ADA, MC, DBMS, UHV, MongoDB, DMS, and Biology.

## Interactive Features:
* `Slicers`: Used to filter data dynamically across different subjects and pass/fail statuses.
* `Legends`: Applied for better differentiation and quick insights into categories (e.g., pass/fail).
* `Filtering and Sorting`: Enabled to allow users to quickly organize the data based on student performance or specific subjects.

## Key Visuals:
* Pie Chart: Displays the overall pass/fail percentage across all students.
* Bar Chart: Summarizes the total marks achieved by each student.
* Table: Lists the individual marks per student in each subject.
* Subject-wise Pass/Fail Cards: Visual cards showing the pass/fail status for each subject.

## Technology Used:
* Power BI: The primary tool used for designing and creating this dashboard.
* Excel: Used to create the dataset from scratch with functions like RANDBETWEEN(), IF(), and others.
* Data Source: Simulated dataset includes students' marks, pass/fail statuses, and USN identifiers.
* Visualization Types: Pie charts, bar charts, table visualizations, slicers, legends, and sorting/filtering mechanisms.

### How to Use:
1. Download the `.pbix` file and open it with Power BI Desktop.
2. Interact with the visuals by applying filters, slicers, and sorting to analyze the data from different angles.
3. Customize the report by modifying the dataset or adjusting the visuals as needed.

## Future Enhancements:
* Adding more interactive features such as `drill-through` and `cross-report` filters.
* Integration with real-time student data for dynamic reporting.
* Enhancing the color scheme and visual theme for better accessibility.

