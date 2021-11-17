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
let resp = cheerio.load(pm.response.text());
console.log(resp);

pm.test("Body is correct", function () {
    pm.response.to.have.body("This is the first responce from server!");
});
 pm.test("Body matches string", function () {
     pm.expect(pm.response.text()).to.include("This is the first responce from server!");
 });
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
let resp = pm.response.json();
let req = request.data;

pm.test("check data1", function () {
    pm.expect(resp.name).to.eql(request.data.name);
    pm.expect(resp.age).to.eql(request.data.age);
    pm.expect(resp.salary).to.eql(+request.data.salary);
});

pm.test("check dat2", function () {
    pm.expect(resp.name).to.eql(req.name);
    pm.expect(resp.age).to.eql(req.age);
    pm.expect(resp.salary).to.eql(+req.salary);
});

let family = resp.family
console.log('family', family)

pm.test("check u_salary_1_5_year", function () {
    pm.expect(resp.family.u_salary_1_5_year).to.eql(req.salary * 4);
});
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
let resp = pm.response.json();
let req = request.data;

pm.test("Check data", function () {
    pm.expect(pm.response.name).to.eql(req.name);
    pm.expect(pm.response.age).to.eql(req.age);
    pm.expect(pm.response.salary).to.eql(req.salary);
});

let family = resp.family
console.log('family', family)

pm.test("check data2", function () {
    pm.expect(resp.family.pets.dog).to.have.property('name');
    pm.expect(resp.family.pets.dog).to.have.property('age');
    pm.expect(resp.family.pets.dog.name).to.eql ('Luky');
    pm.expect(resp.family.pets.dog.age).to.eql (4);
});

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
let resp = pm.response.json();
let req = pm.request.url.query.toObject()
console.log('req', req)

pm.test("check data", function () {
    pm.expect(resp.name).to.eql(req.name);
    pm.expect(resp.age).to.eql(+req.age);
});

console.log("========", resp.name)
console.log("========", req.name)

let req_salary = req.salary;
let resp_salary = resp.salary;

console.log('req_salary', req_salary);
console.log('resp_salary', resp_salary);
console.log('salary [0]', resp.salary[0]);
console.log('salary [1]', resp.salary[1]);
console.log('salary [2]', resp.salary[2]);

let salary0 = resp.salary[0];
let salary1 = resp.salary[1];
let salary2 = resp.salary[2];

pm.test("check data_salary", function () {
    pm.expect(salary0).to.eql(+req_salary);
    pm.expect(+salary1).to.eql(+req_salary*2);
    pm.expect(+salary2).to.eql(+req_salary*3);
});

pm.environment.set("name", resp.name);
pm.environment.set("age", resp.age);
pm.environment.set("salary", resp.salary[0]);

for (let i in resp.salary) {
    console.log(resp.salary[i])
}
console.log(resp.salary)
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
let resp = pm.response.json();
let req = request.data;
console.log(req)

pm.test("response_ok", function () {
 pm.expect(resp).to.have.property('start_qa_salary');
 pm.expect(resp).to.have.property('qa_salary_after_6_months');
 pm.expect(resp).to.have.property('qa_salary_after_12_months');
 pm.expect(resp).to.have.property('qa_salary_after_1.5_year');
 pm.expect(resp).to.have.property('qa_salary_after_3.5_years');
 pm.expect(resp).to.have.property('person');
});

pm.test("qa_salary", function () {
    pm.expect(resp.start_qa_salary).to.eql(+req.salary);
    pm.expect(resp.qa_salary_after_6_months).to.eql(req.salary * 2);
    pm.expect(resp.qa_salary_after_12_months).to.eql(req.salary * 2.7);
    pm.expect(resp['qa_salary_after_1.5_year']).to.eql(req.salary * 3.3);
    pm.expect(resp['qa_salary_after_3.5_years']).to.eql(req.salary * 3.8);
});

let person = resp.person
console.log('person', person)
pm.test("Check", function () {
    pm.expect(person.u_name[1]).to.eql(+req.salary);
    pm.expect(person.u_age).to.eql(+req.age);
    pm.expect(person.u_salary_5_years).to.eql(+req.salary * 4.2)
});

for (let i in resp.person) {
    console.log(resp.person[i])
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
Дальше все запросы требуют наличие токена.
```
var jsonData = pm.response. json();
pm.environment.set("token", jsonData.token);
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
pm.test("Json-schema is ok", function() {const schema = {
    "type": "object",
    "properties": {
    "person": {
        "type": "object",
        "properties": {
            "u_age": {
                "type": "integer"
            },
            "u_name": {
                "type": "array",
                "items": [
                    {
                        "type": "string"
                    },
                    {
                        "type": "integer"
                    },
                    {
                        "type": "integer"
                    }
                ]
            },
            "u_salary_1_5_year": {
                "type": "integer"
            }
          },
          "required": [
            "u_age",
            "u_name",
            "u_salary_1_5_year"
          ]
    },
    "qa_salary_after_12_months": {
        "type": "number"
    },
    "qa_salary_after_6_months": {
        "type": "integer"
    },
    "start_qa_salary": {
        "type": "integer"
    }
  },
  "required": [
    "person",
    "qa_salary_after_12_months",
    "qa_salary_after_6_months",
    "start_qa_salary"
  ]
    }
pm.response.to.have.jsonSchema(schema) 
});

let req = JSON.parse(request.data);
let resp = pm.response.json();
let salary = req.salary;
let resp_salary = resp.start_qa_salary;
let resp_salary6 = resp.qa_salary_after_6_months;
let resp_salary12 = resp.qa_salary_after_12_months;
console.log(resp_salary);
console.log(salary);

pm.test("coefficient", function () {
    pm.expect(resp_salary).to.eql(req.salary);
    pm.expect(resp_salary6).to.eql(req.salary*2)
    pm.expect(resp_salary12).to.eql(req.salary*2.9)
})

let u_salary_1_5_year = resp.person.u_salary_1_5_year;
console.log('u_salary_1_5_year', u_salary_1_5_year)
pm.environment.set("salary", u_salary_1_5_year);


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
let resp = pm.response.json();
let req = request.data;
let resp_salary = resp.salary;
console.log('resp_salary', resp_salary)

pm.test("coefficient", function () {
    pm.expect(resp_salary[0]).to.eql(+req.salary);
    pm.expect(+resp_salary[1]).to.eql(req.salary*2);
    pm.expect(+resp_salary[2]).to.eql(req.salary*3);
});

let resp_salary0 = resp_salary[0];
let resp_salary1 = resp_salary[1];
let resp_salary2 = resp_salary[2];

pm.test('check', function () {
    pm.expect(resp_salary1>resp_salary0).to.be.true;
    pm.expect(resp_salary1<resp_salary2).to.be.true;
});
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
pm.test("Json-schema is ok", function() {const schema = {
  "type": "object",
  "properties": {
    "age": {
      "type": "integer"
    },
    "daily_food": {
      "type": "number"
    },
    "daily_sleep": {
      "type": "number"
    },
    "name": {
      "type": "string"
    }
  },
  "required": [
    "age",
    "daily_food",
    "daily_sleep",
    "name"
  ]
}
pm.response.to.have.jsonSchema(schema) 
});

let resp = pm.response.json();
let req = request.data;
let weight = req.weight;
let daily_food = weight * 0.012;
let daily_sleep = weight * 2.5;
console.log('daily_food', daily_food)
console.log('daily_sleep', daily_sleep)
console.log('weight', weight)

pm.test("check weight", function () {
    pm.expect(daily_food).to.eql(weight*0.012);
    pm.expect(daily_sleep).to.eql(weight*2.5);
});
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
pm.test("Json-schema is ok", function() {const schema = {
  "type": "object",
  "properties": {
    "age": {
      "type": "string"
    },
    "family": {
      "type": "object",
      "properties": {
        "children": {
          "type": "array",
          "items": [
            {
              "type": "array",
              "items": [
                {
                  "type": "string"
                },
                {
                  "type": "integer"
                }
              ]
            },
            {
              "type": "array",
              "items": [
                {
                  "type": "string"
                },
                {
                  "type": "integer"
                }
              ]
            }
          ]
        },
        "u_salary_1_5_year": {
          "type": "integer"
        }
      },
      "required": [
        "children",
        "u_salary_1_5_year"
      ]
    },
    "name": {
      "type": "string"
    },
    "salary": {
      "type": "integer"
    }
  },
  "required": [
    "age",
    "family",
    "name",
    "salary"
  ]
}
pm.response.to.have.jsonSchema(schema) 
});

let resp = pm.response.json();
let req = request.data;

pm.test("check", function () {
    pm.expect(resp.name).to.eql(pm.environment.get("name"));
    pm.expect(resp.age).to.eql(req.age);
    pm.expect(resp.age).to.be.an("string");
});
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
const jsonData = pm.response.json();

let x = jsonData.length
console.log('Количество массивов в ответе x = ', x)

function getRandomInt(x) {
    return Math.floor(Math.random() * x );
};
console.log('рандомное число = ', getRandomInt(x) )

console.log('Наш массив = ', massive = jsonData[getRandomInt(x)])

console.log('Cur_ID массива = ', massive.Cur_ID)

pm.environment.set("curr_code", massive.Cur_ID );
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
pm.test("Json-schema is ok", function() {const schema = {
  "type": "object",
  "properties": {
    "Cur_Abbreviation": {
      "type": "string"
    },
    "Cur_ID": {
      "type": "integer"
    },
    "Cur_Name": {
      "type": "string"
    },
    "Cur_OfficialRate": {
      "type": "number"
    },
    "Cur_Scale": {
      "type": "integer"
    },
    "Date": {
      "type": "string"
    }
  },
  "required": [
    "Cur_Abbreviation",
    "Cur_ID",
    "Cur_Name",
    "Cur_OfficialRate",
    "Cur_Scale",
    "Date"
  ]
}
pm.response.to.have.jsonSchema(schema) 
});
```
