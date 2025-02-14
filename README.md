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
where referee_id **IS NULL** or referee_id != 2

-------------------------------------------------------------
3. Big Countries

![image](https://github.com/user-attachments/assets/fa767a03-0dfb-4c91-b8de-ce859061412e)
![image](https://github.com/user-attachments/assets/f0f88af6-774e-44ae-9210-67bbb4f95509)
![image](https://github.com/user-attachments/assets/eb5a4d2b-24b7-401b-b487-79a1ac4a4083)

SOLUTION:-
select name, population, area from World
where area >= 3000000  or population >= 25000000

--------------------------------------------------------------
4. Article Views I

![image](https://github.com/user-attachments/assets/38407581-ab20-4fd8-92aa-fb77280032e9)
![image](https://github.com/user-attachments/assets/6f01b935-c250-43e0-8f4f-b53524c648a6)
![image](https://github.com/user-attachments/assets/5385dd24-f14c-4754-a5a5-80970d8d3510)

SOLUTION:-
select **DISTINCT** author_id as id from Views 
where viewer_id = author_id
order by author_id asc

-------------------------------------------------------------
5. Invalid Tweets

![image](https://github.com/user-attachments/assets/324ac3c8-7708-4757-960d-b3613e6e8beb)
![image](https://github.com/user-attachments/assets/b7db07b6-83f2-49ac-a5e3-e7739933b371)
![image](https://github.com/user-attachments/assets/8939cf99-5879-4a04-8c3a-3c5d89859fd9)

SOLUTION:-
select tweet_id from Tweets
where **LEN**(content) > 15

-------------------------------------------------------------
6. Replace Employee ID With The Unique Identifier

![image](https://github.com/user-attachments/assets/6081cac2-59fc-4f19-ab78-6fbedfa849a7)
![image](https://github.com/user-attachments/assets/7575c010-472d-4888-8e6d-a9f2e6cdf1f6)
![image](https://github.com/user-attachments/assets/1b7f4707-c805-456d-b08b-fdfe6392cd8b)
![image](https://github.com/user-attachments/assets/a0b4203f-a83c-4d6f-8bf6-8b0d8293c5f3)
![image](https://github.com/user-attachments/assets/9dc53056-69a4-4e09-bd87-d2679dd03b36)

SOLUTION:-
select EmployeeUNI.unique_id, Employees.name 
from Employees 
left join EmployeeUNI 
on Employees.id = EmployeeUNI.id

-------------------------------------------------------------
7. Product Sales Analysis I
   
![image](https://github.com/user-attachments/assets/743dc6fa-ceac-4e8e-8035-82c3d4d4645c)
![image](https://github.com/user-attachments/assets/0944d4d4-e1b6-41b8-91d9-f7142fb15589)
![image](https://github.com/user-attachments/assets/fab748b2-e00c-44f8-891d-5b279e1d8f08)
![image](https://github.com/user-attachments/assets/cb18d838-d864-4759-94cb-5c80430234df)

SOLUTION:-

![image](https://github.com/user-attachments/assets/cc789b6d-140a-4a5a-b0eb-63728c223666)

-------------------------------------------------------------
8. 


SOLUTION:-

-------------------------------------------------------------
9. 


SOLUTION:-

-------------------------------------------------------------
10. 


SOLUTION:-

-------------------------------------------------------------
11. 


SOLUTION:-

-------------------------------------------------------------
12. 


SOLUTION:-

-------------------------------------------------------------
13. 


SOLUTION:-

-------------------------------------------------------------
14. 


SOLUTION:-

-------------------------------------------------------------
15. 


SOLUTION:-

-------------------------------------------------------------
16. 


SOLUTION:-

-------------------------------------------------------------
17. 


SOLUTION:-

-------------------------------------------------------------
18. 


SOLUTION:-

-------------------------------------------------------------
19. 


SOLUTION:-

-------------------------------------------------------------
20. 


SOLUTION:-

-------------------------------------------------------------
21. 


SOLUTION:-

-------------------------------------------------------------
22. 


SOLUTION:-

-------------------------------------------------------------
23. 


SOLUTION:-

-------------------------------------------------------------
24. 


SOLUTION:-

-------------------------------------------------------------
25. 


SOLUTION:-

-------------------------------------------------------------
26. 


SOLUTION:-

-------------------------------------------------------------
27. 


SOLUTION:-

-------------------------------------------------------------
28. 


SOLUTION:-

-------------------------------------------------------------
29. 


SOLUTION:-

-------------------------------------------------------------
30. 


SOLUTION:-

-------------------------------------------------------------
31. 


SOLUTION:-

-------------------------------------------------------------
32. 


SOLUTION:-

-------------------------------------------------------------
33. 


SOLUTION:-

-------------------------------------------------------------
34. 


SOLUTION:-

-------------------------------------------------------------
35. 


SOLUTION:-

-------------------------------------------------------------
36. 


SOLUTION:-

-------------------------------------------------------------
37. 


SOLUTION:-

-------------------------------------------------------------
38. 


SOLUTION:-

-------------------------------------------------------------
39. 


SOLUTION:-

-------------------------------------------------------------
40. 


SOLUTION:-

-------------------------------------------------------------
41. 


SOLUTION:-

-------------------------------------------------------------
42. 


SOLUTION:-

-------------------------------------------------------------
43. 


SOLUTION:-

-------------------------------------------------------------
44. 


SOLUTION:-

-------------------------------------------------------------
45. 


SOLUTION:-

-------------------------------------------------------------
46. 


SOLUTION:-

-------------------------------------------------------------
47. 


SOLUTION:-

-------------------------------------------------------------
48. 


SOLUTION:-

-------------------------------------------------------------
49. 


SOLUTION:-

-------------------------------------------------------------
50. 


SOLUTION:-
-------------------------------------------------------------
