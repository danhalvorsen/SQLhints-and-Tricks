
## Search for a table contains a colum with name 
select * from INFORMATION_SCHEMA.COLUMNS  
where COLUMN_NAME like '%cel%'   
order by TABLE_NAME  
