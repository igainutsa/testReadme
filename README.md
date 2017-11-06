# project NBG

## Servers:

#### tomcat7x : Local Development
	http://localhost:8080


## 	Management:
	
#### DB: NBG
See **`hibernate.cfg.xml`**
Credentials for management : 
>See **`filter_values_development.properties` :** `fv.jdbc.username` , `fv.jdbc.password` , `fv.db.name`

#### solr: NBG
Credentials for management : 
>See **`filter_values_production.properties`** : `fv.jdbc.username` , `fv.jdbc.password` , `fv.db.name`

#### Rest API documentation: NBG
	http://localhost:8080/NBG/swagger




maven build - production:
	
	clean compile war:war -DbuildTarget=production

1)In Eclipse set to jdk1.7.0_79