# Задание.
Используется исходный код с лабораторной работы, посвященной работе с данными с помощью интерфейса PDO или MySQLi. Проверить его работу.
Изменить код для обработки данных результатов запросов (для параметризированных запросов, реализуемых в прошлой лабораторной по вариантам) таким образом, чтобы вывод результата пользователю не приводил к перезагрузке страницы - т.е. использовать технологию Ajax. Использовать следующие форматы ответа от сервера:
в формате простого текста (непосредственно получать сгенерированный фрагмент HTML-кода и выводить его в заданном элементе стартовой страницы);
в формате XML (результат запроса на выборку помещается в генерируемом сервером XML-документе, который клиент считывает через свойство responseXml и формирует вывод пользователю);
в формате JSON (результат запроса на выборку помещается в массив, который затем преобразуется в JSON-строку с помощью метода json_encode и отправляется клиенту, который получает данные выборки из строки с помощью метода JSON.parse и формирует вывод пользователю).
Обратите внимание, необходимо показать применение всех трех форматов ответа от сервера - по одному формату на каждый из трех запросов на выборку.
Возможно использование вместо XMLHttpRequest методов Fetch API для запроса, служащего примером работы с форматом JSON.
## Скрины
![Screenshot_1](https://user-images.githubusercontent.com/93394154/176409930-63d46e69-fe01-4408-a1bb-bf00e3b17470.png)
![Screenshot_2](https://user-images.githubusercontent.com/93394154/176409935-494a5c8b-2a75-45c2-a9d0-35296f9ded3f.png)
![Screenshot_3](https://user-images.githubusercontent.com/93394154/176409938-853fa391-36b7-49e1-862a-cbc885dbe071.png)
