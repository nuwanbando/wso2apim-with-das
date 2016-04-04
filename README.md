### API-M simple deployment with WSO2 DAS ###

Following instructions will help you to setup the deployment

1. Clone the repository to your local file system
2. Navigate to ``` packs/ ``` and copy ```wso2am-1.10.0.zip``` and ```wso2das-3.0.1.zip```
3. navigate into the parent directory (wso2apim-with-das)
4. Execute ``` docker-compose up -d ```

This will setup 

* A mysql server (container) with apimdb / userdb / regdb
* API-Manager runs on its own in a container (store/publisher/km/gateway all in one JVM)
* A container with DAS and configured for API statistics

