---

copyright:
  years: 2015, 2020
lastupdated: "2020-01-27"

keywords: tutorials, recovery and backup, guides, links to documentation, about 

subcollection: cloudant

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:deprecated: .deprecated}
{:external: target="_blank" .external}

<!-- Acrolinx: 2018-11-08 -->

# About
{: #about}

The tutorials, recovery and backup instructions, and guides provide information about basic and advanced tasks that you use in {{site.data.keyword.cloudantfull}}. 
{: shortdesc} 

## Tutorials
{: #tutorials}

Tutorial | Description 
---------|-------------
[Getting started tutorial](/docs/Cloudant?topic=cloudant-getting-started-with-cloudant){: new_window} | A tutorial that describes how to use Python to create an {{site.data.keyword.cloudant_short_notm}} database and populate that database with a simple collection of data.
[Creating an {{site.data.keyword.cloudant_short_notm}} instance](/docs/Cloudant?topic=cloudant-creating-an-ibm-cloudant-instance-on-ibm-cloud#creating-an-ibm-cloudant-instance-on-ibm-cloud){: new_window} | A tutorial that describes how to create an {{site.data.keyword.cloudant_short_notm}} service instance and where to find your service credentials by using the {{site.data.keyword.cloud_notm}} dashboard.
[Creating an {{site.data.keyword.cloudant_short_notm}} instance by using the {{site.data.keyword.cloud_notm}} CLI](/docs/Cloudant?topic=cloudant-creating-an-ibm-cloudant-instance-on-ibm-cloud-by-using-the-ibm-cloud-cli#creating-an-ibm-cloudant-instance-on-ibm-cloud-by-using-the-ibm-cloud-cli){: new_window} | A tutorial that describes how to create an {{site.data.keyword.cloudant_short_notm}} service instance on {{site.data.keyword.cloud_notm}} by using the {{site.data.keyword.cloud_notm}} CLI.
[Creating and leveraging an {{site.data.keyword.cloudant_short_notm}} Dedicated Hardware plan instance](/docs/Cloudant?topic=cloudant-creating-and-leveraging-an-ibm-cloudant-dedicated-hardware-plan-instance-on-ibm-cloud#creating-and-leveraging-an-ibm-cloudant-dedicated-hardware-plan-instance-on-ibm-cloud){: new_window} | A tutorial that describes how to create an {{site.data.keyword.cloudant_short_notm}} Dedicated Hardware plan instance and how to then provision one or more Standard plan instances to run on it by using either the {{site.data.keyword.cloud_notm}} catalog or the {{site.data.keyword.cloud_notm}} CLI.
[Creating and populating a simple {{site.data.keyword.cloudant_short_notm}} database](/docs/Cloudant?topic=cloudant-creating-and-populating-a-simple-ibm-cloudant-database-on-ibm-cloud#creating-and-populating-a-simple-ibm-cloudant-database-on-ibm-cloud){: new_window} | A tutorial that describes how to use the Python programming language to create an {{site.data.keyword.cloudant_short_notm}} database in your {{site.data.keyword.cloud_notm}} service instance, and populate the database with a simple collection of data.
[Creating an {{site.data.keyword.cloudant_short_notm}} Query](/docs/Cloudant?topic=cloudant-creating-an-ibm-cloudant-query#creating-an-ibm-cloudant-query){: new_window}| A tutorial that describes how to create a database, populate it with documents, create an index, and use the index to query the database.
[Creating a backup](/docs/Cloudant?topic=cloudant-creating-a-backup#creating-a-backup){: new_window} | A tutorial that describes how to use the CouchBackup command-line utility to back up and restore a CouchDB or {{site.data.keyword.cloudant_short_notm}} instance. 

## Recovery and backup
{: #recovery-and-backup}

Guide | Description
------|------------
[Disaster recovery and backup](/docs/Cloudant?topic=cloudant-disaster-recovery-and-backup#disaster-recovery-and-backup){: new_window} | An overview of the automatic capabilities and supported tools that are offered by {{site.data.keyword.cloudant_short_notm}}. 
[Configuring {{site.data.keyword.cloudant_short_notm}} for cross-region disaster recovery](/docs/Cloudant?topic=cloudant-configuring-ibm-cloudant-for-cross-region-disaster-recovery#configuring-ibm-cloudant-for-cross-region-disaster-recovery){: new_window} | A guide that explains that one way to enable disaster recovery is to use [{{site.data.keyword.cloudant_short_notm}} for {{site.data.keyword.cloud_notm}} replication to create redundancy across regions.
[{{site.data.keyword.cloudant_short_notm}} backup and recovery](/docs/Cloudant?topic=cloudant-ibm-cloudant-backup-and-recovery#ibm-cloudant-backup-and-recovery){: new_window} | A guide that describes how to use the backup and recovery tool, CouchBackup. 


## Guides
{: #guides}

Guide | Description
------|------------
[Authorized curl: acurl](/docs/Cloudant?topic=cloudant-authorized-curl-acurl-#authorized-curl-acurl-){: new_window} | A guide to set up `acurl` so you are no longer required to enter your user name and password. 
[CAP Theorem](/docs/Cloudant?topic=cloudant-cap-theorem#cap-theorem){: new_window} | A guide that describes the Eventually Consistent model.
[Conflicts](/docs/Cloudant?topic=cloudant-conflicts#conflicts){: new_window} | A guide that describes how to find and resolve conflicts. 
[CouchApps](/docs/Cloudant?topic=cloudant-couchapps#couchapps){: new_window} | A guide that describes what constitutes a CouchApp.
[Database partitioning](/docs/Cloudant?topic=cloudant-database-partitioning#database-partitioning) | A guide that describes partitioned databases and how to use them. 
[Design document management](/docs/Cloudant?topic=cloudant-design-document-management#design-document-management){: new_window} | A guide that describes what a design document is and how to work with one in {{site.data.keyword.cloudant_short_notm}}.
[Document versioning and MVCC](/docs/Cloudant?topic=cloudant-document-versioning-and-mvcc#document-versioning-and-mvcc){: new_window} | A guide that describes multi-version concurrency control (MVCC) and how it works with {{site.data.keyword.cloudant_short_notm}} databases to ensure that all of the nodes in a database's cluster contain only the newest version of a document.
[Five tips for modeling your data to scale](/docs/Cloudant?topic=cloudant-five-tips-for-modeling-your-data-to-scale#five-tips-for-modeling-your-data-to-scale){: new_window} | A guide that considers the finer points of modeling your application's data to work efficiently on a large scale.
[Grouping related documents together in {{site.data.keyword.cloudant_short_notm}}](/docs/Cloudant?topic=cloudant-grouping-related-documents-together-in-ibm-cloudant#grouping-related-documents-together-in-ibm-cloudant){: new_window} | A guide that outlines some of the factors that are involved in building an e-commerce system that takes advantage of {{site.data.keyword.cloudant_short_notm}}'s strengths, by using concepts that are applicable to many other domains.
[How does {{site.data.keyword.cloudant_short_notm}} work with {{site.data.keyword.cloud_notm}} Resource Groups?](/docs/Cloudant?topic=cloudant-how-does-ibm-cloudant-work-with-ibm-cloud-resource-groups-#how-does-ibm-cloudant-work-with-ibm-cloud-resource-groups-){: new_window} | A guide that covers common questions {{site.data.keyword.cloudant_short_notm}} support receives about this transition.
[How is data stored in {{site.data.keyword.cloudant_short_notm}}?](/docs/Cloudant?topic=cloudant-how-is-data-stored-in-ibm-cloudant-#how-is-data-stored-in-ibm-cloudant-){: new_window} | A guide that describes sharding and how it works in {{site.data.keyword.cloudant_short_notm}}.
[IBM Cloud Identity and Access Management (IAM)](/docs/Cloudant?topic=cloudant-ibm-cloud-identity-and-access-management-iam-#ibm-cloud-identity-and-access-management-iam-){: new_window} | A guide that describes {{site.data.keyword.cloudant_short_notm}}'s integration with {{site.data.keyword.cloud_notm}} Identity and Access Management. 
[JSON](/docs/Cloudant?topic=cloudant-json#json){: new_window} | A guide that describes how {{site.data.keyword.cloudant_short_notm}} uses the JavaScript Object Notation (JSON) for formatting the content and structure of the data and responses. 
[Managing tasks](/docs/Cloudant?topic=cloudant-managing-tasks#managing-tasks){: new_window} | A guide that describes how you can manage whether your tasks progress, or if they finish.
[Migrating to {{site.data.keyword.cloudant_short_notm}}](/docs/Cloudant?topic=cloudant-migrating-to-ibm-cloudant-on-ibm-cloud#migrating-to-ibm-cloudant-on-ibm-cloud){: new_window} | A guide that describes how to migrate to an {{site.data.keyword.cloudant_short_notm}} Lite or Standard plan instance on {{site.data.keyword.cloud_notm}}.
[Replication guide](/docs/Cloudant?topic=cloudant-replication-guide#replication-guide){: new_window} | A guide that introduces {{site.data.keyword.cloudant_short_notm}}’s replication functions, discusses common use cases, and shows how to make your application replicate successfully.
[Replication incrementals](/docs/Cloudant?topic=cloudant-replication-incrementals#replication-incrementals){: new_window} | A guide that describes how to create and restore incremental backups. 

 

