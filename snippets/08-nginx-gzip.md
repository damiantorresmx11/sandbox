# nginx-gzip

Minimal gzip block that actually covers the types that matter.

```nginx
gzip on;
gzip_vary on;
gzip_min_length 1024;
gzip_types text/plain text/css application/json application/javascript image/svg+xml;
```
