## 1 задание

Запросите у пользователя на сколько пикселей он бы хотел прокрутить данное окно по X и Y! После получения данных от пользователя прокрутите окно на заданные значения!

## 2 задание

Создайте документ в котором будет 4 ifame элемента. Выведите все iframe документа в консоль через методы доступа у window! (через цыкл можно например)

## 3 задание

Создайте iframe в документе и еще пару элементов в body, в переменной сохраните ссылку на iframe, и через iframe удалите все элементы которые есть в DOM body кроме iframe 

## 4 задание

На события загрузки контента в iframe создайте новый div элемент через JS и добавьте его в конец документа, в нем должен быть текст: "Iframe загрузился!"

## 5 задание

Создайте новый документ (через window.open) который будет шириной в 400, высота 500, без строки url адреса, с видимым статусом, окно должно иметь возможность растягиватся по ширине и высоте и в нем должны присутствовать полосы прокурутки!

## 6 задание

Откройте новое окно (через window.open) в котором откройте google поиск и через 5 секунд закройте вкладку и выдайте сообщение пользователю что у вас было 5 секунд но вы не успели ничего найти и окно закрылось!)

## 7 задание

В документе создайе блок в котором вы будете заполнять информацию о браузере и платформе пользователя.
Выведите пользователю информацию о его браузере и о платформе на которой он работает.

## 8 задание

Создайте в документе 5 блоков div в которых будет записано названия браузеров (Chrome, Safari, FireFox, Opera, IE)

И в зависимости от того каким браузером пользуется клиент вы должны показывать только тот блок который соответствует браузер пользователя. Все остальные блоки должны быть скрыты!

## 9 задание

Проверьте подключены ли у пользователя Coockie? Если да то выведите: "Вы используете coockie, вы молодец", а если нет выведите: "Для посещения страницы сайта подключите coockie"

## 10 задание

Проверьте версию браузера пользователя, если версия последняя ничего не делайте если версия не последняя выведите окно с ссылкой на скачивание новой версии браузера!

## 11 задание

Проверьте высоту и ширину экрана пользователя! Если она меньше чем 1366х800 то подставьте в body класс "little-screen", в другом случае добавьте класс "big-screen"!

## 12 задание

Создайте отдлельный проект в котором будет 4 страницы и меню со ссылками на эти 4 страницы! Создайте 2 кнопки которые будут делать переходы по истории! Будт 2 кнопки: 1 - "Назад", 2 - "Вперед"! При клике на кнопку вперед вы будете направлять пользователя по истории на 1 вперед, при клике назад будете направлять пользователя назад! 

Клик на кнопке можно прописать таки образом:

```
<button onclick=whenGoBack>Назад</button>
<button onclick=whenGoForward>Вперед</button>
```

теперь можно написать 

```
funtion whenGoBack () {
// тут делаем что то когда будем кликать на кнопку Назад
}

funtion whenGoForward () {
// тут делаем что то когда будем кликать на кнопку Вперед
}
```

## 13 задание

Выведите в документе информацию пользователю: "Page hostname is " + hostname ( вы тут должны вывести номер порта )
