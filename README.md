# ETL
---

### Решения по загрузке файлов в базу данных(postgres)

Есть файлы вида csv,json,txt.
Создаем соединение с бд, куда собираемся выгружать файлы.
Настраиваем условия и ограничения , как будет происходить выгрузка в нужную таблицу.
Кроме того, устанавливаем условия по нахождению ошибок.

![решение](https://github.com/facessere/ETL/blob/main/scr/1.jpg)

---

Аналогично удаляем данные из таблиц
![решение](https://github.com/facessere/ETL/blob/main/scr/2.jpg)

---

Данные  формата exel сортируем и представляем в формате json.
Перемещаем файл в лок папку,позже все выгрузим в бд
![решение](https://github.com/facessere/ETL/blob/main/scr/3.jpg)

---

Получение данных из бд
![решение](https://github.com/facessere/ETL/blob/main/scr/4.jpg)

---
Загрузка измерения,в котором хранится некая информация(новые данные)
![решение](https://github.com/facessere/ETL/blob/main/scr/5.jpg)

---
Загрузка данных из бд в DWH
![решение](https://github.com/facessere/ETL/blob/main/scr/6.jpg)
