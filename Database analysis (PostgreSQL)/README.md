# Анализ базы данных

## Данные
Данные крупного сервиса для чтения книг по подписке:
#### Таблица books:
* book_id — идентификатор книги;
* author_id — идентификатор автора;
* title — название книги;
* num_pages — количество страниц;
* publication_date — дата публикации книги;
* publisher_id — идентификатор издателя.

#### Таблица authors
* author_id — идентификатор автора;
* author — имя автора.

#### Таблица publishers
* publisher_id — идентификатор издательства;
* publisher — название издательства.

#### Таблица ratings
* rating_id — идентификатор оценки;
* book_id — идентификатор книги;
* username — имя пользователя, оставившего оценку;
* rating — оценка книги.

#### Таблица reviews
* review_id — идентификатор обзора;
* book_id — идентификатор книги;
* username — имя автора обзора;
* text — текст обзора.

## Библиотеки
* Pandas
* Sqlalchemy
