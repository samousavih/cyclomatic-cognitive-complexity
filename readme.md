# to run sonarqube
1. Run
```sh
docker run -d --name sonarqube2 -e SONAR_ES_BOOTSTRAP_CHECKS_DISABLE=true -p 9000:9000 sonarqube:latest
```
Then go through the steps in UI and create a token for manual run, copy the token and update "sonarqube-run.sh"
2. Run
```sh
sh sonarqube-run.sh
```