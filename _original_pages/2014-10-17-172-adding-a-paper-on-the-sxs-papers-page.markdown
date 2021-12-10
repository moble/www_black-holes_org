---
layout: post
title: Adding a Paper on the "SXS Papers" Page
joomla_id: 172
joomla_url: adding-a-paper-on-the-sxs-papers-page
date: 2014-10-17 01:14:08.000000000 +00:00
---
<p>Inserting a new paper into an article is easy - template has been pre-made and all you need to do is to change out the info. Abstracts are hidden on page load and would be revealed once the "See Abstract" tab is clicked on by the user. The accordion slider is created with a very easy to use plugin - <a href="http://www.nonumber.nl/extensions/sliders/userguide" target="_blank" title="NoNumber's &quot;Slider&quot;">NoNumber's "Slider"</a>.</p>
<h4>This is what the paper template looks like</h4>
<!-- Start of Paper -->
<div class="paper">
<h4>The Title of Your Paper Goes Here</h4>
<p><strong>Author(s):&nbsp;</strong>Names of authors</p>
<p><strong>Journal:&nbsp;</strong>eg, Phys. Rev. D 81, 124042 (2010)</p>
<p><strong>Date Published:&nbsp;</strong>eg, Jun 23, 2099</p>
<p><strong>arXiv Address:&nbsp;</strong><a href="http://arxiv.org/abs/1004.3768" target="_blank">eg, http://arxiv.org/abs/1004.3768</a></p>
<p>{slider <span class="icon-hand-up"> See Abstract</span>|inactive}</p>
<p>The abstract paragraph goes here.</p>
<p>{/sliders}</p>
</div>
<p><a href="#rt-mainbody" class="to-top">Back to Top</a></p>
<!-- End of Paper -->
<h3>Inserting a New Paper Snippet</h3>
<ol>
<li>The following tutorial is for inserting a new paper into the <a href="index.php?Itemid=233">For Researchers -&gt; SXS Papers</a> page. I have made a template with a code snippet for new paper using the extension Content Templater.</li>
<li>Open up the "<strong>SXS Papers</strong>" article in <strong>Content -&gt; Article Manager</strong> - this is where all the papers are currently.</li>
<li>Put your cursor where you want the new paper to be - probably on a new line (for example, put your cursor behind the year header 2012 and hit <strong>ENTER</strong>). To insert this code snippet, mouse over the "<strong>Insert Template</strong>" icon at the bottom of the text editor, a menu with the list of available template will appear (see below screenshot). Pick "<strong>New SXS Paper</strong>".<br /><img class="tnm" alt="new paper" src="images/tutorials/new_paper.jpg" height="396" width="458" /></li>
<li>Now you should have something that looks like the following in the text editor:<br /><img class="tnm" alt="paper template2" src="images/tutorials/paper_template2.jpg" height="394" width="459" /></li>
<li>Replace the template content with your real info for the paper.</li>
<li>Please <span style="text-decoration: underline;"><strong>do not touch</strong></span> the curly bracker tags that say "<strong>slider</strong>" - these are the open and close tags for the accordion slider that hides/shows the abstract. Put your abstract content in between these tags. You can use LaTeX in the abstract (see <a href="website-update-table-of-contents/using-latex-on-the-website" title="Using LaTeX on the Website">Using LaTeX on the Website</a>).</li>
<li><strong>Save</strong> your changes.</li>
</ol>
