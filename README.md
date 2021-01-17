# openSAP - Create and Deliver Cloud-Native SAP S/4HANA Extensions
# https://open.sap.com/courses/s4h13/

# Generate Project 
mvn archetype:generate "-DarchetypeGroupId=com.sap.cloud.s4hana.archetypes" "-DarchetypeArtifactId=scp-cf-tomee" "-DarchetypeVersion=2.1.2" "-DgroupId=com.sap.cloud.s4hana.examples" "-DartifactId=address-manager" "-Dversion=1.0-SNAPSHOT"


# Deployment
cf login
cf push


# VCS
c