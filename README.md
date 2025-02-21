


## Технологии
- **PyQt5**: используется для создания графического интерфейса.
- **PostgreSQL**: база данных для хранения информации об учителях.
- **QSqlQueryModel**: используется для работы с базой данных через модель представления данных в таблице.
## Установка

1. Клонируйте репозиторий:

   ```bash
   
   git clone git@github.com:Rigoprogrammist/desktop-demo-pyt.git
    ```
2. Создайте виртуальное окружение и установите необходимые библиотеки (из requirements.txt):

   ```bash
   python -m venv venv
   ```
3. Для активации виртуального окружения:

   ```bash
    .\venv\Scripts\activate
    
4. Настройка подключения к базе данных PostgreSQL

    В файле `settings.py` нужно настроить следующие параметры подключения:

- `host` — адрес хоста базы данных.
- `port` — порт базы данных.
- `dbname` — имя базы данных.
- `user` — имя пользователя.
- `password` — пароль пользователя.

5. Запуск приложения


    ```bash
    python __main__.py
    ```