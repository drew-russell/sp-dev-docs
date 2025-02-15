---
title: Programming models in SharePoint
description: Describes programming models in SharePoint and provides links to related articles about SharePoint development.
ms.date: 06/13/2022
ms.prod: sharepoint
ms.assetid: 061985ec-6129-4e91-991b-a72488ce1d34
ms.localizationpriority: high
---



# Programming models in SharePoint

You can develop applications for the SharePoint platform in many ways. These applications can be usefully categorized into the following groups based on the tools used to create them, the programming models used to develop them, the methods by which they are packaged and deployed, the methods by which they are marketed, and the devices on which they run.
  

- SharePoint Framework

- SharePoint Add-ins
    
- SharePoint publishing sites
    
- SharePoint farm solutions
    
- Mobile add-ins for SharePoint
    
- Reusable components for SharePoint
    
  
These categories are  *not*  mutually exclusive. For example, you can develop a publishing site as an SharePoint Add-in. The following sections define these categories and guide you to the documentation for each.

## SharePoint Framework
<a name="SPFx"> </a>

The SharePoint Framework (SPFx) is a page and web part model that provides full support for client-side SharePoint development, easy integration with SharePoint data, and support for open source tooling. With the SharePoint Framework, you can use modern web technologies and tools in your preferred development environment to build productive experiences and apps that are responsive and mobile-ready from day one. The SharePoint Framework works for SharePoint Online and soon also for on-premises (SharePoint 2016 Feature Pack 2). For more information, see  [Overview of the SharePoint Framework](../spfx/sharepoint-framework-overview.md).
  

## Add-ins for SharePoint
<a name="Apps"> </a>

A SharePoint Add-in is similar to an add-in on a mobile device. It is a stand-alone productivity solution that does a small number of related tasks, installs easily, and uninstalls cleanly. Users can discover and download SharePoint Add-ins from a public SharePoint add-in store or from their organization's corporate add-in catalog. A SharePoint Add-in can include classic SharePoint components such as lists, custom website pages, web parts, workflows, and content types. But an SharePoint Add-in can also surface a remote web application and remote data in SharePoint. A SharePoint Add-in can also include both SharePoint and remote components. SharePoint Add-ins are very safe applications whose custom logic is always shifted "up" to the cloud or "down" to the client computers. It never runs on the SharePoint servers.
  
    
    
For an introduction to the model for SharePoint Add-ins, see  [SharePoint Add-ins](https://msdn.microsoft.com/library/cd1eda9e-8e54-4223-93a9-a6ea0d18df70%28Office.15%29.aspx). For more information, see  [SharePoint Add-ins compared with SharePoint solutions](sharepoint-add-ins-compared-with-sharepoint-solutions.md), and  [Choose the right API set in SharePoint](choose-the-right-api-set-in-sharepoint.md).
  
    
    

## SharePoint publishing sites
<a name="ECM"> </a>

SharePoint publishing sites provide large-scale content publishing with a high degree of maintainability and regulation compliance. They also provide management of documents, records, taxonomy, and content types. For more information, see  [Build sites for SharePoint](build-sites-for-sharepoint.md).
  
    
    

## SharePoint farm solutions
<a name="Solutions"> </a>

SharePoint farm solutions are trusted SharePoint extensions whose custom logic calls the SharePoint server object model and runs with full trust on the SharePoint servers. These solutions are primarily for custom administrative extensions of SharePoint, such as timer jobs, custom Windows PowerShell commands, and extensions of Central Administration. Farm solutions are distributed as SharePoint solution packages that farm administrators upload to a farm-wide storage location from which they can be deployed. Components in farm solutions can have farm, web application, site collection, or website scope. For more information, see  [Build farm solutions in SharePoint](build-farm-solutions-in-sharepoint.md).
  
    
    

## Mobile add-ins for SharePoint
<a name="Mobile"> </a>

Windows Phone apps, and apps built on non-Microsoft mobile platforms, can access SharePoint websites and data. Tools for building Windows Phone apps that interact with SharePoint are available for installation on Visual Studio 2010 and Visual Studio 2012. A SharePoint client managed API just for use on Windows Phone devices is available. Mobile devices, including non-Microsoft devices, can also access SharePoint data through SharePoint REST/OData endpoints. For more information, see  [Build Windows Phone apps that access SharePoint](build-windows-phone-apps-that-access-sharepoint.md).
  
    
    

## Reusable components for SharePoint
<a name="Reuse"> </a>

The SharePoint platform and Visual Studio 2012 enable encapsulation and reuse of application elements, including elements created with code, script, and XML markup. For more information, see  [Build reusable components for SharePoint](build-reusable-components-for-sharepoint.md).
  
    
    

## In this section
<a name="Reuse"> </a>


-  [Build sites for SharePoint](build-sites-for-sharepoint.md)
    
  
-  [Build farm solutions in SharePoint](build-farm-solutions-in-sharepoint.md)
    
  
-  [Build Windows Phone apps that access SharePoint](build-windows-phone-apps-that-access-sharepoint.md)
    
  
-  [Build reusable components for SharePoint](build-reusable-components-for-sharepoint.md)
    
  

## See also
<a name="SP15devinSP_addlresources"> </a>

-  [Set up your SharePoint Framework development environment](../spfx/set-up-your-development-environment.md)

-  [Set up a general development environment for SharePoint](set-up-a-general-development-environment-for-sharepoint.md)
    
  
-  [Add SharePoint capabilities](add-sharepoint-capabilities.md)
    
  
-  [Accessibility in SharePoint](accessibility-in-sharepoint.md)
    
  
