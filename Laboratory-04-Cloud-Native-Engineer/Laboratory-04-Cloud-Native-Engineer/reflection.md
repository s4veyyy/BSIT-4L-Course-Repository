# Mission Reflection

This laboratory helped me understand how Docker containers are different from traditional Virtual Machines. A Docker container can start much faster because it does not need to boot a complete operating system like a Virtual Machine. Instead, containers share the host operating system, which makes them more lightweight and efficient. This makes container deployment faster and more practical for web applications.

The port mapping `-p 8080:80` is necessary because the Nginx web server runs on port 80 inside the container, while port 8080 allows me to access the application from the host machine. By mapping these ports, I can send requests to `localhost:8080` and reach the Nginx server running inside the container.

When I use the `docker rm` command, the container itself is permanently removed. Any data stored only inside the container can also be lost after the container is removed, which is why persistent data should be stored using volumes or other storage solutions when needed.

I think containerization can improve collaboration between software developers and IT operations teams because applications can be packaged with their required environment and deployed consistently. This supports DevOps practices by making development, testing, and deployment more efficient.

My GitHub portfolio is also improving because I am now adding more organized laboratory activities and technical documentation. Through this activity, I was able to practice Docker commands and document my work using Markdown. It also helped me understand how cloud computing technologies are used in real-world IT environments.
