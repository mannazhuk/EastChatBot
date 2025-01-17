# East_chat_bot
В этом репозитории хранятся необходимые компоненты для запуска чат-бота по поиску информации в китайских и японских СМИ.

Код находится в ноутбуке [chat_bot](chat_bot.ipynb). В нем используются модели Yandex, поэтому в случае ошибки убедитесь, что названия ключей доступа совпадают.

Для запуска нужны:

1. Векторные хранилища 2016 года ([файл 1](faiss_2016_index.index), [файл 2](faiss_2016_index.pkl)); до 2017 ([файл 3](combined_1_index.index), [файл 4](combined_1_index.pkl)) и до 2019 года ([файл 5](combined_2_index.index), [файл 6](combined_2_index.pkl)). Хранилища до 2022 и 2023 годов нельзя прикрепить к репозиторию из-за ограничений размера, поэтому нужно тестировать чат-бот только до 2019 года или же скачать недостающие хранилища по [cсылке](https://drive.google.com/drive/folders/1QBJFiuzWUh0IgpeOqMkdQGtuYRxE1z1x?usp=sharing).

2. Таблицы с данным для поиска ссылок на источники (файлы data_part_N). 

Ноутбуки по обработке данных и созданию векторных хранилищ можно посмотреть в [Архиве](https://github.com/mannazhuk/East_chat_bot/tree/9416543aff52bf2001697e5fa30014cfbb3e21c3/Project%20Archive).
