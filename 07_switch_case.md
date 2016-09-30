# Конструкция switch/case
```javascript
  switch(variable) {
  case 'value1':  // if (variable === 'value1')

    break;

  case 'value2':  // if (variable === 'value2')
    
    break

  default:

    break;
}
```
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
