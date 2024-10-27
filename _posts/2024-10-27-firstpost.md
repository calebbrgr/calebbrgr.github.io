---
layout: post
title: my first post
date: 2024-10-27 14:40:00
description: this is what included tabs in a post could look like
tags: post
categories: sample-posts
tabs: true
---
# First Post

Nulla ipsum sapien, accumsan ut egestas vitae, pharetra interdum libero. Curabitur iaculis facilisis viverra. Integer feugiat ipsum nec metus tempor dictum. Nunc non facilisis massa. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Sed quis felis aliquam, auctor enim id, euismod nisl. Maecenas facilisis, lectus quis feugiat tempus, massa tellus lacinia eros, eu dignissim massa felis vitae nisi. Phasellus eleifend nunc ut tincidunt suscipit. Cras commodo pretium dapibus. Sed vulputate vestibulum mollis. Cras eu nisi orci. Nam vel est quis neque lobortis porta. Donec vel mauris eget lectus varius cursus vel non neque. 

This is an example post with image galleries.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/9.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/7.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A simple, elegant caption looks good between image rows, after each row, or doesn't have to be there at all.
</div>

Images can be made zoomable.
Simply add `data-zoomable` to `<img>` tags that you want to make zoomable.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/8.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/10.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>