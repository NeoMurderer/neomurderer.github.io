# Операторы сравнения
* ==
* !=
* >
* >=
* <
* <=
* ===

## Логические значения
Как и другие операторы(например typeof), сравнение возвращает значение. Это значение имеет логический тип.
Существует всего два логических значения:
* false - нет, ложь
* true - да, истина
### Пример работы
```javascript
  alert(2 > 1); // true
  
  alert(2 != 1); // true
  
  alert(5 == 10); // false
  
```
### Также можно присваивать результат переменной
```javascript
  var a = false;
  
  var b = 5 > 6; 
  alert(b); // true
  
  alert(a == b); // false
  
```
### Сравнение строк происходит побуквенно
```javascript
  alert('б' > 'а'); //  true
  
  alert('a' == 'A'); // false
  
  alert('aaa' > 'b'); //false
  
  alert('2' > '14'); // true - сравниваются строки
```
###
Стоит запомнить что любая буква больше чем ее отсутствие

```javascript
  alert('привет'  > 'прив'); // true;
```
### Сравнение разных типов
При сравнении значений разных типов, используется числовое преобразование
```javascript

  alert('10' > 2); // true 10 преобразовывается в число
  
  alert(0 == false); // true false преобразовывается в число 0
  
  alert( '' == false ); // true как и false пустая строка преобразовывается в число 0
  
  alert(1 == true); // true
  
  alert(true == 'string'); // false
  
  
  alert('1' == 1); 
```
### Строгое сравнение
```javascript
  alert(0 === false); // false
  
```
### Сравнение с undefined
Результат сравнения с undefined всегда, кроме сравнения с null будет false
```javascript
alert( undefined > 0 ); // false
alert( undefined < 0 ); // false
alert( undefined == 0 ); // false
alert( undefined == null);
```
