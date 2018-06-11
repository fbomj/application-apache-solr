
# Apache Solr Opspack

Apache Solr is an open source enterprise search service from the Lucene project. Solr is written in Java and runs as a standalone full-text search server within a servlet container such as Tomcat. Like any service or component in your architecture, you’ll want to monitor it to ensure that it’s available and gather performance data to help with tuning. The Apache Solr Opspack assists in providing scalability for users as well as distributed indexing, replication and load-balanced querying, automated failover/recovery, centralized configuration and more.

## What You Can Monitor

Opsview Monitor contains all the performance metrics needed to monitor and keep your Apache Solr host online. Critical metrics are monitored and alerted on to keep you aware of memory usage, uptime, load averages and more.

## Service Checks

| Service Check |
|:------------- |
| JVM memory |
| System memory |
| System load average |
| System swap |
| Uptime |

## Setup and Configuration

To configure and utilize this Opspack, you simply need to add the 'Application - Apache Solr' Opspack your Opsview Monitor system.

Step 1: Add the host template

![Add Opspack to host](/docs/img/add_apache_solr_host.png?raw=true)

Step 2: Reload and the system will now be monitored

![View host service checks](/docs/img/view_apache_solr_service_checks.png?raw=true)
