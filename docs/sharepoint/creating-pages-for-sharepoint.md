---
title: "Creating Pages for SharePoint | Microsoft Docs"
ms.custom: ""
ms.date: "02/02/2017"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "office-development"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "VB"
  - "CSharp"
helpviewer_keywords: 
  - "SharePoint development in Visual Studio, master pages"
  - "SharePoint development in Visual Studio, page layouts"
  - "SharePoint development in Visual Studio, content pages"
  - "master pages[SharePoint development in Visual Studio], designing"
  - "content pages[SharePoint development in Visual Studio], designing"
  - "page layouts[SharePoint development in Visual Studio], designing"
ms.assetid: 57678ed1-841f-45de-a1d3-5f9e233bf3ce
caps.latest.revision: 15
author: "kempb"
ms.author: "kempb"
manager: "ghogen"
---
# Creating Pages for SharePoint
  You can create application pages, site pages, master pages and page layouts for a SharePoint site.  
  
 You can create application pages by using a template in Visual Studio. Create site pages, master pages, and page layouts, by using SharePoint Designer. Then, you can import these pages into Visual Studio to use them in a SharePoint project.  
  
 You can also modify the appearance and behavior of pages by using cascading style sheets, ECMAScript, and themes.  
  
## Types of SharePoint Pages  
 The following table describes the four main types of pages that a SharePoint site contains.  
  
|Page Type|Description|  
|---------------|-----------------|  
|Application pages|Create an application page if you want the page to contain custom code or you want the page to be shared across multiple sites. Otherwise, a site page might be the best choice.|  
|Site pages|Create a site page if you want to perform any of the following tasks:<br /><br /> -   Add the page to a SharePoint library.<br />-   Enable the page to host features such as dynamic Web Parts and Web Part Zones.<br />-   Enable users to customize the page by using SharePoint Designer.<br /><br /> Do not create a site page if you want the page to contain custom code. Although you can add custom code to a site page, the code stops running when the user customizes the page by using SharePoint Designer.|  
|Master pages|Create a master page if you want to define a common structure for site pages and application pages.|  
|Page layouts|Page layouts are specific to [!INCLUDE[moss_14_long](../sharepoint/includes/moss-14-long-md.md)] and enable you to further define a common structure for site pages and application pages.|  
  
 For an overview of each type of page, see [Building Block: Pages and the User Interface](http://go.microsoft.com/fwlink/?LinkID=182095), and [Page Layouts and Master Pages](http://go.microsoft.com/fwlink/?LinkID=182096).  
  
## Creating Application Pages  
 You can create application pages in Visual Studio by adding an **Application Page** item to a SharePoint project. You can add controls to the page, and then handle control events by adding code.  
  
 You can set breakpoints in the code file of the page, start the debugger, and test the page on a local SharePoint site without performing any additional configuration steps. For more information, see [Creating Application Pages for SharePoint](../sharepoint/creating-application-pages-for-sharepoint.md).  
  
## Creating Site Pages, Master Pages, and Page Layouts  
 You can create site pages, master pages, and page layouts by using SharePoint Designer. Then, you can import these pages into Visual Studio. Import your pages if you want to take advantage of the deployment or source control features that are available in Visual Studio. For more information, see [Importing Items from an Existing SharePoint Site](../sharepoint/importing-items-from-an-existing-sharepoint-site.md).  
  
 Because it is difficult to modify these pages after you import them, you should design these pages before you import them.  
  
## Creating Cascading Style Sheets, ECMAScript, and Themes  
 Visual Studio does not provide templates for developing Cascading Style Sheets (CSS), ECMAScript (JavaScript, JScript), or theme files for SharePoint sites. You can create these files by using the guidance available in the SharePoint SDK or by using tools such as SharePoint Designer.  
  
 You can add these files to your solution directly or you can import them. In either case, you must create the appropriate mapped folders for each item that you add. For more information about how to create a mapped folder, see [How to: Add and Remove Mapped Folders](../sharepoint/how-to-add-and-remove-mapped-folders.md).  
  
 For more information about creating Cascading Style Sheets, see [Cascading Style Sheets Class Usage in SharePoint Foundation](http://go.microsoft.com/fwlink/?LinkID=182098). For more information about creating JavaScript and JScript files for a SharePoint solution, see [Setting Up a Basic ASPX Page for ECMAScript](http://go.microsoft.com/fwlink/?LinkID=182099). For more information about themes, see [Building Block: Pages and the User Interface](http://go.microsoft.com/fwlink/?LinkID=182095).  
  
## Related Topics  
  
|Title|Description|  
|-----------|-----------------|  
|[Creating Application Pages for SharePoint](../sharepoint/creating-application-pages-for-sharepoint.md)|Describes how to add applications pages: .aspx content that is merged with a SharePoint master page.|  
|[How to: Create an Application Page](../sharepoint/how-to-create-an-application-page.md)|Shows you how to create ASP.NET pages that run on a SharePoint site.|  
|[Walkthrough: Creating a SharePoint Application Page](../sharepoint/walkthrough-creating-a-sharepoint-application-page.md)|Shows you how to design and debug an ASP.NET Web page for a SharePoint site.|  
|[Working with Visual Web Developer](http://msdn.microsoft.com/en-us/9c31f93b-c8fb-4599-9b14-6194ec8c7539)|Describes how to use the designer that appears when you open a Web page in your project.|  
  
  