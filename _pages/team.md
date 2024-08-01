---
layout: page
permalink: /team/
title: Members
description: #Our research team.
nav: true
---
<!-- _pages/team.md -->
<div class="team">
  {% for position in site.data.team %}
    <div class="position">
      <h2>{{position[0]}}</h2>
      <div class="row">
        {% for member in position[1] %}
          {% if position[0] == "Professors" %}
            <div class="col-12">
              <div class="card hoverable" id="{{member.name | join: '_' | downcase}}">
                <div class="row no-gutters">
                  {% if member.homepage %}
                    <div class="col-sm-4 col-md-3 profile-image cursor-pointer" onclick="location.href='{{member.homepage}}'">
                  {% else %}
                    <div class="col-sm-4 col-md-3 profile-image">
                  {% endif %}
                  {% include figure.html path=member.photo %}
                  </div>
                  <div class="team col-sm-8 col-md-9">
                    <div class="card-body">
                      {% if member.homepage %}
                      <a href="{{member.homepage}}">
                      {% endif %}
                      <h5 class="card-title">{{member.name | join: ' '}}</h5>
                      <h6 class="card-subtitle mb-2 text-muted">{{member.subtitle}}</h6>
                      <p class="card-text main">
                        {{member.introduction}}
                      </p>
                      {% if member.homepage %}
                      </a>
                      {% endif %}
                      <div class="toolbar">
                        {% if member.email %}
                          <a href="mailto:{{member.email}}" class="card-link"><i class="fas fa-envelope"></i></a>
                        {% endif %}
                        {% if member.homepage %}
                          <a href="{{member.homepage}}" class="card-link"><i class="fas fa-home"></i></a>
                        {% endif %}
                        {% if member.linkedin %}
                          <a href="{{member.linkedin}}" class="card-link" target="_blank"><i class="fab fa-linkedin"></i></a>
                        {% endif %}
                        {% if member.scholar %}
                          <a href="{{member.scholar}}" class="card-link" target="_blank"><i class="ai ai-google-scholar"></i></a>
                        {% endif %}
                        {% if member.github %}
                          <a href="{{member.github}}" class="card-link" target="_blank"><i class="fab fa-github"></i></a>
                        {% endif %}
                      </div>
                      {% if member.location %}
                      <p class="card-text">
                        <small class="test-muted"><i class="fas fa-thumbtack"></i> {{member.location}} </small>
                      </p>
                      {% endif %}
                    </div>
                  </div>
                </div>
              </div>
            </div>
          {% else %}
            <div class="col-sm-4 d-flex">
              <div class="card hoverable flex-grow-1" id="{{member.name | join: '_' | downcase}}">
                <div class="profile-image">
                  {% include figure.html path=member.photo %}
                </div>
                <div class="card-body">
                  {% if member.homepage %}
                  <a href="{{member.homepage}}">
                  {% endif %}
                  <h5 class="card-title">{{member.name | join: ' '}}</h5>
                  <h6 class="card-subtitle mb-2 text-muted">{{member.subtitle}}</h6>
                  {% if member.homepage %}
                  </a>
                  {% endif %}
                  <div class="toolbar">
                    {% if member.email %}
                      <a href="mailto:{{member.email}}" class="card-link"><i class="fas fa-envelope"></i></a>
                    {% endif %}
                    {% if member.homepage %}
                      <a href="{{member.homepage}}" class="card-link"><i class="fas fa-home"></i></a>
                    {% endif %}
                    {% if member.linkedin %}
                      <a href="{{member.linkedin}}" class="card-link" target="_blank"><i class="fab fa-linkedin"></i></a>
                    {% endif %}
                    {% if member.scholar %}
                      <a href="{{member.scholar}}" class="card-link" target="_blank"><i class="ai ai-google-scholar"></i></a>
                    {% endif %}
                    {% if member.github %}
                      <a href="{{member.github}}" class="card-link" target="_blank"><i class="fab fa-github"></i></a>
                    {% endif %}
                  </div>
                  {% if member.location %}
                  <p class="card-text">
                    <small class="test-muted"><i class="fas fa-thumbtack"></i> {{member.location}} </small>
                  </p>
                  {% endif %}
                </div>
              </div>
            </div>
          {% endif %}
        {% endfor %}
      </div>
    </div>
  {% endfor %}
</div>
