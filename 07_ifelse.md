# Условные операторы
Базовая структура
```javascript
  if(true) {
    //...some code
  }
  else {
    //... if false
  }
```
Пример №1
```javascript
  var hasAccess = true;
  
  if(hasAccess == true) {
    alert("У вас есть доступ");
  }
  else {
    alert('Купите у нас премиум!');
  }
```
### Преобразование к логическому типа
* Число 0, пустая строка "", null, undefined, NaN являются false,
* Остальные значения – true.
```javascript
  var result = "0";
  if(result) {
    alert("Успешный результат"); // Зайдет сюда(попадает под второй случай);
  }
```
Для избежания подобного поведения - нужно использовать явное преобразование типов
```javascript
  var result = "0";
  if(Number(result)) {
    alert("Успешный результат"); 
  }
  else {
    alert("Произошла ошибка!"); // Зайдет сюда(строка превращается в число и попадает под первый случай)
  }
```
### Несколько вариантов условия
```javascript
  var accessLevel = "admin";
  var hellowMessage;
  if(accessLevel == 'admin') {
    hellowMessage = 'Привет Админ!';
  }
  else if(accessLevel == 'moderator') {
    hellowMessage = 'Привет Модератор!';
  }
  else {
    hellowMessage = 'Всего лишь обычный пользователь';
  }
  alert(hellowMessage);
  
  
```

### Короткая запись

```javascript
  var accessLevel = 'admin';
  var hasAccess;
  
  access = (accessLevel  == 'admin') ? true : false;
  
  alert(access); // true
```
