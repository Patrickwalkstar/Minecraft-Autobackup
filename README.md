##Minecraft Autobackup

Full Documentation: [Link](https://docs.google.com/document/d/1Pk8957XSIYo4IevNYOqFl9YReAS1Qbcj4ZxVxAaZUbk/edit?usp=sharing)

---
###The Project: 
* Build a Minecraft server using a Docker container and...
* Write a Python script that creates a backup of the server and...
* Stores each backup on GitHub and each zipped backup locally and finally...
* Can perform a number of additional commands:
    * Bring attention to the server by sending notifications on regular intervals of an upcoming server restart
    * Restart the docker container (and the server)
    * Log system information at each step
    * Remove old backups

---
###Automation:
A simple cron job is configured that runs our backup script on a regular basis.
A *cron job* is a task that runs on an operating system's scheduler.
On MacOS, the term is *crontab*. 

---

####Resources:

[Link to Docker documentation to restart a container etc.](https://docs.docker.com/engine/reference/commandline/container_restart/)
[Link to set up a Minecraft server with Docker](https://hub.docker.com/r/itzg/minecraft-server/)
