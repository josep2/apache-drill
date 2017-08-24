## Docker image for Apache Drill 1.10 in Distributed Mode Built For Kubernetes Deployments ##
Maintainer **Jowanza Joseph**

The following environment variables can be modified and have the following default values:
```
DRILL_LOG_DIR=/var/log/drill
DRILLBIT_LOG_PATH=/var/log/drill/drillbit.log
DRILLBIT_QUERY_LOG_PATH=/var/log/drill/drill-query.log
DRILL_MAX_DIRECT_MEMORY=8G
DRILL_HEAP=4G  
DRILL_CLUSTER=drillbit1
```
The only **compulsory** variable is **ZOOKEEPER** which must be set to the *hostname:port*

The default entrypoint is /opt/drill/apache-drill-1.10.0/bin/drillbit.sh run

This repository is forked from bigstepinncs project.


