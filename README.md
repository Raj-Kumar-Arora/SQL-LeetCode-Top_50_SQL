# SQL-LeetCode-Top_50_SQL

Reference URL - https://leetcode.com/studyplan/top-sql-50/
-------------------------------------------------------------
1. Recyclable and Low Fat Products

![image](https://github.com/user-attachments/assets/2b16c58c-cbc7-49f7-b51a-c3c86d6dd471)
![image](https://github.com/user-attachments/assets/7ca91364-75fe-4990-904c-9cf0aa6f9da8)
![image](https://github.com/user-attachments/assets/fea4f3b3-f125-4cd5-957c-fd68cdcd153c)

SOLUTION:-
SELECT product_id from Products
where low_fats = 'Y' and recyclable = 'Y'

-------------------------------------------------------------
2. Find Customer Referee

![image](https://github.com/user-attachments/assets/bc489a96-6dcf-4765-b5bd-fd4bb9310a6b)
![image](https://github.com/user-attachments/assets/006051b9-447e-4538-aae7-f7fb5927c115)
![image](https://github.com/user-attachments/assets/30dc53a8-0728-4df5-af15-ce5324d628e2)

SOLUTION:-
select name from Customer 
where referee_id IS NULL or referee_id != 2
