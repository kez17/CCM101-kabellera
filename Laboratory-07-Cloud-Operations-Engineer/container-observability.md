# Container Observability

## Application Logs

### 404 Error Log

```text
2026/10/12 00:39:18 [error] 29#29: *4 open() "/usr/share/nginx/html/hidden-admin-page" failed (2: No such file or directory), client: 172.17.0.1, server: localhost, request: "GET /hidden-admin-page HTTP/1.1", host: "localhost:8080"
172.17.0.1 - - [12/Oct/2026:00:39:18 +0000] "GET /hidden-admin-page HTTP/1.1" 404 153 "-" "curl/8.5.0" "-"
```

## Container Metrics
