---
layout: post
title: Adding a Glossary Item
joomla_id: 155
joomla_url: adding-a-glossary-item
date: 2014-10-10 04:56:26.000000000 +00:00
---
<p>We use the <strong>Core Design Glossary Plugin</strong> to handle glossary on this website. Each glossary item is just a regular Joomla! article. When you add a glossary item, it will show up on the <a href="index.php?option=com_content&amp;view=category&amp;layout=blog&amp;id=23&amp;Itemid=134">Glossary page</a>, also, on selected content pages, the first instance of this word will be highlighted and its definition will show up in a tool tip bubble when moused over.</p>
<h3>How to Add a Vocabulary</h3>
<ol>
<li>On the backend, go to <strong>Content -&gt; Article Manager</strong> and create a new article (you can add an article via the frontend too if you are granted such access privileges by the super admin).</li>
<li>In "<strong>Title</strong>", put in the new vocabulary term that you want to add, eg, if you want to add the term "Blackhole" and its definition, in the "Title" field, put Blackhole. Spaces are allowed (eg, Supermassive Blackhole).</li>
<li>For the dropdown menu "<strong>Category</strong>", select the category that matches the first alphabet of the term, eg, pick category "B" for the term "Blackhole".</li>
<li>Put the definition inside "Article Text" (the text editor).</li>
<li>Save and you are - the term has been added to the glossary list.</li>
</ol>
<h3>Adding Aliases for the Vocabulary</h3>
<p>Eg, I want both "Blackhole" and "Black Hole" to share the same definition - you don't need to create a new article. See "I've more aliases for one glossary item but I don't want to create a new item" on the <a href="http://www.greatjoomla.com/tutorials/core-design-glossary-plugin/how-to-setup.html" target="_blank">plugin's website</a> (scroll to the bottom).</p>
<h3>Disabling Glossary on a Page</h3>
<p>See "How to disable glossary on specified article?" on the <a href="http://www.greatjoomla.com/tutorials/core-design-glossary-plugin/how-to-setup.html" target="_blank">plugin's website</a>.</p>
<p>To access the settings of this plugin, please go to <strong>Extensions -&gt; Plug-in Manager</strong>, and search for "glossary", you will see <strong>Core Design Glossary Plugin</strong> showing up. Just click on it to access the settings page. For more into on using this plugin, <a href="http://www.greatjoomla.com/information/support/support-index.html" target="_blank">please visit the plugin's website</a>.</p>
<h3>Changing a Top Alphabet Link from Inactive to Active</h3>
<p>Take a look at the alphabet links at the top of the glossary page:</p>
<p><img class="tnm" alt="glossary letters" src="images/tutorials/glossary_letters.jpg" height="154" width="511" /></p>
<p>The orange ones are active, which links to the first glossary item that starts with that alphabet. The grey ones are currently inactive as there are not yet any vocabularies that start with that letter.</p>
<p>To change an inactive (grey) alphabet link to an active (orange) one:</p>
<ol>
<li>On the backend, go to <strong>Content -&gt; Category Manager</strong>, click on the category "<strong>Glossary</strong>".</li>
<li>Click on the button for Source Code Editor (circled in red in the below screeshot - the one with the &lt; &gt; signs)
<p><img class="tnm" alt="category glossary" src="images/tutorials/category_glossary.jpg" height="447" width="624" /></p>
</li>
<li>Clicking on the Source Code Editor button will show you the HTML code for the content area of the page. Let's use the letter "T" as an example here, which is inactive at the moment. To change it to active, just delete the code <code>class="inactive-glossary"</code> (circled in red). Click the Source Code Editor icon again to bring you out of code mode, and click "Save". You are done!</li>
</ol>
