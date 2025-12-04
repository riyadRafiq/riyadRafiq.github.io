---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. candidate in the [Computer Science and Engineering](https://computerscience.engineering.unt.edu/) department at the [University of North Texas](https://www.unt.edu/), where I am also serving as a Graduate Research Assistant in the [Biomedical AI lab](https://www.biomed-ai.com/home). My research focuses on developing a fast and flexible gesture recognition system that utilizes wearable sensor data for individuals with motor impairments who are unable to speak. I am particularly interested in exploring transfer learning, continual learning, and meta-learning strategies for custom gesture training with a few examples. Recently, I have been incorporating large language model (LLM) reasoning to enhance adaptability and robustness in gesture recognition under limited training data. Under the supervision of [Dr. Mark V. Albert](https://sites.google.com/view/biomed-ai/people/mark-v-albert) and [Dr. Weishi Shi](https://scholar.google.com/citations?user=nAPZIPsAAAAJ&hl=en), I am utilizing my expertise in deep learning and AI to make a real-world impact and improve the lives of those in need. Previously, I earned my M.S. in Artificial Intelligence from the University of North Texas and my B.Sc. in Computer Science and Engineering from Chittagong University of Engineering and Technology in Bangladesh.

<h2> Recent News </h2>
------
<ul>
  <li> January 2025: I successfully passed the coding rounds for the Software Engineer, Machine Learning Internship position at **Meta** for Summer 2025, but unfortunately, due to headcount limitations, I was not matched with a team. </li>    
  <li> July 2024: My Ph.D. proposal is officially done. </li>
  <li> May 2024: One research paper is accepted in IJCAI 2024. </li>
  <li> March 2023: One research paper is accepted in ICHI 2023. </li>
  <li> February 2023: One research paper is accepted by the Journal of Patient-Reported Outcomes. </li>
  
  <li class="extra-news" style="display:none;"> December 2022: One research paper is accepted by the MDPI Sensors. </li>
  <li class="extra-news" style="display:none;"> November 2022: I have passed the Ph.D. qualifying exam. </li>
  <li class="extra-news" style="display:none;"> April 2022: Our research has been highlighted in the media: <a href="https://drive.google.com/file/d/1ebNgWJzdmOltDRo5dYI0Fm1hzkN7LXQT/view?usp=drive_link" target="_blank">North Texas Television</a> | <a href="https://news.unt.edu/news-releases/unt-professor-works-improve-communication-people-unable-speak-and-limited-mobility" target="_blank">UNT News</a> | <a href="https://www.ntdaily.com/professor-develops-talkmotion-app-for-those-unable-to-speak/" target="_blank">North Texas Daily</a> </li>
  <li class="extra-news" style="display:none;"> February 2022: Book chapter has been published. </li>
  <li class="extra-news" style="display:none;"> September 2021: Presented a research poster at the ACRM 2021. </li>
  <li class="extra-news" style="display:none;"> August 2021: Undergrad research work has been accepted in ICACC-2021. </li>
  <li class="extra-news" style="display:none;"> June 2021: Selected to participate in the 3-week "NMA-Deep Learning" course offered by Neuromatch Academy. </li>
  <li class="extra-news" style="display:none;"> October 2020: One research paper is accepted in DMIP-2020. </li>
  <li class="extra-news" style="display:none;"> September 2020: I, along with other Machine Learning researchers, organized a technical session titled "Best Practices for Validating Machine Learning in Medicine" at the 2020 Tapia Conference. <a href="https://www.youtube.com/watch?v=YrtqujFsUco&ab_channel=TheBiomedicalAILabatUNT" target="_blank">Session video</a>. </li>
  <li class="extra-news" style="display:none;"> September 2020: Presented one research poster at the 2020 Tapia Conference. <a href="https://drive.google.com/file/d/1-ZCSfBYEvfRfv2AwdSI3CGROKYaP6-eW/view?usp=sharing" target="_blank">Presentation</a>.    
</ul>


<button id="toggle-news-btn" style="
  border:1px solid #007bff;
  background:none;
  padding:6px 12px;
  border-radius:4px;
  cursor:pointer;
  color:#007bff;
">
  Show More
</button>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const hiddenItems = document.querySelectorAll(".extra-news");
  const btn = document.getElementById("toggle-news-btn");

  btn.onclick = function () {
    hiddenItems.forEach(item => {
      item.style.display = item.style.display === "none" ? "list-item" : "none";
    });

    btn.textContent = (btn.textContent === "Show More") ? "Show Less" : "Show More";
  };
});
</script>
