# Задание на разработку Forte-CMS

Сейчас, для создания статичных страниц на сайте, например публичная офферта, политика конфиденциальности или маркетинговые лендинги на различные праздники необходимо дёргать программистов и ставить им отдельные задачи. Чтобы автоматизировать этот процесс, требуется реализовать приложение, в котором можно будет создавать контентные страницы, по аналогии с wordpress, joomla. 

CMS будет делиться на две части: панель администратора для создания страниц и сам сайт, где можно будет смотреть полученные результаты.

В качестве примера можно посмотреть приложение CMS на Joomla:
```
Main Page: https://s1.demo.opensourcecms.com/s/32
Admin Page: https://s1.demo.opensourcecms.com/joomla/administrator/
Username: opensourcecms
Password: opensourcecms
```

## Админка 
Требуется реализовать приложения на Angular, которое будет иметь следующие страницы: 
- создание новой страницы
- список созданных страниц
- редактирование выбранной страницы
- удаление страницы


Список всех созданных страниц
....

Создание новой страницы

В панели администратора, должен быть раздел CMS. Раздел будет иметь примерно следующий вид, см. картинку. Нужно будет подвязаться к API бекенда, чтобы заполненный контент сохранялся к нам на сервера. 

Контент должен заполняться через WYSIWYG редактор. В интернете уже есть существующие плагины WYSIWYG редакторов, вы можете взять их за основу. Основные требования к редактору:
- поддержка html сниппетов
- поддержка css стилей в сниппетах html
- возможность загружать картинки
- возможность загружать iframe видео с ютуба


Удаление страницы

....


Редактирование страницы

....

## Главная страница
На главной странице маркета, можно будет просматривать список созданных страниц из панели администратора и их детальный вид.

## Результат к проверке
- Админка
  - страница просмотра всех страниц
  - страница создания новой страницы
  - страница редактирования страницы
  - удаление выбранной страницы
- Маркет
  - список всех страниц
  - детальный вид отдельной выбранной страницы


По дополнительным вопросам, можно обращаться к
- Мирасу, 
- Тимуру, tmdautov@gmail.com
