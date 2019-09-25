---
title: "How to protect your company app data with Microsoft Intune - Microsoft Graph API"
description: "Lists Microsoft Graph API for Intune endpoints (REST) that manage apps and their policies for a tenant organization."
author: "rolyon"
localization_priority: Normal
ms.prod: "intune"
---

# How to protect your company app data with Microsoft Intune

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Microsoft Intune app protection policies help protect your company data and prevent data loss.

You can use Intune app protection policies to help protect your company’s data. Because Intune app protection policies can be used independent of any mobile-device management (MDM) solution, you can use it to protect your company’s data with or without enrolling devices in a device management solution. By implementing app-level policies, you can restrict access to company resources and keep data within the purview of your IT department.

The following Graph resources are available to manage app protection polices in Intune:

- [Android device owner enrollment profile](intune-androidforwork-androiddeviceownerenrollmentprofile.md)
- [Android enrollment company code](intune-androidforwork-androidenrollmentcompanycode.md)
- [Android for Work app](intune-apps-androidforworkapp.md)
- [Android for Work app configuration schema](intune-androidforwork-androidforworkappconfigurationschema.md)
- [Android for Work app configuration schema item](intune-androidforwork-androidforworkappconfigurationschemaitem.md)
- [Android for Work app configuration schema item data type](intune-androidforwork-androidforworkappconfigurationschemaitemdatatype.md)
- [Android for Work bind status](intune-androidforwork-androidforworkbindstatus.md)
- [Android for Work enrollment profile](intune-androidforwork-androidforworkenrollmentprofile.md)
- [Android for Work enrollment target](intune-androidforwork-androidforworkenrollmenttarget.md)
- [Android for Work mobile app configuration](intune-apps-androidforworkmobileappconfiguration.md)
- [Android for Work settings](intune-androidforwork-androidforworksettings.md)
- [Android for Work sync status](intune-androidforwork-androidforworksyncstatus.md)
- [Android LOB app](intune-apps-androidlobapp.md)
- [Android managed store account app sync status](intune-androidforwork-androidmanagedstoreaccountappsyncstatus.md)
- [Android managed store account bind status](intune-androidforwork-androidmanagedstoreaccountbindstatus.md)
- [Android managed store account enrollment target](intune-androidforwork-androidmanagedstoreaccountenrollmenttarget.md)
- [Android managed store account enterprise settings](intune-androidforwork-androidmanagedstoreaccountenterprisesettings.md)
- [Android managed store app](intune-apps-androidmanagedstoreapp.md)
- [Android managed store app configuration](intune-apps-androidmanagedstoreappconfiguration.md)
- [Android managed store app configuration schema](intune-androidforwork-androidmanagedstoreappconfigurationschema.md)
- [Android managed store app configuration schema item](intune-androidforwork-androidmanagedstoreappconfigurationschemaitem.md)
- [Android managed store app configuration schema item data type](intune-androidforwork-androidmanagedstoreappconfigurationschemaitemdatatype.md)
- [Android minimum operating system](intune-apps-androidminimumoperatingsystem.md)
- [Android permission action](intune-apps-androidpermissionaction.md)
- [Android permission action type](intune-apps-androidpermissionactiontype.md)
- [Android store app](intune-apps-androidstoreapp.md)
- [App configuration setting item](intune-apps-appconfigurationsettingitem.md)
- [Certificate status](intune-apps-certificatestatus.md)
- [Device install state](intune-books-deviceinstallstate.md)
- [E-book install summary](intune-books-ebookinstallsummary.md)
- [Enterprise code signing certificate](intune-apps-enterprisecodesigningcertificate.md)
- [Excluded apps](intune-apps-excludedapps.md)
- [File encryption info](intune-apps-fileencryptioninfo.md)
- [Install state](intune-books-installstate.md)
- [iOS device type](intune-apps-iosdevicetype.md)
- [iOS LOB app](intune-apps-ioslobapp.md)
- [iOS LOB app assignment settings](intune-apps-ioslobappassignmentsettings.md)
- [iOS LOB app provisioning configuration](intune-apps-ioslobappprovisioningconfiguration.md)
- [iOS LOB app provisioning configuration assignment](intune-apps-ioslobappprovisioningconfigurationassignment.md)
- [iOS minimum operating system](intune-apps-iosminimumoperatingsystem.md)
- [iOS mobile app configuration](intune-apps-iosmobileappconfiguration.md)
- [iOS store app](intune-apps-iosstoreapp.md)
- [iOS store app assignment settings](intune-apps-iosstoreappassignmentsettings.md)
- [iOS VPP app](intune-apps-iosvppapp.md)
- [iOS VPP app assigned device license](intune-apps-iosvppappassigneddevicelicense.md)
- [iOS VPP app assigned license](intune-apps-iosvppappassignedlicense.md)
- [iOS VPP app assigned user license](intune-apps-iosvppappassigneduserlicense.md)
- [iOS VPP app assignment settings](intune-apps-iosvppappassignmentsettings.md)
- [iOS VPP app revoke licenses action result](intune-apps-iosvppapprevokelicensesactionresult.md)
- [iOS VPP e-book](intune-books-iosvppebook.md)
- [iOS VPP e-book assignment](intune-books-iosvppebookassignment.md)
- [macOS LOB app](intune-apps-macoslobapp.md)
- [macOS LOB child app](intune-apps-macoslobchildapp.md)
- [macOS minimum operating system](intune-apps-macosminimumoperatingsystem.md)
- [macOS office suite app](intune-apps-macosofficesuiteapp.md)
- [macOS VPP app](intune-apps-macosvppapp.md)
- [macOS VPP app assigned license](intune-apps-macosvppappassignedlicense.md)
- [macOS VPP app assignment settings](intune-apps-macosvppappassignmentsettings.md)
- [macOS VPP app revoke licenses action result](intune-apps-macosvppapprevokelicensesactionresult.md)
- [Managed android LOB app](intune-apps-managedandroidlobapp.md)
- [Managed android store app](intune-apps-managedandroidstoreapp.md)
- [Managed app](intune-apps-managedapp.md)
- [Managed app availability](intune-apps-managedappavailability.md)
- [Managed device mobile app configuration](intune-apps-manageddevicemobileappconfiguration.md)
- [Managed device mobile app configuration assignment](intune-apps-manageddevicemobileappconfigurationassignment.md)
- [Managed device mobile app configuration device status](intune-apps-manageddevicemobileappconfigurationdevicestatus.md)
- [Managed device mobile app configuration device summary](intune-apps-manageddevicemobileappconfigurationdevicesummary.md)
- [Managed device mobile app configuration user status](intune-apps-manageddevicemobileappconfigurationuserstatus.md)
- [Managed device mobile app configuration user summary](intune-apps-manageddevicemobileappconfigurationusersummary.md)
- [Managed e-book](intune-books-managedebook.md)
- [Managed e-book assignment](intune-books-managedebookassignment.md)
- [Managed e-book category](intune-books-managedebookcategory.md)
- [Managed iOS LOB app](intune-apps-managedioslobapp.md)
- [Managed iOS store app](intune-apps-managediosstoreapp.md)
- [Managed mobile LOB app](intune-apps-managedmobilelobapp.md)
- [MDM app config key type](intune-apps-mdmappconfigkeytype.md)
- [Microsoft store for business app](intune-apps-microsoftstoreforbusinessapp.md)
- [Microsoft store for business app assignment settings](intune-apps-microsoftstoreforbusinessappassignmentsettings.md)
- [Microsoft store for business contained app](intune-apps-microsoftstoreforbusinesscontainedapp.md)
- [Microsoft store for business license type](intune-apps-microsoftstoreforbusinesslicensetype.md)
- [Mobile app](intune-apps-mobileapp.md)
- [Mobile app assignment](intune-apps-mobileappassignment.md)
- [Mobile app assignment settings](intune-apps-mobileappassignmentsettings.md)
- [Mobile app category](intune-apps-mobileappcategory.md)
- [Mobile app content](intune-apps-mobileappcontent.md)
- [Mobile app content file](intune-apps-mobileappcontentfile.md)
- [Mobile app content file upload state](intune-apps-mobileappcontentfileuploadstate.md)
- [Mobile app dependency](intune-apps-mobileappdependency.md)
- [Mobile app dependency type](intune-apps-mobileappdependencytype.md)
- [Mobile app install status](intune-apps-mobileappinstallstatus.md)
- [Mobile app install summary](intune-apps-mobileappinstallsummary.md)
- [Mobile app provisioning config group assignment](intune-apps-mobileappprovisioningconfiggroupassignment.md)
- [Mobile app publishing state](intune-apps-mobileapppublishingstate.md)
- [Mobile app relationship](intune-apps-mobileapprelationship.md)
- [Mobile app relationship state](intune-apps-mobileapprelationshipstate.md)
- [Mobile contained app](intune-apps-mobilecontainedapp.md)
- [Mobile LOB app](intune-apps-mobilelobapp.md)
- [Office client checkin status](intune-cirrus-officeclientcheckinstatus.md)
- [Office client configuration](intune-cirrus-officeclientconfiguration.md)
- [Office client configuration assignment](intune-cirrus-officeclientconfigurationassignment.md)
- [Office configuration](intune-cirrus-officeconfiguration.md)
- [Office configuration assignment target](intune-cirrus-officeconfigurationassignmenttarget.md)
- [Office configuration group assignment target](intune-cirrus-officeconfigurationgroupassignmenttarget.md)
- [Office product id](intune-apps-officeproductid.md)
- [Office suite app](intune-apps-officesuiteapp.md)
- [Office suite install progress display level](intune-apps-officesuiteinstallprogressdisplaylevel.md)
- [Office update channel](intune-apps-officeupdatechannel.md)
- [Office user checkin summary](intune-cirrus-officeusercheckinsummary.md)
- [Resultant app state detail](intune-apps-resultantappstatedetail.md)
- [Symantec code signing certificate](intune-apps-symanteccodesigningcertificate.md)
- [User app install status](intune-apps-userappinstallstatus.md)
- [User install state summary](intune-books-userinstallstatesummary.md)
- [VPP licensing type](intune-apps-vpplicensingtype.md)
- [Web app](intune-apps-webapp.md)
- [Win32 LOB app](intune-apps-win32lobapp.md)
- [Win32 LOB app assignment settings](intune-apps-win32lobappassignmentsettings.md)
- [Win32 LOB app detection](intune-apps-win32lobappdetection.md)
- [Win32 LOB app detection operator](intune-apps-win32lobappdetectionoperator.md)
- [Win32 LOB app file system detection](intune-apps-win32lobappfilesystemdetection.md)
- [Win32 LOB app file system detection type](intune-apps-win32lobappfilesystemdetectiontype.md)
- [Win32 LOB app file system requirement](intune-apps-win32lobappfilesystemrequirement.md)
- [Win32 LOB app install experience](intune-apps-win32lobappinstallexperience.md)
- [Win32 LOB app msi information](intune-apps-win32lobappmsiinformation.md)
- [Win32 LOB app msi package type](intune-apps-win32lobappmsipackagetype.md)
- [Win32 LOB app notification](intune-apps-win32lobappnotification.md)
- [Win32 LOB app power shell script detection](intune-apps-win32lobapppowershellscriptdetection.md)
- [Win32 LOB app power shell script detection type](intune-apps-win32lobapppowershellscriptdetectiontype.md)
- [Win32 LOB app power shell script requirement](intune-apps-win32lobapppowershellscriptrequirement.md)
- [Win32 LOB app product code detection](intune-apps-win32lobappproductcodedetection.md)
- [Win32 LOB app registry detection](intune-apps-win32lobappregistrydetection.md)
- [Win32 LOB app registry detection type](intune-apps-win32lobappregistrydetectiontype.md)
- [Win32 LOB app registry requirement](intune-apps-win32lobappregistryrequirement.md)
- [Win32 LOB app requirement](intune-apps-win32lobapprequirement.md)
- [Win32 LOB app return code](intune-apps-win32lobappreturncode.md)
- [Win32 LOB app return code type](intune-apps-win32lobappreturncodetype.md)
- [Windows AppX](intune-apps-windowsappx.md)
- [Windows AppX app assignment settings](intune-apps-windowsappxappassignmentsettings.md)
- [Windows architecture](intune-apps-windowsarchitecture.md)
- [Windows device type](intune-apps-windowsdevicetype.md)
- [Windows minimum operating system](intune-apps-windowsminimumoperatingsystem.md)
- [Windows mobile MSI](intune-apps-windowsmobilemsi.md)
- [Windows office client configuration](intune-cirrus-windowsofficeclientconfiguration.md)
- [Windows office client security configuration](intune-cirrus-windowsofficeclientsecurityconfiguration.md)
- [Windows package information](intune-apps-windowspackageinformation.md)
- [Windows Phone 8.1 AppX](intune-apps-windowsphone81appx.md)
- [Windows Phone 8.1 AppX bundle](intune-apps-windowsphone81appxbundle.md)
- [Windows Phone 8.1 store app](intune-apps-windowsphone81storeapp.md)
- [Windows phone XAP](intune-apps-windowsphonexap.md)
- [Windows store app](intune-apps-windowsstoreapp.md)
- [Windows universal AppX](intune-apps-windowsuniversalappx.md)
- [Windows universal AppX app assignment settings](intune-apps-windowsuniversalappxappassignmentsettings.md)
- [Windows universal AppX contained app](intune-apps-windowsuniversalappxcontainedapp.md)
