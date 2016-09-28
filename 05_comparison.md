# Операторы сравнения
* ==
* !=
* >
* >=
* <
* <=
* ===

Существует два логических значения:
* false - нет, ложь
* true - да, истина

```javascript
  alert(2 > 1); // true
  
  alert(2 != 1); // true
  
  alert(5 == 10); // false
  
```
Сравнение строк происходит побуквенно
```javascript
  alert('б' > 'а'); //  true
  
  alert('a' == 'A'); // false
  
  alert('aaa' > 'b'); //false
  
  alert('2' > '14'); // true - сравниваются строки
```
Сравнение разных типов
```javascript
  alert(0 == false); // true
  
  alert( '' == false ); // true
  
  alert(1 == true); // true
  
  alert(true == 'string'); // false
  
  
  alert('1' == 1); // true '1' преобразовывается в integer
```
Строгое сравнение
```javascript
  alert(0 === false); // false
  
```
