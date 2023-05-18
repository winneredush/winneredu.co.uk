---
layout: page-fullwidth
# title: "Change is good!"
# meta_title: "Feeling Responsive Theme projects"
# subheadline: "Feeling Responsive Theme projects"
# teaser: "History and projects of Feeling Responsive Theme"
header:
  #  image_fullwidth: "header_unsplash_9.jpg"
   image_fullwidth: "Full-piece-pink-and-purple.jpg"
permalink: "/projects/"
---

<!-- <body> -->

<h1 id="table-of-contents">Table of Contents</h1>
<ol>
  <li><a href="#AIvsHuman-m">Males: Speech by Voice-cloning AI and Human</a></li>
  <li><a href="#AIvsHuman-f">Female: Speech by Voice-cloning AI and Human</a></li>

  
</ol>

<h2 id="AIvsHuman-m"><font size="5"><span style="color:blue">Males: Speech by Voice-cloning AI and Human</span></font> <a href="#table-of-contents" style="font-size:10px;">(back to top)</a></h2>

<!-- </body> -->

| confidence.vs.source | human male | AI male |
| --- | --- | --- |
| confident | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_h_m_c_hw_21.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_h_m_c_hw_21.wav) | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_ai_m_c_hw_g_21.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_ai_m_c_hw_g_21.wav) |
| doubtful | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_h_m_d_hw_21.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_h_m_d_hw_21.wav) | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_ai_m_d_hw_g_21.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_ai_m_d_hw_g_21.wav) |
| neutral | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_h_m_n_hw_21.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_h_m_n_hw_21.wav) | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_ai_m_n_hw_g_21.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_ai_m_n_hw_g_21.wav) |


<h2 id="AIvsHuman-f"><font size="5"><span style="color:blue">Females: Speech by Voice-cloning AI and Human</span></font> <a href="#table-of-contents" style="font-size:10px;">(back to top)</a></h2>

<!-- </body> -->

| confidence.vs.source | human female | AI female |
| --- | --- | --- |
| confident | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/9_h_f_c_hw_20.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_h_m_c_hw_21.wav) | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/9_ai_f_c_hw_g_20.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/9_ai_f_c_hw_g_20.wav) |
| doubtful | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/9_h_f_d_hw_20.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_h_m_d_hw_21.wav) | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/9_ai_f_d_hw_g_20.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/9_ai_f_d_hw_g_20.wav) |
| neutral | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/9_h_f_n_hw_20.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/2_h_m_n_hw_21.wav) | [<audio src="https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/9_ai_f_n_hw_g_20.wav" type="audio/wav" controls></audio>](https://raw.githubusercontent.com/wenjunchen29/web/main/files/audios/9_ai_f_n_hw_g_20.wav) |


---

<body>

<h1 id="table-of-contents">What I am working on</h1>
<ol>
  <li><a href="#speaker-identification">Speaker Identification</a></li>
  <li><a href="#vocal-confidence">Vocal Confidence</a></li>
  <li><a href="#voice-identity">Voice Identity Cloning and Speech Style Cloning</a></li>
  <li><a href="#ai-generated-avatars">AI-generated Human Avatars</a></li>
  
</ol>

<h2 id="speaker-identification"><font size="5"><span style="color:blue">Speaker Identification</span></font> <a href="#table-of-contents" style="font-size:10px;">(back to top)</a></h2>
 Have you ever wondered how you can <span style="color:green">*recognize someone’s voice**</span> even if you don’t see their face? How do you know who is speaking when you listen to a podcast or a phone call? How can machines do the same thing? These are some of the questions that speaker identification tries to answer. Speaker identification is the task of determining who is speaking in an audio clip by using voice biometry. It is based on the idea that each speaker has unique voice characteristics that can be extracted and compared with a set of enrolled speaker profiles. Speaker identification can be useful for various applications, such as remote meeting productivity, multiuser device personalization, and forensic analysis. In this website, I will introduce some of the methods and challenges of speaker identification, and refer to some journal papers on this topic, such as <a href="https://www.science.org/doi/abs/10.1126/science.1207327"><span style="background-color:yellow">Perrachione et al. (2011)</span></a>, who showed that human voice recognition depends on language ability.

<div class="flex-video"><iframe width="1200" height="720" src="https://www.youtube.com/embed/YCxPI8ckAXg" frameborder="0" allowfullscreen></iframe></div><!-- /.flex-video -->

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/YCxPI8ckAXg" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>



</body>
---