# SQL-LeetCode-Top_50_SQL

Reference URL - https://leetcode.com/studyplan/top-sql-50/
*** ALL SOLUTIONS TESTED FOR MS SQL SERVER VARIANT ONLY. ***
-------------------------------------------------------------
1. Recyclable and Low Fat Products

![image](https://github.com/user-attachments/assets/7ca91364-75fe-4990-904c-9cf0aa6f9da8)
![image](https://github.com/user-attachments/assets/fea4f3b3-f125-4cd5-957c-fd68cdcd153c)

SOLUTION:-
SELECT product_id from Products
where low_fats = 'Y' and recyclable = 'Y'

-------------------------------------------------------------
2. Find Customer Referee

![image](https://github.com/user-attachments/assets/d8378a17-7679-43df-8be3-a87f6b847e8b)
![image](https://github.com/user-attachments/assets/b68e8a6f-434b-4339-94e4-1d636b48894f)

SOLUTION:-

![image](https://github.com/user-attachments/assets/71b9337a-be2d-476b-9bf1-aca9cf2af5a7)

-------------------------------------------------------------
3. Big Countries

![image](https://github.com/user-attachments/assets/f0f88af6-774e-44ae-9210-67bbb4f95509)
![image](https://github.com/user-attachments/assets/eb5a4d2b-24b7-401b-b487-79a1ac4a4083)

SOLUTION:-
select name, population, area from World
where area >= 3000000  or population >= 25000000

--------------------------------------------------------------
4. Article Views I

![image](https://github.com/user-attachments/assets/6f01b935-c250-43e0-8f4f-b53524c648a6)
![image](https://github.com/user-attachments/assets/5385dd24-f14c-4754-a5a5-80970d8d3510)

SOLUTION:-
select **DISTINCT** author_id as id from Views 
where viewer_id = author_id
order by author_id asc

-------------------------------------------------------------
5. Invalid Tweets

![image](https://github.com/user-attachments/assets/b7db07b6-83f2-49ac-a5e3-e7739933b371)
![image](https://github.com/user-attachments/assets/8939cf99-5879-4a04-8c3a-3c5d89859fd9)

SOLUTION:-
select tweet_id from Tweets
where **LEN**(content) > 15

-------------------------------------------------------------
6. Replace Employee ID With The Unique Identifier

![image](https://github.com/user-attachments/assets/3b84f313-dc5e-463e-9da9-d5acc8ca3e8c)

![image](https://github.com/user-attachments/assets/aaa7624b-30bb-4155-9511-18ba36d1cdc7)
![image](https://github.com/user-attachments/assets/f471a612-b037-44e1-b61e-6636eae968af)

SOLUTION:-

![image](https://github.com/user-attachments/assets/ed45ca6d-b918-4ab1-8de9-aaf923adb948)

-------------------------------------------------------------
7. Product Sales Analysis I
   
![image](https://github.com/user-attachments/assets/743dc6fa-ceac-4e8e-8035-82c3d4d4645c)
![image](https://github.com/user-attachments/assets/0944d4d4-e1b6-41b8-91d9-f7142fb15589)
![image](https://github.com/user-attachments/assets/fab748b2-e00c-44f8-891d-5b279e1d8f08)
![image](https://github.com/user-attachments/assets/cb18d838-d864-4759-94cb-5c80430234df)

SOLUTION:-

![image](https://github.com/user-attachments/assets/cc789b6d-140a-4a5a-b0eb-63728c223666)

-------------------------------------------------------------
8. **Customer Who Visited but Did Not Make Any Transactions**

![image](https://github.com/user-attachments/assets/b74dad5d-8b06-42a5-ab9b-1c8b799033ba)
![image](https://github.com/user-attachments/assets/56e77e72-6346-4309-a956-10527b742dca)
![image](https://github.com/user-attachments/assets/593b9fdb-37e7-42aa-b051-5177b44a7355)
![image](https://github.com/user-attachments/assets/76960bb4-230d-4de8-84a9-500f2c9c0411)

SOLUTION:-

![image](https://github.com/user-attachments/assets/63f2e861-1bab-4cb5-b074-6b55565d99c9)

-------------------------------------------------------------
9. Rising Temperature

![image](https://github.com/user-attachments/assets/a15838d3-16fd-4bcf-86a5-094a4a85f48b)
![image](https://github.com/user-attachments/assets/054adc55-ba8a-4a40-ae73-69f4b008ca2a)

SOLUTION:-

![image](https://github.com/user-attachments/assets/02567cc4-288b-46d8-99f1-5aa76e7a3fa3)

-------------------------------------------------------------
10. Average Time of Process per Machine

![image](https://github.com/user-attachments/assets/63505ede-e9bf-4db0-93af-1fd18b75a8c7)
![image](https://github.com/user-attachments/assets/f0ae6a7f-f72c-4212-8ee2-add4ff5b1253)

SOLUTION:-

![image](https://github.com/user-attachments/assets/95d8ebd7-4cf3-4930-854b-dfba3785e1f0)

-------------------------------------------------------------
11. Employee Bonus

![image](https://github.com/user-attachments/assets/51356fbb-913d-4eba-9864-2be798af47fb)
![image](https://github.com/user-attachments/assets/f2cbc04f-0b58-413f-9c4d-50e7a5c729d1)
![image](https://github.com/user-attachments/assets/b84e4ebb-897e-4331-959c-786a59415325)

SOLUTION:-

![image](https://github.com/user-attachments/assets/6f40e959-d704-4694-b8df-326c38235b39)

-------------------------------------------------------------
12. Students and Examinations

![image](https://github.com/user-attachments/assets/d161a692-ba53-4a9f-8462-4b1f7318c113)

![image](https://github.com/user-attachments/assets/cb703b1c-4b31-4f28-b66f-cace1a0ade35)
 ![image](https://github.com/user-attachments/assets/8f5b610b-4d60-4648-81d5-ea08121efaaa)
  ![image](https://github.com/user-attachments/assets/97bcad20-d207-4701-ba60-02ebc0e8fde0)

![image](https://github.com/user-attachments/assets/f477825e-0348-4bc6-bcf8-92b30ebe4c23)

SOLUTION:-

![image](https://github.com/user-attachments/assets/49c82316-915d-4303-afe5-e421680350cd)

-------------------------------------------------------------
**13. Managers with at Least 5 Direct Reports**

![image](https://github.com/user-attachments/assets/90fd9558-414c-4eac-9741-f5e5f45b7f15)
![image](https://github.com/user-attachments/assets/13dd2fa5-4dfc-40da-8031-a2f35f69e2de)

SOLUTION:-

![image](https://github.com/user-attachments/assets/c74a6e7f-3700-4def-bd70-6e6471850dd2)

-------------------------------------------------------------
14. Confirmation Rate

![image](https://github.com/user-attachments/assets/0d888fd7-60ac-4dc4-9872-8fbfa4297fb5)
![image](https://github.com/user-attachments/assets/8627d1ef-22c8-445b-a68b-2a1f34e3d0bf)
![image](https://github.com/user-attachments/assets/b0a12338-bd32-46da-92b0-535ee353559a)
![image](https://github.com/user-attachments/assets/da7ed73d-6e00-41f6-b1fd-57214e113673)

SOLUTION:-

![image](https://github.com/user-attachments/assets/49105daa-f40d-4fde-b108-999e838ca46f)

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
