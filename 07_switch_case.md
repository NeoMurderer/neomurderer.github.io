# Конструкция switch/case
```javascript
  var accessLevel = "admin";
  var hellowMessage;
  switch(accessLevel) {
    case 'admin' :
      hellowMessage = 'Привет Админ!';
      break;
    
    case 'manager':
      hellowMessage = 'Привет Модератор!';
      break;
    
    default:
      hellowMessage = 'Всего лишь обычный пользователь';
      break;
  }
  alert(hellowMessage);

```
### Вложенные case
```javascript
  switch (browser) {
    case 'IE':
      alert( 'Поддержка не гарантирутеся' );
      break;

    case 'Chrome':
    case 'Firefox':
    case 'Safari':
    case 'Opera':
      alert( 'Спасибо за использование' );
      break;

    default:
      alert( 'Неизвестный браузер' );
  }
```
