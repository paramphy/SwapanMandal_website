---
layout: page
title: Chaitali Mondal
author: [Chandra,Paramesh]
description: Spin Crossover Materials
img: assets/img/chaitali.jpg
importance: 1
category: Past scholars
working_description: 
contactno: 
email: 
altmail: 
orcid_id: 
scholar_userid: 
publons_id: 
research_gate_profile: 
bib_file: chaitali
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


