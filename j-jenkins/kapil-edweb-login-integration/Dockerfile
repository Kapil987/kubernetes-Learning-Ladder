# 3. Dockerfile.edweb-copy-war
# Agent dockerFile image will perform a maven build
# artifcats will be copied here
FROM kapil0123/edweb-tomcatbase
COPY target/*.war /opt/tomcat/webapps/



# Observations
# looks like docker pipeline syntax natively only looks for Dockerfile exactly
# if your Dockerfile is something like Dockerfile.dev it will not be found