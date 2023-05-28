---
layout: page
title: Saikat Samaddar
description: 
img: assets\img\11.jpg
importance: 2
category: Project students
work_title: Double Perovskite Solar Cells
contactno: +91 80161 07987
email: saikatsamadder07@gmail.com
pdf: ../../assets/project_students/Saikat_samaddar/project_saikat_2022.pdf
word: ../../assets/project_students/Saikat_samaddar\word_saikat_2022.docx
presentation: ../../assets/project_students/Saikat_samaddar\presentation_saikat_2022.pptx
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path=page.img title=page.title class="img-fluid rounded z-depth-1" %}
    </div>
     <div class="col-sm mt-3 mt-md-0">
     <h3>Title</h3>
     <div>
        {%- if page.work_title -%}
          <h5>{{page.work_title}}</h5> 
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
      
</div>

</div>

<div class="row">

<h4>Abstract</h4>
</div>
<div class="row">
<div>
        {%- if page.abstract -%}
          {{page.abstract}} 
        {% endif %}
      </div>
</div>
<div class="row">
<div class="links">
{%- if page.pdf %}
    <a href="{{ page.pdf }}" class="btn btn-sm z-depth-0" role="button">PDF</a>
{%- endif %}
{%- if page.word %}
    <a href="{{ page.word }}" class="btn btn-sm z-depth-0" role="button">Word</a>
{%- endif %}
{%- if page.presentation %}
    <a href="{{ page.presentation }}" class="btn btn-sm z-depth-0" role="button">Presentation</a>
{%- endif %}
</div>
</div>


