# supercronic-alpine

Supercrpnic container for x86/amd64, ARM64, arm32v6 (Raspberry Pi)
based on alpine or debian

```
-v <path_to_your>/crontab:/etc/cron.d/crontab:ro
```
file must be readable by user cron (uid 16)

