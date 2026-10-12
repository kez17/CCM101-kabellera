### Actual 404 Error Log

```text
172.17.0.1 - - [12/Oct/2026:00:39:18 +0000] "GET /hidden-admin-page HTTP/1.1" 404 153 "-" "curl/8.5.0" "-"
```

### Importance of Application Logs

Application logs are important because they record HTTP requests, errors, and other events that help administrators identify problems. By examining these records, administrators can troubleshoot failed requests and determine the possible cause of application issues.

## Real-Time Container Metrics

Command executed:

```bash
docker stats
```

| Metric | Result |
|---|---|
| Container Name | `client-website` |
| Memory Usage | To be recorded from `docker stats` |
| CPU Percentage | To be recorded from `docker stats` |

