## 2.8 Groups

### 2.8.1	Overview

XOOPS incorporates a member registration system - you can optionally require people to sign up to your site in order to have access to certain areas or functions. For example, most sites require people to join before they are allowed to contribute news or post messages in the forums Access and administration rights to a XOOPS website are set through a flexible permission system based on 'user groups'. The default groups include anonymous users, registered members and webmasters, but of course you can define as many groups as you need to manage your site. Each group can be given a unique set of access rights governing:

- Which blocks can be seen 
- Which modules can be accessed
- Which modules can be administered
- Which aspects of system administration can be modified

You can change the name of these default groups, but, you cannot delete them. Other user groups can also be set and defined as discussed later.
Custom groups can be created through the Groups Administration page

XOOPS provides a core system of user access rights through the 'Groups' settings. This allows the site administrator to control and filter access on at least 3 different user levels. All modules and their associated blocks must have their settings for visibility, rights and access correctly defined in order to achieve correct display and function on the website. Put simply, if you don’t grant these rights for a block to every available group, it won’t be visible on the page.   
The three default user access groups are as follows:

-	Anonymous users;
-	Registered users;
-	Webmasters (site administrators);
	

You can change the name of these default groups, but, you cannot delete them. Other user groups can also be set and defined as discussed later.

Let’s explain the meaning of each default groups. Someone who visits your site is an ‘Anonymous User’. If a visitor is registered AND logged in to your site, he will be recognized as a ‘Registered User’. The ‘Administrators’ group automatically contains the primary user you created during the installation.

In a typical web setup we may set group permissions as follows:

**a)	Anonymous users:**

Anonymous users may be allowed to view certain content as displayed by a particular module, or groups of modules. When anonymous users visit your site they will automatically see a default level of content for this group without any action on their part. 

**b)	Registered users:**

Registered users of the site can be granted rights to view and interact with other modules not available to the anonymous group. On initial site visit, assuming there is no auto-login function, they see the default content like any other visitor. However, when they login with their correct user details, the page will reload to include any links, menus and module content accessible to the registered group. The site administrator can design a site to display totally different module content, or simply additional module content to registered users. 

**c)	Webmasters:**

As the creator of the XOOPS site the Webmaster or site administrator has complete and overall rights of access and administration. However, it is possible to promote any registered user to Webmaster status and share your privileges. It is safer to create a custom group and grant module and administration access for selected modules if you wish to allow others to administrate areas of the site.
