---
layout: default
title: Home
---
<div class="hero">
  <h1>{{ site.author.name }}</h1>
  <p class="tagline">Researcher &middot; Writer &middot; Political thinker</p>
</div>

<p>Welcome to my personal website. Here you'll find my research, political writing, and blog posts on topics I care about.</p>

<div class="home-sections">
  <div class="home-card">
    <h2>About Me</h2>
    <p>A little about who I am, what I do, and what drives me.</p>
    <a class="read-more" href="{{ '/about' | relative_url }}">Read more &rarr;</a>
  </div>
  <div class="home-card">
    <h2>Works</h2>
    <p>Research papers, political essays, and other projects I've worked on.</p>
    <a class="read-more" href="{{ '/works/' | relative_url }}">Explore &rarr;</a>
  </div>
  <div class="home-card">
    <h2>Blog</h2>
    <p>Thoughts, reflections, and shorter pieces on a range of subjects.</p>
    <a class="read-more" href="{{ '/blog/' | relative_url }}">Read posts &rarr;</a>
  </div>
  <div class="home-card">
    <h2>Archive</h2>
    <p>A chronological index of everything I've published on this site.</p>
    <a class="read-more" href="{{ '/archive' | relative_url }}">Browse &rarr;</a>
  </div>
</div>
