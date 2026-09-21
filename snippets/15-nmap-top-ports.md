# nmap-top-ports

Fast sweep of the thousand most common ports with service detection.

```nmap
nmap -sV --top-ports 1000 -T4 -oN scan.txt 10.0.0.0/24
```
