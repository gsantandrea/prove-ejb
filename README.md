Prova con EJB
===

Testato con Wildfly 21.

Per eseguirlo:

```
cd wildfly-21.0.2.Final
./bin/standalone.sh
./bin/add-user.sh -m -u administrator1 -p password1!
mvn clean package wildfly:deploy -Pwildfly-runtime

```