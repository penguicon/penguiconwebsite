---
layout: page
title: Events Calendar
permalink: /events-calendar/
category: About Penguicon
---
<div id="events-upcoming"></div>
<div id="events-past"></div>
<script>
formatGoogleCalendar.init({
 calendarUrl: 'https://www.googleapis.com/calendar/v3/calendars/penguicon.org_rtf9q8m4h6ml2gbfd7jg8ibp6k@group.calendar.google.com/events?key=AIzaSyArLN1xWJ5NMl9b131-giVz9E_BQM6djME',
 past: true,
 upcoming: true,
 sameDayTimes: true,
 dayNames: true,
 pastTopN: -1,
 upcomingTopN: 3,
 itemsTagName: 'div',
 upcomingSelector: '#events-upcoming',
 pastSelector: '#events-past',
 recurringEvents: true, 
 upcomingHeading: '<h2>Upcoming Events</h2>',
 pastHeading: '<h2>Past Events</h2>',
 format: ['<h3>', '*summary*', '</h3><p>', '*date*', '</p><p>', '*location*', '</p><p>', '*description*', '</p>'],
 timeMin: '2019-07-01T10:00:00-07:00',
 timeMax: '2020-07-01T10:00:00-07:00'
});
</script>