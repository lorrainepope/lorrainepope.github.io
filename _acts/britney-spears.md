---
layout: acts
image:  ../assets/images/britney spears tribute acts.jpg
description: scotbase britney spears tributes are energetic ladies with fabulous vocals, choreographed dance routines and stunning costumes.American Top Pop Princess Britney Spears is well represented at scotbase. choose from our talented britney tributes and your event will sizzle. <hr>
            call today for advice, QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.britney-spears %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
         <!-- <div class="card-body">
          <p class="card-text">{{ item.description }}</p>
        </div> -->
      </div>
    </div>
  {% endfor %}
</div>