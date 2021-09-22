to install new jar

mvn install:install-file -DgroupId=org.egov.edcr -DartifactId=egov-edcr-extract -Dversion=2.1.0-SNAPSHOT -Dfile="D:\target\egov-edcr-extract-2.1.0-SNAPSHOT.jar" -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true