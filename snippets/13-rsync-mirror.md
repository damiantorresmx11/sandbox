# rsync-mirror

Mirror a directory, delete extras, dry run first.

```rsync
rsync -avh --delete --dry-run ./src/ user@host:/srv/app/
```
