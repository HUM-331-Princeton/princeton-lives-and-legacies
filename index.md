---
layout: default
---

# Welcome To Our HUM 331 Final Project Site! #
The goal of this digital platform is to have our audience dive into the question of what makes a legacy on Princeton University’s campus. As we tackled an unconventional year as an academic community both on and off campus, we often found ourselves wistfully remembering walks throughout Princeton’s historical landmarks as well as questioning the names that were attached to certain monuments and buildings. In a time of virtual hugs and handshakes, we wanted to first and foremost bring the campus to those studying off campus and show that digital spaces can bring together elements from inside a library and the monuments and buildings you see outside.

We tackled the Princeton archives, old newspaper records, and outside sources to find the best intersection of lifeblood for each of the individuals below to pair with their on campus memorials. But how do these public commemorations of (in)famous Princetonians intersect with the public and private archival records of their lives? We chose to tackle this first by creating the story map you see below, allowing you to engage with a virtual tour of the campus. This leads you to five pages for five of the most significant (and interesting) Princetonians we could get archival material into our hands on. From world-renowned theoretical physicists to beloved novel writers the dark undercurrent of slavery and racism at Princeton, this site tackles every story from every angle, allowing you to truly ask yourself: Who do we choose from history to build a legacy for, and why?

# Explore The Legacies On Campus #
<iframe src="https://uploads.knightlab.com/storymapjs/c8110923c34d5ea5480530eebcafc33c/princeton-lives-and-legacies/index.html" frameborder="0" width="100%" height="800"></iframe>

# Read Through The Project #
<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <header class="post-header">
      <h2 class="post-title"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
      <h4>By {{ post.author1 }} & {{ post.author2 }}</h4>
      </header>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
