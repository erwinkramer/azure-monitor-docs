---
title: Example log table queries for AutoscaleEvaluationsLog
description:  Example queries for AutoscaleEvaluationsLog log table
ms.topic: generated-reference
ms.service: azure-monitor
ms.author: edbaynash
author: EdB-MSFT
ms.date: 04/14/2025

# This file is automatically generated. Changes will be overwritten. Do not change this file directly. 

---

# Queries for the AutoscaleEvaluationsLog table

For information on using these queries in the Azure portal, see [Log Analytics tutorial](/azure/azure-monitor/logs/log-analytics-tutorial). For the REST API, see [Query](/rest/api/loganalytics/query).


### Review Autoscale evaluations  


Counts Autoscale evaluations in the last hour.  

```query
AutoscaleEvaluationsLog
| where TimeGenerated > ago(1h)
| summarize count() by ResourceId, Profile, OperationName, EvaluationResult
```

