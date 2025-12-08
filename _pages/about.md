---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a 5th-year Ph.D. candidate in the [Computer Science and Engineering](https://computerscience.engineering.unt.edu/) department at the [University of North Texas](https://www.unt.edu/), where I am also serving as a Graduate Research Assistant in the [Biomedical AI lab](https://www.biomed-ai.com/home). My research focuses on developing a fast and flexible gesture recognition system that utilizes wearable sensor data for individuals with motor impairments who are unable to speak. I am particularly interested in exploring transfer learning, continual learning, and meta-learning strategies for custom gesture training with a few examples. Recently, I have been incorporating large language model (LLM) reasoning to enhance adaptability and robustness in gesture recognition under limited training data. Under the supervision of [Dr. Mark V. Albert](https://sites.google.com/view/biomed-ai/people/mark-v-albert) and [Dr. Weishi Shi](https://scholar.google.com/citations?user=nAPZIPsAAAAJ&hl=en), I am utilizing my expertise in deep learning and AI to make a real-world impact and improve the lives of those in need. Previously, I earned my M.S. in Artificial Intelligence from the University of North Texas and my B.Sc. in Computer Science and Engineering from Chittagong University of Engineering and Technology in Bangladesh.

<h2> Recent News </h2>
------
<ul>
  <li> <strong> Jan 2025: </strong> I successfully passed the coding rounds for the Software Engineer, Machine Learning Internship position at <strong> Meta </strong> for Summer 2025, but unfortunately, due to headcount limitations, I was not matched with a team. </li>    
  <li> <strong> Jul 2024: </strong> My Ph.D. proposal is officially done. </li>
  <li> <strong> May 2024: </strong> One research paper is accepted in IJCAI 2024. </li>
  <li> <strong> Mar 2023: </strong> One research paper is accepted in ICHI 2023. </li>
  <li> <strong> Feb 2023: </strong> One research paper is accepted by the Journal of Patient-Reported Outcomes. </li>
  
  <li class="extra-news" style="display:none;"> <strong> Dec 2022: </strong> One research paper is accepted by the MDPI Sensors. </li>
  <li class="extra-news" style="display:none;"> <strong> Nov 2022: </strong> I have passed the Ph.D. qualifying exam. </li>
  <li class="extra-news" style="display:none;"> <strong> Apr 2022: </strong> Our research has been highlighted in the media: <a href="https://drive.google.com/file/d/1ebNgWJzdmOltDRo5dYI0Fm1hzkN7LXQT/view?usp=drive_link" target="_blank">North Texas Television</a> | <a href="https://news.unt.edu/news-releases/unt-professor-works-improve-communication-people-unable-speak-and-limited-mobility" target="_blank">UNT News</a> | <a href="https://www.ntdaily.com/professor-develops-talkmotion-app-for-those-unable-to-speak/" target="_blank">North Texas Daily</a> </li>
  <li class="extra-news" style="display:none;"> <strong> Feb 2022: </strong> Book chapter has been published. </li>
  <li class="extra-news" style="display:none;"> <strong> Sep 2021: </strong> Presented a research poster at the ACRM 2021. </li>
  <li class="extra-news" style="display:none;"> <strong> Aug 2021: </strong> Undergrad research work has been accepted in ICACC-2021. </li>
  <li class="extra-news" style="display:none;"> <strong> Jun 2021: </strong> Selected to participate in the 3-week "NMA-Deep Learning" course offered by Neuromatch Academy. </li>
  <li class="extra-news" style="display:none;"> <strong> Oct 2020: </strong> One research paper is accepted in DMIP-2020. </li>
  <li class="extra-news" style="display:none;"> <strong> Sep 2020: </strong> I, along with other Machine Learning researchers, organized a technical session titled "Best Practices for Validating Machine Learning in Medicine" at the 2020 Tapia Conference. <a href="https://www.youtube.com/watch?v=YrtqujFsUco&ab_channel=TheBiomedicalAILabatUNT" target="_blank">Session video</a>. </li>
  <li class="extra-news" style="display:none;"> <strong> Sep 2020: </strong> Presented one research poster at the 2020 Tapia Conference. <a href="https://drive.google.com/file/d/1-ZCSfBYEvfRfv2AwdSI3CGROKYaP6-eW/view?usp=sharing" target="_blank">Presentation </a>. </li>    
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
    const isHidden = hiddenItems[0].style.display === "none";

    hiddenItems.forEach(item => {
      item.style.display = isHidden ? "list-item" : "none";
    });

    btn.textContent = isHidden ? "Show Less" : "Show More";
  };
});
</script>
