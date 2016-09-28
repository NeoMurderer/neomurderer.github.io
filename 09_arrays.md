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
