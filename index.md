---
layout: home
image: 'assets/images/og_image.jpg'
description: 'Emil Osmanbegovic | Web developer & visual artist from Serbia'
---

## Web developer & visual artist from Serbia

[Read CV](/cv)
[GitHub](https://www.github.com/emilosman)
[Email](mailto:emilosmanbegovic@gmail.com)
[LinkedIn](https://www.linkedin.com/in/emil-osmanbegovi%C4%87-357579123/)

Hello!  
I am a web-developer from Novi Sad, Serbia.

I have been working with web technologies since 2016.

### Tech skills
-
-
-
-

I write code to make my life easier and by extension, help others.

### Experience and Distinctions
Client experience covering projects for ...  
[You can read my detailed CV with work history here.](/cv)

### Personal projects
<div>
 {% if site.paginate %}
        {% assign posts = paginator.posts %}
      {% else %}
        {% assign posts = site.posts %}
      {% endif %}
      
      {%- if posts.size > 0 -%}
        <div class="row">
          {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
          {%- for post in posts -%}
      
            <div class="col-sm-6 col-xs-12">
              <a href="{{ post.url | relative_url }}" class="c-hero__tile c-hero__tile--hover c-shadow mb-4">
                <h3 class="c-hero__tile__label p-2 m-4">
                  {{ post.title | escape }}
                </h3>
                <div class="c-hero__tile__description">{{post.description}}</div>
                <div class="c-hero__tile__image c-hero__tile__image--main">
                  <img src="{{post.image}}" alt="{{post.title | escape}}"/>
                </div>
              </a>
            </div>
      
          {%- endfor -%}
        </div>
      
        {% if site.paginate %}
          <div class="pager">
            <ul class="pagination">
            {%- if paginator.previous_page %}
              <li><a href="{{ paginator.previous_page_path | relative_url }}" class="previous-page">{{ paginator.previous_page }}</a></li>
            {%- else %}
              <li><div class="pager-edge">•</div></li>
            {%- endif %}
              <li><div class="current-page">{{ paginator.page }}</div></li>
            {%- if paginator.next_page %}
              <li><a href="{{ paginator.next_page_path | relative_url }}" class="next-page">{{ paginator.next_page }}</a></li>
            {%- else %}
              <li><div class="pager-edge">•</div></li>
            {%- endif %}
            </ul>
          </div>
        {%- endif %}
      {%- endif -%}
</div>

### Want to chat about tech and art?
Do not hesitate to contact me to work together:
...

-
-
-
-
-

2020, emilosman.com
