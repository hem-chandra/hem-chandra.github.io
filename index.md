---
layout: homepage
---

<div class="quote-container">
  <p class="quote">
    “Ethics is knowing the difference between what you have a right to do and what is right to do.”
  </p>
  <p class="author">— Potter Stewart</p>
</div>

<style>
.quote-container {
    margin-top: 100px;
    text-align: center;
    animation: float 3s ease-in-out infinite;
    font-family: Arial, sans-serif;
}

.quote {
    font-size: 28px;
    font-style: italic;
    color: #333;
    max-width: 800px;
    margin: auto;
}

.author {
    margin-top: 20px;
    font-size: 20px;
    color: #666;
}

@keyframes float {
    0% {
        transform: translateY(0px);
    }
    50% {
        transform: translateY(-12px);
    }
    100% {
        transform: translateY(0px);
    }
}
</style>
<br>

<h1 id="about-me" style="font-size: 36px; margin-bottom: 20px;">
  About Me
</h1>

<p style="margin-top: 30px; font-size: 18px; line-height: 1.8;">
  Welcome! I am <strong>Hem Chandra Joshi</strong>, a passionate researcher working in the areas of Trustworthy and Responsible Artificial Intelligence. Currently, I am working as a Senior Research Fellow at 
  <a href="https://en.wikipedia.org/wiki/IIT_Roorkee" target="_blank">
    Indian Institute of Technology Roorkee (IIT Roorkee)
  </a>, formerly recognized as the first engineering college established in Asia.
  
  I also completed my 
  <strong style="color: #2c3e50;">M.Tech. in Artificial Intelligence</strong> from 
  <a href="https://uohyd.ac.in/" target="_blank">
    University of Hyderabad (Institute of Eminence)
  </a>.
</p>

<p style="font-size: 18px; line-height: 1.8;">
  My core research interests focus on 
  <strong style="color: #0056b3;">F</strong>airness, 
  <strong style="color: #0056b3;">A</strong>ccountability, 
  <strong style="color: #0056b3;">T</strong>ransparency, and 
  <strong style="color: #0056b3;">E</strong>xplainability 
  (<strong style="color: #0056b3;">FATE</strong>) in Artificial Intelligence.
</p>

<div style="background-color: white; border: 1px solid #ccc; padding: 15px; border-radius: 8px;">
  <p style="font-size: 18px; line-height: 1.8; margin: 0;">
    <strong>My Long-term Goal:</strong>
    <span style="color: #800000;">
      To identify and address ethical challenges in AI systems, including algorithmic bias, fairness, interpretability, and explainability, through the development of responsible and trustworthy AI methodologies. Although AI systems have achieved remarkable capabilities, ensuring their transparency, fairness, and trustworthiness in critical domains remains a significant challenge.
    </span>
  </p>
</div>

{% include_relative _includes/news.md %}
{% include_relative _includes/contact.md %}
