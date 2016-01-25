The stub is used to access SOAP methods from clients. It is used in CarabiServer
itself  for making a distributed system, so you have to install it first. Run
`mvn install`
to compile and install the stub. Try to add
`javax.xml.accessExternalSchema=all`
in file $JAVA_HOME/jre/lib/jaxp.properties if you have any problems.
(Create the file if it does not exist.)
