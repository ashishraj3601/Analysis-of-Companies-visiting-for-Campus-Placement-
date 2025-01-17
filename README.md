
# Analysis of Companies visiting for Campus Placement-Dashboard

### Dashboard Link :https://mnnitedu-my.sharepoint.com/:u:/g/personal/ashish_20221031_mnnit_ac_in/EdS-s0LYprVKhyLvsb4PhDwBR9gtcflX2uft0HT069SFgg?e=JfvULP
## Problem Statement

This project focuses on developing a Power BI dashboard to analyze companies visiting the campus for placements. The dashboard provides insights into various domains such as software, consultancy, banking, and core engineering. It highlights key metrics, including the number of offers, selection processes, difficulty levels, and job roles. By visualizing trends and comparing company-specific data, the project aims to guide students in preparing strategically for placements. The interactive interface enables users to filter by domain, company, or job profile, offering a detailed overview of placement opportunities and requirements, helping students make informed decisions and enhance their placement readiness.

Insights:

Software has high demand; focus on coding and problem-solving.
Consultancy values communication and analytical skills.
Banking seeks finance knowledge and aptitude.
Core engineering prefers technical expertise and internships.
What students need to do:

Build domain-specific skills.
Practice mock interviews and aptitude tests.
Research company-specific processes.
Network and seek mentorship.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : Some column names were edited as requied for easy interpretation
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : To show average CTC offered by top 10 companies visiting campus,clustured column chart was used in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for three fields named "difficulty level", "year of visit",& "Domain".
![Screenshot (53)](https://github.com/user-attachments/assets/fd37b684-b456-4ad9-af75-e2bb8d44d2bd)

- Step 9 : A card visual was added to the canvas,representing the overall number of job offered in the camplus placement drive.
        
- Step 10 : A line chart was also added to the report design area representing the average CPI required for different companies.
- Step 11 :A Pie chart was used for representing the shares of job offered by different companies based on domain specification.Using detail labels,data value and percentage is indicated for each slices representing the count of job offers.
- Step 12 : In the report view, under the insert tab, one text boxe was added to the canvas,mentioning the title of the analysis dashboard placed at the left top position.
- Step 13 :A stacked area chart was used to show the median interview score of students of specific branches.
A card visual was used to represent sum of job offered.

![Screenshot (53)](https://github.com/user-attachments/assets/d35f69e6-fef7-488b-aee7-976ca758548c)


        
 

 # Report Snapshot (Power BI DESKTOP)

 
![Screenshot (53)](https://github.com/user-attachments/assets/31fa7e71-c59d-4b44-9888-ac41e6daa8e5)
# Insights

A single page report was created on Power BI Desktop.

Following inferences can be drawn from the dashboard;

### Total Number of job offered = 2054

   Number of job offered in software = 511 (25%)
   
   Number of job offered in core engineering = 285 (14%)

   Number of job offered in consultancy = 411 (20%)

   Number of job offered in banking = 847 (41%)

This insight can assist students to choose and prepare according to specific domain.
           
### Average CTC offered by company

In the report, average CTC of top ten companies were shown. Flipkart offered highest average CTC of Rs.3144255 while lowest average CTC was offered by Barclays Rs.2321675. 

  ### Median interview score  

Median interview score of each branch was shown using stacked area graph. This reflects the student performance in interview of specific branches.


 
 ### Minimum CGPA required
  By using basic filter for top 10 company based on data of average CTC offered, minimum CGPA requied by each companies were shown using the line chart. This analysis may help students to target their preffered companies based on their individual CGPA.
 ### All Analysed data can be separately viewed based on three factors; Difficulty level,year of visit,and Domain using three slicers placed at the right top of the report.
 ![Screenshot (53)](https://github.com/user-attachments/assets/fd37b684-b456-4ad9-af75-e2bb8d44d2bd)

