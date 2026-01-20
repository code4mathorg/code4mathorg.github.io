---
layout: default
permalink: /events/
---

<div id="calendar-container">Loading calendar...</div>

<script type="text/javascript">
const timezone = Intl.DateTimeFormat().resolvedOptions().timeZone 
const html = `<iframe src="https://calendar.google.com/calendar/embed?src=7000a514e4c452c330b7786deba4a311e5d2e7aac1951ba87451e2b0961882a8%40group.calendar.google.com&ctz=${timezone}" style=" border-width:0 " width="800" height="600" frameborder="0" scrolling="no"></iframe>`
document.getElementById('calendar-container').innerHTML = html;
</script>
