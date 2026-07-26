---
permalink: /research/
title: "Research"
author_profile: true
---

## Work in Progress

**The Hawk in the Room**
<br/>
<button onclick="visib('paper-one')" class="abstract-btn">Abstract</button>

<div id="paper-one" style="display: none; text-align: justify; line-height: 1.2"><small>
Coming soon!
</small><br><br/></div>

<style>
.abstract-btn {
  display: inline-block;
  margin-top: 0.2em;
  padding: 0.3em 0.9em;
  font-family: inherit;
  font-size: 0.72em;
  font-weight: bold;
  color: #4d4d4d;
  background-color: #ebebeb;
  border: 0;
  border-radius: 4px;
  cursor: pointer;
  transition: background-color 0.15s ease;
}
.abstract-btn:hover {
  background-color: #dcdcdc;
  color: #1a1a1a;
}
</style>

<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>
