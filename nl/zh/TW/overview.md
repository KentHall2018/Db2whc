---

copyright:
  years: 2014, 2018
lastupdated: "2018-02-27"

---

<!-- Attribute definitions --> 
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# 關於 Db2 Warehouse on Cloud
{: #overview}

在 {{site.data.keyword.dashdblong}} 服務方案中，使用資料倉儲來儲存關聯式資料，包括特殊類型。請使用我們的內建分析或自行連接您的應用程式，來分析您自己的資料，或是從其他雲端服務載入的資料。您可以利用高效能、記憶體內資料庫技術來處理分析工作負載的直欄式表格。{{site.data.keyword.dashdbshort_notm}} Web 主控台會處理一般資料管理作業，例如載入資料，以及像是執行查詢和 R Script 的分析作業。
{: shortdesc}

您也可以將外部應用程式和工具連接到 {{site.data.keyword.dashdbshort_notm}}，並使用它們進一步管理或分析您的資料。例如：
   * 連接 {{site.data.keyword.IBM_notm}} InfoSphere® Data Architect，以設計及部署資料庫綱目。
<!--   * Connect Esri ArcGIS to perform geospatial analytics and map publishing with your data. -->
   * 連接 {{site.data.keyword.IBM_notm}} Cognos® 伺服器，以針對您的資料執行 Cognos 報告。
   * 連接 SQL 型工具，例如 Tableau、Microstrategy 或 Microsoft Excel，以操作或分析您的資料。
   * 連接需要分析資料庫的 {{site.data.keyword.Bluemix_short}} 應用程式。
   * 連接 Aginity Workbench，以將 Netezza® 資料模型和資料移轉到 {{site.data.keyword.dashdbshort_notm}}。

## Db2 Warehouse on Cloud 受管理服務
{: #managed_service}

完整的 {{site.data.keyword.dashdbshort_notm}} 受管理服務處理所有軟體升級、作業系統更新，以及硬體維護。此服務包括全年無休的資料庫及基礎架構性能監視。在硬體故障或軟體失敗的情況下，此服務會自動重新啟動。
{: shortdesc}

## 方案及配置
{: #plans_cfgs}

您可以選擇已針對您需要進行的工作配置和最佳化的 {{site.data.keyword.dashdbshort_notm}} 方案：
{: shortdesc}

   * 嘗試各種事物的入門方案
   * 彈性效能方案，您可以獨立地調整儲存空間及運算資源
   * 小型、中型及大型正式作業方案
   * 適用於平行處理的 MPP 配置
   * 針對高可用性或 Oracle 相容性所配置的方案
   * 以及其他 ...

檢視 {{site.data.keyword.Bluemix}} 型錄中的可用方案：
   * 針對資料倉儲和分析 (OLAP) 工作負載所配置的方案：[{{site.data.keyword.dashdbshort_notm}}](https://console.bluemix.net/catalog/services/db2-warehouse){:new_window}
<!--   * Plans configured for high-speed, transactional processing (OLTP): [{{site.data.keyword.dashdbshort_notm}} for Transactions](https://console.ng.bluemix.net/catalog/services/dashdb-for-transactions-sql-database){:new_window} -->

如果您在型錄中看不到所需要的配置，請與 [{{site.data.keyword.IBM_notm}} 銷售人員 ![外部鏈結圖示](../../icons/launch-glyph.svg "外部鏈結圖示")](https://www.ibm.com/connect/ibm/us/en/?lnk=fcw){:new_window} 聯絡，來討論其他選項。

## 佈建 Db2 Warehouse on Cloud
{: #whse_provision}

{{site.data.keyword.dashdbshort_notm}} 資料庫可以佈建在 {{site.data.keyword.BluSoftlayer_full}} 上，也可以針對 AWS 佈建。
{: shortdesc}

如果您要針對 AWS 佈建資料倉儲，請選取 **MPP Small for AWS** 方案。

<!-- If you want to have the data warehouse provisioned for AWS, select the **{{site.data.keyword.IBM_notm}} {{site.data.keyword.dashdbshort_notm}} for Analytics MPP Small for AWS** plan. -->

<!-- ##dashDB for Transactions
{: #dashDB_tr}

In the {{site.data.keyword.dashdbshort_notm}} for Transactions plans, use the {{site.data.keyword.dashdbshort_notm}} relational database for online transaction processing. You can connect new or existing applications, and you can begin processing transactions and storing your data. With DB2® and Oracle compatibility, you can connect small or large applications and benefit from a managed enterprise-class database system. You can leverage the {{site.data.keyword.dashdbshort_notm}} for Transactions web console to manage users, load data, and get connection information.
{: shortdesc} -->

<!-- ##dashDB web console overview
{: #console_overview}

You can manage your {{site.data.keyword.dashdbshort_notm}} database, analyze your data, and monitor sensitive data with the {{site.data.keyword.dashdbshort_notm}} web console accessible from {{site.data.keyword.Bluemix_notm}}.
{: shortdesc}

Open the web console by clicking the service tile on your application overview page, and then click **Open**.

Single sign-on authentication connects you directly to the web console. You can access connection information from the web console, and the **Downloads** page includes links to client drivers for accessing {{site.data.keyword.dashdbshort_notm}} from remote applications. You can also access sample data and reports.

###Sensitive data reporting

The {{site.data.keyword.dashdbshort_notm}} web console includes a sensitive data reporting feature that detects and monitors sensitive objects in the {{site.data.keyword.dashdbshort_notm}} data warehouse, such as credit card numbers and US Social Security numbers.

To run and view reports that identify columns that contain sensitive data and provide information about connections and activities that access the sensitive data, select **Monitor &gt; Sensitive Data** in the web console. -->


<!-- ##IBM Analytics Services
{: #analytics_services}

For more information about {{site.data.keyword.IBM_notm}} analytics services and finding your local services representative, see: [{{site.data.keyword.IBM_notm}} Analytics Services ![External link icon](../../icons/launch-glyph.svg "External link icon")](http://www.ibm.com/software/data/services/).
{: shortdesc} -->














