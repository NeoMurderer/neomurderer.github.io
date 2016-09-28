# Подключение и выполнение javascript

### Подключение в любом месте
```html
<!DOCTYPE HTML>
<html>

<head>
  <!-- Тег meta для указания кодировки -->
  <meta charset="utf-8">
</head>

<body>
  <!-- Inline script -->
  <script>
	  alert("Hello world");
  </script>
  
  
</body>
</html>
```
### Внешнее подключение

```html
  <script src="main.js" type="text/javascript"></script>
```
#### Async

```html
  <script src="main.js" type="text/javascript" async></script>
```
При наличии атрибута async браузер при возможности запускает скрипт асинхронно

#### Defer

```html
  <script src="main.js" type="text/javascript" defer></script>
```
Атрибут defer откладывает выполнение скрипта до тех пор, пока вся страница не будет загружена полностью
