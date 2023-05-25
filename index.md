---
layout: home
title: Retro Game Art at Its Finest
description: Step into a time machine and experience the nostalgia of retro game art. 
---
<div class="row row-cols-2 row-cols-lg-4">
  {% for product in site.products %} 
  <div class="col mb-3">
    <div class="card shadow-sm rounded-3">
      <a href="{{ product.url }}">
        <img width="100%" src="images/{{ product.image-1 }}">
        <div class="card-body">
          <p class="mb-1">{{ product.title }}</p>
          <small class="text-secondary">{{ product.size }}</small><br>
          <strong>{{ product.price }}</strong> <small>{{ product.shipping }}</small>
        </div>
      </a>
    </div>
  </div>
  {% endfor %}
</div>
<hr class="col-md-3 mb-5 mt-5">
<div class="row mt-5">
  <div class="col-md-3">
    <h3 class="mb-4">About</h3>
    <img class="rounded-circle pb-2" width="88px" src="images/Naccarato-Tony.jpeg">
    <p>Liam Wooley<br>
    <small class="text-muted">Utah</small></p>
    <p>
    <small>Digital AI Artist</small><br>
    <span class="fw-bold">-</span>
    </p>
  </div>
  <div class="col-md-7 mt-5">
    <p></p>
  </div>
</div>