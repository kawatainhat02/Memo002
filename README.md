# Memo002
My SQL
mysql 

SELECT column_name 
FROM table_name;

UPDATE table_name
SET some_column = some_value
WHERE some_column = some_value;

DELETE FROM table_name
WHERE some_column = some_value;

INSERT INTO table_name (column_1, column_2, column_3) 
VALUES (value_1, ‘value_2’, value_3);

CREATE DATABASE databasename;

CREATE TABLE table_name (
column_1 datatype, 
column_2 datatype, 
column_3 datatype
);

ALTER TABLE table_name 
ADD column_name datat

DROP TABLE table_name;ype;

CREATE INDEX index_name 
ON table_name (column_name1, column_name2…);

ALTER TABLE table_name
DROP INDEX index_name;

List of all MySQL commands:
Note that all text commands must be first on line and end with ';'
?         (\?) Synonym for `help'.
clear     (\c) Clear the current input statement.
connect   (\r) Reconnect to the server. Optional arguments are db and host.
delimiter (\d) Set statement delimiter.
edit      (\e) Edit command with $EDITOR.
ego       (\G) Send command to mysql server, display result vertically.
exit      (\q) Exit mysql. Same as quit.
go        (\g) Send command to mysql server.
help      (\h) Display this help.
nopager   (\n) Disable pager, print to stdout.
notee     (\t) Don't write into outfile.
pager     (\P) Set PAGER [to_pager]. Print the query results via PAGER.
print     (\p) Print current command.
prompt    (\R) Change your mysql prompt.
quit      (\q) Quit mysql.
rehash    (\#) Rebuild completion hash.
source    (\.) Execute an SQL script file. Takes a file name as an argument.
status    (\s) Get status information from the server.
system    (\!) Execute a system shell command.
tee       (\T) Set outfile [to_outfile]. Append everything into given
               outfile.
use       (\u) Use another database. Takes database name as argument.
charset   (\C) Switch to another charset. Might be needed for processing
               binlog with multi-byte charsets.
warnings  (\W) Show warnings after every statement.
nowarning (\w) Don't show warnings after every statement.
resetconnection(\x) Clean session context.
query_attributes Sets string parameters (name1 value1 name2 value2 ...)
for the next query to pick up.
ssl_session_data_print Serializes the current SSL session data to stdout 
or file.



