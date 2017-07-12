# mysql study

## dump structure out of mysqldb
- mysqldump -u user -p pwd -d(just no-datacontent) db_name tbl_name > *.sql

### samples
- mysqldump -uroot -proot -d dbname > db.sql;
- mysqldump -uroot -proot dbname > db.sql;
- mysqldump -uroot -proot -d dbname tblname > db.sql;
- mysqldump -uroot -proot dbname tblname > db.sql;

## group_concat
`group_concat([DISTINCT] COL [ORDER BY COL DESC| ASC])`
