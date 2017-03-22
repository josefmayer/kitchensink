## kitchensink


### Technologies
JSF, CDI, JAX-RS, EJB, JPA
on JEE 7 Wildfly

ORM: Hibernate
Database: H2



### Steps

###### Start a Wildfly Server:
For Linux:   *WILDFLY_HOME/bin/standalone.sh*
For Windows: *WILDFLY_HOME\bin\standalone.bat*


###### Build and Deploy the Application:
*mvn clean install wildfly:deploy*


###### Access the Application:
http://localhost:8080/kitchensink


###### Undeploy Application:
*mvn wildfly:undeploy*


## original source
<https://github.com/wildfly/quickstart/>







