---
title: Azure Monitor Logs reference - WOUserAudits
description: Reference for WOUserAudits table in Azure Monitor Logs.
ms.topic: generated-reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: orens
author: osalzberg
ms.date: 04/14/2025

# This file is automatically generated. Changes will be overwritten. Do not change this file directly.
---

# WOUserAudits

Contains all workload orchestration API Server audit logs including the events generated as a result of interactions with any external system or toolchain. These events are useful for monitoring all the interactions with the workload orchestration API server and between workload orchestration and external orchestrated targets, e.g. Kubernetes. Requires Diagnostic Settings to use the Resource Specific destination table.


## Table attributes

|Attribute|Value|
|---|---|
|**Resource types**|microsoft.edge/diagnostics|
|**Categories**|Audit, Azure Resources|
|**Solutions**| LogManagement|
|**Basic log**|Yes|
|**Ingestion-time transformation**|No|
|**Sample Queries**|[Yes](/azure/azure-monitor/reference/queries/wouseraudits)|



## Columns
  
[!INCLUDE [wouseraudits](~/reusable-content/ce-skilling/azure/includes/azure-monitor/reference/tables/wouseraudits-include.md)]
