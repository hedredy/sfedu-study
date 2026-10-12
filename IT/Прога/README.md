# Прога

```dataview
TABLE type as "Тип", date as "Дата", status as "Статус", tags as "Теги"
FROM "IT/Прога"
WHERE file.name != "README"
SORT date desc
```
