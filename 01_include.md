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
  <script src="main.js">
  	alert("Hello world"); // так как указан src - содержимое игнорируется
  </script>
```
Если указан атрибут src, то содержимое тега игнорируется
#### Async

```html
  <script src="main.js" async></script>
```
При наличии атрибута async браузер при возможности запускает скрипт асинхронно и указанный в атрибуте src файл будет выполняться без ожидания загрузки и отображения веб-страницы
#### Defer

```html
  <script src="main.js" defer></script>
```
Атрибут defer откладывает выполнение скрипта до тех пор, пока вся страница не будет загружена полностью
