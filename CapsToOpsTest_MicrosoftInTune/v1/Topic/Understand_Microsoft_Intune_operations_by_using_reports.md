---
description: na
keywords: na
pagetitle: Understand Microsoft Intune operations by using reports
search: na
ms.date: 2015-11-17
ms.service: microsoft-intune
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 857309c2-61c9-4c22-becf-4839fedeaece
ms.author: 03258b9b-2cea-4654-ab05-a27214174f4b
---
# Understand Microsoft Intune operations by using reports
Use the information in this topic to help you create and manage [!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)] reports that provide information about software, hardware, and software licenses in your organization.

## Using Reports
[!INCLUDE[wit_firstref](../Token/wit_firstref_md.md)] reports provide information about software, hardware, and software licenses in your organization. Reports can help you confirm current needs and forecast future spending. The **Reports** workspace gives you the tools to create and manage reports. For more information about reports, see [Understand Microsoft Intune operations by using reports](../Topic/Understand_Microsoft_Intune_operations_by_using_reports.md).

### Report types

|Report type <br /> <br />|Description <br /> <br />|
|---------------|---------------|
|**Update reports** <br /> <br />|Show the software updates that succeeded on computers in your organization, in addition to the updates that failed, are pending, or are needed. For more information on software updates, see [Keep Windows PCs up to date with software updates in Microsoft Intune](../Topic/Keep_Windows_PCs_up_to_date_with_software_updates_in_Microsoft_Intune.md). <br /> <br />|
|**Detected Software reports** <br /> <br />|Show software installed on computers in your organization and includes the software versions. You can filter the information that displays based on the software publisher and the software category. You can expand the updates in the list to show more detail (such as the computers on which it is installed) by clicking the directional arrow next to the list item. **Note:** When you retire computers or change their group memberships in [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)], it can take several minutes for these changes to be reflected in the detected software report. For the most accurate software inventory data, wait a few minutes after retiring computers or changing their group memberships before you run a detected software report that includes those computers. <br />|
|**Computer Inventory reports** <br /> <br />|Show information about managed computers in your organization. Use this report to plan hardware purchases and to understand more about the hardware needs of users in your organization. For more information on working with managed computers, see [Manage Windows PCs with Microsoft Intune](../Topic/Manage_Windows_PCs_with_Microsoft_Intune.md). <br /> <br />|
|**Mobile Device Inventory reports** <br /> <br />|Show information about the mobile devices in your organization. You can filter the information that displays based on groups, whether the device is a jailbroken or rooted device, and by operating system. <br /> <br />|
|**License Purchase reports** <br /> <br />|Show the software titles for all licensed software in selected license groups, based on their licensing agreements. The available filters are: <br /> <br /><ul><li>**All agreements** shows all licensed software products that are managed by [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)]. </li><li>**Volume licensing agreements** shows only VLSC software products. </li><li>**Other software licensing agreements** shows software products that are managed outside VLSC. </li> </ul> **Note:** If software license information has not refreshed in more than 24 hours, it will refresh when you generate a license report. <br />A license report is not an exact calculation of software titles that are being used, or proof of compliance with agreements. The report is a tool to help you make licensing decisions for your organization. [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)] might not detect some products that are able to have a Microsoft volume license. <br /> <br />|
|**License installation reports** <br /> <br />|Compare installed software on computers in your organization with your current license agreement coverage according to the  Volume Licensing Service Center (VLSC). Filters include: <br /> <br /><ul><li>**All agreements** shows all licensed software products that are managed by [!INCLUDE[wit_nextref](../Token/wit_nextref_md.md)]. </li><li>**Volume licensing agreements** shows only VLSC software products. </li><li>**Other software licensing agreements** shows software products that are managed outside VLSC. </li> </ul>|
|**Terms and Conditions reports** <br /> <br />|Shows whether users accepted terms and conditions you deployed, and which version they accepted. You can specify up to 10 users whose acceptance of any terms and conditions that were deployed to them are shown, or show the acceptance status for a particular term deployed to them. <br /> <br />|
|**Noncompliant Apps reports** <br /> <br />|Show information about the users who have apps installed that are on your lists of compliant and noncompliant apps. Use this report to find users and devices that are not in compliance with your company app policies. <br /> <br />|
|**Certificate Compliance reports** <br /> <br />|Shows which certificates have been issued to users and devices through the Network Device Enrollment Service. Use this report to find certificates that are issued, expired, and revoked. <br /> <br />|
|**Device History reports** <br /> <br />|Shows a historical log of retire, wipe, and delete actions. Use this report to see who initiated actions on devices in the past. <br /> <br />|
|**Mac OS X Hardware Report** <br /> <br />|Displays hardware details for all enrolled Mac OS X devices in the groups you select. For information about the hardware inventory collected from these devices, see [Understand your devices with inventory in Microsoft Intune](../Topic/Understand_your_devices_with_inventory_in_Microsoft_Intune.md). <br /> <br />|
|**Mac OS X Software Report** <br /> <br />|Displays the software installed on all Mac OS X devices in the groups you selected. The report lists: <br /> <br /><ul><li>The software name (as a bundle ID) </li><li>The short version (or friendly) name </li><li>The version </li><li>The number of devices with the software installed </li> </ul>|

#### To create a report

1. In the [!INCLUDE[wit_adminconsole](../Token/wit_adminconsole_md.md)], click **Reports**, and then click the report type you want to generate, described on the table above.

2. On the **Create New Report** page, accept the default values or customize them to filter the results that will be returned by the report. For example, you could select that only software published by Microsoft will be displayed in the detected software report.

3. Click **View Report** to open the report in a new window.

To sort the report by any of the displayed columns, click the column heading. Additionally, some reports allow you to expand items in the list to show more detail.

## More report actions
In addition, reports support the following actions:

|Action <br /> <br />|More information <br /> <br />|
|----------|--------------------|
|**Print** <br /> <br />|In an open report, click the print icon and follow the instructions. <br /> <br />|
|**Export** <br /> <br />|In an open report, click the export icon and follow the instructions. You can export a report to comma separated values (.csv) or HTML format. <br /> <br />|
|**Save** <br /> <br />|On the **Create New Report** page, each user can save up to 100 reports. Configure the report parameters to your requirements and then click **Save**, or **Save As** if you want to use a different name. <br /> <br />|
|**Load** <br /> <br />|On the **Create New Report** page, click **Load** to retrieve any previously saved sets of report parameters. <br /> <br />|
|**Delete** <br /> <br />|In the **Reports** workspace, select the desired report type, click **Load**, and then, in the list of reports, click the delete (x) icon next to the report. <br /> <br />|

## See Also
[Monitoring and reports with Microsoft Intune](../Topic/Monitoring_and_reports_with_Microsoft_Intune.md)

