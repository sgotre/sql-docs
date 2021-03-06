---
title: "Using Transactions | Microsoft Docs"
ms.custom: ""
ms.date: "03/14/2017"
ms.prod: "sql-non-specified"
ms.prod_service: "database-engine"
ms.service: ""
ms.component: "smo"
ms.reviewer: ""
ms.suite: "sql"
ms.technology: 
  - "docset-sql-devref"
ms.tgt_pltfrm: ""
ms.topic: "reference"
helpviewer_keywords: 
  - "SQL Server Management Objects, transactions"
  - "transactions [SMO]"
  - "SMO [SQL Server], transactions"
ms.assetid: 399aded8-bee3-4cfb-a671-1877c7d0de9f
caps.latest.revision: 37
author: "JennieHubbard"
ms.author: "jhubbard"
manager: "jhubbard"
ms.workload: "Inactive"
---
# Using Transactions
[!INCLUDE[appliesto-ss-xxxx-xxxx-xxx-md](../../../includes/appliesto-ss-xxxx-xxxx-xxx-md.md)]
  In [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] Management Objects (SMO), transaction processing is achieved through the connection to the instance of [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] by using the <xref:Microsoft.SqlServer.Management.Common.ServerConnection> object. The <xref:Microsoft.SqlServer.Management.Common.ServerConnection> object is referenced by the <xref:Microsoft.SqlServer.Replication.ReplicationObject.ConnectionContext%2A> property of the <xref:Microsoft.SqlServer.Management.Smo.Server> object when the connection is established. Methods such as <xref:Microsoft.SqlServer.Management.Common.DataTransferProgressEventType.StartTransaction>, <xref:Microsoft.SqlServer.Management.Common.ServerConnection.RollBackTransaction%2A>, and <xref:Microsoft.SqlServer.Management.Common.ServerConnection.CommitTransaction%2A> belong to the <xref:Microsoft.SqlServer.Management.Smo.Server.ConnectionContext%2A> object property.  
  
## See Also  
 [Creating SMO Programs](../../../relational-databases/server-management-objects-smo/create-program/creating-smo-programs.md)  
  
  
