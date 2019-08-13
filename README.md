
# Apache Solr Opspack

Apache Solr is an open source enterprise search service from the Lucene project. Solr is written in Java and runs as a standalone full-text search server within a servlet container such as Tomcat. Like any service or component in your architecture, you’ll want to monitor it to ensure that it’s available and gather performance data to help with tuning. The Apache Solr Opspack assists in providing scalability for users as well as distributed indexing, replication and load-balanced querying, automated failover/recovery, centralized configuration and more.

## What You Can Monitor

Opsview Monitor contains all the performance metrics needed to monitor and keep your Apache Solr host online. Critical metrics are monitored and alerted on to keep you aware of memory usage, uptime, load averages and more.

## Service Checks

| Service Check | Description |
|:------------- |:----------- |
| JVM memory | JVM Total Memory, Memory Used and Percentage Used. Warning and Critical thresholds are applied to the Percentage Used. |
| System memory | Total Physical Memory, Physical Memory Used and Percentage Used. Warning and Critical thresholds are applied to the Percentage Used. |
| System load average | The System Load Averages. |
| System swap | Total Swap, Swap Used and Percentage Used. Warning and Critical thresholds are applied to the Percentage Used. |
| Uptime | The JVM Uptime. No Warning or Critical threholds. |

## Setup and Configuration

To configure and utilize this Opspack, you simply need to add the 'Application - Apache Solr' Opspack to your Opsview Monitor system.

#### Step 1: Add the Host Template
Add the **Application - Apache HTTP Server** Host Template to your Opsview Monitor host.

> For more information, refer to [Opsview Knowledge Center - Adding Host Templates to Hosts](https://knowledge.opsview.com/docs/host#section-host-templates).

#### Step 2: Apply changes and the system will now be monitored

![View host service checks](docs/img/output.png?raw=true)
