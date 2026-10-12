## Mission Overview
This activity focused on observability and reliability practices in cloud computing. Moving beyond simple deployment, I performed baseline health checks on a Linux host, deployed a containerized Nginx web server, generated simulated user traffic, and used logs and real-time metrics to verify system health — demonstrating the role of a Cloud Operations / Site Reliability Engineer.

## Objectives
- Use native Linux command-line tools to monitor CPU, memory, and disk usage
- Deploy a containerized web application and generate HTTP traffic
- Retrieve and analyze container logs to identify specific request patterns and errors
- Monitor live container resource consumption using Docker metrics
- Document findings professionally in Markdown and maintain a GitHub portfolio

## Monitoring Commands Executed
| Command | Purpose |
|---|---|
| free -h | Display total and available system memory |
| df -h / | Show disk usage on the root filesystem |
| top | Real-time view of CPU load and running processes |
| docker run -d --name clientwebsite -p 8080:80 nginx | Launch Nginx container on port 8080 |
| curl http://localhost:8080 | Generate HTTP GET requests |
| docker logs clientwebsite | Retrieve application access logs |
| docker stats | Live dashboard of container CPU, memory, and network usage |

## Skills Learned
- Establishing a performance baseline before application deployment
- Differentiating between event logs and resource metrics
- Troubleshooting containerized services using built-in Docker tools
- Interpreting HTTP status codes from access logs
- Writing clear, structured technical documentation
- Following evidence-based engineering practices
