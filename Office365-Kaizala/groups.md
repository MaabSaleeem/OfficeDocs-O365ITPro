---
title: Kaizala groups
ms.author: chucked
author: chuckedmonson
manager: serdars
ms.date: 8/21/2018
ms.audience: Admin
ms.topic: article
ms.service: Kaizala
ms.custom: Kaizala
localization_priority: Normal
search.appverid:
- MET150
- MOE150
- MED150
- MBS150
ms.assetid: 858bead0-f99b-4215-83c6-b8812bbe3edd
description: Learn how to send instant messages, pictures, and documents to groups of Kaizala users.
---

# Kaizala groups

With Microsoft Kaizala, you can send instant messages, pictures and documents to other Kaizala users. You can also create Kaizala Actions (like polls and surveys) and send them to an individual user or a group. You can create Kaizala groups and add users to these groups individually or in bulk. The groups may be created either from the mobile app or through the Kaizala management portal, but the bulk creation and management capabilities are only available through the latter.
  
Check out [Kaizala users](users.md) for information about adding users to Kaizala Groups. 
  
## Kaizala groups

There are two type of Kaizala groups:
  
![Screenshot: Kaizala organization groups view](media/c05e9bd2-05cb-4178-a44a-053e01db36bc.png)
  
- **Kaizala organization groups** These groups belong to your organization and are created via the Kaizala management portal. If these Kaizala groups were created through the mobile app, the group admins can link them to the organization through the **Settings** page or from the private groups tab. Kaizala group admins can only manage the groups that they are admins of. However, Office 365 global admins will have access and ability to manage all organization groups, even if they aren't a member or admin of any Kaizala group. 
    
- **Kaizala private groups** These are groups that aren't linked to any organization and are created via the mobile app. Kaizala private groups can't be managed via the Kaizala management portal. Only Kaizala group members and Kaizala group admins can view or manage these groups. To be able to manage these groups, the Kaizala group admin has to link them to an organization group. 
    
## Create Kaizala groups

Follow the steps below to create a new Kaizala group:
  
- On the Kaizala management portal, from the left navigation bar, choose **Groups**, and then **Create Group**. Enter group name and click or tap **Create**. 
    
    ![Screenshot: Enter the name to create a new Kaizala group](media/f913453e-6a66-45bd-a51c-114ebf5be0d7.png)
  
- On the **Users** tab, after making sure that the phone numbers are of the right region, enter a phone number for each user you want to add to this Kaizala Group. You can also enter a list of comma-separated phone numbers in the text box. Click or tap **Add users** to complete. For example, to add 3 users, enter: **99885544, 99885543, 99885542**. 
    
    ![Screenshot: Add users to Kaizala groups](media/d71f75ba-24bb-443c-8cfe-f46a4c95d9b3.png)
  
Once you've added users to a Kaizala Group, you can start sending surveys, polls and other actions via the mobile app. Check out [creating a Kaizala Action](actions.md) for more details. 
  
## Add multiple user phone numbers to a Kaizala group

If you want to add several users without using the comma separated list, you can do so using **Bulk upload**. There are two types of groups: 
  
- **User Group Mapping** Use this CSV template file to enter the group name, users' phone numbers and user type. You can add multiple groups at a time. The CSV template file contains the instructions and examples. Read the instructions carefully before filling and uploading the file. This file is mandatory and must be uploaded before proceeding to the next step. 
    
- **Parent Group Mapping** Use this CSV template file to define the group hierarchy. Parent group name and child group name can be provided in the list to setup the groups according to the required organization structure. This file is optional. If a corresponding group name doesn't exist in the template CSV file, then that group is ignored in the parent group mapping file. 
    
![Screenshot: Bulk add users to Kaizala](media/8f4f5b63-ae6e-4aac-959f-a9022612a058.png)
  
You can add these groups and users all at once from an Excel spreadsheet or other file saved in CSV format. [Add several users at the same time to Office 365 - Admin Help](https://support.office.com/article/1f5767ed-e717-4f24-969c-6ea9d412ca88#__toc316652088)
  
1. Click or tap **Groups**, and then click or tap **Bulk Upload Users**. 
    
2. On the **Bulk Upload Users** page, first download the **User Group Mapping** CSV template file and follow the steps to add your groups and user phone numbers. If you want to define group hierarchy, download and use the **Parent Group Mapping** CSV template file. Save the file to a location that you'll remember. 
    
3. After you've saved the file, on the **Bulk Upload Users** page, select the file you saved above, and click **Upload**. 
    
    > [!NOTE]
    > If there are problems with the file, the problem is displayed in the panel. Click on the job timestamp link to see the detailed logs. 
  
4. If there aren't any problems with the file, click **Upload** to upload your groups and users info. 
    
## Add a Kaizala subgroup

1. On the Kaizala management portal, from the left navigation bar, choose **Groups**, and then choose a group from the dropdown list. Click or tap **Add Group**. 
    
    ![Screenshot: Add a Kaizala  sub-group to a parent group](media/890765a2-9e2e-409f-88fa-0e478dfeb0c6.png)
  
### Remove a Kaizala subgroup

1. On the Kaizala management portal, from the left navigation bar, choose **Groups**, and then choose a group from the dropdown list. Click or tap **Remove**. 
    
    ![Screenshot: Add a Kaizala  sub-group to a parent group](media/890765a2-9e2e-409f-88fa-0e478dfeb0c6.png)
  
## Export Kaizala group information

You can export information of all Kaizala groups to a CSV file.
  
- On the Kaizala management portal, from the left navigation bar, choose **Groups**, and then choose **Bulk Upload Users**. 
    
- Click or tap **Export Existing Groups**. 
    
You can then view information related to  groups and users from an Excel spreadsheet or any other app that can open CSV files. [Add several users at the same time to Office 365 - Admin Help](https://support.office.com/article/1f5767ed-e717-4f24-969c-6ea9d412ca88#__toc316652088)
  
## Troubleshooting Kaizala groups

Read this section to help troubleshoot groups issues that you're having in Kaizala.
  
### I am unable to add groups through Bulk Upload Users feature

For each bulk upload activity, there is a unique job that gets created. From the Kaizala home page, go to **Groups**, **Bulk Upload Users** to view the bulk upload jobs history. Find the job that you're having issues with, click on the job name to see and read the error log to find any errors. Fix the errors and then try to re-run the bulk upload again. 
  
### I already created a group from mobile app. How do I convert this to an organization group?

By default, when a group is created from the mobile app, it's created as a private group. You can convert this to an organization group from the **Settings** page in the Kaizala admin portal. You can also convert an organization group into a private group, but you can't convert a private group to an organization group or vice-versa from the mobile app. 
  
### I am a Kaizala organization admin. I converted an organization group to a private group, which I am not a member of, and now I can't see it anymore. Where did it go?

This is by design. Kaizala organization admins can only see the organization groups. You can't see other private groups unless you are a member or administrator of that group.
  

