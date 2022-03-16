# Обработка длительных заданий

Напишите сайт для архивации данных:

* Пользователь может увидеть существующих список заархивированных файлов.
* Пользователь может скачивать ранее заархивированные файлы.
* Пользователь может добавить новый файл.
* При добавлении нового файла сайт должен сжать его с помощью архиватора.
* Пользователь должен иметь возможность выбирать один из 3 архиваторов.
* При сжатии сайт должен продолжать свою обычную работу.
* Сайт должен быть написан на Flask
* Обработка архивации должна выполняться с помощью фонового задания Celery

## Ссылки

* [Документация Flask](https://flask.palletsprojects.com/en/2.0.x/)
* [Документация Celery](https://docs.celeryproject.org/en/stable/getting-started/introduction.html)
* [Модуль subprocess](https://docs.python.org/3/library/subprocess.html)
* [Пример работы с Celery](https://blog.miguelgrinberg.com/post/using-celery-with-flask)
* [Пример загрузки файла на Flask](https://flask.palletsprojects.com/en/1.1.x/patterns/fileuploads/)
