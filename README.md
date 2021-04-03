# PacktpubDevOp
Packtpub DevOps with GITFlow Jenkins Artifactory Sonar ELK JIRA

# Starting from 7.8.x, PostgreSQL needs to be started before starting the other services.

```
docker-compose -p rt-postgres -f docker-compose-postgres.yaml up -d
docker-compose -p rt up -d
docker-compose -p rt ps
docker-compose -p rt down
```
