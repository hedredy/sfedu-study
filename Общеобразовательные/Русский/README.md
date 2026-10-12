# Русский

```dataview
TABLE type as "Тип", date as "Дата", status as "Статус", tags as "Теги"
FROM "Общеобразовательные/Русский"
WHERE file.name != "README"
SORT date desc
```
