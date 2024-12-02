---
title: Projects
layout: default
permalink: /projects/
published: true
---

<div class="ProjectContainer">
  <div id="projectsGrid">
    {% for project in site.projects %}
      <div class="projectTile">
        <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
          <img src="{{ project.image }}" alt="{{ project.title }} Thumbnail">
          <div class="projectContent">
            <span class="categoryTag {{ project.category | downcase | replace: ' ', '-' }}">
              {{ project.category }}
            </span>
            <h2>{{ project.title }}</h2>
            <p>{{ project.description }}</p>
          </div>
        </a>
      </div>
    {% endfor %}
  </div>
</div>

<style>
  #projectsGrid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }
  
  .projectTile {
    width: 300px;
    height: 200px;
    position: relative;
    border-radius: 8px;
    overflow: hidden;
  }
  
  .projectTile img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }
  
  .projectContent {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    padding: 15px;
    background: rgba(0, 0, 0, 0.7);
    color: white;
    display: flex;
    flex-direction: column;
  }
  
  .projectContent h2 {
    margin: 0 0 8px 0;
    font-size: 1.2rem;
    color: white;
  }
  
  .projectContent p {
    margin: 0;
    font-size: 0.9rem;
    color: rgba(255, 255, 255, 0.9);
    line-height: 1.4;
    flex-grow: 1;
  }
  
  .projectTile a {
    text-decoration: none;
  }

  .categoryTag {
    display: inline-block;
    padding: 2px 6px;
    border-radius: 3px;
    font-size: 0.7rem;
    font-weight: 500;
    margin-top: auto;
    align-self: flex-start;
  }

  /* Category-specific colors */
  .software-development {
    background-color: #61dafb;
    color: #000;
  }

  .hardware-development {
    background-color: #ff6b6b;
    color: #fff;
  }

  .mechanical-design {
    background-color: #ffd93d;
    color: #000;
  }

  .entrepreneurship {
    background-color: #4cd137;
    color: #fff;
  }

  .random {
    background-color: #a55eea;
    color: #fff;
  }
</style>
