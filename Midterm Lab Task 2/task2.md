# Midterm Lab Task 2
- This portfolio is about cleaning an excel using power query
 ## Step by Step Process


**Step 1: Download and Load Data**  
1. Download the "Uncleaned_DS_jobs.csv" dataset.  
2. Open Excel, go to **Data** > **New Query** > **From File** > **Text/CSV** to load the file.  

**Step 2: Data Cleaning Tasks**  
1. **Duplicate Raw Data**  
2. **Salary Estimate Column**  
   - Remove everything after the "(" symbol using **Transform** > **Extract** > **Text Before Delimiter**.  
3. **Create Min and Max Salary Columns**  
   - Use **Add Column** > **Column from Examples** to create Min Sal (e.g., 101) and Max Sal.  
4. **Role Type Column**  
   - Add a custom column with a formula to classify job roles based on job titles.  
5. **Split Location Column**  
   - Correct location names (e.g., "New Jersey" becomes "NJ") and split the column by comma.  
6. **Size Column**  
   - Split the company size into MinCompanySize and MaxCompanySize.  
7. **Remove Negative Values**  
   - Filter out negative values in columns like Competitors, Revenues, and Industry.  
8. **Clean Company Name**  
   - Remove rates after the company name.  
9. **Copy Applied Steps**  
   - Go to **Home** > **Advanced Editor** and copy the steps for your portfolio.  

**Step 3: Reshape and Group Tables**  
1. **Duplicate Data for Salary by Role**  
   - Right-click raw data, duplicate it, and rename it "Sal By Role Type dup".  
   - Choose columns for Role Type, Min Sal, and Max Sal, then multiply Min/Max Sal by 1000.  
   - Group by Role Type and calculate average salary.  
2. **Create Reference for Salary by Size**  
   - Duplicate raw data again, rename it "Sal By Role Size ref", and follow similar steps to group by size.  
3. **Map State Data**  
   - Right-click **Unclean DS Jobs**, add a new query for State Mapping, merge it with the dataset, and clean the state names.  
4. **Create Reference for Salary by State**  
   - Duplicate the raw data and follow similar steps to group by State and calculate average salary.  

**Step 4: Check Dependencies**  
1. Go to **View** > **Dependencies** to check the queries’ setup.


 ### Screenshots/Documentations
 ![Image](https://github.com/user-attachments/assets/d170c27d-4f9e-425d-8a86-d95ef2f93e67)
![Image](https://github.com/user-attachments/assets/d16189df-e3d3-4069-ab24-896a49c5709a)
![Image](https://github.com/user-attachments/assets/a1f97acc-d0e5-4a06-bcc5-5898477a0293)
![Image](https://github.com/user-attachments/assets/3d6b5e54-f03e-4c43-9dfc-29e7421c88c8)
![Capturess2](https://github.com/user-attachments/assets/a76271dc-3655-4be9-8b19-a3c6fd469ab2)
