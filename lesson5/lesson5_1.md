```sql
SELECT SUM(新增確診數) AS 全球2020總確診數
FROM world
WHERE EXTRACT(YEAR FROM 日期) = 2020;
```