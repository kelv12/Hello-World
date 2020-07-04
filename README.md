# Hello-World
Azure Active Directory integration with BambooHR
BambooHR with Azure AD provides you with the following benefits:

You can control in Azure AD who has access to BambooHR.
You can enable your users to be automatically signed-in to BambooHR (Single Sign-On) with their Azure AD accounts.
You can manage your accounts in one central location - the Azure portal.
If you want to know more details about SaaS app integration with Azure AD, see What is application access and single sign-on with Azure Active Directory. If you don't have an Azure subscription, create a free account before you begin.

Prerequisites
To configure Azure AD integration with BambooHR, you need the following items:

An Azure AD subscription. If you don't have an Azure AD environment, you can get one-month trial here
BambooHR single sign-on enabled subscription
Scenario description
In this tutorial, you configure and test Azure AD single sign-on in a test environment.

BambooHR supports SP initiated SSO
Adding BambooHR from the gallery
To configure the integration of BambooHR into Azure AD, you need to add BambooHR from the gallery to your list of managed SaaS apps.

To add BambooHR from the gallery, perform the following steps:

In the Azure portal, on the left navigation panel, click Azure Active Directory icon.

The Azure Active Directory button

Navigate to Enterprise Applications and then select the All Applications option.

The Enterprise applications blade

To add new application, click New application button on the top of dialog.

The New application button

In the search box, type BambooHR, select BambooHR from result panel then click Add button to add the application.

BambooHR in the results list

Configure and test Azure AD single sign-on
In this section, you configure and test Azure AD single sign-on with BambooHR based on a test user called Britta Simon. For single sign-on to work, a link relationship between an Azure AD user and the related user in BambooHR needs to be established.

To configure and test Azure AD single sign-on with BambooHR, you need to complete the following building blocks:

Configure Azure AD Single Sign-On - to enable your users to use this feature.
Configure BambooHR Single Sign-On - to configure the Single Sign-On settings on application side.
Create an Azure AD test user - to test Azure AD single sign-on with Britta Simon.
Assign the Azure AD test user - to enable Britta Simon to use Azure AD single sign-on.
Create BambooHR test user - to have a counterpart of Britta Simon in BambooHR that is linked to the Azure AD representation of user.
Test single sign-on - to verify whether the configuration works.
Configure Azure AD single sign-on
In this section, you enable Azure AD single sign-on in the Azure portal.

To configure Azure AD single sign-on with BambooHR, perform the following steps:

In the Azure portal, on the BambooHR application integration page, select Single sign-on.

Configure single sign-on link

On the Select a Single sign-on method dialog, select SAML/WS-Fed mode to enable single sign-on.

Single sign-on select mode

On the Set up Single Sign-On with SAML page, click Edit icon to open Basic SAML Configuration dialog.

Edit Basic SAML Configuration

On the Basic SAML Configuration section, perform the following steps:

BambooHR Domain and URLs single sign-on information

a. In the Sign on URL text box, type a URL using the following pattern: https://<company>.bamboohr.com

b. In the Identifier (Entity ID) text box, type a URL using the following pattern: BambooHR-SAML

 Note

The Sign on URL value is not real. Update the value with actual sign-on URL. Contact BambooHR Client support team to get the value. You can also refer to the patterns shown in the Basic SAML Configuration section in the Azure portal.

On the Set up Single Sign-On with SAML page, in the SAML Signing Certificate section, click Download to download the Certificate (Base64) from the given options as per your requirement and save it on your computer.

The Certificate download link

On the Set up BambooHR section, copy the appropriate URL(s) as per your requirement.

Copy configuration URLs

a. Login URL

b. Azure Ad Identifier

c. Logout URL

Configure BambooHR Single Sign-On
In a new window, sign in to your BambooHR company site as an administrator.

On the home page, do the following:

The BambooHR Single Sign-On page

a. Select Apps.

b. In the Apps pane, select Single Sign-On.

c. Select SAML Single Sign-On.

In the SAML Single Sign-On pane, do the following:

The SAML Single Sign-On pane

a. Into the SSO Login Url box, paste the Login URL that you copied from the Azure portal in step 6.

b. In Notepad, open the base-64 encoded certificate that you downloaded from the Azure portal, copy its content, and then paste it into the X.509 Certificate box.

c. Select Save.

Create an Azure AD test user
The objective of this section is to create a test user in the Azure portal called Britta Simon.

In the Azure portal, in the left pane, select Azure Active Directory, select Users, and then select All users.

The "Users and groups" and "All users" links

Select New user at the top of the screen.

New user Button

In the User properties, perform the following steps.

The User dialog box

a. In the Name field enter BrittaSimon.

b. In the User name field type brittasimon@yourcompanydomain.extension
For example, BrittaSimon@contoso.com

c. Select Show password check box, and then write down the value that's displayed in the Password box.

d. Click Create.

Assign the Azure AD test user
In this section, you enable Britta Simon to use Azure single sign-on by granting access to BambooHR.

In the Azure portal, select Enterprise Applications, select All applications, then select BambooHR.

Enterprise applications blade

In the applications list, type and select BambooHR.

The BambooHR link in the Applications list

In the menu on the left, select Users and groups.

The "Users and groups" link

Click the Add user button, then select Users and groups in the Add Assignment dialog.

The Add Assignment pane

In the Users and groups dialog select Britta Simon in the Users list, then click the Select button at the bottom of the screen.

If you are expecting any role value in the SAML assertion then in the Select Role dialog select the appropriate role for the user from the list, then click the Select button at the bottom of the screen.

In the Add Assignment dialog click the Assign button.

Create BambooHR test user
To enable Azure AD users to sign in to BambooHR, set them up manually in BambooHR by doing the following:

Sign in to your BambooHR site as an administrator.

In the toolbar at the top, select Settings.

The Settings button

Select Overview.

In the left pane, select Security > Users.

Type the username, password, and email address of the valid Azure AD account that you want to set up.

Select Save.

 Note

To set up Azure AD user accounts, you can also use BambooHR user account-creation tools or APIs.

Test single sign-on
In this section, you test your Azure AD single sign-on configuration using the Access Panel.

When you click the BambooHR tile in the Access Panel, you should be automatically signed in to the BambooHR for which you set up SSO. For more information about the Access Panel, see Introduction to the Access Panel.
