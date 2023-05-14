---
permalink: /research/
layout: page
title: "Research Interests"
sitemap: false
---
<!-- {% include _google_search.html %} -->


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
    {text: 'Text for Research Interest 2', image: 'https://raw.githubusercontent.com/wenjunchen29/web/main/images/gallery-example-2.jpg'},
    {text: 'Text for Research Interest 3', image: 'https://raw.githubusercontent.com/wenjunchen29/web/main/images/gallery-example-3.jpg'},
    {text: 'Text for Research Interest 4', image: 'https://raw.githubusercontent.com/wenjunchen29/web/main/images/gallery-example-41.jpg'},
    {text: 'Text for Research Interest 5', image: 'https://raw.githubusercontent.com/wenjunchen29/web/main/images/gallery-example-5.jpg'},
];

function showContent(index) {
    var content = research_interests[index-1];
    document.getElementById('text').textContent = content.text;
    document.getElementById('image').src = content.image;
}
</script>

</body>
</html>
