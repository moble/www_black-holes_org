---
layout: post
title: Creating a New Page (Menu Item)
joomla_id: 167
joomla_url: creating-a-new-page-menu-item
date: 2014-10-15 10:59:03.000000000 +00:00
---
<p>To create a new content page in Joomla, first of all, you need to <a href="website-update-table-of-contents/adding-and-editing-content-basics" title="create an article">create an article with your new content</a>. However, that is not enough. To view this newly created article, you need to <strong>create a menu item</strong> that points to it. Without an active menu item that points to this article, your article simply exists in the database, but not visible to anyone on the frontend.</p>
<p>For the SXS website, I set up the menu system as following:</p>
<ul>
<li>There is the <strong>main menu</strong>, which is right underneath the logo/header area of the website. The main menu consists of links to almost every page on the SXS site (except a few pages under "Simulations" which is accessible as links inside the "Simulations" page).</li>
<li>Most of the interior pages of the site has a "<strong>sidebar menu</strong>" showing the other pages in its same category, eg, look to the sidebar on your right of this current page - the "Tutorial Menu" is a sidebar menu that consists of links to all other tutorial pages.</li>
</ul>
<h3>How to Add a Menu Item</h3>
<ol>
<li>Using this method, you will have a menu link to your page in the "Main Menu", as well as the corresponding Sidebar Menu.</li>
<li>First of all, in the backend, <strong>mouse over</strong> "<strong>Menus</strong>", you will see a list of existing menus, eg, "Main Menu" (with a star next to it, indicating that is the default main menu of the website), "Relativity Sidebar Menu", "Gravitational Wave Astronomy Sidebar Menu" etc - you get the idea. <strong>Click on any of the menus</strong> that you wish to add a link to (<span style="text-decoration: underline;">or</span> you can use that "<strong>Add New Menu Item</strong>" link). I recommend clicking on the menu link so that you can see a list of existing links.
<p><img class="tnm" alt="add menu link" src="images/tutorials/add_menu_link.jpg" height="282" width="374" /></p>
</li>
<li>In our example, if you click on "About SXS Sidebar Menu", you will see a list of menu links to other pages in the "About SXS" category. Here you can edit the existing menu items, eg, click on the green check marks/red dots to publish or unpublish a menu link, click on the blue up/down arrows to change their orders etc.<br />
<p><img class="tnm" alt="add menu link2" src="images/tutorials/add_menu_link2.jpg" height="399" width="475" /></p>
</li>
<li>Let's say you want to add a page called "SXS History" under "About SXS". Click on the orange "<strong>New</strong>" button (see above screenshot). I have already created an article earlier called "SXS History" for this demo.<br />
<p><img class="tnm" alt="add menu link3" src="images/tutorials/add_menu_link3.jpg" height="372" width="540" /></p>
</li>
<li>In the New Menu Item screen, for "<strong>Menu Item Type</strong>", click on the "<strong>Select</strong>" button to select your menu type - there are many options available and please feel free to play around with them. For 90% of the time, you are adding a content page (same for our example here "SXS History") - in this case, select "<strong>Single Article</strong>" under Articles.</li>
<li>Next, you need to put in a "<strong>Menu Title</strong>" - this is what you will see as the menu link on the website.</li>
<li>Select the "<strong>Parent Item</strong>" - this is the "parent" (the menu item that is one level up) of the menu item you are creating, in this case, it is "About SXS" since "SXS History" is a subpage of "About SXS".</li>
<li>Under "<strong>Required Settings</strong>", Click the <strong>"Select/Change" button</strong> to select the article (you must have already created first) that this menu item links to.</li>
<li>Click "<strong>Save</strong>" and now you have a new menu link on your Sidebar Menu. However, you also want this to appear in the Main Menu of the website.</li>
<li>To add this link also to the Main Menu, hover on <strong>"Menu" -&gt; "Main Menu" -&gt; "Add a New Menu item"</strong> (click).</li>
<li>This time, for "<strong>Menu Item Type</strong>", select "<strong>Menu Item Alias</strong>" under "<strong>System Links</strong>" (scroll all the way down). This will create an alias to the sidebar menu item that you have already created.
<p><img class="tnm" alt="add main menu" src="images/tutorials/add_main_menu.jpg" height="375" width="544" /></p>
</li>
<li>Put in a "<strong>Menu Title</strong>" and pick the "<strong>Parent Item</strong>" as before.</li>
<li>Under "<strong>Required Settings</strong>", for "<strong>Menu Item</strong>", select the already created menu item that you want this alias to point to. In this example, choose "SXS History" under "about-sxs-menu" (this is the system name of the "About SXS Sidebar Menu").</li>
<li><strong>Save</strong> and you are done - now you have this link in both the main menu and the corresponding sidebar menu of your choice.</li>
</ol>
<h3>How to add Small Text Description Under a Main Menu Link</h3>
<ol>
<li>Sometimes, you want to add a brief description under a main menu item, for example, in the below screenshot, "Ripples in the Fabric of Space Time" under "Gravitational Waves":<br />
<p><img class="tnm" alt="menu smalltext" src="images/tutorials/menu_smalltext.jpg" height="271" width="327" /></p>
</li>
<li>To do this, open up a menu item to edit, under "<strong>Dropdown Menu Options</strong>", in "<strong>Subtext Line</strong>", put in your description.
<p><img class="tnm" alt="menu subtext" src="images/tutorials/menu_subtext.jpg" height="313" width="465" /></p>
</li>
<li><strong>Save</strong> and you are done.</li>
</ol>
