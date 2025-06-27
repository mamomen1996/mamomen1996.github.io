---
permalink: /
title: "Home Page"
author_profile: true
classes: wide smaller-font
---

<!-- Swiper Slider Bar -->
<div class="swiper mySwiper" style="margin-bottom: 2rem;">
  <div class="swiper-wrapper">
    <div class="swiper-slide"><img src="/images/media_1.jpg" alt="Media 1"></div>
    <div class="swiper-slide"><img src="/images/media_2.jpg" alt="Media 2"></div>
    <div class="swiper-slide"><img src="/images/media_3.jpg" alt="Media 3"></div>
    <div class="swiper-slide"><img src="/images/media_4.jpg" alt="Media 4"></div>
    <div class="swiper-slide"><img src="/images/media_5.jpg" alt="Media 5"></div>
    <div class="swiper-slide"><img src="/images/media_6.jpg" alt="Media 6"></div>
    <div class="swiper-slide"><img src="/images/media_7.jpg" alt="Media 7"></div>
    <div class="swiper-slide"><img src="/images/media_8.jpg" alt="Media 8"></div>
  </div>
  <!-- Add Pagination -->
  <div class="swiper-pagination"></div>
  <!-- Add Navigation -->
  <div class="swiper-button-next"></div>
  <div class="swiper-button-prev"></div>
</div>

{% capture custom_content %}
## About Me
<div style="text-align: justify; font-size: 20px;">
M.Sc. Student, Researcher and Inventor with over <strong>3 years</strong> of combined experience in Artificial General Intelligence research and industry experience as a <strong>Software Engineer</strong>. I have experience in <strong>Robotics, IOR, Machine Learning, Deep Learning, Data Analysis, Web development and System Administration</strong>. My current research focuses on Artificial General Intelligence, Brain-Inspired AGI, Conscious AGI, Embodied AGI, Multimodal Learning and Computational Neuroscience. Proficient in <strong>Python, C++, Git, Linux, PostgreSQL</strong>, and various machine learning and deep learning frameworks.
</div>


{: .small}

---
## Research Interests

1. **Artificial General Intelligence**
   - ...

2. **Machine Consciousness**
   - ...

3. **Computational Neuroscience**
   - ...

4. **Cognitive Neuroscience**
   - ...

5. **Reinforcement Learning**
   - ...

6. **Multi Modal Learning**
   - ...
  
7. **Artificial Neural Networks**
   - ...

---
## Technical Skills
- **Programming:** Python, C++, SQL
- **Machine Learning & AI:** TensorFlow, PyTorch, Scikit-learn, Keras, OpenCV, PIL
- **Data Analysis & Visualization:** NumPy, Pandas, Matplotlib, Seaborn, Plotly, SKLearn, SciPy
- **Tools:** Git, GitHub, Linux
- **Hardware:** Sensor fusion, Microcontroller programming (Raspberry Pi)

{: .small}
{% endcapture %}

{{ custom_content | markdownify }}
 ---

## Selected Projects 
