# systemd-user-service

Run a long-lived process as the logged-in user, restarted on failure.

```systemd
[Unit]
Description=%i worker

[Service]
ExecStart=/usr/bin/node /srv/app/worker.js
Restart=on-failure
RestartSec=5

[Install]
WantedBy=default.target
```
