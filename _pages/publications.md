---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021,2022,2023]
---

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
### Working in Progress
{% bibliography --query @idea %}
{% bibliography --query @unpublished %}
</div>


<div class="jumbotron">
### Published
{% bibliography --query @article %}
</div>

