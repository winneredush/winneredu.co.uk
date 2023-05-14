---
layout: page-fullwidth
show_meta: false
title: "Style your content!"
subheadline: "Layouts of Feeling Responsive"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/design/"

---
<div id="publications">
  <h2>Publications</h2>
  <ul>
    <li><a href="#2023">2023</a></li>
    <li><a href="#2022">2022</a></li>
    <li><a href="#2021">2021</a></li>
    <li><a href="#2020">2020</a></li>
  </ul>
  <h3 id="2023">In Press / 2023</h3>
  <ul>
    <li> <strong>Darda, K. M.</strong>, & <strong>Cross, E. S.</strong> (2023). The computer, A choreographer? Aesthetic responses to randomly-generated dance choreography by a computer. <em>Heliyon, 9</em>(1), e12750. <a href="https://www.soba-lab.com/_files/ugd/3e5863_50a01c4a582f4b76a11c8184253292fe.pdf">pdf</a><a href="https://doi.org/10.1016/j.heliyon.2022.e12750">doi</a><a href="https://osf.io/4hsby/">Open Science Framework</a><a href="https://psyarxiv.com/yvgxk/">preprint</a></li>


  </ul>
  <h3 id="2022">2022</h3>
  <ul>
    <li>Bara, I., Binney, R. J., & Ramsey, R. (2022). Investigating the Role of Working Memory Resources across Aesthetic and Non-Aesthetic Judgments. Quarterly Journal of Experimental Psychology. <a href="pdf">pdf</a>  <a href="doi">doi</a>  <a href="Open Science Framework">Open Science Framework</a>  <a href="preprint">preprint</a></li>
  </ul>
  <h3 id="2021">2021</h3>
  <ul>
    <li>Bara, I., Darda, K. M., Kurz, A. S., & Ramsey, R. (2021). Functional Specificity and Neural Integration in the Aesthetic Appreciation of Artworks with Implied Motion. European Journal of Neuroscience. <a href="pdf">pdf</a>  <a href="doi">doi</a>  <a href="Open Science Framework">Open Science Framework</a>  <a href="preprint">preprint</a></li>
  </ul>
</div>


---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>