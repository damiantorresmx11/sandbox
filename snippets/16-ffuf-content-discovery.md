# ffuf-content-discovery

Directory discovery filtered by response size to cut the noise.

```ffuf
ffuf -u https://target/FUZZ -w wordlist.txt -mc 200,204,301,302,401,403 -fs 0 -t 40 -o out.json
```
