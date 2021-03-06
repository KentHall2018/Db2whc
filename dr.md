---

copyright:
  years: 2014, 2018
lastupdated: "2018-10-22"

---

<!-- Attribute definitions --> 
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:pre: .pre}

# Disaster recovery (DR)
{: #dr}

If your data warehouse instance is deployed in a data center that suffers a significant data center outage with an expected downtime of more than 8 hours, you will be sent a request to allow service operators to fail over your instance to another data center before disaster recovery actions can begin.
{: shortdesc}

A Db2 backup of your database is done every day. Daily backups are stored in the IBM Cloud Object Storage service from which it is replicated to multiple availability zones. If something should happen to your primary data center, our service operators will work with you to stand up your recovered database in a secondary data center.

## **Brazil: Supplementary Rule 14** (applies to systems provisioned for the Brazilian federal government)
{: #rule_14}

At this time, the disaster recovery (DR) option for Db2 Warehouse on Cloud offerings is not available in Brazil for the federal government due to Supplementary Rule 14.

