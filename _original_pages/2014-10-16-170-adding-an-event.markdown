---
layout: post
title: Adding an Event
joomla_id: 170
joomla_url: adding-an-event
date: 2014-10-16 12:22:35.000000000 +00:00
---
<p>The <strong>Upcoming Events</strong> and the calendar in the <a href="index.php?option=com_dpcalendar&amp;view=calendar&amp;Itemid=441">SXS Events page</a> were handled by the <strong>GCalendar</strong> plugin which syncs the events on the website to Google Calendar. However, GCalendar uses an older version of the Google API, which will no longer be supported after Nov 2014. Thus, the company came out with <strong>DPCalendar</strong> which is compatible with Google's new API and they provided <a href="http://joomla.digital-peak.com/documentation/58-dpcalendar/697-how-to-migrate-from-gcalendar" target="_blank">a way to migrate GCalendar to the new DPCalendar</a>. Please note that <strong>we need to keep both extensions</strong> for it to work properly - think of DPCalendar as a patch update of GCalendar.</p>
<p>Currently, <strong>Upcoming Events</strong> and the calendar in the <a href="index.php?option=com_dpcalendar&amp;view=calendar&amp;Itemid=441">SXS Events</a> page sync with the Google Calendar under <a href="mailto:projectsxs@gmail.com">projectsxs@gmail.com</a> (Mike Boyle and Yvonne Tang have access to at the moment). There are <strong>3 subcalendars - SXS - All, SXS - Faculty and SXS Public Events</strong>. It is set up so that "<strong>Upcoming Events</strong>" will display all events aded to SXS - All and SXS Public Events, while the calendar in the <a href="index.php?option=com_dpcalendar&amp;view=calendar&amp;Itemid=441">SXS Events</a> page will display events from all three.</p>
<h3>Adding an Event</h3>
<p>To add an event, go to Google Calendar and click on a date, a box will pop up for you to add the event (see below screenshot). In "<strong>What</strong>", enter the name of your event. For "<strong>Calendar</strong>", pick the correct calendar that your event belongs to. To add more info, click on "<strong>Edit event &gt;&gt;</strong>" or just click the "<strong>Create event</strong>" button to save the event - you can always go back to edit it later.</p>
<p><img class="tnm" alt="adding event" src="images/tutorials/adding_event.jpg" height="273" width="598" /></p>
<p>When you are in the event editing screen, you can for example, add a time, a location and a description to the event (see below screenshot), which will all sync in real time with the events displayed on the SXS website. To enter a <strong>time</strong> for the event, you need to first <strong>uncheck the "All day" check box</strong>. If you enter a valid location in "<strong>Where</strong>", a Google Map with a marker showing the location of the event will be displayed on the event page.</p>
<p><img class="tnm" alt="editing event" src="images/tutorials/editing_event.jpg" height="464" width="591" /></p>
<p>Hit <strong>Save</strong> when you are done.</p>
