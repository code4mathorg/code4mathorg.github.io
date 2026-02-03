---
layout: default
permalink: /events/
---

<div id="calendar-container">Loading calendar...</div>

## You may also be interested in these [MathTech.org](https://mathtech.org) events:

<div id="mathtech-calendar-container">Loading calendar...</div>

<script type="text/javascript">
const timezone = Intl.DateTimeFormat().resolvedOptions().timeZone 
const html = `<iframe src="https://calendar.google.com/calendar/embed?src=7000a514e4c452c330b7786deba4a311e5d2e7aac1951ba87451e2b0961882a8%40group.calendar.google.com&ctz=${timezone}" style=" border-width:0 " width="800" height="600" frameborder="0" scrolling="no"></iframe>`
document.getElementById('calendar-container').innerHTML = html;
const html2 = `<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&mode=AGENDA&showNav=1&showCalendars=0&showTitle=0&src=ODhjYmI0NWJhNDdjMDk0Yjk0ZjFkNjg1MjJhMTQxZjQ5NTllZWRlMDFiMDNjYzQ1MzAyNzg0YTE0ODJlY2Y3ZkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%23F09300&ctz=${timezone}" style=" border-width:0 " width="800" height="600" frameborder="0" scrolling="no"></iframe>`
document.getElementById('mathtech-calendar-container').innerHTML = html2;
</script>
