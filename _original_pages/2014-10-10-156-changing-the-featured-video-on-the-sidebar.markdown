---
layout: post
title: Changing the "Featured Video" on the Sidebar
joomla_id: 156
joomla_url: changing-the-featured-video-on-the-sidebar
date: 2014-10-10 06:51:16.000000000 +00:00
---
<p>Video embedding on this website is handled using the <strong>AllVideos plugin by JoomlaWorks</strong>.&nbsp;<a href="http://www.joomlaworks.net/extensions/free/allvideos" target="_blank"></a>Please <a href="http://www.joomlaworks.net/extensions/free/allvideos" target="_blank">check out their site for complete documentation</a> if needed, as they support videos hosted on many websites, not just Youtube. I only mention Youtube here since SXS has a Youtube channel.</p>
<ol>
<li>On the backend, go to <strong>Extensions -&gt; Module Manager</strong>.</li>
<li>Open up the "<strong>Featured Video</strong>" (marked by <span style="color: #ff6600;"><strong>Orange</strong></span> color) module.</li>
<li>In the editor area, you will see a simple line of code like this:
<p><img alt="youtube" src="images/tutorials/youtube.png" /></p>
</li>
<li>The string between the pair of youtube curly bracket tags is the "ID" of the video. You can find this string in the Youtube URL of the video that typically looks like this <a href="https://www.youtube.com/watch?v=yhUzYLMU6jM">https://www.youtube.com/watch?v=yhUzYLMU6jM</a> (this is the URL of the official Cosmos trailer for example).</li>
<li>If you want to put this video in the sidebar, just replace the string between the tags with the ID of this video (<strong>string in the URL after youtube.com/watch?v=</strong>). In our example, put yhUzYLMU6jM between the pair of youtube curly bracket tags.</li>
<li>Save and you are done.</li>
</ol>
