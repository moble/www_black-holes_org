---
layout: post
title: Adding a Bio to the "People" Page
joomla_id: 174
joomla_url: adding-a-bio-to-the-people-page
date: 2014-10-17 05:59:21.000000000 +00:00
---
<p>This tutorial walks you through the process of adding a bio to the "People" page. Just like for SXS Papers, we have a code snippet template already set up for you to insert into the article.</p>
<h4>An Example of the Bio Item</h4>
<p><!-- Start of a new bio --></p>
<p>{slider Replace_With_Your_Full_Name|inactive}</p>
<div class="bio">
<h3>Your Full Name</h3>
<h4>Your Professional Title or Your Advisor (for grad students)</h4>
<img alt="Name" src="images/people/placeholder.jpg" />
<div class="contact-info"><span class="phone">Phone:Your_Phone_Number </span><span class="email">Email:youremail</span><br /><span class="address">Office Address:Your_Office_Address</span></div>
<h5>Institution</h5>
<p>eg, Cornell University</p>
<h5>Specialty Areas</h5>
<p>eg, Theoretical Astrophysics</p>
<h5>Research Projects</h5>
<p>eg, Solving Einstein's Equations for Black Hole Mergers Using Supercomputers.</p>
<h5>Biography</h5>
<p>1st Paragraph</p>
<p>2nd Paragraph (optional)</p>
<h5>Selected Publications</h5>
<ul>
<li>Black Hole-Neutron Star Mergers for 10 Solar Mass Black Holes. F. Foucart, M. D. Duez, L. E. Kidder, M. A. Scheel, B. Szilagyi and S. A. Teukolsky. Phys. Rev., D85, 044015 (2012). [<a href="http://arxiv.org/abs/1111.1677" target="_blank">http://arxiv.org/abs/1111.1677</a>]</li>
<li>Black Hole-Neutron Star Mergers for 10 Solar Mass Black Holes. F. Foucart, M. D. Duez, L. E. Kidder, M. A. Scheel, B. Szilagyi and S. A. Teukolsky. Phys. Rev., D85, 044015 (2012). [<a href="http://arxiv.org/abs/1111.1677" target="_blank">http://arxiv.org/abs/1111.1677</a>]</li>
<li>Black Hole-Neutron Star Mergers for 10 Solar Mass Black Holes. F. Foucart, M. D. Duez, L. E. Kidder, M. A. Scheel, B. Szilagyi and S. A. Teukolsky. Phys. Rev., D85, 044015 (2012). [<a href="http://arxiv.org/abs/1111.1677" target="_blank">http://arxiv.org/abs/1111.1677</a>]</li>
</ul>
</div>
<p>{/sliders} <!-- End of a bio --></p>
<p>Inserting a New Bio into the People Page</p>
<ol>
<li>Open up the "<strong>People</strong>" article in <strong>Content -&gt; Article Manager</strong>.</li>
<li>Let's go into Source Code mode for a second by clicking the <strong>&lt;&gt; Source Code Editor icon</strong>. This ensures that you are inserting the code snippet in the right place, and not get nested into some other tabs or sliders.</li>
<li>First, figure out where you want to put your bio, in our example, we will put our demo bio right after Saul Teukolsky's bio/before Christian Ott's. As in the screenshot below, <strong>place your cursor after the HTML comment &lt;!-- End of a bio --&gt;</strong> (see below screenshot).</li>
<li>To insert this code snippet, mouse over the "<strong>Insert Template</strong>" button at the bottom of the text editor, a menu with the list of available templates will appear (see below screenshot). Pick "<strong>Bio Template</strong>".<br /><a href="images/tutorials/new_paper.jpg" class="thumbnail highslide " title="new paper"><img class="tnm" alt="inserting bio" src="images/tutorials/inserting_bio.jpg" height="405" width="483" /></a></li>
<li>The code snippet will be loaded and inserted into the code as follow (see below screenshot - this is what you should see. Everything in the red rectangle is the newly added snippet. Click the <strong>Source Code Editor icon</strong> &lt;&gt; to exit the code mode.<br /><img class="tnm" alt="adding bio" src="images/tutorials/adding_bio.jpg" height="519" width="484" /></li>
<li>You will see your newly added template in the text editor. <strong>Highlight the template text and replace with your own info</strong>. Your email is protected from spambots by a effective cloaking plugin, also, it is automatically converted to a clickable "mail to" link. Do not forget to replace the template text "<strong>Replace_With_Your_Full_Name</strong>" with your name inside the slider tag also - this will show up as your name in the clickable tab. To change the placeholder image to your photo, click on the image to select it, then click the <strong>Insert/Edit Image</strong> icon to bring up the Image Manager - you can upload and replace your image here.<br /><img class="tnm" alt="adding bio2" src="images/tutorials/adding_bio2.jpg" height="495" width="477" /></li>
<li><strong>Save</strong> and you are done.</li>
</ol>
<h3>Note</h3>
<p>Please do not delete the HTML comments eg, <code>&lt;!-- Start of a New Bio --&gt;</code> that came with the bio templates since they give a visual separation of where one bio starts and ends.</p>
