# Именование переменных:
* Имя может состоять из: букв, цифр, символов $ и _
* Регистр имеет значенние

### Имена переменных

```javascript
  // Valid 
  var name = "Mike";
  var $ = true;
  var PI = 3.14;
  var status404  = 404;
  
  // Invalid 
  var 404error = false;
  var user-name = "Admin";
  
  
```
### Регистр
Названия переменных является регистрозависимым.
```javascript
  var email = "admin@local.host";

  alert(Email); // Uncaught ReferenceError: Email is not defined

```

### Правила именования переменных
Никакого транслита 
```javascript
  var polsovatel = "Admin"; // wrong
  
  var chisloPI = 3.14; // wrong
  
  var login = "Admin"; // Ok
  
  var numberPI = 3.14; // Ok
  
```
Camel case
```javascript
  var windowheight = 500; // wrong

  var windowHeight = 500; // ok

  var window_height = 500; // ok too
```
