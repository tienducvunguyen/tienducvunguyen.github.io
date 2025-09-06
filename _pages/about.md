---
permalink: /about/
title: "About Me"
layout: single
author_profile: true
toc: true
---

Hi! I'm Duc Vu, an undergraduate researcher at Michigan State University.  
My work focuses on:

- Graph signal processing and hypergraphs
- Brain networks and physiological signal modeling
- Real-time biomedical sensing systems

### Hobbies

**Soccer**  
Although I only began playing soccer in college, it has since become one of my main passion. I find myself deeply engaged with the sport—not just in playing it, but also in following professional leagues like the Premier League.

**Drawing**  
I enjoy drawing, particularly portraits. My early sketches were more stylized—drawing inspiration from animation and medieval themes but recently I’ve been focusing on improving my fundamentals, such as form and anatomy, in order to improve my portrait drawings. Interestingly enough, people have told me I am very intense while drawing.

<!-- Drawing slideshow -->
<div class="slideshow-container">

  <div class="mySlides fade">
    <img src="/assets/images/art1.jpg" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/images/art2.jpg" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/images/art3.jpg" style="width:100%">
  </div>

  <div class="mySlides fade">
    <img src="/assets/images/art4.jpg" style="width:100%">
  </div>

  <!-- Navigation arrows -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>

<br>

<!-- Dots -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
  <span class="dot" onclick="currentSlide(4)"></span> 
</div>


**Gaming**  
Video games are my long-time interest, and I’ve enjoyed both multiplayer titles like *Counter-Strike* and *Dark Souls*, as well as more narrative-driven single-player games. Lately, I’ve grown especially interested in atmospheric games like *Bloodborne*, *Frostpunk*, *Resident Evil 7*, and *Clair Obscur: Expedition 33*. I find myself constantly listening to these games soundtracks on repeat. 

**Neuroscience & Signal Processing**  
One of my deeper intellectual hobbies is exploring the intersection of neuroscience and signal processing. I’m truly intrigued by how the brain, a complex biological system, can be studied through mathematical frameworks like graph theory and signal filtering. I find beauty in viewing the brain as a highly sophisticated learning and communication system, full of nonlinearities and quirks.

### 📬 Contact

- Email: [tienducvunguyen@example.com](mailto:tienducvunguyen@example.com)  
- LinkedIn: [https://www.linkedin.com/in/duc-vu-94147828b/](https://www.linkedin.com/in/duc-vu-94147828b/)  



<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>
