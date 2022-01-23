HW_1_Postman
![](/imgHW1Postman/.png)<br>
# Создать запросы в Postman.

**Protocol:** http <br> 
**IP:** 162.55.220.72 <br>
**Port:** 5005 <br>

### EP_1
Method: GET <br>
EndPoint: /get_method <br>
request url params: <br>
 name: str <br>
 age: int <br>

response: <br>
[<br>
    “Str”,<br>
    “Str”<br>
]<br>

![1](/imgHW1Postman/1.png)<br>
---

### EP_2
Method: POST<br>
EndPoint: /user_info_3<br>
request form data: <br>
 name: str<br>
 age: int<br>
 salary: int<br>

response: <br>
{'name': name,<br>
          'age': age,<br>
          'salary': salary,<br>
          'family': {'children': [['Alex', 24], ['Kate', 12]],<br>
                     'u_salary_1_5_year': salary * 4}}<br>
                     
![2](/imgHW1Postman/2.png)<br>

---

### EP_3
Method: GET<br>
EndPoint: /object_info_1<br>
request url params: <br>
 name: str<br>
 age: int<br>
 weight: int<br>

response: <br>
{'name': name,<br>
          'age': age,<br>
          'daily_food': weight * 0.012,<br>
          'daily_sleep': weight * 2.5}<br>

![3](/imgHW1Postman/3.png)<br>
---

### EP_4
Method: GET<br>
EndPoint: /object_info_2<br>
request url params: <br>
 name: str<br>
 age: int<br>
 salary: int<br>

response: <br>
{'start_qa_salary': salary,<br>
          'qa_salary_after_6_months': salary * 2,<br>
          'qa_salary_after_12_months': salary * 2.7,<br>
          'qa_salary_after_1.5_year': salary * 3.3,<br>
          'qa_salary_after_3.5_years': salary * 3.8,<br>
          'person': {'u_name': [user_name, salary, age],<br>
                     'u_age': age,<br>
                     'u_salary_5_years': salary * 4.2}<br>
          }<br>
![4](/imgHW1Postman/4.png)<br>

---

### EP_5
Method: GET<br>
EndPoint: /object_info_3<br>
request url params: <br>
 name: str<br>
 age: int<br>
 salary: int<br>

response: <br>
{'name': name,<br>
          'age': age,<br>
          'salary': salary,<br>
          'family': {'children': [['Alex', 24], ['Kate', 12]],<br>
                     'pets': {'cat':{'name':'Sunny',<br>
                                     'age': 3},<br>
                              'dog':{'name':'Luky',<br>
                                     'age': 4}},<br>
                     'u_salary_1_5_year': salary * 4}<br>
          }<br>

![5](/imgHW1Postman/5.png)<br>

--- 

### EP_6
Method: GET<br>
EndPoint: /object_info_4<br>
request url params: <br>
 name: str<br>
 age: int<br>
 salary: int<br>

response: <br>
{'name': name,<br>
          'age': int(age),<br>
          'salary': [salary, str(salary * 2), str(salary * 3)]<br>
          }<br>

![6](/imgHW1Postman/6.png)<br>

---

### EP_7
Method: POST<br>
EndPoint: /user_info_2<br>
request form data: <br>
 name: str<br>
 age: int<br>
 salary: int<br>

response: <br>
{'start_qa_salary': salary,<br>
          'qa_salary_after_6_months': salary * 2,<br>
          'qa_salary_after_12_months': salary * 2.7,<br>
          'qa_salary_after_1.5_year': salary * 3.3,<br>
          'qa_salary_after_3.5_years': salary * 3.8,<br>
          'person': {'u_name': [user_name, salary, age],<br>
                     'u_age': age,<br>
                     'u_salary_5_years': salary * 4.2}<br>
          }<br>
          
![7](/imgHW1Postman/7.png)<br>
