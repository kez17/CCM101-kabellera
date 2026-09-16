# Mission Reflection

This laboratory activity helped me understand the difference between traditional Virtual Machines and containers. A Virtual Machine normally requires a complete guest operating system, so starting and preparing a VM can take more time and resources. In comparison, a Docker container uses the host operating system kernel and packages the application with its required dependencies. Because of this, containers can usually start much faster and require fewer resources for many application workloads.

The port mapping `-p 8080:80` was necessary because the Nginx web server was listening on port 80 inside the container, while I accessed the service through port 8080 on the host. The mapping connects the host's port 8080 to the container's port 80. Without an appropriate published port, I would not be able to access the Nginx service through the host using `localhost:8080`.

The `docker rm` command removes the specified container after it has been stopped. This means the container itself and its writable container filesystem are removed. However, Docker images are separate from containers, so removing the container does not automatically remove the Nginx image.

Containerization can also change how developers and IT operations teams work together. Developers can package applications and dependencies into consistent container images, while operations teams can deploy those containers in different environments. This supports more consistent development, testing, and deployment and is an important part of modern DevOps practices.

My GitHub portfolio is also evolving from a collection of individual laboratory activities into a more organized technical record of what I have learned. Laboratory 04 adds practical Docker experience to my previous cloud computing activities. By documenting commands, screenshots, challenges, and reflections, I can show both the technical procedures I performed and my understanding of the concepts behind them.
