Run below commands to test the class loading:

`mvn compile`
`mvn exec:java`


Run below command to test native-image building:

`mvn clean package -Pnative -DskipTests`
