# nb-server

# Build
mvn install

# Run in Production
java -jar -Dspring.profiles.active=prod target/gotoclasses-0.0.1-SNAPSHOT.jar

# Run in Dev
java -jar -Dspring.profiles.active=dev target/gotoclasses-0.0.1-SNAPSHOT.jar

# Configuration
# Change the database setting in application.properties file.
# Change the uploadimage path according to OS in application.properties file.

# TODO
# need to make bat file and sh file
