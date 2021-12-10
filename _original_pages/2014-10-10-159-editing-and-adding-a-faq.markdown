---
layout: post
title: Editing and Adding a FAQ
joomla_id: 159
joomla_url: editing-and-adding-a-faq
date: 2014-10-10 23:17:53.000000000 +00:00
---
<p>The FAQ page on this website makes use of the <strong>Minitek FAQ Book Extension</strong>. We are using the latest version 1.6.9 that is compatible for Joomla 2.5.</p>
<h3>To Add or Edit an FAQ</h3>
<ol>
<li>On the backend, go to <strong>Components -&gt; FAQ Book -&gt; Dashboard</strong>. You will see the below interface:
<p><img class="tnm" alt="faq" src="images/tutorials/faq.jpg" height="266" width="469" /></p>
</li>
<li>If you click on <strong>Categories</strong>, you will see that currently, there is one top level category<strong> SXS FAQs</strong> and <strong>6 subcategories - Relativity, Gravitational Waves, White Dwarfs &amp; Neutron Stars, Black Holes, Big Bang, Other Questions</strong>. If needed, you can create a new category by clicking the orange "<strong>New</strong>" button. For the option field "<strong>Parent</strong>", please select "<strong>SXS FAQs</strong>" in the dropdown menu.</li>
<li>To edit or add an FAQ, please click the <strong>FAQs icon</strong> on the dashboard, or click the "<strong>FAQs</strong>" link on the navigation tabs (see above screenshot, the 4 tabs are - Dashboard, Categories, FAQs and About).</li>
<li>You will see a list of existing FAQs, click on any of them to make your edit. Hit "<strong>Save</strong>" to save your changes.</li>
<li>To add an FAQ, click the orange "<strong>New</strong>" button to open up the new FAQ page.</li>
<li>Make sure to select the correct "<strong>Category</strong>" in the dropdown menu options. The rest is self explanatory.</li>
<li><strong>Trick:</strong> Native Joomla does not support <strong>superscript or subscript</strong> in the article titles, the same goes for FAQ titles - Joomla basically ignores all HTML tags in the Title field. To get around this issue, I used the extension <strong>NoNumber ReReplacer</strong> to trick Joomla into allowing this. To add superscript into the title, use the <code>[<span style="display: none;">s</span>sup] [<span style="display: none;">s</span>/sup]</code> tags. For subscripts, use <code>[<span style="display: none;">s</span>sub] [<span style="display: none;">s</span>/sub]</code> tags. For example, if I want to display 10<sup>2</sup> in an article/FAQ title, I would put <code>10[<span style="display: none;">s</span>sup]2[<span style="display: none;">s</span>/sup]</code>in the Title field.</li>
</ol>
