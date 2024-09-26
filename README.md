###

# Podman
ActiveMQ Classic
```
podman run --detach --name activemq-classic -p 61616:61616 -p 8161:8161 --rm apache/activemq-classic:5.17.6
```
ActiveMQ Artemis
```
podman run --detach --name activemq-artemis -p 61616:61616 -p 8161:8161 --rm apache/activemq-artemis:latest
```

# OpenShift


# Troubleshooting
```curl -u admin:admin -H origin:localhost http://localhost:8161/api/jolokia/read/org.apache.activemq:type=Broker,brokerName=localhost,service=Health/CurrentStatus | grep Good```


