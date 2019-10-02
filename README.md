# PostgreSQLDump
An automatic function to dump database tables without any grant rather then the select
#Example of execution 

For a full dump of the table simply run 

SELECT dump('public','user', 'true')
