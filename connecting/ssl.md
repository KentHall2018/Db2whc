---

copyright:
  years: 2014, 2018
lastupdated: "2018-09-25"

---

<!-- Attribute definitions --> 
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# Secure Sockets Layer (SSL) support

The {{site.data.keyword.dashdbshort_notm}} database uses a certificate for SSL connections that is issued by a third-party digital certificate authority (CA). 
{: shortdesc}

The CA certificate is part of the Db2 driver package. If your application connects with a driver from the Db2 driver package, you do not need to download the certificate separately. You can download the Db2 driver package from the web console.

However, if your application has its own driver, you might need to download the certificate separately. You can download the certificate from the web console.

Secure Sockets Layer (SSL) is a security protocol that provides communication privacy. SSL enables client and server applications to communicate in a way that is designed to prevent eavesdropping, tampering, and message forgery. SSL-enabled client applications use standard encryption techniques to help ensure secure communication.

Configuring your applications to connect to your {{site.data.keyword.dashdbshort_notm}} database with SSL depends on your company policy. Both the standard and the SSL protocols that you can use to connect to the database transmit user names and passwords as encrypted data. If you want to ensure complete end-to-end security, transmit all database information, including sensitive data and metadata, through an SSL connection. Administrators can make SSL connections mandatory by changing a setting on the web console.


