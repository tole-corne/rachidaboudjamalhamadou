---
title: "Home"
---

<style>
.carousel { 
  position: relative; 
  overflow: hidden; 
}

.carousel-track {
  display: flex;
  gap: 1rem;
  flex-wrap: nowrap;
  overflow-x: auto;
  scroll-behavior: smooth;
  padding-bottom: .25rem;
  -ms-overflow-style: none;
  scrollbar-width: none;
}

.carousel-track::-webkit-scrollbar { 
  display: none; 
}

.carousel .card { 
  flex: 0 0 300px; 
}

.profile-pic {
  width: 220px;
  height: 220px;
  border-radius: 50%;
  object-fit: cover;
  object-position: center 25%;
  transform: scale(0.9);
}
</style>

<section id="about" class="section">
<div class="about-container">

<img src="{{ '/assets/images/rachid.png' | relative_url }}"
     alt="Rachid Abou Djamal Hamadou"
     class="profile-pic">

<div class="about-text">

<h1>Hello World! I'm Rachid Abou Djamal Hamadou</h1>

<p>Data Science & AI Student | Cloud & Data Technologies</p>

<p>
Curious about data, artificial intelligence and modern technologies,
I enjoy building projects that explore how data can be processed,
analyzed and transformed into useful insights.
</p>

<p>
<strong>Core skills:</strong>
Python · SQL · Data Analysis · Cloud Computing · Machine Learning
</p>

<p class="social-links">

<a href="https://www.linkedin.com/in/rachid-abou-djamal-hamadou"
   target="_blank"
   aria-label="LinkedIn">
<i class="fa-brands fa-linkedin"></i>
</a>

<a href="https://github.com/tole-corne"
   target="_blank"
   aria-label="GitHub">
<i class="fa-brands fa-github"></i>
</a>

</p>

</div>
</div>
</section>
