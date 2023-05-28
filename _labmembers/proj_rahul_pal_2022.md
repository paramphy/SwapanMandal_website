---
layout: page
title: Rahul Pal
description: 
img: assets/project_students/Rahul_pal/rahul_img.jpg
importance: 1
category: Project students
work_title: Simulations on Photovoltaic Devices
abstract: In the modern era, it is a challenge to meet the enormous energy demand of our everyday life solely based on fossil fuels. Thus, developing smart and useful materials which transforms light into usable energy are the most investigated research methods for the generation of renewable energy source. In the field of photovoltaics, perovskite solar cells (PSC) have been called a game-changer. With the enormous advancement in perovskite solar cells’ power conversion efficiency (PCE), which increased from 3.8% to 25% in few years. In our work we have given a brief introduction to charge generation and charge transport in perovskite solar cells and the underlaying physics of it. To simulate the physical properties of the solar cell we have used Solar Cell Capacitance Simulator (SCAPS-1D) application and the numerical methods related to this is also briefly discussed initially. Next, an organic-inorganic mixed single perovskite CH3NH3PbI3 material is employed as an active layer for solar cell fabrication and (SCAPS-1D) was used to study the device configuration Glass/ITO/WS2/CH3NH3PbI3/P3HT/Au. The device performance is investigated by varying the solar cell active layer thickness, bandgap, doping concentration and temperature. Further, using the optimal value of the different parameters, the performance of the photo-voltaic device such as power conversion efficiency (PCE) and Fill Factor (FF) are obtained as 28.38%, and 90.93%, respectively. Also, Open-circuit voltage (VOC) of 1.4275 V and short-circuit current density (JSC) of 21.86 mA cm−2 were achieved. The effect of donor concentrations has been investigated by changing its value for the proposed device from 1 x 10-12 cm-3 to 1 x 10-20 cm-3. The power convergence efficiency of the perovskite solar cell has therefore been improved by the use of several charge transport materials. Our simulation analysis demonstrates that the suggested design might be used to create a device for enhancing the effectiveness of the perovskite solar cell.
contactno: +91 97351 04626
email: rahulpalscience2000@gmail.com
pdf: ../../assets/project_students/Rahul_pal/project_rahul_2022.pdf
word: ../../assets/project_students/Rahul_pal/word_rahul_2022.docx
presentation: ../../assets/project_students/Rahul_pal/presentation_rahul_2022.pptx
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
</div>
</div>


