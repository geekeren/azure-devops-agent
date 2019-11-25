# azure-devops-agent

```
CURRENT_UID=$(id -u):$(id -g)
export VSTS_TOKEN=xxx
export VSTS_ACCOUNT=xxx
docker-compose up -d --scale azure-devops-agent=4 --no-recreate
```