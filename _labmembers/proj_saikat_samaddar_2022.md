---
layout: page
title: Saikat Samaddar
description: M.Sc. 2023
img: assets/project_students/Saikat_samaddar/saikat_img.jpg
importance: 2
category: Project students
work_title: Double Perovskite Solar Cells
abstract: Meeting the enormous energy demand of our modern world solely through fossil fuels is a daunting challenge. As a result, researchers are investigating smart and useful materials that can transform light into usable energy as a renewable energy source. Perovskite solar cells (PSC) are considered a game-changer in the field of photovoltaics due to their enormous advancement in power conversion efficiency (PCE), increasing from 3.8% to 25% in just a few years. In this study, we provide a brief introduction to the charge generation and charge transport in perovskite solar cells and the underlying physics. We use the Solar Cell Capacitance Simulator (SCAPS-1D) application to simulate the physical properties of the solar cell, and we discuss the numerical methods related to this. We employ an inorganic double perovskite Cs2BiAgI6 material as an active layer for solar cell fabrication and investigate the device configuration ITO/TiO2/Cs2BiAgI6/CBTS/Au. We vary the solar cell active layer thickness, bandgap, doping concentration, and temperature to study the device's performance. We also investigate the effect of donor concentrations by changing its value for the proposed device from 1 x 10-12 cm-3 to 1 x 10-20 cm-3. The power conversion efficiency of the perovskite solar cell is improved by using several charge transport materials. Our simulation analysis demonstrates that the suggested design could be used to create a device for enhancing the effectiveness of the perovskite solar cell. 
contactno: +91 80161 07987
pdf: ../../assets\project_students\Saikat_samaddar\project_saikat_2022.pdf
word: ../../assets\project_students\Saikat_samaddar\word_saikat_2022.docx
presentation: ../../assets/project_students\Saikat_samaddar\presentation_saikat_2022.pptx
bio: ../../assets\project_students\Saikat_samaddar\saikat_bio.docx
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
{%- if page.bio %}
    <a href="{{ page.bio }}" class="btn btn-sm z-depth-0" role="button">Bio</a>
{%- endif %}
</div>
</div>