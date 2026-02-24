# Sqlmap

Set sqlmap directory in sqlmap.bat first.

## Protected Authentication
Link to a protected login page: ```http://alscheift.my.id/login```

### Try to inject
```sqlmap.bat -u "http://alscheift.my.id/login" --batch --dbs```


## Unprotected Authentication (injectable)
Link to a unprotected login page: ```http://alscheift.my.id/unsafe/login```

### Get General DBMS information
```sqlmap.bat -u "http://alscheift.my.id/unsafe/login" --batch --dbs```
