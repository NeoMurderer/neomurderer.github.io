# Массивы
```javascript
  var countries = ['Ukraine','USA','Norway'];
  
  
  alert(countries[0]); // Ukraine
  
  alert(countries.length); // 3
```
## Методы
### Добавление/удаление элементов
```javascript
   var countries = [];
  
   countries.push('Ukraine'); // push добавляет элемент в конец массива
   
   countries[1] = "USA";
   
   alert(countries[0]); // Ukraine
   alert(countries.length); // 2
   
   
   countries.pop(); // pop удаляет последний элемент массива
   
   alert(countries.length); // 1
```
### Из строки в массив и наоборот

```javascript
  var names = "John,Martin,Alex";
  
  var namesArray = names.split(',');
  
  alert(namesArray[0]); // John
  
  namesArray[0] = 'Anna';
    
  var anotherNames = namesArray.join(', ');
  alert(anotherNames) // Anna,Martin,Alex
  
```
### Удаление по индексу

```javascript
  var arr = ['Скоро','наступит','весна'];
  
  arr.splice(0,1); // Удаляем 1 элемент с 0 позиции
  alert(arr); // ['наступит','весна']
```
Замена элемента 
```javascript
  var arr = ['Скоро','наступит','весна'];
  
  arr.splice(0,1,'Через','пол','года'); // Удаляем 1 элемент с 0 позиции и добавляем 3 элемента
  alert(arr); // ['Через','пол','года','наступит','весна']
```
Вставка элемента в середину
```javascript
  var arr = ['Скоро','наступит','весна'];
  
  arr.splice(2,0,'теплая'); // Удаляем 0 элементов с 2 позиции и добавляем 1 элемент
  alert(arr); // ['Скоро','наступит','теплая','весна']
```
