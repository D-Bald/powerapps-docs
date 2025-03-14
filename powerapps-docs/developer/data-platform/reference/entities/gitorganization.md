---
title: "Git Organization (GitOrganization) table/entity reference (Microsoft Dataverse)"
description: "Includes schema information and supported messages for the Git Organization (GitOrganization) table/entity with Microsoft Dataverse."
ms.date: 11/09/2024
ms.service: powerapps
ms.topic: reference
author: phecke
ms.author: pehecke
search.audienceType: 
  - developer
---

# Git Organization (GitOrganization) table/entity reference



## Messages

The following table lists the messages for the Git Organization (GitOrganization) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Create`<br />Event: False |`POST` /gitorganizations<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `CreateMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.CreateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.CreateMultipleRequest>|
| `Delete`<br />Event: False |`DELETE` /gitorganizations(*gitorganizationid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Retrieve`<br />Event: False |`GET` /gitorganizations(*gitorganizationid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveEntityChanges`<br />Event: False | |<xref:Microsoft.Xrm.Sdk.Messages.RetrieveEntityChangesRequest>|
| `RetrieveMultiple`<br />Event: False |`GET` /gitorganizations<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `Update`<br />Event: False |`PATCH` /gitorganizations(*gitorganizationid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `UpdateMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpdateMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpdateMultipleRequest>|
| `Upsert`<br />Event: False |`PATCH` /gitorganizations(*gitorganizationid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|
| `UpsertMultiple`<br />Event: False |<xref:Microsoft.Dynamics.CRM.UpsertMultiple?displayProperty=nameWithType /> |<xref:Microsoft.Xrm.Sdk.Messages.UpsertMultipleRequest>|

## Properties

The following table lists selected properties for the Git Organization (GitOrganization) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Git Organization** |
| **DisplayCollectionName** | **Git Organizations** |
| **SchemaName** | `GitOrganization` |
| **CollectionSchemaName** | `GitOrganizations` |
| **EntitySetName** | `gitorganizations`|
| **LogicalName** | `gitorganization` |
| **LogicalCollectionName** | `gitorganizations` |
| **PrimaryIdAttribute** | `gitorganizationid` |
| **PrimaryNameAttribute** |`organizationname` |
| **TableType** | `Virtual` |
| **OwnershipType** | `OrganizationOwned` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [GitOrganizationId](#BKMK_GitOrganizationId)
- [OrganizationName](#BKMK_OrganizationName)

### <a name="BKMK_GitOrganizationId"></a> GitOrganizationId

|Property|Value|
|---|---|
|Description|**Unique identifier for entity instances**|
|DisplayName|**Git Organization**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`gitorganizationid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_OrganizationName"></a> OrganizationName

|Property|Value|
|---|---|
|Description|**The name of the Git organization.**|
|DisplayName|**Git Organization Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`organizationname`|
|RequiredLevel|ApplicationRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|1000|




### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   

