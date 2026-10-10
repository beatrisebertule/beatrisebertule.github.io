---
layout: default
title: About
---

<div class="hero">
  <img class="avatar" src="{{ '/assets/img/avatar.svg' | relative_url }}" alt="Photo of {{ site.name }}">
  <div class="hero-text">
    <h1>Hi, I'm {{ site.name }} 👋</h1>
    <p class="lead">{{ site.tagline }}</p>
    <p class="muted small">📍 {{ site.location }}</p>
  </div>
</div>

<div class="buttons">
  <a class="btn primary" href="{{ '/cv/' | relative_url }}">View my CV</a>
  <a class="btn" href="{{ site.links.linkedin }}" target="_blank" rel="noopener">LinkedIn</a>
  <a class="btn" href="{{ site.links.github }}" target="_blank" rel="noopener">GitHub</a>
</div>

## Who I am

Write two or three short paragraphs about yourself here. What do you do, what
drives you, and what are you working on right now? Keep it personal and simple —
this is the first thing visitors read.

For example: I'm a developer who enjoys turning messy problems into clear, useful
tools. I've spent the last few years working on … and I'm currently exploring …

## What you'll find here

<div class="cards">
  <a class="card" href="{{ '/experience/' | relative_url }}" style="text-decoration:none">
    <span class="emoji">💼</span>
    <h3>Experience</h3>
    <p>Where I've worked and what I care about professionally.</p>
  </a>
  <a class="card" href="{{ '/hobbies/' | relative_url }}" style="text-decoration:none">
    <span class="emoji">🎨</span>
    <h3>Hobbies</h3>
    <p>What I get up to when I'm not working.</p>
  </a>
  <a class="card" href="{{ '/cv/' | relative_url }}" style="text-decoration:none">
    <span class="emoji">📄</span>
    <h3>CV</h3>
    <p>My full CV, to read online or download as PDF.</p>
  </a>
</div>

## Get in touch

The easiest way to reach me is by [email](mailto:{{ site.email }}) or on
[LinkedIn]({{ site.links.linkedin }}).
