# Managing Timestamps

## References

### Postgres: timestamp vs timestampz  
https://www.postgresqltutorial.com/postgresql-timestamp/  

The timezone recorded depends on the local timezone of the server running the code  


### How does one create a record with end of the day timestamp of local time?
Use momentjs endOf() function for this. Usage:
 `moment().endOf("day");`  
 
Refer for more detaiils: https://momentjs.com/docs/#/manipulating/end-of/  


### GMT vs UTC  
Refer to this thread if you are not clear about the difference between GMT and UTC:  
https://stackoverflow.com/questions/48942916/difference-between-utc-and-gmt/48960297
