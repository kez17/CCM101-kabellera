# Mission Reflection

In this laboratory activity, I learned the importance of monitoring a server and maintaining the performance of cloud applications. Checking the host server's CPU, memory, and disk space is important even when containers are running properly because the containers depend on the host's resources. If these resources become insufficient, the application may slow down or stop working.

I also learned how the `docker logs` command helps troubleshoot problems when users cannot access a web application. By checking the logs, I can identify failed requests, error messages, and other events that may help explain the problem. This makes troubleshooting easier because I can use actual information instead of guessing the cause.

The difference between monitoring logs and metrics is that logs show recorded events and errors, while metrics display numerical information about system performance. For example, `docker logs` can show an HTTP 404 error, while `docker stats` displays the container's CPU usage, memory consumption, and network activity. Both are important for understanding the condition of an application.

Large enterprise companies can monitor thousands of containers using tools such as Prometheus and Grafana. Prometheus collects performance metrics, while Grafana displays the information through dashboards and graphs. These tools help administrators monitor multiple containers and detect problems more efficiently.

Overall, this activity improved my ability to troubleshoot Linux environments and manage Docker containers. I gained experience checking system resources, deploying an Nginx web server, generating HTTP requests, examining application logs, and monitoring container performance. I also understood the importance of documenting results and taking screenshots as evidence. This laboratory activity helped me develop practical skills that are useful in cloud computing and server administration.
