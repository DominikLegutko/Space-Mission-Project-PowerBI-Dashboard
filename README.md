# Space-Mission-Project-PowerBI-Dashboard

## Project Description
This project analyzes space mission data. The analysis is conducted using Power BI, a powerful data visualization tool, to explore and understand various aspects of space missions.

## Tools

- **Data Analysis Tool:** Power BI
- **Dataset:** `space_mission.csv`
  
## Main Goals and Questions

**Rocket Launch Trends:**
- How have rocket launches trended over time? Has the mission success rate increased?

**Companies with Most Successful Missions:**
- Which company has had the most successful space missions? Has this trend remained consistent?

**Most Frequently Used Rockets:**
- Which rockets have been used for the most space missions? Are they still active?

**Launch Location Patterns:**
- Are there any noticeable patterns in launch locations?
Możesz skopiować powyższy tekst i wkleić go do pliku README na GitHubie. Tekst ten utrzyma formatowanie w formie pogrubień i list, zachowując czytelność.


### Dashboard Creation Plan and Schema

1. **Data Acquisition:**
   - Retrieve data from the mavesanalitycs website or load the `space_mission.csv` file.

2. **Load Data into Power BI:**
   - Load the data into Power BI to initiate the analysis.

3. **Modify 'Price' Column:**
   - Format the 'Price' column appropriately for easier financial analysis.

4. **Create 'Date Table':**
   - Create a new table containing dates to serve as a time dimension.

5. **Establish Relationships and Create 'Measurements' Table:**
   - Create relationships between the Space missions table and the Date Table for analyzing time trends.
   - Create a new table called 'Measurements' containing various measures related to space missions, including:
     - **Total Missions:** Calculate the total number of space missions.
     - **Successful Missions:** Calculate the number of successful space missions.
     - **Total Price:** Calculate the total cost of space missions.
     - **Failed Missions:** Calculate the number of failed space missions.
     - **Partial Failed Missions:** Calculate the number of partially successful space missions.
     - **Prelaunch Failed Missions:** Calculate the number of missions that failed before launch.
     - **Legend and Successful Rate:** Create a measure displaying legends explaining the data symbols and the percentage of successful missions.

6. **Report Designing and Data Modeling:**
   - Create visualizations and design the report in Power BI, incorporating all the measures and relationships.

7. **Data Filtering:**
   - Add filters to facilitate information search, including a filter in the top right corner for quick data exploration.
  

     
