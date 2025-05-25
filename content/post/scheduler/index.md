---
title: 최신 교육 일정 정보
description: 미용 교육 정복하자✨🪄
slug: study-schedule
date: 2022-05-06 00:00:00+0000
image: edu_cover.png
categories:
    - Example Category
tags:
    - Example Tag
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

<link href="https://cdn.jsdelivr.net/npm/fullcalendar@6.1.8/main.min.css" rel="stylesheet" />
<script src="
https://cdn.jsdelivr.net/npm/fullcalendar@6.1.17/index.global.min.js
"></script>

<div id="calendar"></div>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    var calendarEl = document.getElementById('calendar');
    var calendar = new FullCalendar.Calendar(calendarEl, {
      initialView: 'dayGridMonth',
      events: [
        { title: '미팅', start: '2025-06-01' },
        { title: '마감일', start: '2025-06-10' }
      ]
    });
    calendar.render();
  });
</script>

<style>
  #calendar {
    max-width: 900px;
    margin: 40px auto;
  }
</style>