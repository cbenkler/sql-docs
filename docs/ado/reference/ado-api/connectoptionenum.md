---
description: "ConnectOptionEnum"
title: "ConnectOptionEnum | Microsoft Docs"
ms.prod: sql
ms.prod_service: connectivity
ms.technology: ado
ms.custom: ""
ms.date: "01/19/2017"
ms.reviewer: ""
ms.topic: conceptual
apitype: "COM"
f1_keywords: 
  - "ConnectOptionEnum"
helpviewer_keywords: 
  - "ConnectOptionEnum enumeration [ADO]"
ms.assetid: bff07eeb-dee3-4e4e-9b2d-d56061ea744d
author: rothja
ms.author: jroth
---
# ConnectOptionEnum
Specifies whether the [Open](./open-method-ado-connection.md) method of a [Connection](./connection-object-ado.md) object should return after the connection is established (synchronously) or before (asynchronously).  
  
|Constant|Value|Description|  
|--------------|-----------|-----------------|  
|**adAsyncConnect**|16|Opens the connection asynchronously. The [ConnectComplete](./connectcomplete-and-disconnect-events-ado.md) event may be used to determine when the connection is available.|  
|**adConnectUnspecified**|-1|Default. Opens the connection synchronously.|  
  
## ADO/WFC Equivalent  
 Package: **com.ms.wfc.data**  
  
|Constant|  
|--------------|  
|AdoEnums.ConnectOption.ASYNCCONNECT|  
|AdoEnums.ConnectOption.CONNECTUNSPECIFIED|  
  
## Applies To  
 [Open Method (ADO Connection)](./open-method-ado-connection.md)