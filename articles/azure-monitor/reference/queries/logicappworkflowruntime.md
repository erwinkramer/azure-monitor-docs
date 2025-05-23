---
title: Example log table queries for LogicAppWorkflowRuntime
description:  Example queries for LogicAppWorkflowRuntime log table
ms.topic: generated-reference
ms.service: azure-monitor
ms.author: edbaynash
author: EdB-MSFT
ms.date: 04/14/2025

# This file is automatically generated. Changes will be overwritten. Do not change this file directly. 

---

# Queries for the LogicAppWorkflowRuntime table

For information on using these queries in the Azure portal, see [Log Analytics tutorial](/azure/azure-monitor/logs/log-analytics-tutorial). For the REST API, see [Query](/rest/api/loganalytics/query).


### Count of failed workflow operations from Logic App Workflow Runtime  


Count of failed workflow operations from Logic App Workflow Runtime in selected time range for each workflow.  

```query
LogicAppWorkflowRuntime
| where Status == "Failed"
| summarize count() by WorkflowName
```

