---
title: Example log table queries for AZFWDnsQuery
description:  Example queries for AZFWDnsQuery log table
ms.topic: generated-reference
ms.service: azure-monitor
ms.author: edbaynash
author: EdB-MSFT
ms.date: 04/14/2025

# This file is automatically generated. Changes will be overwritten. Do not change this file directly. 

---

# Queries for the AZFWDnsQuery table

For information on using these queries in the Azure portal, see [Log Analytics tutorial](/azure/azure-monitor/logs/log-analytics-tutorial). For the REST API, see [Query](/rest/api/loganalytics/query).


### DNS proxy logs  


DNS Proxy events. These logs are only available when DNS Proxy is enabled.  

```query
AZFWDnsQuery
| take 100
```

