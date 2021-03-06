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

# Db2 Warehouse on Cloud 정보
{: #overview}

{{site.data.keyword.dashdblong}} 서비스 플랜에서는 데이터 웨어하우스를 사용하여 특수 유형을 포함한 관계형 데이터를 저장할 수 있습니다. 기본 제공 분석을 사용하거나 사용자의 앱에 연결하여 다른 클라우드 서비스에서 로드한 데이터 또는 사용자 고유의 데이터를 분석하십시오. 분석 워크로드에 대한 종횡배열 테이블이 있는 고성능, 인메모리 데이터베이스 기술을 활용할 수 있습니다. {{site.data.keyword.dashdbshort_notm}} 웹 콘솔은 데이터 로드와 같은 일반 데이터 관리 태스크, 쿼리 및 R 스크립트 실행과 같은 분석 태스크를 처리합니다.
{: shortdesc}

외부 애플리케이션과 도구를 {{site.data.keyword.dashdbshort_notm}}에 연결하고 이 기능들을 사용하여 데이터를 더 정교하게 관리, 분석할 수도 있습니다. 예를 들어, 다음과 같습니다.
   * {{site.data.keyword.IBM_notm}} InfoSphere® Data Architect를 연결하여 데이터베이스 스키마를 디자인하고 배치합니다.
<!--   * Connect Esri ArcGIS to perform geospatial analytics and map publishing with your data. -->
   * {{site.data.keyword.IBM_notm}} Cognos® 서버를 연결하여 데이터에 대해 Cognos 보고서를 실행합니다.
   * Tableau, Microstrategy 또는 Microsoft Excel 등의 SQL 기반 도구를 연결하여 데이터를 조작하거나 분석합니다.
   * 분석 데이터베이스가 필요한 {{site.data.keyword.Bluemix_short}} 애플리케이션을 연결합니다.
   * Aginity Workbench를 연결하여 Netezza® 데이터 모델과 데이터를 {{site.data.keyword.dashdbshort_notm}}로 마이그레이션합니다.

## Db2 Warehouse on Cloud 관리 서비스
{: #managed_service}

{{site.data.keyword.dashdbshort_notm}}의 완전한 관리 서비스는 소프트웨어 업그레이드, 운영 체제 업데이트 및 하드웨어 유지보수 모두를 처리합니다. 서비스에는 데이터베이스 및 인프라의 24x7 상태 모니터링이 포함됩니다. 하드웨어 또는 소프트웨어 장애가 발생하는 경우 서비스는 자동으로 다시 시작됩니다.
{: shortdesc}

## 플랜 및 구성
{: #plans_cfgs}

수행해야 하는 작업에 맞게 구성되고 최적화된 {{site.data.keyword.dashdbshort_notm}} 플랜을 선택할 수 있습니다.
{: shortdesc}

   * 테스트를 위한 엔트리 플랜
   * 스토리지 및 컴퓨팅 리소스를 독립적으로 스케일링할 수 있는 Flex Performance 플랜
   * 프로덕션을 위한 소규모, 중간 규모, 대규모 플랜
   * 병렬 처리를 위한 MPP 구성
   * 고가용성 또는 Oracle 호환성을 위해 구성된 플랜
   * 기타...

{{site.data.keyword.Bluemix}} 카탈로그에서 사용 가능한 플랜 보기:
   * 데이터 웨어하우스 및 분석(OLAP) 워크로드에 대해 구성된 플랜: [{{site.data.keyword.dashdbshort_notm}}](https://console.bluemix.net/catalog/services/db2-warehouse){:new_window}
<!--   * Plans configured for high-speed, transactional processing (OLTP): [{{site.data.keyword.dashdbshort_notm}} for Transactions](https://console.ng.bluemix.net/catalog/services/dashdb-for-transactions-sql-database){:new_window} -->

카탈로그에서 필요한 구성을 찾을 수 없는 경우 [{{site.data.keyword.IBM_notm}} 영업 팀 ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")](https://www.ibm.com/connect/ibm/us/en/?lnk=fcw){:new_window}에 문의하여 다른 옵션에 대해 논의하십시오.

## Db2 Warehouse on Cloud의 프로비저닝
{: #whse_provision}

{{site.data.keyword.dashdbshort_notm}} 데이터베이스는 {{site.data.keyword.BluSoftlayer_full}} 및 AWS용으로 프로비저닝할 수 있습니다.
{: shortdesc}

데이터 웨어하우스를 AWS용으로 프로비저닝하려는 경우 **MPP Small for AWS** 플랜을 선택하십시오.

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














