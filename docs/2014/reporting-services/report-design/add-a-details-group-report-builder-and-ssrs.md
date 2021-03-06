---
title: "Add a Details Group (Report Builder and SSRS) | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "reporting-services-native"
ms.tgt_pltfrm: ""
ms.topic: conceptual
ms.assetid: 5ef8efba-6d48-4aeb-a3b9-a02ba5a44614
caps.latest.revision: 6
author: maggiesMSFT
ms.author: maggies
manager: craigg
---
# Add a Details Group (Report Builder and SSRS)
  The detail data from a report dataset is specified as a group with no group expression. Add a detail group to an existing tablix data region when you want to display the detail data for a matrix, add back detail data that you have deleted from a table or list, or to add additional detail groups. For more information about groups, see [Understanding Groups &#40;Report Builder and SSRS&#41;](understanding-groups-report-builder-and-ssrs.md).  
  
> [!NOTE]  
>  [!INCLUDE[ssRBRDDup](../../includes/ssrbrddup-md.md)]  
  
### To add a details group to a tablix data region  
  
1.  On the design surface, click anywhere in a tablix data region to select it. The Grouping pane displays the row and column groups for the selected data region.  
  
2.  In the Grouping pane, right-click a group that is an innermost child group. Click **Add Group**, and then click **Child Group**. The **Tablix Group** dialog box opens.  
  
3.  In **Group expression**, leave the expression blank. A details group has no expression.  
  
4.  Select **Show detail data**.  
  
5.  [!INCLUDE[clickOK](../../includes/clickok-md.md)]  
  
     A new details group is added as a child group in the Grouping pane, and the row handle for the group you selected in step 1 displays the details group icon. For more information about handles, see [Tablix Data Region Cells, Rows, and Columns &#40;Report Builder&#41; and SSRS](tablix-data-region-cells-rows-and-columns-report-builder-and-ssrs.md).  
  
## See Also  
 [Add or Delete a Group in a Data Region &#40;Report Builder and SSRS&#41;](add-or-delete-a-group-in-a-data-region-report-builder-and-ssrs.md)   
 [Understanding Groups &#40;Report Builder and SSRS&#41;](understanding-groups-report-builder-and-ssrs.md)   
 [Tablix Data Region &#40;Report Builder and SSRS&#41;](../tablix-data-region-report-builder-and-ssrs.md)   
 [Tables &#40;Report Builder  and SSRS&#41;](tables-report-builder-and-ssrs.md)   
 [Matrices &#40;Report Builder and SSRS&#41;](create-a-matrix-report-builder-and-ssrs.md)   
 [Lists &#40;Report Builder and SSRS&#41;](create-invoices-and-forms-with-lists-report-builder-and-ssrs.md)   
 [Tables, Matrices, and Lists &#40;Report Builder and SSRS&#41;](tables-matrices-and-lists-report-builder-and-ssrs.md)  
  
  
