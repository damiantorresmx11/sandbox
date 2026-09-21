# find-large-files

Ten biggest files under the current directory.

```bash
find . -type f -printf '%s\t%p\n' | sort -rn | head -10 | numfmt --to=iec --field=1
```
