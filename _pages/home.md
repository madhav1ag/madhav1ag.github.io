---
title: "Madhav Agarwal - Home"
layout: gridlay
excerpt: "Madhav Agarwal"
sitemap: false
permalink: /
---

<div class="container-fluid">

<div class="row">

<div class="col-sm-8">

<div style="text-align: justify">
I am a Ph.D. student at <a href="https://www.eng.ed.ac.uk/research/institutes/idcom/" target="_blank">IDCOM</a>
in the <a href="https://www.eng.ed.ac.uk/" target="_blank">School of Engineering</a>, 
<a href="https://www.ed.ac.uk/" target="_blank">University of Edinburgh</a>. 
I am supervised by <a href="https://smcdonagh.github.io/" target="_blank">Dr. Steven McDonagh</a> and 
<a href="https://laurasevilla.me/" target="_blank">Dr. Laura Sevilla</a>.
My interest lies in Multimodal Learning, 3D Human Motion Modeling, and Generation.

Before moving to the UK, I spent a wonderful year in Germany working on building lip-syncing and synthetic media generation models. 
I also spent three months at <a href="https://niessnerlab.org/" target="_blank">Visual Computing & Artificial Intelligence</a> group at <a href="https://www.tum.de" target="_blank">Technical University of Munich</a>
with <a href="https://niessnerlab.org/members/matthias_niessner/profile.html"
target="_blank">Prof. Matthias Nießner</a>.

I completed MS by Research at <a href="http://cvit.iiit.ac.in/" target="_blank">CVIT, IIIT Hyderabad</a> under the guidance of <a href="https://faculty.iiit.ac.in/~jawahar/index.html" target="_blank">Prof. C.V. Jawahar</a> and <a href="https://vinaypn.github.io/" target="_blank">Prof. Vinay P. Namboodiri</a>.  My graduate research focused on Lip-Sync, Talking Head Generation, and Face Reenactment, along with their optimization for real-world problems. 
Additionally, I worked on the task of Table Detection in Document Images with high accuracy under the supervision of Prof. C.V. Jawahar and Dr. Ajoy Mondal. 
Prior to this, I worked as a Data Scientist and a team lead with several companies, broadly in the domains of Facial Recognition, Video Surveillance using AI, and Document Image Processing.
</div>

<div style="text-align: justify">
My work has been published in top computer vision and machine learning conferences. 
I am also actively involved with start-ups as an advisor and consultant.
</div>


<!-- <div style="text-align: justify">
Contact: madhav <coda>[dot] agarwal
                <coda>[at] ed
			          <coda>[dot] ac
			    	    <coda>[dot] uk
				        </coda>
			          </coda>
                </coda>
		            </coda>
</div> -->


<p align="center">
  <a href="./docs/MadhavAgarwalCV.pdf">CV</a> /
  <a href="https://scholar.google.com/citations?user=t8VdoRYAAAAJ&hl=en">Google Scholar</a> /
  <a href="https://github.com/mdv3101">Github</a> /
  <a href="https://www.linkedin.com/in/madhav3101/">LinkedIn</a> /
  <a href="https://arxiv.org/a/agarwal_m_1"> arXiv </a> /
  <a href="https://orcid.org/0000-0001-8267-1024">ORCID</a>
</p>

### News
****
{% for article in site.data.news limit:7 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{% endfor %}
#### <a href="{{ site.url }}{{ site.baseurl }}/allnews.html">See all news</a>

</div>

<div class="col-sm-4" style="display:table-cell; vertical-align:left; text-align:left">

  <ul style="overflow: hidden">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile_pic.jpg" class="img-responsive" width="100%" />
  </ul>

  <!-- <br clear="all" /> -->
<div style="text-align: right">
Contact: madhav.agarwal(at)ed(dot)ac(dot)uk
</div>

</div>

</div>
</div>

<div class="col-sm-12">

### Publications
****

{% for publi in site.data.publist limit:5 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="300px" style="float: left" />

<div style="text-align: justify">
 <p>{{ publi.description }}</p>
</div>

<div style="text-align: justify">
 <p><em>{{ publi.authors }}</em></p>
</div>

 <p>{{ publi.venue }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a></p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>
 /
 <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
 /
 <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
 /
 <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>
 /
 <a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}

<br clear="all"/>

#### <a href="{{ site.url }}{{ site.baseurl }}/publications">See all publications</a>

</div>

<div class="col-sm-12">

### Miscellaneous
****


#### Conference Reviewer

* CVPR 2025
* ECCV 2024
* WACV 2023
* ICPR 2022

#### Journal Reviewer


* International Journal of Computer Vision ([IJCV](https://link.springer.com/journal/11263)) 2025
* ACM Computing Surveys ([ACMCS](https://dl.acm.org/journal/csur)) 2023



#### Thesis

* Masters: <a href="https://web2py.iiit.ac.in/research_centres/publications/view_publication/mastersthesis/1265" target="_blank">Face Reenactment: Crafting Realistic Talking Heads for Enhanced Video Communication and Beyond</a>

<p> &nbsp; </p>



</div>
