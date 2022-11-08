Here the path for my.ini on XAMPP

xampp\mysql\bin\my.ini

Open my.ini and add the following
[mysqld]
event_scheduler=ON
then restart mySql service.

To check the status use the below mySql query

SELECT @@event_scheduler
