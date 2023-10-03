# FROM quay.io/wildfly/wildfly:latest
FROM registry.redhat.io/jboss-eap-7/eap-xp4-openjdk11-openshift-rhel8@sha256:96efb7454f026816f5be40a2000d8fa1523e2dde0380732c1992bf9207cb2c65
COPY target/ROOT.war /wildfly/standalone/deployments/ROOT.war 
CMD $STI_SCRIPTS_PATH/run
