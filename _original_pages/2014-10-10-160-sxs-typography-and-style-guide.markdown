---
layout: post
title: SXS Typography and Style Guide
joomla_id: 160
joomla_url: sxs-typography-and-style-guide
date: 2014-10-10 23:34:17.000000000 +00:00
---
<p>This is meant to be a guide to the styling to some common HTML elements on the SXS website. All the styles have been predefined in custom CSS/less files made for SXS, and there is no need to manually add the style (eg, no need to pick a font or color manually) to the HTML elements. In the article text editor, you can choose what kind of element you are inputting with the <strong>format selector</strong> (circled in red below), eg, paragraph, Headings (different elvels, Heading 1 is the largest). You can also add ordered lists and unordered lists by clicking their corresponding icons.</p>
<p><strong>To choose a formatting for your text</strong>, eg, you want your text to be Heading 2, just <strong>highlight the text</strong> in the text editor, and use the <strong>format selector</strong> (circled in red in the below screenshot) to choose your desired element. Hitting <strong>ENTER</strong> will give you a new <strong>paragraph</strong>, while hitting <strong>SHIFT + ENTER</strong> will give you a <strong>line break</strong>.</p>
<p><strong>Tip:</strong> When you start a new article with a paragraph element, sometimes you might need to highlight that whole paragraph and manually select "Paragraph" with the format selector. For the subsequent paragraphs however, you just need to hit <strong>ENTER</strong>.</p>
<h4>What's the difference between a paragraph and a line break?</h4>
<p>A <strong>paragraph</strong> is styled in our CSS (style sheet) to have a margin after it, ie, there will be some empty space below a paragraph. A <strong>line break</strong> does not add space after the line.</p>
<p><img class="tnm" alt="format selector" src="images/tutorials/format_selector.jpg" height="243" width="438" /></p>
<h3>General Formatting</h3>
<p><strong>We do not use Heading 1 in our articles</strong> since the Article Title itself is of level Heading 2 (this is a Joomla setting) - we do not want anything inside the article to have a larger heading than the title of the article itself. We will show you some of these elements below.</p>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<p>This is a regular paragraph. This is <strong>bold text</strong>. This is <em>text in italic</em>. This is <span style="text-decoration: underline;">underlined text</span>.</p>
<ol>
<li>Ordered List item 1</li>
<li>Ordered List item 2</li>
<li>Ordered List item 3</li>
</ol>
<ul>
<li>Unordered List item 1</li>
<li>Unordered List item 2</li>
<li>Unordered List item 3</li>
</ul>
<p><a href="https://black-holes.org" title="This is a regular link.">This is a regular link.</a></p>
<p><a href="https://black-holes.org" class="button">This is a button link.</a></p>
<p>Read more about <a href="index.php?option=com_content&amp;view=article&amp;id=166&amp;Itemid=434" title="Adding Links and Buttons">Adding Links and Buttons here</a>.</p>
<h4>A Table With Class="data"</h4>
<table class="data">
<thead>
<tr><th>Header 1</th><th>Header 2</th><th>Header 3</th></tr>
</thead>
<tbody>
<tr>
<td>1</td>
<td>a</td>
<td>1</td>
</tr>
<tr>
<td>2</td>
<td>b</td>
<td>2</td>
</tr>
<tr>
<td>3</td>
<td>c</td>
<td>3</td>
</tr>
</tbody>
</table>
<h5>The HTML code used for the above table:</h5>
<p><img class="frame" alt="table html" src="images/compact_objects/table_html.png" height="347" width="243" /></p>
<h4>An Animated Blockquote</h4>
<p>The blockquote element below is used in the beginning of several science pages, eg, <a href="the-science-relativity/relativity/the-disputed-center-of-the-universe" title="The Disputed Center of the Universe">The Disputed Center of the Universe</a>.</p>
<blockquote class="animated fadeInDown">
<p class="quote">The fault, dear Brutus, <br /> Is not in our stars, <br /> But in ourselves...</p>
<p class="source">Julius Caesar (I, ii, 140–141)</p>
</blockquote>
<p>The HTML code for the above blockquote:</p>
<p><img class="frame" alt="blockquote" src="images/tutorials/blockquote.png" /></p>
<p>I added the classes "animated" and "fadeInDown" for the subtle animated effect (only happens once on page load). If you would rather use the blockquote without this effect, just take away "class="animated fadeInDown" inside the blockquote tag.</p>
<h3>Fonts Used on SXS Website</h3>
<p>We made use of high quality free webfonts available through the <a href="https://www.google.com/fonts" target="_blank" title="Google Font API">Google Font API</a>. This allows everyone to be able to experience the website in the font we specified, even though the font might not be installed on the person's own computer/device.</p>
<p><a href="https://www.google.com/fonts/specimen/Open+Sans" target="_blank" title="Open Sans">Open Sans</a> - The font we use for body text, eg, this current line you are reading. This is also the font we use for Heading 3 and Heading 5.</p>
<p><a href="https://www.google.com/fonts/specimen/Oswald" target="_blank" title="Oswald">Oswald</a> - This font we use for Heading 2 (eg, the title of this article), top level navigation of the Main Menu, titles of the modules on the sidebar and footer.</p>
<p><strong>Georgia</strong> - This is not a Google Font, but a common serif font that is installed on most computers. This font is used for Heading 4, as well as blockquotes ("Inspiration" on the sidebar, and some quotes on the Science pages).</p>
<h3>Formatting Tips</h3>
<h4>Subscript &amp; Superscript in Article Titles or FAQ Titles</h4>
<p>Native Joomla does not support <strong>superscript or subscript</strong> in the article titles, the same goes for FAQ titles - Joomla basically ignores all HTML tags in the Title field. To get around this issue, I used the extension <strong>NoNumber ReReplacer</strong> to trick Joomla into allowing this. To add superscript into the title, use the <code>[<span style="display: none;">s</span>sup] [<span style="display: none;">s</span>/sup]</code> tags. For subscripts, use <code>[<span style="display: none;">s</span>sub] [<span style="display: none;">s</span>/sub]</code> tags. For example, if I want to display 10<sup>2</sup> in an article/FAQ title, I would put <code>10[<span style="display: none;">s</span>sup]2[<span style="display: none;">s</span>/sup]</code>in the Title field.</p>
