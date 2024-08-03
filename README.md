Данный парсинг данных создан для решения следующей **задачи:**
*построить парсер, принимающий уникальный идентификатор пользователя сервиса Кинопоиск, возвращающий информацию об оценках фильмов этим пользователем и рейтинг этих же фильмов от Кинопоиска.*

Сервис Кинопоиск является крупнейшим сервисом о кино в рунете. Для того, чтобы облегчить поиск подходящего для просмотра фильма, можно воспользоваться рекомендательными системами, которые можно усовершенствовать лично для каждого. На данном сервисе есть возможность находить и добавлять "Друзей по интересам" - тех пользователей, чьи оценки фильмов, предпочтения к жанрам и пр. совпадают с Вашими. Таким образом, используя данный парсер можно узнать о Вашем "Друге по интересам" какие фильмы смотрел и как их оценил, и какая оценка была от самого сервиса, что позволит быстрее и качественнее подобрать подходящий фильм, нежели искать в "свободном плавании" по сервису.

![](https://drive.google.com/file/d/1CCljU3mSW53yjZw4_3gdjScZVa3nCT9f/view?usp=drive_link)

 **Возможность последующий интеграции:**
 Реализованную функцию можно будет интегрировать в потенциальный класс, который будет решать множество задач парсинга по сервису Кинопоиск.
 Пример результата работы парсера можно увидеть в файле Excel, где представлены оценки о 34 фильмах, которые на текущий момент времени есть у пользователя, идентификатор которого был использован для демонстрации работы.

 Инструкция по запуску кода:
  выполните команду
 '''python
 python3 -m Парсинг данных Кинопоиск.py Config.py
 '''
 Файл config - это файл с настройками, где переменная user_login - хранит значение идентификатора пользователя. **Его можно изменить на любой другой нужный id.**
 *Примечание:* из-за срабатывания механизмов блокировок парсинга на сайте Кинопоиск, извлечение данных с большого количества страниц с оценками может быть затруднено и результат будет ограничен.

 Cпасибо за Ваш интерес!
