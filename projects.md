---
layout: page
title: Projects
permalink: /projects/
style: /assets/index.css
---

<section id="projects">
  <div class="tabs">
    {% for project in site.data.projects %}
      <div class="tab">
        <input type="radio" id="tab-{{ forloop.index }}" name="tabs" {% if forloop.first %}checked="checked"{% endif %}>
        <label for="tab-{{ forloop.index }}">{{ project.name }}</label>
        <div class="tab-content">
          <div class="tab-header">
            <h3>{{ project.name }}</h3>
            {% if project.url %}
              <div class="tab-url">
                <a href="{{ project.url }}" target="_blank">{{ project.url }}</a>
              </div>
            {% endif %}
          </div>
          <div class="tab-body">
            {% if project.image %}
              <img src="{{ project.image | relative_url }}" alt="{{ project.name }} logo" class="tab-image">
            {% endif %}
            <p class="tab-description">{{ project.description }}</p>
          </div>
        </div>
      </div>
    {% endfor %}
  </div>
</section>