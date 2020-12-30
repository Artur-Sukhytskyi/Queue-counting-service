# Queue-counting-service
# Сервис подсчёта с очередями

В этом задании пишем сервис, который считает, сколько раз встречается слово python на странице.
Этот сервис должен состоять из следующих частей:
1. Веб-форма для внесения сайтов в спискок задач;
2. Очередь, которая эти задания запускает;
3. Часть, которая обрабатывает результаты;
4. Табличка со статистикой с результатами.

Чтобы запустить приложение на локальной машине нужно: 
- склонировать этот репозиторий
- перейти в папку репозиторием
- установить зависимости из requirements.txt
- еслли не устоновлен docker, то устанвить
- выполнить в командной строке команду docker-compose up -d

После успешного выполнения команды, на 127.0.0.1:5000 будет доступно приложение с двумя эндпоинтами: 
- /add_website, / -- форма для добавления сайта в очередь для подсчета слова "Python"
- /results -- таблица с результатами подсчетов

In this task, we write a service that counts how many times the word python occurs on the page.
This service should consist of the following parts:
1. Web form for adding sites to the list of tasks;
2. The queue that starts these tasks;
3. The part that processes the results;
4. Table with statistics with the results.

To run the application on a local machine you need:
- clone this repository
- go to the folder by the repository
- install dependencies from requirements.txt
- if docker is not installed, then install
- run the command docker-compose up -d on the command line

After the successful execution of the command, an application with two endpoints will be available at 127.0.0.1:5000:
- / add_website, / - a form for adding a site to the queue for counting the word "Python"
- / results - table with calculation results
