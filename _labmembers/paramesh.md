---
layout: page
title: Paramesh Chandra
description: Currently Working
img: assets/img/1.jpg
importance: 1
category: Currently working
working_on: 
contactno: 
email: parameshchandra28@gmail.com
altmail: 
orcid_id: 131656232
scholar_userid: 
publons_id: 
research_gate_profile: 
---
{%- if page.img %}
        {%- include figure.html
          path=page.img
          alt="project thumbnail" -%}
        {%- endif %}

# Working on
Perovskite solar cells
# Contact details
## Phone no. 
+91-9007869662
## Email id.
parameshchandra28@gmail.com

parameshchandra.rs@visva-bharati.ac.in


{%- if page.email -%}
<a href="{{ page.contactno | encode_email }}" title="contact no."><i class="fas fa-envelope"></i></a>
{% endif %}
{%- if page.email -%}
<a href="mailto:{{ page.email | encode_email }}" title="email"><i class="fas fa-envelope"></i></a>
{% endif %}
{%- if page.orcid_id -%}
<a href="https://orcid.org/{{ page.orcid_id }}" title="ORCID"><i class="ai ai-orcid"></i></a>
{% endif %}
{%- if page.scholar_userid -%}
<a href="https://scholar.google.com/citations?user={{ page.scholar_userid }}" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
{% endif %}
{%- if page.research_gate_profile -%}
<a href="https://www.researchgate.net/profile/{{page.research_gate_profile}}/" title="ResearchGate"><i class="ai ai-researchgate"></i></a>
{% endif %}