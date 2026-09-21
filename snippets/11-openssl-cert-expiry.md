# openssl-cert-expiry

Expiry date of a live TLS certificate.

```openssl
echo | openssl s_client -servername example.com -connect example.com:443 2>/dev/null | openssl x509 -noout -dates
```
