---
layout: about
title: about
permalink: /
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

# profile:
#   align: right
#   image: prof_pic.jpg
#   image_circular: false # crops the image to make it circular
#   more_info: >
#     <p>555 your office number</p>
#     <p>123 your address street</p>
#     <p>Your City, State 12345</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div style="display:flex; justify-content:center; align-items:center; gap:30px;">

  <img
    src="{{ '/assets/img/group_logo_light.png' | relative_url }}"
    class="only-light"
    alt="ARG at NTU Singapore"
    style="width: 40%; height: auto;"
  >

  <img
    src="{{ '/assets/img/group_logo_dark.png' | relative_url }}"
    class="only-dark"
    alt="ARG at NTU Singapore"
    style="width: 40%; height: auto;"
  >

  <img
    src="{{ '/assets/img/ntu_logo.svg' | relative_url }}"
    alt="NTU"
    style="width: 50%; height: auto;"
  >

</div>

<img src="/assets/img/group_photo.jpg" alt="ARGer at NTU Singapore" style="width:80%; height:auto; display:block; margin:0 auto 1.5rem auto;">

Welcome! We are the Algorithmic Robotics Group within the [College of Computing and Data Science](https://www.ntu.edu.sg/computing) at [Nanyang Technological University](https://www.ntu.edu.sg/), Singapore. We design planning and learning algorithms to build general-purpose intelligent robots capable of performing long-horizon manipulation tasks and interacting with other robots and humans.

content_after_news: |
  <a name="research"></a>

  <h2 class="mt-4">Research Areas</h2>

  <h3 class="mt-3">Long-horizon planning and decision-making</h3>

  <p>
  Achieving long-horizon planning and decision-making capabilities, such as cooking a meal or cleaning a messy room, is essential for building intelligent robots. However, these tasks are challenging because they require selecting appropriate high-level actions, such as picking up a cup, and effectively planning how to execute those actions while satisfying physical and geometric constraints. We design <a href="https://arxiv.org/abs/2010.01083" target="_blank">task and motion planning</a> algorithms to effectively address such challenges. Additionally, we are interested in exploring <a href="https://arxiv.org/abs/2410.05828" target="_blank">new problem classes</a> by introducing practically relevant constraints and objectives.
  </p>

  <h3 class="mt-4">Robot learning</h3>

  <p>
  We aim for robots to learn from past experiences and adapt their behaviors in a generalizable and robust manner to handle novel tasks. Recent advancements in deep learning and foundation models offer significant opportunities for robotics to embrace data-driven approaches by leveraging breakthroughs in computer vision and natural language processing. Robot learning encompasses, but is not limited to, the development of <a href="https://arxiv.org/abs/2406.09246" target="_blank">robot foundation models</a>, the use of <a href="https://arxiv.org/abs/2204.01691" target="_blank">LLMs</a>, and the learning of <a href="https://arxiv.org/abs/2409.16012" target="_blank">representations</a>, <a href="https://www.researchgate.net/profile/George-Konidaris/publication/323078755_From_Skills_to_Symbols_Learning_Symbolic_Representations_for_Abstract_High-Level_Planning/links/5a7e8e48a6fdcc0d4ba8342c/From-Skills-to-Symbols-Learning-Symbolic-Representations-for-Abstract-High-Level-Planning.pdf" target="_blank">symbols</a>, <a href="https://arxiv.org/abs/2206.10680" target="_blank">skills</a>, <a href="https://arxiv.org/abs/2103.04374" target="_blank">policies</a>, and <a href="https://arxiv.org/abs/2211.07847" target="_blank">heuristics</a>. In designing the learning pipeline, we often consider approaches such as few-shot learning, imitation learning, lifelong learning, and curriculum learning.
  </p>

  <h3 class="mt-4">Interaction with other agents</h3>

  <p>
  Robots are often deployed in environments where they coexist with other robots or humans, working collaboratively toward a common goal. Interactions with other robots involve challenges such as task decomposition, allocation, and <a href="https://arxiv.org/abs/2309.08897" target="_blank">multi-robot planning</a>. In contrast, interactions with humans require inferring human intentions or behaviors and dynamically adapting the robot's strategy based on these inferences. <a href="https://arxiv.org/abs/2202.10450" target="_blank">Ad-hoc teamwork</a> aims to address these challenges, enabling effective and seamless human-robot collaboration.
  </p>