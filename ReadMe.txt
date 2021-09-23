to install new jar

mvn install:install-file -DgroupId=nic.egov.edcr -DartifactId=egov-edcr-extract -Dversion=2.1.0-SNAPSHOT -Dfile="D:\Nic Project\OBPS\JK\Egov\eGov-dcr-service\egov\egov-edcr-extract\target\egov-edcr-extract-2.1.0-SNAPSHOT.jar" -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true