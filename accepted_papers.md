---
title: Call for Papers
# workshop_name: neurips2025
site_description: Workshop on ML for Systems at NeurIPS 2025, December 6, San Diego Convention Center, Upper Level Room 5AB
mini_site_description: Workshop on ML for Systems at NeurIPS '25, Dec 6, Upper Level Room 5AB
site_title: ML For Systems
---
<div id="content-wrapper">
<div class ="accepted_papers_section">
<div class="inner clearfix">
    <section class="main-content">
        <h2>Accepted Papers</h2>
{% for paper in site.data.neurips2025.papers %}
<p><details><summary>🔽 <b>{{paper.title}}</b>. {{ paper.authors }}.</summary>
<p>{{paper.abstract}} <a href="/assets/papers/neurips2025/paper{{paper.tag}}.pdf"><b>(paper)</b></a></p>
</details></p>
{% endfor %}
</section>
</div>
</div>
</div>
