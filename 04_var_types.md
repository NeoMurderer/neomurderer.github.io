# Типы переменных - 6 типов данных

### Number
Используется как для целых, так и для дробных чисел
```javascript

var number = 1;
number = 3.14;

```
### String
```javascript
var str = "John";
str = 'Можно писать предложения и использовать одинарные кавычки';
```
### Boolean
Используется для хранения значения типа да/нет
```javascript
// Boolean
var isLogged = true;
isLogged = false;
```
### Null
Это специальное значение, которое имеет смысл «ничего» или «значение неизвестно».
```javascript
var age = null;
```

### Undefined
Имеет смысл «значение не присвоено».
Если переменная объявлена, но в неё ничего не записано, то её значение как раз и есть undefined:
```javascript
var person;
alert(person); // undefined
// or
person  = undefined;
```
### Object
Используется для коллекций данных и для объявления более сложных сущностей
```javascript
var person = {
	firstName: 'John',
	secondName: 'Martin'
};
```

### Оператор typeof
Оператор typeof возвращает тип аргумента
```javascript

typeof 1.53 // "number"

typeof "John" // "string"

typeof true // "boolean"

typeof null // "object"

typeof undefined // "undefined"

typeof {} // "object"
```
# Итого

Есть 5 «примитивных» типов: number, string, boolean, null, undefined и 6-й тип – object.
