---
layout              : page-fullwidth
title               : "SoBAFun"
#meta_title          : "Contact and use our contact form"
#subheadline         : "Contact Form"
# teaser              : "Let's keep in touch!"
permalink           : "/SoBAFun/"

---
<!DOCTYPE html>
<html>
<head>
<style>
.container {
  display: flex;
}
.main-image {
  flex-grow: 1;
}
.image-list {
  width: 200px;
  overflow: auto;
  border-left: 1px solid #000;
}
.image-list img {
  width: 100%;
  cursor: pointer;
  margin-bottom: 10px;
}
</style>
</head>
<body>

<div class="container">
  <div class="main-image">
    <img id="selected-image" src="{{ site.urlimg }}gallery-example-1.jpg" alt="">
  </div>

  <div id="scroll-container" class="image-list">
    <img onclick="updateImage(event)" src="{{ site.urlimg }}gallery-example-1.jpg" alt="">
    <img onclick="updateImage(event)" src="{{ site.urlimg }}gallery-example-2.jpg" alt="">
    <img onclick="updateImage(event)" src="{{ site.urlimg }}gallery-example-3.jpg" alt="">
    <img onclick="updateImage(event)" src="{{ site.urlimg }}gallery-example-4.jpg" alt="">
  </div>
</div>

<script>
function updateImage(event) {
  document.getElementById('selected-image').src = event.target.src;
}

var container = document.getElementById('scroll-container');
var scrollInterval;

container.addEventListener('mouseenter', function() {
  scrollInterval = setInterval(function() {
    container.scrollTop += 1;
  }, 100);  // 100 milliseconds = 0.1 second
});

container.addEventListener('mouseleave', function() {
  clearInterval(scrollInterval);
});
</script>

</body>
</html>



---
![fun1](https://static.wixstatic.com/media/3e5863_1a33c49ae4d84587b68927bf29d630c5~mv2.jpg/v1/fill/w_843,h_632,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/3e5863_1a33c49ae4d84587b68927bf29d630c5~mv2.jpg)
