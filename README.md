Quick Start: Siteforce and Web Sites
====================================
 
Use this guide to learn Siteforce and get a Force.com data-driven web site up and running in just a few minutes.

Register for a Free DE Org
--------------------------
It's easy to get started with Force.com and Siteforce because it's a cloud platform: no servers to configure, no software to install. You'll be up and running in just a few minutes by registering for a Developer Edition organization (account), or DE org for short. DE orgs are multipurpose environments with all of the features and permissions that allow you to develop, package, and test cloud apps.

1.	Visit [Developer Force](http://developer.force.com/join) and fill in and submit the form. We'll send you an activation email when you do, so make sure to use an email address that you'll be able to access right now. 
2.	Once you receive the activation email, click on the login link and change your password.
3.	Leave this browser window open once you are in.

DE orgs come pre-installed with some standard apps and data. You’re going to build a data-driven web site with Siteforce based on the standard Product object. If you want to familiarize yourself with the Product object, click the **apps menu** (upper right) **> Sales >** the **Product** tab.

Enable Siteforce Privileges
---------------------------

To begin, enable Siteforce publishing permissions for yourself.

1.	Click ***your name*** (upper right) **> Setup > My Personal Information > Personal Information > Edit**.
2.	Enable the **Siteforce Publisher User** option, then click **Save**.

Build Your Web Site
-------------------

While it’s easy to build a web site from scratch with Siteforce, you’ll save some time by importing a pre-built site, previewing it, and making a few changes to see the power of Siteforce.

Download this git repository to access an example web site export file.

Next, create a new site by importing the file you just downloaded.

1.	Click the **apps menu > Siteforce >** the **Siteforce** tab (on the left) **> New**.
2.	In the Siteforce wizard, specify the site name as *Cirrus Inc.*, click **Import a Siteforce** website **> Choose File**, choose the file you just downloaded, then click **Create**.
3.	After Siteforce imports the pre-built site, watch the demo video to get an overview of Siteforce features.

Browse the New Site
-------------------

The Siteforce Studio displays the contents of your new site. You can view individual pages, page templates, style sheets, and all other assets such as images that the site uses.

1.	From the default **Site Pages** view, notice the **Site Map** folder contains four pages. 
2.	Double-click the **home** page to preview the home page, which the studio then opens in a new browser tab. 
3.	Click on the various menu links to display the static Home, Support, and Contact pages, then click on the **Products** menu and notice there’s nothing on the Product page. That’s because the page was left incomplete. Ready to fix it?

Configure the Site
------------------

With Siteforce and Force.com, you can make changes in real-time to your web site with just a few simple mouse clicks. No waiting for IT. Start with some data security configuration by assigning the correct permissions to the anonymous web site user profile so that such users can read data from the Project object.

1.	Click **Site Configuration > Cirrus Inc Profile**.
2.	In the new browser tab that opens up, click **Edit**, find the **Standard Object Permissions** section, enable **Read** for **Products**, then click **Save**.

Modify a Page
-------------

The existing product page needs some work: a heading and a table that lists all of the products in the database. Easy. From the Siteforce studio, start by adding a simple content block with a primary heading for the page.

1.	Mouse over the product page and use the quick access menu (gear) to edit the page.
2.	From the sidebar, drag and drop a **Content Block** on the page.
3.	Double-click the new block and edit the text so that it’s just *Products*. Then use the formatting bar above to style it as **Heading 1** and click **Save**.

Now add a simple data table display the products from the database.

1.	From the sidebar, drag and drop a **Data Table** onto the page.
2.	On the first page of the Data Table wizard, choose the **Product** object and configure a field filter such that the **Active** field must be equal to true, then click **Next**.
3.	On the second page of the wizard, add the **Product Code** and **Product Name** fields to the table, click **Reload Preview** for a quick look, then click **Save**.

Your page is ready to preview. Click **Preview** (upper right) and view your dynamic, database-drive page. That was almost too easy!

Next Steps
----------

This was just a quick preview of Siteforce. There’s so much more you can do. For more developer information and resources concerning Siteforce, check out the Siteforce page on [Developer Force](http://wiki.developerforce.com/Siteforce).
