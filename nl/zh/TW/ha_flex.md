---

copyright:
  years: 2014, 2018
lastupdated: "2018-03-15"

---

<!-- Attribute definitions --> 
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# 高可用性 (HA)：彈性效能方案
{: #ha_flex}

如果發生非預期的節點失效，您的彈性效能 MPP 叢集會在短暫的關閉時間之後回到完整容量，這是因為使用了 IBM Container Service（以 Kubernetes 為基礎）。會使用來自儲存區的節點來移動失效的實體。
{: shortdesc}

## 運算 HA
{: #compute_ha}

任何節點失效都會立即被容器服務偵測到。在失效節點中執行的容器與 Pod，會排定到來自節點儲存區的新節點。在短暫的關閉時間之後，系統便會回到 100% 正常作業。

## 儲存空間 HA
{: #storage_ha}

您的儲存空間配置了雙同位元 RAID6 實作，該實作提供對於在相同 RAID 群組發生雙重磁碟故障的防禦，以確保系統具有高效能和高度可用的儲存空間。

## 網路 HA
{: #net_ha}

藉由使用備援網路介面卡 (NIC) 佈建您的服務，網路連線便成為高度可用。 

如果容器服務偵測到網路問題，Pod 和容器可以在短暫的關閉時間之後自動重新啟動。
