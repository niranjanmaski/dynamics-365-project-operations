---
# required metadata

title: Set up workflows for Expense management
description: You can set up a workflow process that is used to review and approve travel and expense documents.
author: suvaidya
manager: AnnBe
ms.date: 09/23/2020
ms.topic: article
ms.prod: 
ms.service: dynamics-project-operations
ms.technology: 

# optional metadata

ms.search.form: 
audience: Application User
# ms.devlang: 
ms.reviewer: kfend
ms.search.scope: 
# ms.tgt_pltfrm: 
# ms.custom: 
ms.search.region: 
# ms.search.industry: 
ms.author: shylaw
ms.search.validFrom: 
ms.dyn365.ops.version: 

---

# Set up workflows for Expense management

_**Applies To:** Project Operations for resource/non-stocked based scenarios, Lite deployment - deal to proforma invoicing_

You can set up a workflow process to review and approve travel and expense documents. You can define workflows for expense reports, travel requisitions, and cash advance requests.

A workflow represents a business process and defines how a document flows through the system. The workflow also indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

- **Consistent processes**: You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps ensure that documents are processed and approved in a consistent and efficient manner.
- **Process visibility**: You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.
- **Centralized work list**: Users can view a centralized work list to view the workflow tasks and approvals assigned to them. 

## Workflow types

The following table lists the types of workflows that you can create in **Expense Management**.


|              <strong>Type</strong>              |                   <strong>Use this type to</strong>                   |
|-------------------------------------------------|-----------------------------------------------------------------------|
|   <strong>Expense report auto approval</strong> |            Create approval workflows for expense reports.             |
|  <strong>Expense report auto posting</strong>   |        Create automatic posting workflows for expense reports.        |
|       <strong>Expense line item</strong>        |     Create approval workflows for line items on expense reports.      |
| <strong>Expense line item auto posting</strong> | Create automatic posting workflows for line items on expense reports. |
|       <strong>Travel requisition</strong>       |          Create approval workflows for travel requisitions.           |
|      <strong>Cash advance request</strong>      |         Create approval workflows for cash advance requests.          |
|        <strong>VAT tax recovery</strong>        | Create approval workflows for the recovery of value-added tax (VAT).  |