



## 1. import and clone repo to local

 git clone https://{user_name}:{token}@github.com/{org_name}/workshop-project.git  
 
 
## 2. manual scan
 
mvn clean install -DskipTests=true sonar:sonar -Dsonar.host.url=https://sonarcloud.io  -Dsonar.token=6ed5a9a58c87cf381058da4a39faa9f6df8789e2


