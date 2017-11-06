# project NBG

### Servers:

##### tomcat7x : Local Development

[http://localhost:8080](http://localhost:8080)


###### ======================
#### Rest API documentation: NBG
###### ======================

http://localhost:8080/NBG/swagger


###### ======================
#### DB: NBG
###### ======================

See hibernate.cfg.xml

Credentials for management : 
see filter_values_development.properties : fv.jdbc.username, fv.jdbc.password, fv.db.name


###### ======================
#### solr: NBG
###### ======================

Credentials for management : 
see filter_values_production.properties : fv.jdbc.username, fv.jdbc.password, fv.db.name


 


maven build - production:
	
	clean compile war:war -DbuildTarget=production

1)In Eclipse set to jdk1.7.0_79