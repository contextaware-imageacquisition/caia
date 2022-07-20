---
layout: default
title: Context Aware Image Acquisition
---

<p style="text-align: justify;">
CAIA is a prototype workflow for the image documentation of existing buildings. It is based on openBIM standards such as the Industry Foundation Classes (IFC) and the BIM Collaboration Format (BCF). 
</p>

<p style="text-align: justify;">
Since most buildings today are not yet digitised, or even BIMified, CAIA is based first and foremost on a simple component: the 2D plan.
Using this plan in combination with your mobile device you can capture images on site and locate them in the building, either by manually positioning them, or by using Augmented Reality tracking.
</p>

<figure>
  <img src="{{site.baseurl}}images/Screenshots/ScreeshotCAIA.png" alt="CAIA mobile app"/>
  <figcaption style="text-align: center;"></figcaption>
</figure>

<p style="text-align: justify;">
These images can be uploaded to a server and shared with other participants of your project. A web application can access this information so you can review and filter your captured images in the browser.
</p>

<figure>
  <img src="{{site.baseurl}}images/Screenshots/SC_2D_Image.png" alt="2D view of the web application"/>
  <figcaption style="text-align: center;"></figcaption>
</figure>

<p style="text-align: justify;">
No BIM is necessary, which satisfies the needs of most building related projects.

However, CAIA can be connected with the BIM methodology, so that images, located on 2D plans, are spatially linked with the BIM model.
</p>

<figure>
  <img src="{{site.baseurl}}images/Screenshots/SC_3D_Image.png" alt="3D view of the web application"/>
  <figcaption style="text-align: center;"></figcaption>
</figure>


## Acknowledgements

This project was funded by the H2020 [BIM4Ren](https://bim4ren.eu) Project and received an [Epic Megagrant](https://www.unrealengine.com/en-US/blog/epic-megagrants-fall-2020-update) in 2020.



<!-- <div class="posts">
  {% for post in paginator.posts %}
    <article class="post">
      <a href="{{ site.baseurl }}{{ post.url }}">
        <h1>{{ post.title }}</h1>

        <div>
          <p class="post_date">{{ post.date | date: "%B %e, %Y" }}</p>
        </div>
      </a>
      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}

  <!-- pagination
  {% if paginator.total_pages > 1 %}
  <div class="pagination">
    {% if paginator.previous_page %}
      <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">&laquo; Prev</a>
    {% else %}
      <span>&laquo; Prev</span>
    {% endif %}

    {% for page in (1..paginator.total_pages) %}
      {% if page == paginator.page %}
        <span class="webjeda">{{ page }}</span>
      {% elsif page == 1 %}
        <a href="{{ '/' | prepend: site.baseurl | replace: '//', '/' }}">{{ page }}</a>
      {% else %}
        <a href="{{ site.paginate_path | prepend: site.baseurl | replace: '//', '/' | replace: ':num', page }}">{{ page }}</a>
      {% endif %}
    {% endfor %}

    {% if paginator.next_page %}
      <a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}">Next &raquo;</a>
    {% else %}
      <span>Next &raquo;</span>
    {% endif %}
  </div>
  {% endif %}
</div> -->
