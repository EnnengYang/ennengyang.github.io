<h2 id="pre_publications" style="margin: 2px 0px -15px;">Selected Preprints</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.pre_publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 0px;padding-left: 5px;padding-top: 0px;">
    {% if link.image %}
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=50%">
    {% endif %}
    {% if link.conference_short %}
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 0px;padding-left: 15px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %}
      <a href="{{ link.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Paper</a>
      {% endif %}
      {% if link.code %}
      <a href="{{ link.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if link.page %}
      <a href="{{ link.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if link.appendix %}
      <a href="{{ link.appendix }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">supplemental</a>
      {% endif %}
      {% if link.bibtex %}
      <a href="{{ link.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if link.notes %}
      <strong> <i style="color:#e74d3c;font-size:12px;">{{ link.notes }}</i></strong>
      {% endif %}
      {% if link.others %}
      {{ link.others }}
      {% endif %}
    </div>
    <!-- <div class="cite"><img src="https://img.shields.io/github/stars/ennengyang/Awesome-Forgetting-in-Deep-Learning"></div> -->
    <div class="cite"><img src="https://img.shields.io/github/stars/ennengyang/Awesome-Forgetting-in-Deep-Learning?style=flat&label=Stars&logo=github&labelColor=f6f6f6&color=9cf&logoColor=020d12"></div>
  </div>
</div>
</li>

<br>

{% endfor %}

</ol>
</div>
