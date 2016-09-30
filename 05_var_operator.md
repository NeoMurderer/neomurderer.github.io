# Основные операции
Для работы с переменными JavaScript поддерживает все стандартные операторы(например обычные сложение +, умножение *, вычитание - и другие)
### Математические операции

```javascript
  var index = 0;
  index = index + 1;
  
  alert(index) // 1;
  
  var x, y;
  x = 5;
  y = 10;
  
  alert(x * y)) // 50
```
### Инкремент/декремент: ++, --

```javascript
  /* Инкремент */
  var i = 2;
  i++;
  alert(i); // 3;
  
  /* Декремент */
  
  var coins = 5;
  
  coins--;
  
  alert(coins); // 4
```

Префиксная форма
```javascript
  var i = 3;
  alert(i++); // 3
  
  alert(i) // 4
  
  var coins = 10;
  
  alert(++coins); // 11
```
Сокращенная запись
```javascript
  var x = 9;
  
  x*=5; // equal x = x * 5;
  alert(x); // 45
```
### Логический оператор !(НЕ)
```javascript
  var result = 2 > 1;
  
  alert(!result); // false
```
* Если оператор применяется к неопределенному значению или выражению null, возникает ошибка времени выполнения.
* Объекты преобразуются в строки.
* Строки преобразуются в числа, если это возможно.Если это невозможно, возникает ошибка времени выполнения.
* Логические значения интерпретируются как числа (0 для false, 1 для true).
### Логический оператор &&(И) ||(или)
```javascript
  var result = expression1 && expression2 
  
  var result = expression1 || expression2 
```

### Операции со строками 
Работа оператора "+"
```javascript
  var name = "John";
  var secondName = "Snow";
  
  alert(name + secondName); // JohnSnow
  
  var age = 20;
  alert("Мне уже " + age + " лет"); // Если хоть один аргумент является строкой - остальные преобразуются в String
```
### Преобразование к числу
```javascript
  alert('6' / 2); // 3
  
  var a = '4';
  var b = '10';
  
  var x = +a;
  var y = +b;
  
  alert(x+y); // 14
  
  //or
  
  alert(+a + +b); // 14
```

[Приоритет операторов](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)
[JavaScript Operators](https://msdn.microsoft.com/en-us/library/ce57k8d5(v=vs.94).aspx)
