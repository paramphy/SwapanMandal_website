---
layout: page
title: Paramesh Chandra
description: Perovskite solar cells
img: assets/img/1.jpg
importance: 1
category: Currently working
working_on: 
contactno: +91-9007869662
email: parameshchandra28@gmail.com
altmail: parameshchandra.rs@visva-bharati.ac.in
orcid_id: 131656232
scholar_userid: 21512
publons_id: 515151
research_gate_profile: 15515
---
{%- if page.img %}
        {%- include figure.html
          path=page.img
          alt="project thumbnail" -%}
{%- endif %}
 
<div>
<div>
{%- if page.contactno -%}
:telephone_receiver:  {{page.contactno}} 
{% endif %}
</div>

<div>
{%- if page.email -%}
:email: {{page.email}}
{% endif %}
</div>
<div>
{%- if page.altmail -%}
:email: {{page.altmail}}
{% endif %}
</div>
<div>
{%- if page.orcid_id -%}
<a href="https://orcid.org/{{ page.orcid_id }}">
<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" />
https://orcid.org/{{ page.orcid_id }}
</a>
{% endif %}
</div>

{%- if page.scholar_userid -%}
<a href="https://scholar.google.com/citations?user={{ page.scholar_userid }}" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
{% endif %}
{%- if page.research_gate_profile -%}
<a href="https://www.researchgate.net/profile/{{page.research_gate_profile}}/" title="ResearchGate"><i class="ai ai-researchgate"></i></a>
{% endif %}

