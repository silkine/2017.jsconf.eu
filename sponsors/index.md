---
  layout: simple-page
  title: Sponsorship for JSConf EU 2017
  title-short: Sponsors
  pattern: bg-pink-white
---

{% assign sponsors=site.tags.sponsor %}
{% assign overview=true %}

<p>
  We are offering sponsorship packages and partnerships for JSConf EU 2017. <a href="mailto:contact@jsconf.eu">Contact us for details</a>.
</p>

<p>
  Check out our a summary video of the last JSConf EU for a closer look at the event.
</p>

<div class="embed_container">
  <iframe width="560" height="315" src="http://www.youtube.com/embed/VHbnuNng0M8" frameborder="0" allowfullscreen="true"></iframe>
</div>

<!-- <p>
  These companies are our supporters in 2017:
</p>

{% for post in sponsors %}
  {% if post.level == "sponsor-special" %}
  <div class="sponsor">
    <img src="{{ site.baseurl }}{{post.image}}" class="img-flex" />
    <h4>
      <a href="{{ site.baseurl }}{{post.permalink}}">{{ post.title }}</a>
    </h4>
    {{ post.content }}
  </div>
  {% endif %}
{% endfor %}

{% for post in sponsors %}
  {% if post.level == "sponsor-main" %}
  <div class="sponsor">
    <img src="{{ site.baseurl }}{{post.image}}" class="img-flex" />
    <h4>
      <a href="{{ site.baseurl }}{{post.permalink}}">{{ post.title }}</a>
    </h4>
    {{ post.content }}
  </div>
  {% endif %}
{% endfor %}

{% for post in sponsors %}
  {% if post.level == "sponsor-support" %}
  <div class="sponsor">
    <img src="{{ site.baseurl }}{{post.image}}" class="img-flex" />
    <h4>
      <a href="{{ site.baseurl }}{{post.permalink}}">{{ post.title }}</a>
    </h4>
    {{ post.content }}
  </div>
  {% endif %}
{% endfor %}

{% for post in sponsors %}
  {% if post.level == "sponsor-custom" %}
  <div class="sponsor">
    <img src="{{ site.baseurl }}{{post.image}}" class="img-flex" />
    <h4>
      <a href="{{ site.baseurl }}{{post.permalink}}">{{ post.title }}</a>
    </h4>
    {{ post.content }}
  </div>
  {% endif %}
{% endfor %}

{% for post in sponsors %}
  {% if post.level == "sponsor-verycustom" %}
  <div class="sponsor">
    <a href="{{ site.baseurl }}{{post.permalink}}"><img src="{{ site.baseurl }}{{post.image}}" class="img-flex" /></a>
    <h4>
      <a href="{{ site.baseurl }}{{post.permalink}}">{{ post.title }}</a>
    </h4>
    {{ post.content }}
  </div>
  {% endif %}
{% endfor %}

<div class="sponsor">
  <h4>
    Travel sponsors
  </h4>
  <ul>
    <li>Atlassian<Uli>
    <li>VhTO<Uli>
    <li>Namely<Uli>
    <li>ThoughtWorks<Uli>
    <li>Angefragt<Uli>
    <li>Opera Software ASA<Uli>
    <li>Zendesk<Uli>
    <li>Google<Uli>
  </ul>
</div>
-->
