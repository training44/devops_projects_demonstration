
FROM jboss/wildfly
COPY wildfly-spring-boot-sample-1.0.0.war /opt/jboss/wildfly/standalone/deployments/
# Expose the ports we're interested in
EXPOSE 8080 9990 9090

# Set the default command to run on boot
# This will boot WildFly in the standalone mode and bind to all interface
CMD ["/opt/wildfly/bin/standalone.sh", "-c", "standalone-full.xml", "-b", "0.0.0.0"]
