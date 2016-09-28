# Циклы

### Цикл while
```javascript
  while(true) {
    // сделать что-то
  }
```
Пример
```javascript
  var i = 0;
  
  while(i < 10) {
    i++;
  }
  alert(i); // 10
```

### Цикл do...while

```javascript
  do {
    // Сначала делаем
  } while(true) // Потом проверяем
```
Пример
  ```javascript
  var i = 0;
  do {
    i++;
  } while(i < 10) 
  alert(i); // 10
```

### Цикл for
* Инициализация - действие которое вызывается вначале цикла(зачастую - обьявление счетчика)
* Условие - условие продолжения цикла. Если ложно - цикл завершается 
* Шаг  - действие после выполнения итерации цикла(зачастую увеличение/уменьшение счетчика)
```javascript
  for(инициализация;условие;шаг){
    // делаем что-либо
  }
```
Пример 
```javascript
  for(var i = 0; i < 5; i++) {
    alert(i);
  }
  
  var i = 0;
  for(; i < 5; ) {
    alert(i);
    i++;
  }
 
```
### Прерывание цикла break. Следующая итерация continue
```javascript
  var count = 0;
  while(true) {
    count++;
    if(count == 5) {
      break;
    }
  }
  alert(count);
```
Continue
```javascript
  var result = 1;
  for(var i = 0;i < 3; i++) {
    if(i == 1) continue;
    result = result * (i + 1);
    alert(result) // 1, 3
  }
```
