# cyclistic-bike-share---case-study-wtith-power-BI

## INTRODUCTION
- This capstone project is belong to Google Data Analytics Professional Certificate Course. In this case study, I will be analyzing a public dataset for a fictional company called Cyclistic, provided by the course. Here, I will be using Power BI Tool for this analysis because of its potential benefits to reproducibility, transparency, easy statistical analysis tools and data visualizations.

  ![image](https://github.com/user-attachments/assets/39335853-f77e-4bef-afca-8f2edd1b1d37)

- ## The following sets of data analysis process will be followed:

    -    Ask,

    -   Prepare

    -   Process

    -  Analyze

    -   Share

     -  Act.
** Scenerio**

You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members.But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data.

## ASK

- Three questions will guide the future marketing program:
   - 1. How do annual members and casual riders use Cyclistic bikes differently?

   -  2. Why would casual riders buy Cyclistic annual memberships?

   - 3. How can Cyclistic use digital media to influence casual riders to become members?

Lily Moreno (director of marketing and my manager) has assigned me the first question to answer: How do annual members and casual riders use Cyclistic bikes differently?

### Key tasks

- 1: Identify the business task
   - The main business obejective is to design marketing strategies aimed at converting casual riders into annual members by understanding how they differ.
     
- 2: Consider key stakeholders
   - The key stakeholders are the Director of Marketing (Lily Moreno), Marketing Analytics team, and Executive team.
 
### Deliverable

- 1: A clear statement of the business task
   - To find the differences between the casual riders and annual members

## PREPARE

- I will use Cyclistic’s historical trip data to analyze and identify trends.The data has been made available by Motivate International Inc. under this [license](https://divvybikes.com/data-license-agreement). Datasets are available here [link](https://divvy-tripdata.s3.amazonaws.com/index.html).
### Key tasks

   - 1: Download data and store it appropriately.
       - Data has been downloaded and copies have been stored securely on my computer.
   - 2: Identify how it’s organized.
       - The data is in CSV (comma-separated values) format, and there are a total of 13 columns.
   - 3: Sort and filter the data.
      - For this analysis, I will be using data for the year 2019 and 2020.
   - 4: Determine the credibility of the data.
       - For the purposes of this case study, the datasets are appropriate and will enable me to answer the business questions. The data has been made available by Motivate International Inc. This is public data that I can use to explore how different customer types are using Cyclistic bikes. But data-privacy issues will prohibit me from using rider’s personally identifiable information and this will prevent me from determining if riders have purchased multiple single passes. All ride ids are unique.

### Deliverable

- 1: A description of all data sources used
   - The main source of all the data used was provided by the [Cyclistic Company](https://divvy-tripdata.s3.amazonaws.com/index.html).
   - Download and save all Data in a folder
   - Import all data to Power BI
   - Load and merg all 13 tables into a single file
      - I made sure all the data sets have the same number of columns and also the name of each columns are the same before merging it all together
    
## PROCESS
- **Cleaning up data and adding data to prepare for analysis**

### Key tasks

- 1: Check the data for errors.

- 2: Choose your tools.

- 3: Transform the data so you can work with it effectively.

- 4: Document the cleaning process.

### Deliverables

- 1: Documentation of any cleaning or manipulation of data.
  - I inspected the new table that has been created by the following steps
    - 1: Open your **Transform data** page and create a column which is named ride_length.Calculate the length of each ride by subtracting the column started_at from the column ended_at (for
 example, =[ended_at]-[started_at]) and format as **duration**  deleted all negative or zero duration rows.
    - 2:  Create a column called day_of_week, and calculate the day of the week that each ride
 started using the WEEKDAY command(for example, WEEKDAY([started_at])).
 Format as text.
- 2: Deleted all duplicate data by selected all.
- 3:  Proceed to the analyze step.

## ANALYZE

All the data have been strored appropriately and has been prepared for analysis, so they are ready for exploration.
### Key tasks

Aggregate your data so it’s useful and accessible.
Organize and format your data.
Perform calculations.
Identify trends and relationships.
### Deliverables

A summary of your analysis

### Visualise the **distribution of casual riders and member rider** by py chart

- <p align="center">
  <img src="https://github.com/user-attachments/assets/689daeb3-7fc3-420b-9e1d-d1fd614b53db" alt="HR Dashboard" width="400">
</p>


- From the above graph, we can observe that there are more member riders compared to casual rides based on the ride count.

### Visualise the **distribution of ride duration b/w casual riders and member rider** by line chart



<p align="center">
  <img src="https://github.com/user-attachments/assets/6a063467-f2ad-4e8c-8a18-3fc1177cc59e" alt="ride_length distribution b/w casual and memeber Dashboard" width="800">
</p>



- Here we can see on **saturday** casual riders are on peak in  spending time. 
- On thursday and wednesday member riders are on peak in spending time.
- We also can observe that when member riders duration increase and simultanously casual riders duration decrease and vice-versa.

### Visualise the **number of rides b/w casual riders and member rider** on the basis of  different bikes type by pi-chart
  ![image](https://github.com/user-attachments/assets/af4044d4-344c-4680-9661-a5fb87e45678)

- From given charts we can see that docked bike is  used only by casual member
- Number of rides on docked bikes is least comparison to others




  




  <p align="center">
  <img src="https://github.com/user-attachments/assets/032e74a5-8cd1-4acf-b5c8-3ab4e6564116" alt="ride_length distribution b/w casual and memeber Dashboard" width="600">
</p>








