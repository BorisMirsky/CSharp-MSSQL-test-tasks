ЗАДАЧА 1
Создать ASP.NET приложение TestWebApp, состоящее из одной страницы default.aspx, на
которой расположен элемент управления гиперссылка : “Запустить”. На событие onclick необходимо
запустить исполняемый файл на компьютере клиента, например notepad.exe
Событие может быть как серверное, так и клиентское.


ЗАДАЧА 2
Создать ASP.NET приложение TestWebApp, состоящее из одной страницы default.aspx, на
которой расположены элементы управления гиперссылка : “Выбрать” и &lt;div id=”divValue”&gt;
Создать win-console приложение TestWinApp.
На событие onclick на странице default.aspx приложения TestWebApp необходимо отправить
параметризированный запрос (i=1&amp;j=2) приложению TestWinApp, которое расположено на
компьютере клиента в предопределенной папке. При получении запроса приложение TestWinApp
должно обработать полученные параметры i и j, выполнить операцию сложения и вернуть результат
приложению TestWebApp. Полученный результат вывести в divValue на той странице, которая
инициировала запрос.
ОБЩИЕ ТРЕБОВАНИЯ:
Операционная система на компьютере клиента - Windows
При проверке приложение будет развернуто на IIS в локальной сети, если необходимо
используйте зоны местной интрасети или доверенные зоны.
Решение заданий не должно требовать установки дополнительных серверных приложений.
Разрешаются к использованию любые технологии, кроме ActiveX и компонентов Silverlight.
Функционал приложения TestWebApp должен работать в любом браузере(IE, Chrome, Firefox,
Safari).




Как пользоваться
1. Предполагаем, что установлена Visual Studio.
2. В папке KESKO_ASP.NET/KESKO_task1 находится задание 1. Склонировать проект, открыть в VS. Среда разработки сама подхватит и установит недостающие пакеты.
3. В папках KESKO_ASP.NET/KESKO_task2 и KESKO_ASP.NET/KESKO_console_task2 находится задание 2. Склонировать проект, открыть в VS. \
   Должны быть открыты обе программы. Сначала запускаем KESKO_task2, затем в течение 5 секунд надо запустить KESKO_console_task2. \

   






