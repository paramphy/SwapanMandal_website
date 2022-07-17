---
layout: page
title: Paramesh Chandra
author: [Chandra,Paramesh]
description: Perovskite solar cells
img: assets/img/param.jpg
importance: 1
category: Currently working
working_description: Our research work is focused on reducing lead toxicity and increasing the stability of perovskite solar cells. 
contactno: +91-9007869662
email: parameshchandra28@gmail.com
altmail: parameshchandra.rs@visva-bharati.ac.in
orcid_id: 0000-0002-2408-0493
scholar_userid: UAL4EEkAAAAJ
publons_id: 515151
research_gate_profile: Paramesh-Chandra
bib_file: param
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path=page.img title=page.title class="img-fluid rounded z-depth-1" %}
    </div>
     <div class="col-sm mt-3 mt-md-0">

     <div>
        {%- if page.contactno -%}
          <h4>Work Summery </h4>  {{page.working_description}} 
        {% endif %}
      </div>
      
      <h4>Contact details</h4>
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
      
      <h4>Social</h4>
      <div>
        {%- if site.orcid_id -%}
            <a href="https://orcid.org/{{ site.orcid_id }}" title="ORCID"><i class="ai ai-orcid"></i></a>
            {% endif %}
      {%- if page.scholar_userid -%}
          <a href="https://scholar.google.com/citations?user={{ page.scholar_userid }}" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
      {% endif %}
      {%- if page.research_gate_profile -%}
        <a href="https://www.researchgate.net/profile/{{page.research_gate_profile}}/" title="ResearchGate"><i class="ai ai-researchgate"></i></a>
      {% endif %}
        
    </div>
</div>
</div>

<div class="publications">
<h2>Publications</h2>
{% bibliography -f {{page.bib_file}} %}
</div>


