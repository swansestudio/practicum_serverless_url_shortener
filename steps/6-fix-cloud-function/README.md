# Шаг 6. Внесем изменения в функцию для использования БД для хранения ссылок

Добавьте файл `requirements.txt`, в нем указана версия библиотеки для работы в YDB.   
Внесите правки в код функции `index.py`, можете полностью перезаписать файл. 

## Добавьте переменные окружения
В переменные окружения функции необходимо добавить три переменные:
Первая — `endpoint` — нужно указать протокол grpcs:// и добавить значение `Эндпоинт` из секции `YDB эндпоинт`.
Вторая — `database` — это значение поля `База данных` из секции `YDB эндпоинт`, начинаться с `/ru-central1/...`.
Третья — `USE_METADATA_CREDENTIALS` — выставите значение переменной в `1`.

После вснесения всех изменений обязательно нажмите кнопку — `Создать версию`.
    
## Видео

