<h2 id="publications" style="margin: 2px 0px -15px;">
Selected Publications
<a href="https://www.ccf.org.cn/Academic_Evaluation/By_category/" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CCF-Rank]</a>
<a href="https://www.caai.cn/index.php?s=/home/article/detail/id/3445.html" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CCAI-Rank]</a>
<a href="http://portal.core.edu.au/conf-ranks/" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CORE-Rank (conf)]</a>
<a href="http://portal.core.edu.au/jnl-ranks/" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:14px;">[CORE-Rank (jnl)]</a>
<!-- <img src="https://img.shields.io/badge/dynamic/json?style=plastic&labelColor=f6f6f6&color=9cf&style=flat&label=Citations&logo=Google%20Scholar&query=total_citations&url=https://cse.bth.se/~fer/googlescholar-api/googlescholar.php?user=vWBd1VsAAAAJ"> -->
</h2>


<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<!-- <div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 0px;padding-left: 5px;padding-top: 0px;">
    {% if link.image %}
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=50">
    {% endif %}
    {% if link.conference_short %}
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
  </div> -->
  <div class="col-sm-12" style="position: relative;padding-right: 0px;padding-left: 15px;">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical">{{ link.conference }}
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
      <a href="{{ link.appendix }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Supplemental</a>
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
  </div>
</div>
</li>

<br>

{% endfor %}

</ol>
</div>
