## Домашняя работа Postman №1

Protocol: http
IP: 162.55.220.72
Port: 5005

EP_1
Method: GET
EndPoint: /get_method
request url params: 
 name: str
 age: int

response: 
[
    “Str”,
    “Str”
]
```
{
	"info": {
		"_postman_id": "6124136f-8146-4024-91aa-c0b175bebe49",
		"name": "HW_1",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "EP_1",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://162.55.220.72:5005/get_method?name=Dima&age=23",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"get_method"
					],
					"query": [
						{
							"key": "name",
							"value": "Dima"
						},
						{
							"key": "age",
							"value": "23"
						}
					]
				}
			},
			"response": []
		},
```
==================

EP_2
Method: POST
EndPoint: /user_info_3
request form data: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}}
```
{
			"name": "EP_2",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "Dima",
							"type": "text"
						},
						{
							"key": "age",
							"value": "23",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "1000",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/user_info_3",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"user_info_3"
					]
				}
			},
			"response": []
		},
```
==================

EP_3
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int

response: 
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}
```
{
			"name": "EP_3",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": ""
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_1?name=Dima&age=23&weight=1000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_1"
					],
					"query": [
						{
							"key": "name",
							"value": "Dima"
						},
						{
							"key": "age",
							"value": "23"
						},
						{
							"key": "weight",
							"value": "1000"
						}
					]
				}
			},
			"response": []
		},
```
==================

EP_4
Method: GET
EndPoint: /object_info_2
request url params: 
 name: str
 age: int
 salary: int

response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
```
{
			"name": "EP_4",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": []
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_2?name=Dima&age=23&salary=1000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_2"
					],
					"query": [
						{
							"key": "name",
							"value": "Dima"
						},
						{
							"key": "age",
							"value": "23"
						},
						{
							"key": "salary",
							"value": "1000"
						}
					]
				}
			},
			"response": []
		},
```
==================

EP_5
Method: GET
EndPoint: /object_info_3
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'pets': {'cat':{'name':'Sunny',
                                     'age': 3},
                              'dog':{'name':'Luky',
                                     'age': 4}},
                     'u_salary_1_5_year': salary * 4}
          }
```
{
			"name": "EP_5",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": []
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_3?name=Dima&age=23&salary=1000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_3"
					],
					"query": [
						{
							"key": "name",
							"value": "Dima"
						},
						{
							"key": "age",
							"value": "23"
						},
						{
							"key": "salary",
							"value": "1000"
						}
					]
				}
			},
			"response": []
		},
```
==================

EP_6
Method: GET
EndPoint: /object_info_4
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
          'age': int(age),
          'salary': [salary, str(salary * 2), str(salary * 3)]}
```
	{
			"name": "EP_6",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": []
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_4?name=Dima&age=23&salary=1000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_4"
					],
					"query": [
						{
							"key": "name",
							"value": "Dima"
						},
						{
							"key": "age",
							"value": "23"
						},
						{
							"key": "salary",
							"value": "1000"
						}
					]
				}
			},
			"response": []
		},
```
==================

EP_7
Method: POST
EndPoint: /user_info_2
request form data: 
 name: str
 age: int
 salary: int

response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
```
{
			"name": "EP_7",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "Dima",
							"type": "text"
						},
						{
							"key": "age",
							"value": "23",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "1000",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "http://162.55.220.72:5005/user_info_2",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"user_info_2"
					]
				}
			},
			"response": []
		}
	]
}
```
____
## Домашняя работа Postman №1.5

http://162.55.220.72:5005/first
1. Отправить запрос.
2. Статус код 200
3. Проверить, что в body приходит правильный string.
```
{
	"info": {
		"_postman_id": "60bbca83-7ea7-490d-8629-507f350d02d6",
		"name": "HW_1.5",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "first",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"let resp = cheerio.load(pm.response.text());\r",
							"console.log(resp);\r",
							"\r",
							"pm.test(\"Body is correct\", function () {\r",
							"    pm.response.to.have.body(\"This is the first responce from server!\");\r",
							"});\r",
							" pm.test(\"Body matches string\", function () {\r",
							"     pm.expect(pm.response.text()).to.include(\"This is the first responce from server!\");\r",
							" });"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "{{url}}first",
					"host": [
						"{{url}}first"
					]
				}
			},
			"response": []
		},
```
http://162.55.220.72:5005/user_info_3
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Проверить, что name в ответе равно name s request (name вбить руками.)
5. Проверить, что age в ответе равно age s request (age вбить руками.)
6. Проверить, что salary в ответе равно salary s request (salary вбить руками.)
7. Спарсить request.
8. Проверить, что name в ответе равно name s request (name забрать из request.)
9. Проверить, что age в ответе равно age s request (age забрать из request.)
10. Проверить, что salary в ответе равно salary s request (salary забрать из request.)
11. Вывести в консоль параметр family из response.
12. Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)
```
{
			"name": "user_info_3",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"let resp = pm.response.json();\r",
							"let req = request.data;\r",
							"\r",
							"pm.test(\"check data1\", function () {\r",
							"    pm.expect(resp.name).to.eql(request.data.name);\r",
							"    pm.expect(resp.age).to.eql(request.data.age);\r",
							"    pm.expect(resp.salary).to.eql(+request.data.salary);\r",
							"});\r",
							"\r",
							"pm.test(\"check dat2\", function () {\r",
							"    pm.expect(resp.name).to.eql(req.name);\r",
							"    pm.expect(resp.age).to.eql(req.age);\r",
							"    pm.expect(resp.salary).to.eql(+req.salary);\r",
							"});\r",
							"\r",
							"let family = resp.family\r",
							"console.log('family', family)\r",
							"\r",
							"pm.test(\"check u_salary_1_5_year\", function () {\r",
							"    pm.expect(resp.family.u_salary_1_5_year).to.eql(req.salary * 4);\r",
							"});"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "{{name}}",
							"type": "text"
						},
						{
							"key": "age",
							"value": "{{age}}",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "{{salary}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}user_info_3",
					"host": [
						"{{url}}user_info_3"
					]
				}
			},
			"response": []
		},
```
http://162.55.220.72:5005/object_info_3
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Спарсить request.
5. Проверить, что name в ответе равно name s request (name забрать из request.)
6. Проверить, что age в ответе равно age s request (age забрать из request.)
7. Проверить, что salary в ответе равно salary s request (salary забрать из request.)
8. Вывести в консоль параметр family из response.
9. Проверить, что у параметра dog есть параметры name.
10. Проверить, что у параметра dog есть параметры age.
11. Проверить, что параметр name имеет значение Luky.
12. Проверить, что параметр age имеет значение 4.
```
{
			"name": "object_info_3",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"let resp = pm.response.json();\r",
							"let req = request.data;\r",
							"\r",
							"pm.test(\"Check data\", function () {\r",
							"    pm.expect(pm.response.name).to.eql(req.name);\r",
							"    pm.expect(pm.response.age).to.eql(req.age);\r",
							"    pm.expect(pm.response.salary).to.eql(req.salary);\r",
							"});\r",
							"\r",
							"let family = resp.family\r",
							"console.log('family', family)\r",
							"\r",
							"pm.test(\"check data2\", function () {\r",
							"    pm.expect(resp.family.pets.dog).to.have.property('name');\r",
							"    pm.expect(resp.family.pets.dog).to.have.property('age');\r",
							"    pm.expect(resp.family.pets.dog.name).to.eql ('Luky');\r",
							"    pm.expect(resp.family.pets.dog.age).to.eql (4);\r",
							"});\r",
							""
						],
						"type": "text/javascript"
					}
				}
			],
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": []
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_3?name={{name}}&age={{age}}&salary={{salary}}",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_3"
					],
					"query": [
						{
							"key": "name",
							"value": "{{name}}"
						},
						{
							"key": "age",
							"value": "{{age}}"
						},
						{
							"key": "salary",
							"value": "{{salary}}"
						}
					]
				}
			},
			"response": []
		},
```
http://162.55.220.72:5005/object_info_4
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Спарсить request.
5. Проверить, что name в ответе равно name s request (name забрать из request.)
6. Проверить, что age в ответе равно age из request (age забрать из request.)
7. Вывести в консоль параметр salary из request.
8. Вывести в консоль параметр salary из response.
9. Вывести в консоль 0-й элемент параметра salary из response.
10. Вывести в консоль 1-й элемент параметра salary параметр salary из response.
11. Вывести в консоль 2-й элемент параметра salary параметр salary из response.
12. Проверить, что 0-й элемент параметра salary равен salary из request (salary забрать из request.)
13. Проверить, что 1-й элемент параметра salary равен salary*2 из request (salary забрать из request.)
14. Проверить, что 2-й элемент параметра salary равен salary*3 из request (salary забрать из request.)
15. Создать в окружении переменную name
16. Создать в окружении переменную age
17. Создать в окружении переменную salary
18. Передать в окружение переменную name
19. Передать в окружение переменную age
20. Передать в окружение переменную salary
21. Написать цикл который выведет в консоль по порядку элементы списка из параметра salary.
```
{
			"name": "object_info_4",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"let resp = pm.response.json();\r",
							"let req = pm.request.url.query.toObject()\r",
							"console.log('req', req)\r",
							"\r",
							"pm.test(\"check data\", function () {\r",
							"    pm.expect(resp.name).to.eql(req.name);\r",
							"    pm.expect(resp.age).to.eql(+req.age);\r",
							"});\r",
							"\r",
							"console.log(\"========\", resp.name)\r",
							"console.log(\"========\", req.name)\r",
							"\r",
							"let req_salary = req.salary;\r",
							"let resp_salary = resp.salary;\r",
							"\r",
							"console.log('req_salary', req_salary);\r",
							"console.log('resp_salary', resp_salary);\r",
							"console.log('salary [0]', resp.salary[0]);\r",
							"console.log('salary [1]', resp.salary[1]);\r",
							"console.log('salary [2]', resp.salary[2]);\r",
							"\r",
							"let salary0 = resp.salary[0];\r",
							"let salary1 = resp.salary[1];\r",
							"let salary2 = resp.salary[2];\r",
							"\r",
							"pm.test(\"check data_salary\", function () {\r",
							"    pm.expect(salary0).to.eql(+req_salary);\r",
							"    pm.expect(+salary1).to.eql(+req_salary*2);\r",
							"    pm.expect(+salary2).to.eql(+req_salary*3);\r",
							"});\r",
							"\r",
							"pm.environment.set(\"name\", resp.name);\r",
							"pm.environment.set(\"age\", resp.age);\r",
							"pm.environment.set(\"salary\", resp.salary[0]);\r",
							"\r",
							"for (let i in resp.salary) {\r",
							"    console.log(resp.salary[i])\r",
							"}\r",
							"console.log(resp.salary)"
						],
						"type": "text/javascript"
					}
				}
			],
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": []
				},
				"url": {
					"raw": "http://162.55.220.72:5005/object_info_4?name=Dima&age=23&salary=1000",
					"protocol": "http",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_4"
					],
					"query": [
						{
							"key": "name",
							"value": "Dima"
						},
						{
							"key": "age",
							"value": "23"
						},
						{
							"key": "salary",
							"value": "1000"
						}
					]
				}
			},
			"response": []
		},
```
http://162.55.220.72:5005/user_info_2
1. Вставить параметр salary из окружения в request
2. Вставить параметр salary из окружения в age
3. Вставить параметр salary из окружения в name
4. Отправить запрос.
5. Статус код 200
6. Спарсить response body в json.
7. Спарсить request.
8. Проверить, что json response имеет параметр start_qa_salary
9. Проверить, что json response имеет параметр qa_salary_after_6_months
10. Проверить, что json response имеет параметр qa_salary_after_12_months
11. Проверить, что json response имеет параметр qa_salary_after_1.5_year
12. Проверить, что json response имеет параметр qa_salary_after_3.5_years
13. Проверить, что json response имеет параметр person
14. Проверить, что параметр start_qa_salary равен salary из request (salary забрать из request.)
15. Проверить, что параметр qa_salary_after_6_months равен salary*2 из request (salary забрать из request.)
16. Проверить, что параметр qa_salary_after_12_months равен salary*2.7 из request (salary забрать из request.)
17. Проверить, что параметр qa_salary_after_1.5_year равен salary*3.3 из request (salary забрать из request.)
18. Проверить, что параметр qa_salary_after_3.5_years равен salary*3.8 из request (salary забрать из request.)
19. Проверить, что в параметре person, 1-й элемент из u_name равен salary из request (salary забрать из request.)
20. Проверить, что что параметр u_age равен age из request (age забрать из request.)
21. Проверить, что параметр u_salary_5_years равен salary*4.2 из request (salary забрать из request.)
22. Написать цикл который выведет в консоль по порядку элементы списка из параметра person.
```
{
			"name": "user_info_2",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"let resp = pm.response.json();\r",
							"let req = request.data;\r",
							"console.log(req)\r",
							"\r",
							"pm.test(\"response_ok\", function () {\r",
							" pm.expect(resp).to.have.property('start_qa_salary');\r",
							" pm.expect(resp).to.have.property('qa_salary_after_6_months');\r",
							" pm.expect(resp).to.have.property('qa_salary_after_12_months');\r",
							" pm.expect(resp).to.have.property('qa_salary_after_1.5_year');\r",
							" pm.expect(resp).to.have.property('qa_salary_after_3.5_years');\r",
							" pm.expect(resp).to.have.property('person');\r",
							"});\r",
							"\r",
							"pm.test(\"qa_salary\", function () {\r",
							"    pm.expect(resp.start_qa_salary).to.eql(+req.salary);\r",
							"    pm.expect(resp.qa_salary_after_6_months).to.eql(req.salary * 2);\r",
							"    pm.expect(resp.qa_salary_after_12_months).to.eql(req.salary * 2.7);\r",
							"    pm.expect(resp['qa_salary_after_1.5_year']).to.eql(req.salary * 3.3);\r",
							"    pm.expect(resp['qa_salary_after_3.5_years']).to.eql(req.salary * 3.8);\r",
							"});\r",
							"\r",
							"let person = resp.person\r",
							"console.log('person', person)\r",
							"pm.test(\"Check\", function () {\r",
							"    pm.expect(person.u_name[1]).to.eql(+req.salary);\r",
							"    pm.expect(person.u_age).to.eql(+req.age);\r",
							"    pm.expect(person.u_salary_5_years).to.eql(+req.salary * 4.2)\r",
							"});\r",
							"\r",
							"for (let i in resp.person) {\r",
							"    console.log(resp.person[i])\r",
							"}"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "{{name}}",
							"type": "text"
						},
						{
							"key": "age",
							"value": "{{age}}",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "{{salary}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}user_info_2",
					"host": [
						"{{url}}user_info_2"
					]
				}
			},
			"response": []
		}
	],
	"event": [
		{
			"listen": "prerequest",
			"script": {
				"type": "text/javascript",
				"exec": [
					""
				]
			}
		},
		{
			"listen": "test",
			"script": {
				"type": "text/javascript",
				"exec": [
					"pm.test(\"Status code is 200\", function () {",
					"    pm.response.to.have.status(200);",
					"});"
				]
			}
		}
	],
	"variable": [
		{
			"key": "name",
			"value": "Dima"
		},
		{
			"key": "age",
			"value": "23"
		},
		{
			"key": "salary",
			"value": "1000"
		}
	]
}
```
____
## Домашняя работа Postman №2

1) необходимо залогиниться
POST
http://162.55.220.72:5005/login
login : str (кроме /)
password : str

Приходящий токен необходимо передать во все остальные запросы.

===================
дальше все запросы требуют наличие токена.
===================
```
{
	"info": {
		"_postman_id": "41da8915-3dee-4d70-a839-2e532b3037be",
		"name": "HW_2",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "1 login",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"var jsonData = pm.response. json();\r",
							"pm.environment.set(\"token\", jsonData.token);"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "login",
							"value": "Dima",
							"type": "text"
						},
						{
							"key": "password",
							"value": "1705",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}login",
					"host": [
						"{{url}}login"
					]
				}
			},
			"response": []
		},
```
2) http://162.55.220.72:5005/user_info
req. (RAW JSON)
POST
age: int
salary: int
name: str
auth_token

resp.
{'start_qa_salary':salary,
 'qa_salary_after_6_months': salary * 2,
 'qa_salary_after_12_months': salary * 2.9,
 'person': {'u_name':[user_name, salary, age],
                                'u_age':age,
                                'u_salary_1.5_year': salary * 4}
                                }

Тесты:
1) Статус код 200
2) Проверка структуры json в ответе.
3) В ответе указаны коэффициенты умножения salary, напишите тесты по проверке правильности результата перемножения на коэффициент.
4) Достать значение из поля 'u_salary_1.5_year' и передать в поле salary запроса http://162.55.220.72:5005/get_test_user
```
{
			"name": "2 user_info",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"pm.test(\"Json-schema is ok\", function() {const schema = {\r",
							"    \"type\": \"object\",\r",
							"    \"properties\": {\r",
							"    \"person\": {\r",
							"        \"type\": \"object\",\r",
							"        \"properties\": {\r",
							"            \"u_age\": {\r",
							"                \"type\": \"integer\"\r",
							"            },\r",
							"            \"u_name\": {\r",
							"                \"type\": \"array\",\r",
							"                \"items\": [\r",
							"                    {\r",
							"                        \"type\": \"string\"\r",
							"                    },\r",
							"                    {\r",
							"                        \"type\": \"integer\"\r",
							"                    },\r",
							"                    {\r",
							"                        \"type\": \"integer\"\r",
							"                    }\r",
							"                ]\r",
							"            },\r",
							"            \"u_salary_1_5_year\": {\r",
							"                \"type\": \"integer\"\r",
							"            }\r",
							"          },\r",
							"          \"required\": [\r",
							"            \"u_age\",\r",
							"            \"u_name\",\r",
							"            \"u_salary_1_5_year\"\r",
							"          ]\r",
							"    },\r",
							"    \"qa_salary_after_12_months\": {\r",
							"        \"type\": \"number\"\r",
							"    },\r",
							"    \"qa_salary_after_6_months\": {\r",
							"        \"type\": \"integer\"\r",
							"    },\r",
							"    \"start_qa_salary\": {\r",
							"        \"type\": \"integer\"\r",
							"    }\r",
							"  },\r",
							"  \"required\": [\r",
							"    \"person\",\r",
							"    \"qa_salary_after_12_months\",\r",
							"    \"qa_salary_after_6_months\",\r",
							"    \"start_qa_salary\"\r",
							"  ]\r",
							"    }\r",
							"pm.response.to.have.jsonSchema(schema) \r",
							"});\r",
							"\r",
							"let req = JSON.parse(request.data);\r",
							"let resp = pm.response.json();\r",
							"let salary = req.salary;\r",
							"let resp_salary = resp.start_qa_salary;\r",
							"let resp_salary6 = resp.qa_salary_after_6_months;\r",
							"let resp_salary12 = resp.qa_salary_after_12_months;\r",
							"console.log(resp_salary);\r",
							"console.log(salary);\r",
							"\r",
							"pm.test(\"coefficient\", function () {\r",
							"    pm.expect(resp_salary).to.eql(req.salary);\r",
							"    pm.expect(resp_salary6).to.eql(req.salary*2)\r",
							"    pm.expect(resp_salary12).to.eql(req.salary*2.9)\r",
							"})\r",
							"\r",
							"let u_salary_1_5_year = resp.person.u_salary_1_5_year;\r",
							"console.log('u_salary_1_5_year', u_salary_1_5_year)\r",
							"pm.environment.set(\"salary\", u_salary_1_5_year);\r",
							"\r",
							""
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\"age\": 23,\"name\": \"Dima\",\"salary\": 1000,\"auth_token\": \"{{token}}\"}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "{{url}}user_info",
					"host": [
						"{{url}}user_info"
					]
				}
			},
			"response": []
		},
```
===================

3) http://162.55.220.72:5005/new_data
req.
POST
age: int
salary: int
name: str
auth_token

Resp.
{'name':name,
  'age': int(age),
  'salary': [salary, str(salary*2), str(salary*3)]}

Тесты:
1) Статус код 200
2) Проверка структуры json в ответе.
3) В ответе указаны коэффициенты умножения salary, напишите тесты по проверке правильности результата перемножения на коэффициент.
4) проверить, что 2-й элемент массива salary больше 1-го и 0-го
```
{
			"name": "3 new_data",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"let resp = pm.response.json();\r",
							"let req = request.data;\r",
							"let resp_salary = resp.salary;\r",
							"console.log('resp_salary', resp_salary)\r",
							"\r",
							"pm.test(\"coefficient\", function () {\r",
							"    pm.expect(resp_salary[0]).to.eql(+req.salary);\r",
							"    pm.expect(+resp_salary[1]).to.eql(req.salary*2);\r",
							"    pm.expect(+resp_salary[2]).to.eql(req.salary*3);\r",
							"});\r",
							"\r",
							"let resp_salary0 = resp_salary[0];\r",
							"let resp_salary1 = resp_salary[1];\r",
							"let resp_salary2 = resp_salary[2];\r",
							"\r",
							"pm.test('check', function () {\r",
							"    pm.expect(resp_salary1>resp_salary0).to.be.true;\r",
							"    pm.expect(resp_salary1<resp_salary2).to.be.true;\r",
							"});"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "age",
							"value": "23",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "1000",
							"type": "text"
						},
						{
							"key": "name",
							"value": "Dima",
							"type": "text"
						},
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}new_data",
					"host": [
						"{{url}}new_data"
					]
				}
			},
			"response": []
		},
```
===================

4) http://162.55.220.72:5005/test_pet_info
req.
POST
age: int
weight: int
name: str
auth_token

Resp.
{'name': name,
 'age': age,
 'daily_food':weight * 0.012,
 'daily_sleep': weight * 2.5}

Тесты:
1) Статус код 200
2) Проверка структуры json в ответе.
3) В ответе указаны коэффициенты умножения weight, напишите тесты по проверке правильности результата перемножения на коэффициент.
```
{
			"name": "4 test_pet_info",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"pm.test(\"Json-schema is ok\", function() {const schema = {\r",
							"  \"type\": \"object\",\r",
							"  \"properties\": {\r",
							"    \"age\": {\r",
							"      \"type\": \"integer\"\r",
							"    },\r",
							"    \"daily_food\": {\r",
							"      \"type\": \"number\"\r",
							"    },\r",
							"    \"daily_sleep\": {\r",
							"      \"type\": \"number\"\r",
							"    },\r",
							"    \"name\": {\r",
							"      \"type\": \"string\"\r",
							"    }\r",
							"  },\r",
							"  \"required\": [\r",
							"    \"age\",\r",
							"    \"daily_food\",\r",
							"    \"daily_sleep\",\r",
							"    \"name\"\r",
							"  ]\r",
							"}\r",
							"pm.response.to.have.jsonSchema(schema) \r",
							"});\r",
							"\r",
							"let resp = pm.response.json();\r",
							"let req = request.data;\r",
							"let weight = req.weight;\r",
							"let daily_food = weight * 0.012;\r",
							"let daily_sleep = weight * 2.5;\r",
							"console.log('daily_food', daily_food)\r",
							"console.log('daily_sleep', daily_sleep)\r",
							"console.log('weight', weight)\r",
							"\r",
							"pm.test(\"check weight\", function () {\r",
							"    pm.expect(daily_food).to.eql(weight*0.012);\r",
							"    pm.expect(daily_sleep).to.eql(weight*2.5);\r",
							"});"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "age",
							"value": "23",
							"type": "text"
						},
						{
							"key": "weight",
							"value": "72",
							"type": "text"
						},
						{
							"key": "name",
							"value": "Dima",
							"type": "text"
						},
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}test_pet_info",
					"host": [
						"{{url}}test_pet_info"
					]
				}
			},
			"response": []
		},
```
===================

5) http://162.55.220.72:5005/get_test_user
req.
POST
age: int
salary: int
name: str
auth_token

Resp.
{'name': name,
 'age':age,
 'salary': salary,
 'family':{'children':[['Alex', 24],['Kate', 12]],
 'u_salary_1.5_year': salary * 4}
  }

Тесты:
1) Статус код 200
2) Проверка структуры json в ответе.
3) Проверить что занчение поля name = значению переменной name из окружения
4) Проверить что занчение поля age в ответе соответсвует отправленному в запросе значению поля age
```
{
			"name": "5 get_test_user",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"pm.test(\"Json-schema is ok\", function() {const schema = {\r",
							"  \"type\": \"object\",\r",
							"  \"properties\": {\r",
							"    \"age\": {\r",
							"      \"type\": \"string\"\r",
							"    },\r",
							"    \"family\": {\r",
							"      \"type\": \"object\",\r",
							"      \"properties\": {\r",
							"        \"children\": {\r",
							"          \"type\": \"array\",\r",
							"          \"items\": [\r",
							"            {\r",
							"              \"type\": \"array\",\r",
							"              \"items\": [\r",
							"                {\r",
							"                  \"type\": \"string\"\r",
							"                },\r",
							"                {\r",
							"                  \"type\": \"integer\"\r",
							"                }\r",
							"              ]\r",
							"            },\r",
							"            {\r",
							"              \"type\": \"array\",\r",
							"              \"items\": [\r",
							"                {\r",
							"                  \"type\": \"string\"\r",
							"                },\r",
							"                {\r",
							"                  \"type\": \"integer\"\r",
							"                }\r",
							"              ]\r",
							"            }\r",
							"          ]\r",
							"        },\r",
							"        \"u_salary_1_5_year\": {\r",
							"          \"type\": \"integer\"\r",
							"        }\r",
							"      },\r",
							"      \"required\": [\r",
							"        \"children\",\r",
							"        \"u_salary_1_5_year\"\r",
							"      ]\r",
							"    },\r",
							"    \"name\": {\r",
							"      \"type\": \"string\"\r",
							"    },\r",
							"    \"salary\": {\r",
							"      \"type\": \"integer\"\r",
							"    }\r",
							"  },\r",
							"  \"required\": [\r",
							"    \"age\",\r",
							"    \"family\",\r",
							"    \"name\",\r",
							"    \"salary\"\r",
							"  ]\r",
							"}\r",
							"pm.response.to.have.jsonSchema(schema) \r",
							"});\r",
							"\r",
							"let resp = pm.response.json();\r",
							"let req = request.data;\r",
							"\r",
							"pm.test(\"check\", function () {\r",
							"    pm.expect(resp.name).to.eql(pm.environment.get(\"name\"));\r",
							"    pm.expect(resp.age).to.eql(req.age);\r",
							"    pm.expect(resp.age).to.be.an(\"string\");\r",
							"});"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "age",
							"value": "23",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "{{salary}}",
							"type": "text"
						},
						{
							"key": "name",
							"value": "Dima",
							"type": "text"
						},
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}get_test_user",
					"host": [
						"{{url}}get_test_user"
					]
				}
			},
			"response": []
		},
```
===================

6) http://162.55.220.72:5005/currency
req.
POST
auth_token

Resp. Передаётся список массив объектов.
[
{"Cur_Abbreviation": str,
 "Cur_ID": int,
 "Cur_Name": str
}
…
{"Cur_Abbreviation": str,
 "Cur_ID": int,
 "Cur_Name": str
}
]

Тесты:
1) Можете взять любой объект из присланного списка, используйте js random.
В объекте возьмите Cur_ID и передать через окружение в следующий запрос.
```
{
			"name": "6 currency",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"const jsonData = pm.response.json();\r",
							"\r",
							"let x = jsonData.length\r",
							"console.log('Количество массивов в ответе x = ', x)\r",
							"\r",
							"function getRandomInt(x) {\r",
							"    return Math.floor(Math.random() * x );\r",
							"};\r",
							"console.log('рандомное число = ', getRandomInt(x) )\r",
							"\r",
							"console.log('Наш массив = ', massive = jsonData[getRandomInt(x)])\r",
							"\r",
							"console.log('Cur_ID массива = ', massive.Cur_ID)\r",
							"\r",
							"pm.environment.set(\"curr_code\", massive.Cur_ID );"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}currency",
					"host": [
						"{{url}}currency"
					]
				}
			},
			"response": []
		},
```
 ===================

7) http://162.55.220.72:5005/curr_byn
req.
POST
auth_token
curr_code: int

Resp.
{
    "Cur_Abbreviation": str
    "Cur_ID": int,
    "Cur_Name": str,
    "Cur_OfficialRate": float,
    "Cur_Scale": int,
    "Date": str
}

Тесты:
1) Статус код 200
2) Проверка структуры json в ответе.
```
{
			"name": "7 curr_byn",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"pm.test(\"Json-schema is ok\", function() {const schema = {\r",
							"  \"type\": \"object\",\r",
							"  \"properties\": {\r",
							"    \"Cur_Abbreviation\": {\r",
							"      \"type\": \"string\"\r",
							"    },\r",
							"    \"Cur_ID\": {\r",
							"      \"type\": \"integer\"\r",
							"    },\r",
							"    \"Cur_Name\": {\r",
							"      \"type\": \"string\"\r",
							"    },\r",
							"    \"Cur_OfficialRate\": {\r",
							"      \"type\": \"number\"\r",
							"    },\r",
							"    \"Cur_Scale\": {\r",
							"      \"type\": \"integer\"\r",
							"    },\r",
							"    \"Date\": {\r",
							"      \"type\": \"string\"\r",
							"    }\r",
							"  },\r",
							"  \"required\": [\r",
							"    \"Cur_Abbreviation\",\r",
							"    \"Cur_ID\",\r",
							"    \"Cur_Name\",\r",
							"    \"Cur_OfficialRate\",\r",
							"    \"Cur_Scale\",\r",
							"    \"Date\"\r",
							"  ]\r",
							"}\r",
							"pm.response.to.have.jsonSchema(schema) \r",
							"});"
						],
						"type": "text/javascript"
					}
				}
			],
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "auth_token",
							"value": "{{token}}",
							"type": "text"
						},
						{
							"key": "curr_code",
							"value": "{{curr_code}}",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "{{url}}curr_byn",
					"host": [
						"{{url}}curr_byn"
					]
				}
			},
			"response": []
		}
	],
	"event": [
		{
			"listen": "prerequest",
			"script": {
				"type": "text/javascript",
				"exec": [
					""
				]
			}
		},
		{
			"listen": "test",
			"script": {
				"type": "text/javascript",
				"exec": [
					"pm.test(\"Status code is 200\", function () {",
					"    pm.response.to.have.status(200);",
					"});"
				]
			}
		}
	]
}
```
===============
