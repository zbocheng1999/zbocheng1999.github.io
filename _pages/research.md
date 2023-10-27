---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

## Research
Demand side of Education
<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Example Research</h4>

Example description
</div>
</div>

## Publications
<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron">
#### Research in Progress
#### No paper, only titles, but you can think that I am working on something
{% bibliography --query @idea %}
#### Papers exist but not done yet
{% bibliography --query @unpublished %}
</div>


<div class="jumbotron">
#### Published
{% bibliography --query @article %}
</div>