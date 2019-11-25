# azure-devops-agent

```
CURRENT_UID=$(id -u):$(id -g)
docker-compose up -d --scale azure-devops-agent=3 --no-recreate
```