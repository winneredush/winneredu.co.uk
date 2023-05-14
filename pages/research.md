---
permalink: /research/
layout: page
title: "Research Interests"
sitemap: false
---

<!DOCTYPE html>
<html>
<head>
<style>
#leftnav {
    width: 20%;
    float: left;
    overflow: auto;
    height: 600px; /* adjust to your liking */
}

#content {
    width: 75%;
    float: right;
}

#content img {
    width: 100%;
    height: auto;
}

</style>
</head>
<body>

<div id="leftnav">
    <h3>Research Interests</h3>
    <ul>
        <li onclick="showContent(1)">Research Interest 1</li>
        <li onclick="showContent(2)">Research Interest 2</li>
        <li onclick="showContent(3)">Research Interest 3</li>
        <li onclick="showContent(4)">Research Interest 4</li>
        <li onclick="showContent(5)">Research Interest 5</li>
    </ul>
</div>

<div id="content">
    <div id="text"></div>
    <img id="image" src="" alt="">
</div>

<script>
var research_interests = [
    {text: 'Text for Research Interest 1', image: 'https://raw.githubusercontent.com/wenjunchen29/web/main/images/gallery-example-1.jpg'},
    {text: 'Text for Research Interest 2222222', image: 'https://raw.githubusercontent.com/wenjunchen29/web/main/images/gallery-example-1.jpg'},
    {text: 'Text for Research Interest 3', image: 'https://raw.githubusercontent.com/wenjunchen29/web/main/images/gallery-example-1.jpg'},
    {text: 'Text for Research Interest 4', image: 'https://raw.githubusercontent.com/wenjunchen29/web/main/images/gallery-example-1.jpg'},
    {text: 'Text for Research Interest 5', image: 'https://raw.githubusercontent.com/wenjunchen29/web/main/images/gallery-example-1.jpg'},
];

function showContent(index) {
    var content = research_interests[index-1];
    document.getElementById('text').textContent = content.text;
    document.getElementById('image').src = content.image;
}
</script>

</body>
</html>

<!-- ---
layout              : page-fullwidth
show_meta           : false
title               : "Getting Started in 10 Steps"
subheadline         : "A Step-by-Step Guide"
teaser              : "This step-by-step guide helps you to customize Feeling Responsive to your needs."
header:
   image_fullwidth  : "header_homepage_13.jpg"
permalink           : "/research/"
---
1. Open `_config.yml` and work it through, it's well documented.
1. Add your own `logo.png` to `/assets/img/`.
1. Add your own social media links and open `_data/socialmedia.yml`.
1. Open `_sass/_01_settings_colors.scss` and adjust the the colors to your taste.
1. Customize your navigation and open `_data/navigation.yml`.
1. Translate this theme and open `_data/language.yml`.
1. Change the links in the footer and open `_data/services.yml` and `_data/network.yml`.
1. Open `_data/authors.yml` and edit author information and set default author in `config.yml`.
1. Make it yours and add your own content.
1. [Read the documentation][1] to check out all features of *Feeling Responsive*.

<a class="radius button small" href="{{ site.url }}{{ site.baseurl }}/documentation/">Check out the documentation for all the tricks ›</a>


 [1]: {{ site.url }}{{ site.baseurl }}/documentation/ -->
