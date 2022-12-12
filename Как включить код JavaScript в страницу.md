# Как включить код JavaScript в страницу
```javascript
<!doctype html>  /* Стандартный заголовок HTML5
doctype, элементы <html> и <head>. */
<html lang="en">
<head> /*В раздел <head> страницы до-
бавляется элемент script.*/
<meta charset="utf-8">
<title>Just a Generic Page</title>
<script>
setTimeout(wakeUpUser, 5000);
function wakeUpUser() { /*В нем записывается фрагмент
кода JavaScript.*/
/*Еще раз: сейчас для нас не важно, как работает
этот код. И все же... Посмотрите на него и предпо-
ложите, что происходит в каждой из строк.*/
alert("Are you going to stare at this boring page forever?");
}
</script>
</head>
<body> /*Элемент <body> выглядит вполне традиционно.*/
<h1>Just a generic heading</h1>
<p>Not a lot to read about here. I'm just an obligatory paragraph living in
an example in a JavaScript book. I'm looking for something to make my life more
exciting.</p>
</body>
</html>
```
### РАССЛАБЬТЕСЬ
```javascript
setTimeout(wakeUpUser, 5000); /*Вероятно, мы создаем код, который можно будет использовать в других местах, и присваиваем ему имя «wakeUpUser»?*/
/*Здесь каким-то образом отсчитывается пять секунд? Подсказка: 1000 миллисекунд = 1 секунда.*/
function wakeUpUser() {
alert("Are you going to stare at this boring page forever?");/*Тут все понятно: выводится сообщение для пользователя*/
```
