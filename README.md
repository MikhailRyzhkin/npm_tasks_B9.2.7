# npm_tasks_B9.2.7

Задание B9.2.7
Что нужно сделать:

1. Установите Node.js.
2. Установите npm.
3. Создайте репозиторий или используйте уже созданный вами для обучения.
4. Создайте автоматически package.json.
5. Установите в свой проект библиотеку jquery.
6. Сделайте коммит изменений.

Ссылку на удаленный репозиторий опубликуйте в форме для ввода ответа в финальном юните.
При желании вы можете ее отправить в Slack и предложить коллегам посмотреть, прокомментировать вашу работу.

Действия:
0. Устанавливаем  Node.js и npm.
1. Регистрируюсь в npm фронтенд хранилище артефактов: https://www.npmjs.com/
2. Создаём папку проекта и переходим в неё
3. Инициализируем через: npm init. Указываем при запросе данные по имени, описанию, связанному гит-репозиторию. У нас создаётся автоматически package.json
4. Ставим пакет jquery: npm install jquery. При установке пакета создаётся папка с модулями "node_modules", а в ней подпапка установленного модуля jquery.
5. Создаём файл .gitignore и вносим в него папку с модулями, т.к. они всегда при команде npm install установят указанный в конфиге файла package.json модуль.
6. Логинимся в хранилище артефактов фронтенда npm: npm login.
7. Отправляем пакет в репозиторий хранилищ артефактов фронтенда npm: npm publish.
8. Делаем коммит и отправляем в удалённый github репозиторий код задачи.

https://github.com/MikhailRyzhkin/npm_tasks_B9.2.7
https://www.npmjs.com/package/npm_tasks_b9.2.7