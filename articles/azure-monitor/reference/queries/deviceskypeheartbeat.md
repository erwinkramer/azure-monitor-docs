---
title: Example log table queries for DeviceSkypeHeartbeat
description:  Example queries for DeviceSkypeHeartbeat log table
ms.topic: generated-reference
ms.service: azure-monitor
ms.author: edbaynash
author: EdB-MSFT
ms.date: 04/14/2025

# This file is automatically generated. Changes will be overwritten. Do not change this file directly. 

---

# Queries for the DeviceSkypeHeartbeat table

For information on using these queries in the Azure portal, see [Log Analytics tutorial](/azure/azure-monitor/logs/log-analytics-tutorial). For the REST API, see [Query](/rest/api/loganalytics/query).


### Skype Error  


SurfaceHub Skype error.  

```query
DeviceSkypeHeartbeat
| where State == "Unhealthy" 
| sort by TimeGenerated desc
```

