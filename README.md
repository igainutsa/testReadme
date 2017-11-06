# project NBG ![alt text][logo]

## Servers:
***
#### tomcat7x : Local Development
	http://localhost:8080


## 	Management:
***
	
#### DB: NBG
See **`hibernate.cfg.xml`**

Credentials for management : 
>See **`filter_values_development.properties` :** `fv.jdbc.username` , `fv.jdbc.password` , `fv.db.name`

#### solr: NBG
Credentials for management : 
>See **`filter_values_production.properties`** : `fv.jdbc.username` , `fv.jdbc.password` , `fv.db.name`

#### Rest API documentation: NBG
	http://localhost:8080/NBG/swagger

	
## 	install project in local:
***
1. clone project in computer
2. downloads and install program Workbench [link](https://dev.mysql.com/downloads/workbench/)
3. downloads snd install SQL [link](https://drive.google.com/drive/folders/0B4alBSKMwoHLMFhvRnZGY3c1WGM)
..* create table from name `fv.db.name`


maven build - production:
	
	clean compile war:war -DbuildTarget=production

1)In Eclipse set to jdk1.7.0_79



[logo]: https://github.com/ivangainutsa/testReadme/blob/master/favicon.ico "Logo"
