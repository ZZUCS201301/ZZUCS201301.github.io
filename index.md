---
layout: page
title: 编号201324301
tagline: --our story
---
{% include JB/setup %}

###This is our story

<script src="//code.jquery.com/jquery-1.11.0.min.js"></script>
<style>
.timeline {
  position: relative;
  margin-top: 30px;
  margin-bottom: 30px;
  height: 60px;
}
.line {
  height: 4px;
  background-color: #888;
  width: 100%;
  top: 50%;
  margin-top: 0px;
  position: absolute;
}
.time-item {
  position: relative;
  display: inline-block;
  zoom: 1;
  margin-right: 40px;
}
.time {
  display: block;
  background-color: #1A69EC;
  color: #fff;
  border-radius: 60px;
  width: 60px;
  height: 60px;
  line-height: 60px;
  font-size: 13px;
  text-align: center;
}
.event {
  background-color: rgba(0,0,0,.8);
  padding: 10px;
  border-radius: 4px;
  -webkit-border-radius: 4px;
  display: none;
  position: absolute;
  bottom: 40px;
  color: #fff;
}
.event:before {
  content: "";
  display: block;
  position: absolute;
  bottom: -20px;
  height: 0;
  width: 0;
  overflow: hidden;
  font-size: 0;
  line-height: 0;
  border-color: rgba(0,0,0,.8) transparent transparent transparent;
  border-style: solid dashed dashed dashed;
  border-width: 40px 0 0 0;
}
.time-item:hover .event {
  display: block;
}
</style>
<div class="timeline">
    <div class="line"></div>
    <div class="time-item">
      <span class="time">2013.09</span>
      <div class="event">We met.</div>
    </div>
    <div class="time-item">
      <span class="time">2014</span>
      <div class="event">To be continued</div>
    </div>
</div>
