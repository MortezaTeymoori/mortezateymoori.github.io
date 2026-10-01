---
layout: page
permalink: /publications/
title: Publications
description: Preprints, peer-reviewed journal articles, and conference contributions.
paperyears: [2025, 2024, 2023, 2022, 2017, 2016]
Proceedingyears: [2026, 2025, 2024, 2023, 2022, 2019, 2016, 2014, 2012]
nav: true
---

<div class="publications">
<h1>Preprints</h1>
<h2 class="year">2026</h2>
<ol class="bibliography">
  <li>
    <div class="row">
      <div class="col-sm-2 abbr"><abbr class="badge">arXiv</abbr></div>
      <div class="col-sm-8">
        <div class="title">Light Coils: MRI with Fully Optical Data and Power Transmission</div>
        <div class="periodical"><em>arXiv preprint arXiv:2607.04211</em> 2026</div>
        <div class="links">
          <a href="https://arxiv.org/abs/2607.04211" class="btn btn-sm z-depth-0" role="button">arXiv</a>
          <a href="{{ '/lightcoils/' | relative_url }}" class="btn btn-sm z-depth-0" role="button">Project page</a>
        </div>
      </div>
    </div>
  </li>
  <li>
    <div class="row">
      <div class="col-sm-2 abbr"><abbr class="badge">arXiv</abbr></div>
      <div class="col-sm-8">
        <div class="title">Optically-powered Low Power Low Noise Amplifiers for MRI</div>
        <div class="periodical"><em>arXiv preprint arXiv:2607.10019</em> 2026</div>
        <div class="links">
          <a href="https://arxiv.org/abs/2607.10019" class="btn btn-sm z-depth-0" role="button">arXiv</a>
        </div>
      </div>
    </div>
  </li>
</ol>
</div>

<div class="publications">
<h1>Peer-Reviewed Journal Articles</h1>
{% for y in page.paperyears %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @article[year={{y}}]* %}
{% endfor %}
</div>

<div class="publications">
<h1>Conference Contributions</h1>
{% for x in page.Proceedingyears %}
  <h2 class="year">{{x}}</h2>
  {% bibliography -f papers -q @inproceedings[year={{x}}]* %}
{% endfor %}
</div>
