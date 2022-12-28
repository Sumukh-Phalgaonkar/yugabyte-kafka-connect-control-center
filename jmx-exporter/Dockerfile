FROM quay.io/yugabyte/debezium-connector:latest
# FROM quay.io/vaibhav_yb/test_repo:1.9.5.y.2.11
# FROM quay.io/yugabyte/debezium-connector:1.9.5.y.2-SNAPSHOT
RUN mkdir /kafka/etc && cd /kafka/etc && curl -so jmx_prometheus_javaagent-0.9.jar https://repo1.maven.org/maven2/io/prometheus/jmx/jmx_prometheus_javaagent/0.9/jmx_prometheus_javaagent-0.9.jar
ADD kafka-connect.yml /etc/jmx-exporter/
