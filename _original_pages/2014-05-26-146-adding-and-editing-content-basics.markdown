---
layout: post
title: Adding and Editing Content - Basics
joomla_id: 146
joomla_url: adding-and-editing-content-basics
date: 2014-05-26 11:22:57.000000000 +00:00
---
<p>We installed the <strong>JCE Editor</strong> (THE most popular Joomla article editor) for this project as it allows one to do much more than the default editor that comes with Joomla. I only cover the basics here as the icons are fairly self explanatory (think Microsoft Word icons). For anything that is not covered here, <a href="https://www.joomlacontenteditor.net/support/documentation/56-editor" target="_blank" title="JCE's complete documentation">please check out JCE's complete documentation</a>.</p>
<h3>Editing Content via the Backend</h3>
<p>Most of the content in Joomla (and this site) are organized in the form of "<strong>articles</strong>", which belong to "<strong>categories</strong>" created by the users (for this website, some of the example categories are "relativity", "compact objects"). To access these articles, go to <strong>Content -&gt; Article Manager</strong> on the top tool bar. You will see something like the image below:</p>
<p><img class="tnm" alt="article manager" src="images/tutorials/article_manager.jpg" height="269" width="745" /></p>
<p>As you can probably guess, most of these <strong>"articles" correspond to the different pages of the website</strong> (with some exceptions such as the glossary, but I will talk more about that later). Also, you can filter the articles you see by playing with the select bars near the top area, eg, you can choose to display only articles from a certain category.</p>
<p>To edit the content of an article, just click on the name of the article and the editing page will open up:</p>
<p><img class="tnm" alt="article editor" src="images/tutorials/article_editor.jpg" height="444" width="744" /></p>
<p>As you can see, the text editor has icons similar to Microsoft Word and the like. They also behave in a very similar manner. Hitting enter will get you a new paragraph.</p>
<p><img class="caption tnr" title="Code mode button (circled in red)" alt="code" src="images/tutorials/code.jpg" /><span style="text-decoration: underline;">Before you make any changes to the article, I suggest you click into "code" mode (see image on the right), copy everything and paste it into Notepad or any plain text editor on your computer</span>. This way if you make a mistake, you can always go back to the original (I have made a complete back up of the site in this state also).</p>
<p>To make simple changes, just highlight the text you want to change and type over it like you would in a regular text editor. Hit "Save" (the icon with the orange check mark) after you are done editing.</p>
<p>Please try not to compose a whole article in the article editor, <strong>each login session has a time limit and you do not want to lose your work</strong>. If you need to work on an article for a long time, please do so first on your own regular text editor, then copy the content over to Joomla, or at least save frequently.</p>
<p>More specifics on working with images, adding bios, glossary, papers etc will be coming soon. For the mean time, please feel free to look around and get familiar with the Joomla interface.</p>
<h3>Editing (Most of) the Content via the Frontend</h3>
<p>If you are looking at this page, chances are that you are already logged in through the frontend login page. Frontend editing is recommended only for simpler edits as less features are available. To do so:</p>
<ol>
<li>Navigate to the page on the website that you wish to edit, as an example, go to About Us -&gt; Our Motivation.</li>
<li>A new <strong>"edit" icon</strong> (see below screenshot circled in red) will show up next to the email icon at the top of the article (below the title). Clicking on it will bring you into the editing screen.
<p><img class="tnm" alt="frontend edit" src="images/tutorials/frontend_edit.jpg" height="220" width="709" /></p>
</li>
<li>Use the text editor to make your changes. When you are done, hit the "Save" button.
<p><img class="tnm" alt="frontend edit2" src="images/tutorials/frontend_edit2.jpg" height="793" width="710" /></p>
</li>
</ol>
<h3>Important&nbsp; - Why is the Article Locked? (Updated 11/6/2014)</h3>
<p>When you are done editing an article, please do not just close the browser window or hit the back button even if you do not modify it - remember to always hit one of the buttons - <strong>"Save", "Cancel", "Save &amp; Close" (backend only) or "Close" (backend only)</strong> - this will "check out" the article properly. Not hitting one of the buttons will put a lock on the article and others might not be able to access it, since the system thinks that you are still editing the article and will prevent more than one person to modify it.</p>
<p>For admins, in certain situation if you need to remove the locks on all articles (eg, need to edit a locked article and can't find the person who last edited it to close it properly), you can go to <strong>Site -&gt; Maintenance -&gt; Global Check-in</strong> on the backend to remove the locks on all currently checked out articles. Note: Performing a Global Check-in while documents are open for editing will result in data loss. <span style="font-weight: bold;">All</span> Checked Out Items will be checked in, and any unsaved changes will be lost.</p>
