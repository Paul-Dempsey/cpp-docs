---
title: "Switching Between Dialog Box Controls and Code | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology:  
  - "cpp-windows"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "events [C++], viewing for controls"
  - "Windows messages [C++], controls"
  - "messages [C++], viewing for dialog boxes"
  - "Dialog editor, accessing code"
  - "code [C++], switching from Dialog Editor"
  - "controls [C++], jumping to code"
  - "Dialog editor, switching between controls and code"
ms.assetid: 7da73815-b853-4203-ba45-bbe570695122
caps.latest.revision: 9
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
translation.priority.ht: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---
# Switching Between Dialog Box Controls and Code
In MFC applications, you can double-click on dialog box controls to jump to their handler code or to quickly create stub handler functions.  
  
 With a control selected, click the **ControlEvents** button or the **Messages** button in the [Properties window](/visualstudio/ide/reference/properties-window) to view a complete list of Windows messages and events available for the selected item. Choose from the list to create or edit handler functions.  
  
### To jump to code from the dialog editor  
  
1.  Double-click on a control within the dialog box to jump to the declaration for its most-recently implemented message handling function. (For ATL-based dialog classes, you always jump to the constructor definition.)  
  
### To view events for a control  
  
1.  With a control selected, click the **ControlEvents** button in the [Properties window](/visualstudio/ide/reference/properties-window).  
  
    > [!NOTE]
    >  Clicking the **ControlEvents** button when the *dialog box* has focus exposes a list of all the controls in the dialog box, which you can then expand to edit the events for the individual controls.  
  
     When a single control has focus in the dialog box, you can right-click it and select **Add Event Handler** from the shortcut menu. This enables you to specify the class to which the handler is added. For more information, see [Adding an Event Handler](../ide/adding-an-event-handler-visual-cpp.md).  
  
### To view messages for a dialog box  
  
1.  With the dialog box selected, click the **Messages** button in the [Properties window](/visualstudio/ide/reference/properties-window).  
  
 For information on adding resources to managed projects, please see [Resources in Desktop Apps](https://msdn.microsoft.com/library/f45fce5x.aspx) in the *.NET Framework Developer's Guide.* For information on manually adding resource files to managed projects, accessing resources, displaying static resources, and assigning resource strings to properties, see [Creating Resource Files for Desktop Apps](https://msdn.microsoft.com/library/xbx3z216.aspx). For information on globalization and localization of resources in managed apps, see [Globalizing and Localizing .NET Framework Applications](https://msdn.microsoft.com/library/h6270d0z.aspx).  
  
 Requirements  
  
 Win32  
  
## See Also  
 [Dialog Editor](../windows/dialog-editor.md)

