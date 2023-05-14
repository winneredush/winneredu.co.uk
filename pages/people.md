---
layout: page-fullwidth
subheadline: "People"
title: "People | So-lab"
teaser: "These are your options to style the header of each webpage individually. <em>Feeling Responsive</em> uses <a href='http://srobbin.com/jquery-plugins/backstretch/'>Backstretch by Scott Robin</a> to expand them from left to right. The width should be 1600 pixel or higher using a ratio like 16:9 or 21:9 or 2:1."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/people/"

---
<!-- Use a div element to create a batch for each person -->

<div class="batch">

<!-- Use an image element to display the picture of the person -->
<img src="{{ site.urlimg }}ETH_City.jpg" alt="">

<!-- Use a paragraph element to display the name and title of the person -->
<p class="name">Emily S. Cross<br>Principal Investigator</p>

<!-- Use another paragraph element to display the text about the person -->
<p class="text">Emily completed a BA at Pomona College (USA), an MSc at the University of Otago (NZ), and a PhD at Dartmouth College (USA). She hails from the small town of Chagrin Falls in the great state of Ohio. Through her work in the SoBA lab, she addresses how experience shapes perception and is especially interested in how we learn new physical skills by watching others, how action expertise is manifest in the brain, the neural foundations of art appreciation, and how learning shapes our social encounters with artificial agents. When not in the lab, Emily can be found exploring the great outdoors with her two young sons, or trying to learn Swiss German.</p>

</div>

<!-- Add some CSS code to style and position the elements -->
<style>
/* Set the batch background color and margin */
.batch {
  background-color: lightblue;
  margin: 20px;
}

/* Set the image width and height */
img {
  width: 200px;
  height: 250px;
}

/* Set the name font size and alignment */
.name {
  font-size: 18px;
  text-align: center;
}

/* Set the text font size and margin */
.text {
  font-size: 16px;
  margin: 10px;
}

/* Use flexbox to arrange the elements horizontally */
.batch {
  display: flex;
}

/* Set the image and name elements to take up 1/5 of the batch width */
img, .name {
  flex-basis: 20%;
}

/* Set the text element to take up 4/5 of the batch width */
.text {
  flex-basis: 80%;
}
</style>

---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>