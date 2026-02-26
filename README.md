# LW1_BAsic_Sales_data
PART 1: Launching Power BI & Loading Data

Step 1: -Open Power BI Desktop, Click Start, Open Microsoft Power BI Desktop
                <img width="1714" height="907" alt="image" src="https://github.com/user-attachments/assets/976a95ef-1a0c-487f-b8e7-02456ba4a065" />

                
Step 2: Load the Dataset
        1. Click Home Tab
                 <img width="1851" height="931" alt="Screenshot 2026-02-12 115342" src="https://github.com/user-attachments/assets/77ad7bd3-c801-458e-a7da-97fe44444422" />
        2. Click Get Data
                <img width="303" height="192" alt="Screenshot 2026-02-12 115425" src="https://github.com/user-attachments/assets/879c5850-4378-422d-a595-aa1758ec536e" />
        3. Select Text/CSV
                <img width="373" height="231" alt="Screenshot 2026-02-12 115524" src="https://github.com/user-attachments/assets/ce6250c8-928c-412a-ba77-593e7a300107" />
        4. Browse and select:
                <img width="965" height="586" alt="Screenshot 2026-02-12 115557" src="https://github.com/user-attachments/assets/f3729304-787e-41b0-8654-1998bc677f7c" />
        5. Click Load
                <img width="869" height="569" alt="Screenshot 2026-02-12 213714" src="https://github.com/user-attachments/assets/db8678ca-1b7b-447e-a4fb-5bee0d14e36d" />


                
Step 3: Verify Data in Data View
        1. Click the Data View icon (table icon on the left)
                <img width="1918" height="1018" alt="image" src="https://github.com/user-attachments/assets/5fc522ef-8274-4d43-9ef4-e183bdd11151" />
        2. Check:
           ○ Are all columns visible?
                   <img width="1901" height="1006" alt="Screenshot 2026-02-12 120549" src="https://github.com/user-attachments/assets/902da758-bb16-4b4f-80b5-ab5493d0c926" />
           ○ Is “Date” formatted as Date?
                   <img width="1910" height="999" alt="Screenshot 2026-02-12 120632" src="https://github.com/user-attachments/assets/ad3aed68-a274-4daf-9dc8-7504adabb296" />
           ○ Is “Sales” formatted as Decimal Number?
                   <img width="1789" height="735" alt="Screenshot 2026-02-12 120718" src="https://github.com/user-attachments/assets/98b4284f-8db0-46c6-a301-b36e2d89e2da" />


                   
PART 2: Exploring the Interface
        <img width="1919" height="1027" alt="Screenshot 2026-02-12 121239" src="https://github.com/user-attachments/assets/b3732db7-fb5a-4dae-a9c3-92b5bc348600" />


        
PART 3: Creating Auto-Generated Visuals


Step 1: Quick Visualization
        1. Drag Sales into canvas & 2. Power BI automatically creates a visual
              <img width="1754" height="619" alt="Screenshot 2026-02-12 121752" src="https://github.com/user-attachments/assets/a9a3346b-66cc-4216-bbfc-583acc726aa6" />
        Question:
              ● What type of chart was created?
              - It a Clustered Column Chart
              ● What does it show?
              - Its shows that the sume of sale is 220229

              
Step 2: Create a Sales by Region Chart
        1. Click blank canvas & 2. Select Clustered Column Chart
              <img width="1698" height="694" alt="Screenshot 2026-02-12 145106" src="https://github.com/user-attachments/assets/a55f7b15-63ba-46d8-adea-0586abcc1524" />
        3. Drag: ○ Region → X-axis , ○ Sales → Values
              <img width="1707" height="628" alt="image" src="https://github.com/user-attachments/assets/7e8a577b-bc84-4334-8de9-8d342b7ed5ec" />
        Question:
          ● Which region has highest sales?
              - Its a the WEST region who got the highest sum of sales that 59041

              
Step 3: Sales by Category
        1. Insert a Pie Chart
          <img width="1616" height="578" alt="Screenshot 2026-02-12 145804" src="https://github.com/user-attachments/assets/52c2d7e9-3a2c-47ee-856c-ba0d1984077a" />
        2. Drag: ○ Category → Legend, ○ Sales → Values
          <img width="1403" height="588" alt="image" src="https://github.com/user-attachments/assets/811e5543-a9d6-42d8-9901-24937188e5b1" />
        Question:
          ● Which category dominates?
           - Its the Electronic 
          ● Is the distribution balanced?
           - The distribution is not balanced.

           
Step 4: Sales Over Time
        1. Insert Line Chart
          <img width="1557" height="727" alt="image" src="https://github.com/user-attachments/assets/f517d8ba-1f0a-4db6-9748-efc323775ec8" />
        2. Drag: ○ Date → X-axis, ○ Sales → Values
          <img width="1501" height="801" alt="image" src="https://github.com/user-attachments/assets/eb924e17-ba5f-4d46-8b20-61e2063cf808" />
        Question:
          ● Is there growth?
            - None, Its goes down from the date year of 2024 the sum of sale is about 202487 then went down to 17742 of date year 2025
          ● Any noticeable trend?
            - There is a significant decrease from 2024 to 2025

            
            
PART 4: Basic Data Insight Interpretation
● Which region contributes most revenue?
   - its the WEST


● Which product category performs best?
   - its the ELECTRONIC


● Are sales consistent across dates?
   - NO, it decrease from 2024 to 2025


● What business recommendation can you suggest?
   - Food Court 


LABORATORY QUESTIONS

Part A – Technical Questions

  1. What are the five columns in the dataset?
     - Category
     - Date
     - Product
     - Region
     - Sale

  2. What data type is assigned to the “Sales” column?
     - Decimal Number

  3. Which Power BI view allows you to see raw data?
     - Data View

  4. What chart type is best for showing trends over time?
     - Line Chart

  5. What aggregation is automatically applied to Sales?
     - Sum

Part B – Analytical Questions

  6. Which region has the highest total sales?
     - It is the West region that has the highest total sales.

  7. Which category has the lowest performance?
     - Office Supplies shows the lowest overall sales performance.

  8. Are sales increasing, decreasing, or stable?
     - Sales are clearly decreasing, as shown by the sharp drop from 2024 to 2025.

  9. If you were a manager, which region would you prioritize?
      - I would prioritize the lowest-performing region like north to improve performance while maintaining strong regions like the West.

  10. Provide one actionable recommendation based on the data.
      - I Find out why sales dropped in 2025 and run special promotions in the weaker regions and product categories to boost sales.


ENHANCEMENT SECTION

Advanced Exploration:

Task 1: Add a Card Visualization (1. Insert Card, 2. Drag Sales, 3. Format: ○ Increase font size, ○ Change title to “Total Sales”)
        <img width="1425" height="632" alt="image" src="https://github.com/user-attachments/assets/91b3706a-d192-4e8d-96d3-476c6b31ed2b" />
Question:
● What is the total sales amount?
    - 220k is the tTotal Sale

Task 2:( Add Slicer: 1. Insert Slicer, 2. Drag Region, 3. Test filtering )
   - <img width="1660" height="467" alt="image" src="https://github.com/user-attachments/assets/c1a67340-6b89-4a39-9497-18a142863370" />

Question:
● What happens to other visuals when you click a region?
    - When you click a region like North, the other charts update to show data for that region only. This is called cross-filtering.

● Why is filtering important in BI?
    - Filtering is important in BI because it helps you focus on specific data, compare results, spot trends quickly, and make better decisions.

Task 3: Sort Sales:(1. Click Region Chart, 2. Click three dots (...), 3. Sort by Sales Descending)
    - <img width="1710" height="662" alt="image" src="https://github.com/user-attachments/assets/20a09b7b-35bf-4c22-9033-f429b0c215e0" />

Question:
● Does sorting improve readability?
  - Yes, sorting improves readability.
  
● Why?
  - Because it puts the data in order, making it easier to compare and see which products or regions perform best or worst.

Task 4: Identify Outliers
● Which region is significantly higher or lower?
  - West is higher, and North is lower.
  
● What might explain that difference?
  - West may have more customers or higher demand than North.











