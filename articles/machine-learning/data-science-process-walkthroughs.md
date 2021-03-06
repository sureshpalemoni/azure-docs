---
title: Team Data Science Process walkthroughs  | Microsoft Docs
description: Walkthoughs show how to combine cloud and on-premises tools and services into a workflow or pipeline to create an intelligent application.
services: machine-learning
documentationcenter: ''
author: bradsev
manager: jhubbard
editor: cgronlun

ms.assetid: aa63d5a5-25ee-4c4b-9a4c-7553b98d7f6e
ms.service: machine-learning
ms.workload: data-services
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.date: 07/25/2017
ms.author: bradsev

---
# Team Data Science Process walkthroughs
The **end-to-end walkthroughs** itemized here each demonstrate the steps in the Team Data Science Process for **specific scenarios**. They illustrate how to combine cloud, on-premises tools, and services into a workflow or pipeline to create an **intelligent application**. The walkthroughs are grouped by **platform** they use: 

- Spark with PySpark and Scala
- HDInsight (Hadoop)
- Azure Data Lake 
- SQL Server
- SQL Data Warehouse 


## HDInsight Spark using PySpark and Scala

- The [Use Spark on Azure HDInsight](machine-learning-data-science-spark-overview.md) walkthrough uses the Team Data Science Process in a scenario using an [Azure HDInsight Spark cluster](https://azure.microsoft.com/services/hdinsight/) to store, explore, and feature engineer data from the publicly available NYC taxi trip and fare dataset.

- The [Use Scala with Spark on Azure](machine-learning-data-science-process-scala-walkthrough.md) walkthrough shows how to use Scala for supervised machine learning tasks with the Spark machine learning library (MLlib) and SparkML packages on an Azure HDInsight Spark cluster. It walks you through the tasks that constitute the [Data Science Process](http://aka.ms/datascienceprocess): data ingestion and exploration, visualization, feature engineering, modeling, and model consumption. The models built include logistic and linear regression, random forests, and gradient boosted trees.


## HDInsight Hadoop 

- The [Use HDInsight Hadoop clusters](machine-learning-data-science-process-hive-walkthrough.md) walkthrough uses an [Azure HDInsight Hadoop cluster](https://azure.microsoft.com/services/hdinsight/) to store, explore and feature engineer data from a publicly available NYC taxi trip and fare dataset

- The [Use Azure HDInsight Hadoop Clusters on a 1-TB dataset](machine-learning-data-science-process-hive-criteo-walkthrough.md) walkthrough presents a scenario that uses an [Azure HDInsight Hadoop cluster](https://azure.microsoft.com/services/hdinsight/) to store, explore, feature engineer, and down sample data from a publicly available [Criteo](http://labs.criteo.com/downloads/download-terabyte-click-logs/) dataset.


## Azure Data Lake

- The [Use Azure Data Lake for data science](machine-learning-data-science-process-data-lake-walkthrough.md) shows how to use Azure Data Lake to do data exploration and binary classification tasks on a sample of the NYC taxi dataset to predict whether or not a tip is paid by a customer. 


## SQL Server and SQL Data Warehouse 

- The [Use SQL Data Warehouse](machine-learning-data-science-process-sqldw-walkthrough.md) walkthrough shows you how to build and deploy machine learning classification and regression models using SQL Data Warehouse (SQL DW) for a publicly available NYC taxi trip and fare dataset.

- The [Use SQL Server](machine-learning-data-science-process-sql-walkthrough.md) walkthrough shows you build and deploy machine learning classification and regression models using SQL Server and a publicly available NYC taxi trip and fare dataset.

- The [Use SQL Server R Services](https://msdn.microsoft.com/library/mt612857.aspx) walkthrough provides data scientists with a combination of R code, SQL Server data, and custom SQL functions to build and deploy an R model to SQL Server.

- The [Use T-SQL with SQL Server R Services](https://msdn.microsoft.com/library/mt683480.aspx) walkthrough provides SQL programmers with experience building an advanced analytics solution with Transact-SQL using SQL Server R Services to operationalize an R solution.

- The [Use T-SQL with SQL Server Python Services](https://docs.microsoft.com/en-us/sql/advanced-analytics/tutorials/sqldev-in-database-python-for-sql-developers) walkthrough provides SQL programmers with experience building a machine learning solution in SQL Server. It demonstrates how to incorporate Python into an application by adding Python code to stored procedures.

## What's next?
For an overview of topics that walk you through the tasks that comprise the data science process in Azure, see [Data Science Process](http://aka.ms/datascienceprocess). 

