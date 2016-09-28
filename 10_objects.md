# Обьекты

Создание обьекта
```javascript
  var emptyObject =  new Object();
  var obj = {
    property:'value',
    secondProperty: 12
  };
```
Добавление свойства к обьекту
```javascript
  var person = {};
  
  person.name = "John";
  person.age = 19;
  
  alert(person.age); // 19
  
  alert(person); // [object Object] - произошло преобразование в String
  
  alert(person.secondName); // undefined - нет свойства с ключем secondName
  
```
Доступ к свойству обьекта
```javascript
  var person = {};
  person['name'] = 'Ada'; 
  
  alert(person.name); // Ada
  
  /* Доступ к свойсту через переменную */
  var key = 'name';
  
  alert(person[key]); // Ada
```
Вложенные обьекты
```javascript
  var user = {
    login:'admin',
    favouriteCountries:['Ukraine','USA','Norway'],
    isAdmin:true
  }
  alert(user.favouriteCountries[0]); // Ukraine
```
Перебор свойств обьекта
```javascript
  for (key in obj) {
    // key - ключ обьекта
  }
```
Пример
```javascript
  var person = {
    name:'Ada',
    secondName:'Lovelace',
    age:18
  };
  for (key in person) {
    alert(key); // name,secondName,age
  }
  
  for (key in person) {
    alert(person[key]); // Ada,Lovelace,18
  }
```

Сравнение обьектов
```javascript
  var first = { 
    id: 0
   };
  var second = { 
    id : 0 
  };
  alert(first == second); // false - Сравнение объекта истинно лишь в том случае, если оба операнда ссылаются на один и тот же объект в памяти
```
Одинаковые обьекты
```javascript
  var first = { 
    id: 0
   };
  var second = first;
  second.id = 1;
  alert(first == second); // True - Созданы от одного конструктора
```
