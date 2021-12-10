---
layout: post
title: Adding a Random Quote ("Inspiration" Section on the Sidebar)
joomla_id: 164
joomla_url: adding-a-random-quote-inspiration-section-on-the-sidebar
date: 2014-10-14 01:33:49.000000000 +00:00
---
<p>We use the popular <a href="http://www.mytidbits.us/joomla321/" target="_blank">Rquotes component</a> to display random quotes on the sidebar of the SXS website.</p>
<h3>Adding (or Editing) a Quote to the Pool</h3>
<ol>
<li>In the backend, go to <strong>Components -&gt; Rquote! -&gt; Rquotes</strong>, you will see all the quotes that are currently in the pool. There is only one category "<strong>SXS Quotes</strong>" at the moment.</li>
<li>Click on any of the existing quotes to edit - it uses the JCE Editor just like any other articles.</li>
<li>Click on the orange "<strong>New</strong>" button to add a new quote.</li>
<li>This is what the interface looks like:
<p><img class="tnm" alt="quote" src="images/people/quote.jpg" height="601" width="450" /></p>
</li>
<li>Make sure to select "<strong>SXS Quotes</strong>" for the <strong>Category</strong> dropdown. In the top text editor, enter your quote. In the bottom editor which says "Author (optional)", enter the source of the quote (if needed).</li>
<li>Save when you are done. Your new quote will be added to the rotation.</li>
<li><strong>Trick</strong> - what if I want to <strong>start a new line</strong> <strong>in my quote but do not want a new paragraph</strong> (eg, for a poem)? Answer: Do <strong>NOT</strong> hit enter (or it will create a new paragraph which adds extra padding space below the line). Instead, hit <strong>SHIFT + Enter - </strong>that will give you a line break without starting a new paragraph.</li>
<li>To double check if this is working, you can click the <strong>Source Code Editor icon</strong> (circled in red below - the &lt; &gt; icon) to get into code mode for a second:
<p><img class="tnm" alt="quote br" src="images/people/quote_br.jpg" height="160" width="700" /></p>
</li>
<li>Just like in the above screenshot, <code>&lt;br /&gt;</code> is a line break, which should be placed right before the start of a new line (same goes for the "author" text). For example, the above set up will give you this:
<p><img alt="quote result" src="images/people/quote_result.jpg" /></p>
</li>
</ol>
