Программа получает данные о компаниях и вакансиях с сайта hh.ru, создает таблицы в БД PostgreSQL и загружает полученные данные в созданные таблицы.
Список компаний и соответствующие им id представлены в файле employer.json.

main.py - файл для запуска программы 
database.py - файл, содержащий основные запросы для создания и использования БД 
HH_class.py - файл для работы с сайтом hh.ru 
utils.py - файл, содержащий дополнительные функции для обработки данных

Перед началом работы необходимо задать конфигурацию для подключения к базе данных в файле .env, которая должна содержать следующую информацию:

host, user, password, port, а также установить виртуальное окружение согласно pyproject.toml
