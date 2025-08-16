# BACKUP 
```
pg_dump "postgresql://dbname:pass@..." -Fc -f backup.dump

```

# RESTORE 
```
pg_restore -d "postgresql://new_user:new_password@new-host:5432/new_db" -Fc -c backup.dump

```
