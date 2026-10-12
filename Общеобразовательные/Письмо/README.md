# Письмо

```dataview
TABLE type as "Тип", date as "Дата", status as "Статус", tags as "Теги"
FROM "Общеобразовательные/Письмо"
WHERE file.name != "README"
SORT date desc
```
