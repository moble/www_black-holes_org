---
layout: post
title: Inserting Youtube Videos/Audio Clips Inside an Article
joomla_id: 171
joomla_url: inserting-youtube-videos-audio-clips-inside-an-article
date: 2014-10-10 06:51:16.000000000 +00:00
---
<h3>Embedding a Youtube Video</h3>
<p>Video embedding on this website is handled using the <strong>AllVideos plugin by JoomlaWorks</strong>.&nbsp;<a href="http://www.joomlaworks.net/extensions/free/allvideos" target="_blank"></a>Please <a href="http://www.joomlaworks.net/extensions/free/allvideos" target="_blank">check out their site for complete documentation</a> if needed, as they support videos hosted on many websites, not just Youtube. I only mention Youtube here since SXS has a Youtube channel.</p>
<ol>
<li>In the article text editor area, put in an expression in the form as below will embed a Youtube video into your article.<br />
<p><img alt="youtube" src="images/tutorials/youtube.png" /></p>
</li>
<li>The string between the pair of youtube curly bracket tags is the "ID" of the video. You can find this string in the <strong>Youtube URL</strong> of the video that typically looks like this <a href="https://www.youtube.com/watch?v=yhUzYLMU6jM">https://www.youtube.com/watch?v=yhUzYLMU6jM</a> (this is the URL of the official Cosmos trailer for example).</li>
<li>If you want to put this video in the sidebar, just replace the string between the tags with the ID of this video (<strong>string in the URL after youtube.com/watch?v=</strong>). In our example, put yhUzYLMU6jM between the pair of youtube curly bracket tags.</li>
<li><strong>Save</strong> and you are done.</li>
</ol>
<h3>Inserting an Audio Clip</h3>
<ol>
<li>It is easy to insert an audio clip like those on the <a href="index.php?option=com_content&amp;view=article&amp;id=121&amp;Itemid=238">Explore -&gt; Sounds</a> page.</li>
<li>I have made a template with a code snippet for sound clips using the extension Content Templater. To insert this code snippet, mouse over the "<strong>Insert Template</strong>" icon at the bottom of the text editor, a menu with the list of available template will appear. Pick "<strong>Sound Clip Template</strong>".<br /><img class="tnm" alt="sound template" src="images/tutorials/sound_template.jpg" height="347" width="509" /></li>
<li>Now you should have something that looks like the following in the text editor<br /><img class="tnm" alt="sound" src="images/tutorials/sound.jpg" height="92" width="345" /></li>
<li>Replace "<strong>Text description of the sound clip goes here</strong>" with your own description.</li>
<li>Click the <strong>&lt;&gt; icon</strong> to go into Source Code Editor.</li>
<li>Change the part circled in red (see below screenshot) to the <strong>filename of the sound clip</strong> you are inserting. This sound clip needs to already exist in the "<strong>sound</strong>" folder inside the website's root directory.<br /><img class="tnm" alt="sound file name" src="images/tutorials/sound_file_name.jpg" height="336" width="486" /></li>
<li>Click the &lt;&gt; icon again to leave the code mode and save your changes.</li>
</ol>
<h4>This is what the above sound clip template gives you:</h4>
<div class="sound">
<p class="icon-volume-up">&nbsp;My Sound Clip (Tutorial)</p>
<p>
<audio src="sound/Periodic.wav" type="audio/x-wav"></audio>
</p>
</div>
