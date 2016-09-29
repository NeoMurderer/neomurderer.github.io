# Основные операции

### Математические операции
* +
* - 
* *
* /
* %

[Приоритет операторов](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)
```javascript
  var index = 0;
  index = index + 1;
  alert(index) // 1;
  
  var x,y;
  x = 5;
  y = 10;
  
  alert(x * (y /2)) // 25
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
### Операции со строками 
Работа оператора "+"
```javascript
  var name = "John";
  var secondName = "Snow";
  
  alert(name + secondName); // JohnSnow

```
Получение длинны строки
```javascript
  var name = "John"
  alert(name.length)
```

