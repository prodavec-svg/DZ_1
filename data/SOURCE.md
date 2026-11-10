# Steel Plates Faults — источники данных

## Текущий источник ноутбука

Страница Kaggle: https://www.kaggle.com/datasets/eouedraogo4/steel-plates-faults
Идентификатор: `eouedraogo4/steel-plates-faults`, версия 1.
Скачано и проверено 2026-11-08 через `kagglehub` 1.0.2.
Файл: `kaggle/SteelPlatesFaults.csv`.
Размер: 1 941 строка и 34 столбца.
SHA-256: `a1e4de8e521d90e3fc438ee929fec2d0947d7c7af63179efba5d0635a170e557`.

Ноутбук скачивает данные через Kaggle и читает непосредственно этот CSV.
Проверено совпадение значений, названий столбцов и порядка строк с ранее скачанной версией UCI.
Сами файлы CSV имеют разное текстовое представление и разные контрольные суммы.

## Ранее скачанная версия UCI


Источник: UCI Machine Learning Repository, dataset ID 198.
Страница: https://archive.ics.uci.edu/dataset/198/steel+plates+faults
Архив: https://archive.ics.uci.edu/static/public/198/steel%2Bplates%2Bfaults.zip
DOI: https://doi.org/10.24432/C5J88N
Авторы: Buscema, M., Terzi, S., & Tastle, W. (2010).
Лицензия: Creative Commons Attribution 4.0 (CC BY 4.0).
Лицензия: https://creativecommons.org/licenses/by/4.0/
Дата скачивания: 2026-11-08.

В задании указан Kaggle: https://www.kaggle.com/datasets/eouedraogo4/steel-plates-faults
Его публичный адрес скачивания вернул HTTP 404. Поэтому загружена исходная версия из UCI.
Побайтовое совпадение с копией Kaggle не проверялось.

## Файлы и преобразование

- `raw/Faults.NNA` — исходная таблица без заголовка, сохранена без изменений.
- `raw/Faults27x7_var` — исходный список названий 34 столбцов, сохранён без изменений.
- `steel_plates_faults.csv` — те же данные с заголовком и разделителем-запятой.

Размер CSV: 1 941 строка данных, 34 столбца: 27 признаков и 7 индикаторов класса.
Каждая строка содержит ровно одну единицу в семи последних столбцах.
Имена сохранены как в источнике, включая написание `K_Scatch`.
Значения и порядок строк не изменены; очистка, удаление строк и преобразование целевой переменной не выполнялись.

## SHA-256

- `steel-plates-faults-uci.zip`: `cb8eb9859198b63f053e443513036b401746fa517ef58bd17c846c6741c93919`
- `Faults.NNA`: `08994f5b0185a8e6cc22afe9910fd36834990fb1ca30852ed79012a832fbff55`
- `Faults27x7_var`: `887dbfa140b48877b706865ef277550dc0203699243c600e24bfe8b090a9a953`
- `steel_plates_faults.csv`: `0cba888222e8231df63fa164a6c50a0848007fd6ce41207d5798ac26b3d1b881`
