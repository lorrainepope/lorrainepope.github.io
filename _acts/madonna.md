---
layout: acts
image:  ../assets/images/madonna tribute acts and shows.jpg
description: scotbase madonna tributes all have the wow factor. fabulous vocals, choreographed dance routines, stunning costumes and amazing musicians these shows are not to be missed.undoubtedly, madonna is the Ultimate Queen Of Pop and after four decades she is as popular as ever. as is our tributes to her. <hr>
            call now for INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.madonna %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>
