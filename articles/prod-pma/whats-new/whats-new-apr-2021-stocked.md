---
title: What's new or changed in Project Operations, April 2021 for stocked/production-based scenarios
description: This topic provides information about the quality updates available in the April 2021 release of Project Operations for stocked/production-based scenarios.
author: andchoi
ms.date: 04/22/2021
ms.topic: article
ms.prod:
ms.reviewer: kfend 
ms.author: andchoi
---

# What's new or changed in Project Operations, April 2021 for stocked/production-based scenarios

_**Applies To:** Project Operations for stocked/production based scenarios_

This topic applies to the following Dynamics 365 Project Operations components and versions:

- Project management and accounting in Dynamics 365 Finance environment version 10.0.18
 
### Quality updates
                                                                                                                                                                                  
| Feature area                      | Reference number| Quality update                                                                                                                                                                          |
|-----------------------------------|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Project management and accounting | [534393](https://fix.lcs.dynamics.com/Issue/Details/?bugId=534393) | An error occurs on the **Project sorting** grid.                                                                                                                                                      |
| Project management and accounting | [542850](https://fix.lcs.dynamics.com/Issue/Details/?bugId=542850) | The committed amount is overstated after the unit price and quantity is corrected on a project purchase order.                                                                                    |
| Project management and accounting | [543645](https://fix.lcs.dynamics.com/Issue/Details/?bugId=543645) | The **ProjParameters** variable is declared but never assigned a record buffer before it is used.                                                                                     |
| Project management and accounting | [543674](https://fix.lcs.dynamics.com/Issue/Details/?bugId=543674) | The **ResRollup** tables are deleted when the **Populate project resources across all companies** batch job is executed.                                                                          |
| Project management and accounting | [544417](https://fix.lcs.dynamics.com/Issue/Details/?bugId=544417) | There is an issue when updating the **Project sales price** field on a purchase order using the **Purchase order lines V2** entity.                                                                           |
| Project management and accounting | [547652](https://fix.lcs.dynamics.com/Issue/Details/?bugId=547652) | Depending on the ID numbers, subprojects can't be created.   The following error occurs, “Function Global::int642int has been incorrectly called."                                         |
| Project management and accounting | [484274](https://fix.lcs.dynamics.com/Issue/Details/?bugId=484274) | The customer receives the wrong accounts when invoicing a purchase order with the procurement category and item on same invoice.                                                                      |
| Project management and accounting | [509920](https://fix.lcs.dynamics.com/Issue/Details/?bugId=509920) | Adjusting a project transaction with indirect costs from billable to   non-billable and back to billable isn't correctly clearing the WIP.                                       |
| Project management and accounting | [511274](https://fix.lcs.dynamics.com/Issue/Details/?bugId=511274) | Invoice amounts are incorrect when using retention and total discount in a sales order.                                                                                          |
| Project management and accounting | [511315](https://fix.lcs.dynamics.com/Issue/Details/?bugId=511315) | The address name on the line details isn't changed even when a different transaction type is selected.                                                                           |
| Project management and accounting | [522983](https://fix.lcs.dynamics.com/Issue/Details/?bugId=522983) | Committed costs with an item requirement and purchase order are incorrect in the purchase order invoice process with part product receipt and part invoicing.                       |
| Project management and accounting | [524226](https://fix.lcs.dynamics.com/Issue/Details/?bugId=524226) | When a project's financial dimensions changes, the purchase order header doesn't reflect the changes.                                                                                                  |
| Project management and accounting | [524979](https://fix.lcs.dynamics.com/Issue/Details/?bugId=524979) | The generated **Fixed price project** report is blank.                                                                                                         |
| Project management and accounting | [529445](https://fix.lcs.dynamics.com/Issue/Details/?bugId=529445) | Invoice isn't picking the project ID reference when reviewing the vendor invoices on the **Pay when paid** page.                                                                          |
| Project management and accounting | [529982](https://fix.lcs.dynamics.com/Issue/Details/?bugId=529982) | Timesheet entry is incorrect for a user with restricted access for one legal entity in the **HR manager** role as the category isn't defaulted correctly.                                         |
| Project management and accounting | [530008](https://fix.lcs.dynamics.com/Issue/Details/?bugId=530008) | The original project date isn't considered in the adjustment, which causes an error when the **Use adjustment date as new project date** field is set to **No**.                                             |
| Project management and accounting | [530788](https://fix.lcs.dynamics.com/Issue/Details/?bugId=530788) | When project estimates are calculated using a batch, the results are incorrect.                                                                                                         |
| Project management and accounting | [530834](https://fix.lcs.dynamics.com/Issue/Details/?bugId=530834) | The spent amount on the project contract is not aligned to the on-account amount on the project.                                                                             |
| Project management and accounting | [530883](https://fix.lcs.dynamics.com/Issue/Details/?bugId=530883) | The project accountant and project manager roles can't create an hour journal with an approval group setup.                                                                                 |
| Project management and accounting | [531974](https://fix.lcs.dynamics.com/Issue/Details/?bugId=531974) | Can't post a Microsoft Excel imported Expense journal.                                                                                                                                       |
| Project management and accounting | [532548](https://fix.lcs.dynamics.com/Issue/Details/?bugId=532548) | Vendor transaction reversal from intercompany scenarios, including vendor invoice and expense reports, is allowed.                                                                     |
| Project management and accounting | [533426](https://fix.lcs.dynamics.com/Issue/Details/?bugId=533426) | Project adjustment isn't updating the sales amount correctly with indirect costs.                                                                                                    |
| Project management and accounting | [534869](https://fix.lcs.dynamics.com/Issue/Details/?bugId=534869) | When a credit note for a fixed-priced project invoice is created and it uses the unit of delivery billing rule, the released units aren't available for rebilling. |
| Project management and accounting | [535428](https://fix.lcs.dynamics.com/Issue/Details/?bugId=535428) | A project contract with a different currency doesn't calculate the accounting currency correctly on an Item journal or invoice proposal.                                                   |
| Project management and accounting | [537158](https://fix.lcs.dynamics.com/Issue/Details/?bugId=537158) | Change the project on the purchase order line to transfer an item requirement.                                                                                                                          |
| Project management and accounting | [540603](https://fix.lcs.dynamics.com/Issue/Details/?bugId=540603) | Importing to a project budget from a forecast results in incorrect amounts.                                                                                                                    |
| Project management and accounting | [540622](https://fix.lcs.dynamics.com/Issue/Details/?bugId=5406222) | General ledger entries aren't created when adjusting a transaction from billable to non-billable.                                                                                            |
| Project management and accounting | [540633](https://fix.lcs.dynamics.com/Issue/Details/?bugId=540633) | Project transactions aren't created with pay-when-paid when the feature key, **Enable cost amount calculation feature for project vendor invoice retention term** is turned on.                  |
| Project management and accounting | [541421](https://fix.lcs.dynamics.com/Issue/Details/?bugId=541421) | Multiple issues with the **Create invoice proposal** page.                                                                                                                             |
| Project management and accounting | [543390](https://fix.lcs.dynamics.com/Issue/Details/?bugId=543390) | The **All projects** page doesn’t show the list with the new language code.                                                                                                            |
| Project management and accounting | [543803](https://fix.lcs.dynamics.com/Issue/Details/?bugId=543803) | The unapproved budget amount in the project budget balance is incorrect when the budget is revised more than two times.                                                                |
| Project management and accounting | [543968](https://fix.lcs.dynamics.com/Issue/Details/?bugId=543968) | The **Purchase agreement** page isn't visible in Finance legal entities that are integrated with Project Operations.                                                                               |
| Project management and accounting | [545456](https://fix.lcs.dynamics.com/Issue/Details/?bugId=545456) | The correct voucher date isn't uploaded to the Project hours journal lines.                                                                                                            |
| Project management and accounting | [545878](https://fix.lcs.dynamics.com/Issue/Details/?bugId=545878) | In Project Operations for resource-based scenarios, you can't convert a quote to won because of an integration error.                                                                      |
| Project management and accounting | [546604](https://fix.lcs.dynamics.com/Issue/Details/?bugId=546604) | In Project Operations, you will receive an error message when you try to create an association between a contract line and a project ID because of the check for overlapping contract lines and transaction types.                        |
| Project management and accounting | [546949](https://fix.lcs.dynamics.com/Issue/Details/?bugId=546949) | The **Resource/project validation groups** page has performance issues when there are more than 14,000 records in the **ProjValEmplProjSetup** table.                                                                     |
| Project management and accounting | [547440](https://fix.lcs.dynamics.com/Issue/Details/?bugId=547440) | The **ProjCDSProjectContractEntity** can set the funding source invoice address from a different customer.                                                                                   |
| Project management and accounting | [547606](https://fix.lcs.dynamics.com/Issue/Details/?bugId=547606) | The standard lookup of the resource isn't available after the release of 10.0.15.                                                                                          |
| Project management and accounting | [547831](https://fix.lcs.dynamics.com/Issue/Details/?bugId=547831) | The ledger account and posting type on the purchase order invoice voucher is mismatched for the service item. The project group is set to **Balance** and the ledger account is incorrect.                   |
| Project management and accounting | [550030](https://fix.lcs.dynamics.com/Issue/Details/?bugId=550030) | The activity number isn't shown for a pending vendor invoice, even   though **Block parent activity selection** is set to **No**.                                            |
| Project management and accounting | [550379](https://fix.lcs.dynamics.com/Issue/Details/?bugId=550379) | When you use the navigation path, **Project** > **Budget** > **Revisions** > **New** > **Import**, the system creates a project budget revision for all projects.                                                            |
| Project management and accounting | [550577](https://fix.lcs.dynamics.com/Issue/Details/?bugId=550577) | The wrong posting and general ledger entries occur when adjusting a transaction with different transaction and accounting currencies.                                                                        |
| Project management and accounting | [557376](https://fix.lcs.dynamics.com/Issue/Details/?bugId=557376) | No dimensions are included when creating a posting invoice for a   transaction.                                                                                                   |
| Project management and accounting | [559416](https://fix.lcs.dynamics.com/Issue/Details/?bugId=559416) | The **PurchTotals.purchNewTotalAmount()** method is called when creating a pending vendor invoice, which wasn't linked with any purchase order causing a performance issue.                    |
| Travel and Expense                | [480451](https://fix.lcs.dynamics.com/Issue/Details/?bugId=480451) | There is a posting error related to mileage setup.                                                                                                                                          |
| Travel and Expense                | [522084](https://fix.lcs.dynamics.com/Issue/Details/?bugId=522084) | **Split to personal** for foreign currency expense transactions isn't working.                                                                                                         |
| Travel and Expense                | [523938](https://fix.lcs.dynamics.com/Issue/Details/?bugId=523938) | The expense category drop-down menu is showing incorrect categories regardless if **Delegates** is set up as a resource.                                         |
| Travel and Expense                | [539266](https://fix.lcs.dynamics.com/Issue/Details/?bugId=539266) | You can't save an intercompany expense report because of a Resource/category validation error.                                                                                             |
| Travel and Expense                | [532610](https://fix.lcs.dynamics.com/Issue/Details/?bugId=532610) | The wrong mileage rate calculation in expense report posting has split lines.                                                                                                        |
| Travel and Expense                | [537404](https://fix.lcs.dynamics.com/Issue/Details/?bugId=537404) | You can't post an intercompany expense report when the sales tax is included and the offset account type on the payment method is **Worker**.                                                   |
| Travel and Expense                | [542927](https://fix.lcs.dynamics.com/Issue/Details/?bugId=542927) | Rolled back the changes to the **TrvRequisitionLine** data entity and the unique index associated to the entity.                                                                                            |
| Travel and Expense                | [543239](https://fix.lcs.dynamics.com/Issue/Details/?bugId=543239) | Logging added at specific points in the expense report to support creating and updating source document lines.                                                                                           |
| Travel and Expense                | [544323](https://fix.lcs.dynamics.com/Issue/Details/?bugId=544323) | The wrong subledger journal is offered in intercompany scenarios if the sales tax is posted to the Destination legal entity.                                              |
| Travel and Expense                | [546877](https://fix.lcs.dynamics.com/Issue/Details/?bugId=546877) | In Project Operations, the expense estimate isn't deleted from Finance when it's deleted from Dataverse.                                                                                         |
| Travel and Expense                | [550575](https://fix.lcs.dynamics.com/Issue/Details/?bugId=550575) | When the expense category is a non-project category, the financial dimensions selected on the **Expenses** page aren't copied to the expense report.                                          |

### Regulatory updates
For information about regulatory updates for Finance and Operations apps, see [Regulatory updates](/dynamics365/finance/localizations/regulatory-updates). You can also sign in to LCS and view the planned regulatory updates using the Issue search tool. Issue search lets you search by country, type of feature, and release.


[!INCLUDE[footer-include](../../includes/footer-banner.md)]