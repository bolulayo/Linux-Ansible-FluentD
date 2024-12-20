# Linux-Ansible-FluentD
automate the installation and configuration of a web server using Ansible

![nginx hello world](./images/hello-world.png)

## Working Fluentd Service
![fluentd-service](./images/fluentd-service.png)

## Fluentd Logs
![fluentd-logs](./images/fluentd-logs.png)


## Log management solution

Log management solution is implemented using logrotate, which is the standard Linux solution for log rotation. 
The configuration:
- Rotates logs daily
- Keeps 5 days of logs
- Compresses old logs to save space
- Handles log rotation gracefully with Nginx
- Automatically deletes logs older than 5 days