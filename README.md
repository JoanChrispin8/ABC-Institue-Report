# ABC-Institue-Report

ABC-Institue-Report
🔗 Dashboard Link: https://drive.google.com/file/d/1YWvmMwyYZlG_dPaip-Tg_ucQVpV1n_Cg/view?usp=sharing

This dashboard was developed for ABC Institute to analyze and monitor key academic and operational metrics. It provides visibility into course enrollments, student demographics, financial insights, and certification trends. These insights help the institution optimize course offerings, improve student engagement, and manage finances effectively.

✅ Steps Followed:

1.Data Loading

-> Loaded CSV/Excel data into Power BI Desktop.

2.Data Cleaning & Profiling

-> Used Power Query Editor.

-> Enabled Column Profile, Column Quality, and Column Distribution.

-> Switched profiling to entire dataset for accuracy.

3.Null Handling

-> Checked for nulls in key columns and excluded them where necessary for metrics accuracy.

4.Theme Customization

-> Applied a clean Power BI theme via the View tab.

5.Visual Filters (Slicers)

-> Filters added for:

-> Year

-> City

-> Course

6.DAX Calculations

-> Total Fees

 [Total Fees = SUM(Data[Fees])]
-> Total Students

 [Total Students = COUNT(Data[StudentID])
-> Certificates Issued

Counted based on issuance flag or column in the dataset.
7.Age Group Categorization

-> Created a calculated column for age buckets:

    [Age Group = 
    IF(Data[Age] <= 20, "Below 20",
    IF(Data[Age] <= 25, "20-25",
    IF(Data[Age] <= 30, "25-30", "30+")))]
8.Visuals Created

📊 Count of Courses by Month: 

   ->Bar/line chart showing how many courses were conducted per month.

   ![Image](https://github.com/user-attachments/assets/40fda9ab-c2d3-49e5-ad53-d39185160e5b)   

👥 Count of Courses by Age Group: 

    ->Chart displaying course popularity across age groups.

   ![Image](https://github.com/user-attachments/assets/53a1ce09-c24d-4b1e-a16d-9db132c3a5eb)

🧾 Certificates Issued: 

    ->Visual showing the number of certifications awarded.

   ![Image](https://github.com/user-attachments/assets/5ebc0b6b-7c6d-4a20-acce-ca24bc2a322f)

💰 Sum of Fees by Course: 

    ->Chart comparing total fees collected per course.

   ![Image](https://github.com/user-attachments/assets/ce25dc5b-2688-42a9-9991-a6bd6b227863)

📈 Total Fees: 

    ->Card displaying overall revenue.

   ![Image](https://github.com/user-attachments/assets/9db905e6-5845-41a7-820c-ab02041e131c)

👨‍🎓 Total Students: 

    ->Card showing total number of students.

   ![Image](https://github.com/user-attachments/assets/5db785db-ac6d-4800-b538-5ee98f3fd0d0)

🗓️ Year-wise Distribution:

   ![Image](https://github.com/user-attachments/assets/eeff7eca-5e37-46e1-9a70-95dead527e2c)


🌆 City-wise Distribution:

   ![Image](https://github.com/user-attachments/assets/1b65b104-7345-4c2b-b869-2518ebad93ee)


📘 Course:

   ![Image](https://github.com/user-attachments/assets/d4918f58-75d6-45d3-a64c-9d9b3a2dbe45)


9.Publishing:

-> Report published to Power BI Service for sharing and online access.

📊 Key Insights:

Total Students: [Insert number]

Total Fees Collected: ₹[Insert value]

Popular Courses: [Insert list if known]

Top Cities by Enrollment: [Insert list]

Most Active Months: [Insert months]

Age Group with Most Enrollments: [Insert age group]

Certificates Issued: [Insert total]
