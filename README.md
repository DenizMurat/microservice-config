# microservice-config
This repository provides the configurations for the article-microservice-1 and webapp application-properties. You can change e.g. the property ${config.changed.test} (webapp.yml) and do a refresh POST request in the terminal -> curl -X POST http://localhost:8080/refresh. Afterwards you can see the changed property with this URL: 'http://localhost:8080/changedConfig'.  
