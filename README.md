# NoSQL_Assignment_2
Column Family database

A column-oriented, open-source database management system (DBMS) called HBase is made to handle massive amounts of structured data. Since it's built on top of Apache Hadoop, HBase can store and handle enormous volumes of data over distributed clusters of limited hardware.

Large datasets may be read and written in real-time by using NoSQL database - HBase. It is frequently used in applications such as social networks, online advertising, financial services, and web analytics that need quick and random read/write access to very big databases.

Job Recuritment application is used to organize and manage the details of the companies, staffs,new appointments available.It will help the company to check their staff details , new appointment available and professional details of the staffs.This configuration includes,

1. Company - Company name,Revenue in Crore,Market Value,Total Employees
2. Staff - Staff ID, Staff Name,Position, LPA
3. New Application - AID,Name,Qualification,YOE

Tables Created using hbase
1. Company Table 

| CID | Company Name | Revenue in Crore | Market Value    | Total Employees |
|-----|--------------|------------------|-----------------|-----------------|
| 1   | Infosys      | INR 500 cr       | $69.48 Billion  | 259,619+        |
| 2   | Wipro        | INR 569 cr       | $24.15 Billion  | 231,671+        |
| 3   | Amazon       | INR 21,200 cr    | $1.011 Trillion | 1,298,000+      |

2.Staff Table

| Staff ID | Staff Name  | Position  | LPA |
|----------|-------------|-----------|-----|
| SI101    | Raju Ram    | Manager   | 24  |
| SW079    | Vijay Yadav | HR        | 12  |
| SA123    | Vignesh     | Developer | 6   |

3. New Application Table

| AID   | Name      | Qualification | YOE |
|-------|-----------|---------------|-----|
| 97562 | Sivakumar | IT            | 2   |
| 86725 | Mugesh    | CSC,PG in MBA | 5   |

I used the following terms to do the desired operation:

1) put - The values of the family in the table are updated and added using the "put" keyword.
    ![Screenshot 2023-03-29 080121](https://user-images.githubusercontent.com/122344020/228411342-3e626f8c-3457-411b-b48d-84bf2a01d362.png)
2) scan  - The table's entities are displayed using the "scan" keyword.
   get - The table's particular row are displayed using the "get" keyword.
   ![Screenshot 2023-03-29 075855](https://user-images.githubusercontent.com/122344020/228411354-f10d65d9-e103-4ded-a9e4-d695ac4c64a2.png)
   ![scan](https://user-images.githubusercontent.com/122344020/228555986-101a00b6-ecbb-4b99-b6cd-ab5d96c78f16.png)
3) create - The table is created with the "create" keyword .
    ![create](https://user-images.githubusercontent.com/122344020/228556438-0ac98691-625a-4284-9ac3-5f333b95989e.png)
4) drop - The value and the table can both be deleted using the "drop" keyword before using it we need to disable the table.
   ![delete](https://user-images.githubusercontent.com/122344020/228557530-f51c0737-5cd2-4fdf-b2a6-086f8ea70a2e.png)

Column-family databases are an effective tool for managing data, and as businesses continue to produce and gather more and more data, their use will likely increase.

Abbreviations used in this application:
    
    CID - Company ID
    AID - New Application ID 
    YOE  - Years of Experience
    LPA - Lakhs per Annum 
    
    





