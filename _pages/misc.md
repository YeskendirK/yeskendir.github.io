---
layout: page
permalink: /repositories/
title: Miscellaneous
description: 
nav: true
nav_order: 3
---

### Honors & Awards

<!-- #Education -->
<div class="publications">
        <div class="row">
            <div class="col-sm-4 abbr">
                <div class="title">Honorable Mention</div>
            </div>
            <div class="col-sm-8">
                <div class="title"><b>Asian Physics Olympiad (APhO)</b></div>
                Singapore, 2014
            </div>
        </div>
        <div class="row">
            <div class="col-sm-4 abbr">
                <div class="title">Silver Medal</div>
            </div>
            <div class="col-sm-8">
                <div class="title"><b>International Zhautykov Olympiad (Physics)</b></div>
                Kazakhstan, 2014
            </div>
        </div>
        <div class="row">
            <div class="col-sm-4 abbr">
                <div class="title">Silver Medal</div>
            </div>
            <div class="col-sm-8">
                <div class="title"><b>National Physics Olympiad</b></div>
                Kazakhstan, 2014
            </div>
        </div>
        <div class="row">
            <div class="col-sm-4 abbr">
                <div class="title">Gold Medal</div>
            </div>
            <div class="col-sm-8">
                <div class="title"><b>National Physics Olympiad</b></div>
                Kazakhstan, 2013
            </div>
        </div>
        <div class="row">
            <div class="col-sm-4 abbr">
                <div class="title">Silver Medal</div>
            </div>
            <div class="col-sm-8">
                <div class="title"><b>National Physics Olympiad</b></div>
                Kazakhstan, 2012
            </div>
        </div>
</div>
<br>

### GitHub Page

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div>
{% endif %}



{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
