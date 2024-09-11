---
# Display name
# title: 吳健雄

# Name pronunciation (optional)
name_pronunciation: Baris Sarper Tezcan

# Full name (for SEO)
first_name: Baris Sarper
last_name: Tezcan

# Status emoji
# status:
#   icon: ☕️

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Undergraduate Student

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Middle East Technical University (METU)
    url: https://www.metu.edu.tr/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:barissarper@gmail.com'
    label: E-mail Me
  # - icon: brands/x
  #   url: https://twitter.com/GetResearchDev
  # - icon: brands/instagram
  #   url: https://www.instagram.com/
  - icon: brands/github
    url: https://github.com/barissarpertezcan
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/barissarpertezcan/
  # - icon: academicons/google-scholar
  #   url: https://scholar.google.com/
  # - icon: academicons/orcid
  #   url: https://orcid.org/

interests:
  - Computer Vision
  - Minimal Supervision Algorithms
  - Generative AI

education:
  - area: B.Sc. in Computer Engineering  
    institution: Middle East Technical University
    date_start: 2019-08-29
    date_end: 2024-06-25
    summary: |
      - CGPA: 3.91/4.0

      Courses included:
      - CENG483: Introduction to Computer Vision
      - CENG501: Deep Learning
      - CENG796: Deep Generative Models
      
  - area: Double Major in Mathematics
    institution: Middle East Technical University
    date_start: 2022-09-22
    date_end: 2025-01-27
    # maybe relevant math courses can be added here
    summary: |
      - CGPA: 3.82/4.0
      
      Courses included:
      - MATH371: Differential Geometry
      - MATH358: Partial Differential Equations
      - MATH478: Mathematical Aspects of Cryptography

    # button:
    #   text: 'Read Thesis'
    #   url: 'https://example.com'
 
  # - area: BSc Artificial Intelligence
  #   institution: Massachusetts Institute of Technology
  #   date_start: 2016-01-01
  #   date_end: 2020-12-31
  #   summary: |
  #     GPA: 3.4/4.0
      
  #     Courses included:
  #     - lorem ipsum dolor sit amet, consectetur adipiscing elit
  #     - lorem ipsum dolor sit amet, consectetur adipiscing elit
  #     - lorem ipsum dolor sit amet, consectetur adipiscing elit

# to add hyperlink, use <a href="https://google.com" target="_blank" rel="noopener noreferrer">selam</a>

work:
  - position: Undergraduate Researcher
    company_name: Middle East Technical University
    company_url: https://user.ceng.metu.edu.tr/~gcinbis/
    # company_logo: '' # metu logo can be added here
    date_start: 2022-09-01
    date_end: 2023-09-01
    summary: |2-
      - Worked on the project “Weakly Supervised Learning for Remote Sensing Images” under the supervision of <a href="https://user.ceng.metu.edu.tr/~gcinbis/" target="_blank" rel="noopener noreferrer">R. Gokberk Cinbis</a>.
      - Modified <a href="https://arxiv.org/abs/2101.11253" target="_blank" rel="noopener noreferrer">Puzzle-CAM</a> by replacing the background class activation map (CAM) with a ”couldn’t decide” CAM to handle uncertain predictions, addressing the lack of a background class in the remote sensing domain. Evaluated model performance across various confidence thresholds using the DeepGlobe Land Cover Classification Dataset.
      - Conducted experiments on the effect of background and foreground threshold values in class activation maps on pseudo label quality using the PASCAL VOC dataset, identifying a key bottleneck in the weakly supervised semantic segmentation pipeline.

  - position: Computer Vision / Machine Learning Intern
    company_name: Kuartis
    company_url: https://kuartis.com/
    # company_logo: '' # kuartis logo can be added here
    date_start: 2023-07-01
    date_end: 2023-09-01
    summary: |2-
      - Conducted a literature review on Weather Classification for Autonomous Driving. Collected data for various weather conditions, applied the CLAHE filter to images, and divided them into patches. Adopted model architectures for multi-frame input, trained, and tested several image classification models.
      - Performed a literature review on Semantic Occupancy Prediction. Presented a report summarizing state-of-the-art architectures, loss functions, and datasets.
      - Implemented a horizon detection pipeline for Marines using classical vision methods. Utilized the Canny edge detector to extract edges at different scales, fused the extracted edge maps, fitted horizon lines on the fused maps using the Hough Line Transform, and eliminated outliers with RANSAC.
      - Evaluated several trackers in the OpenCV library and determined that the CSRT Tracker is the most accurate while achieving real-time performance.
      - Delivered a presentation on dataset curation, neural architecture search (NAS), and hyperparameter optimization.
    button:
      text: 'Read Internship Report'
      url: 'https://drive.google.com/file/d/1wdvLHTA2j-__drK1_lvz2Nj314IBsXiC/view?usp=drive_link'

  - position: Research Intern
    company_name: ROMER Lab
    company_url: https://romer.metu.edu.tr/
    company_logo: "custom/romer-logo.svg" # logo does not work
    date_start: 2022-07-01
    date_end: 2022-09-01

    summary: |2-
      - Worked on a project that aims to reposition a robot arm concerning the position, orientation, and alignment of a captured image of an object, ensuring it appears as though the arm never moved.
      - Researched, implemented, and compared several feature-based image-matching algorithms, including SIFT, SURF, FAST, ORB, and the <a href="https://arxiv.org/abs/1911.11763" target="_blank" rel="noopener noreferrer">SuperGlue model</a>, for accurate image alignment.
      - Applied RANSAC and NN ratio matching algorithms to eliminate weak matches, enhancing the robustness of the image-matching process.
    button:
      text: 'Read Internship Report'
      url: 'https://drive.google.com/file/d/1ix-z_szTtdNrKaY11G4a1cmBrfSwGbCW/view?usp=drive_link'


# Skills
# Add your own SVG icons to `assets/media/icons/`
# skills:
#   - name: Technical Skills
#     items:
#       - name: Python
#         description: ''
#         # percent: 80
#         icon: code-bracket
#       - name: Data Science
#         description: ''
#         percent: 100
#         icon: chart-bar
#       - name: SQL
#         description: ''
#         percent: 40
#         icon: circle-stack
#   - name: Hobbies
#     color: '#eeac02'
#     color_border: '#f0bf23'
#     items:
#       - name: Hiking
#         description: ''
#         percent: 60
#         icon: person-simple-walk
#       - name: Cats
#         description: ''
#         percent: 100
#         icon: cat
#       - name: Photography
#         description: ''
#         percent: 80
#         icon: camera

# languages:
#   - name: English
#     percent: 100
#   - name: Chinese
#     percent: 75
#   - name: Portuguese
#     percent: 25

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.

awards:
  - title: METU Graduation Project Competition (3rd Place)
    url: https://senior.ceng.metu.edu.tr/2024/RoboDetection/
    date: '2024-06-25'
    awarder: METU Computer Engineering Department
    icon: metu-ceng
    summary: |2-
      - Led a 5-person team in developing RoboDetection, a robot dog simulation project designed to aid rescue teams in disaster zones. The system, controlled via a remote web interface, autonomously detects and tracks individuals while generating a real-time 2D map of the environment.
      - Established the ROS connection between the server and the simulation environment using Husarnet VPN, enabling remote movement commands to be sent to the robot dog via a web interface.
      - Subscribed to the camera topic in the simulation to retrieve camera data and prepared it for transmission to the web interface for real-time monitoring.
      - Implemented the 2D map generation feature using the gmapping package in ROS, allowing the robot dog to create a real-time map of its environment.
  - title: TEKNOFEST Artificial Intelligence in Transportation Competition (2nd Place)
    url: https://drive.google.com/file/d/1nc37jQdmikfnnQ2c14G1KtQ9ffgaG-Mj/view
    date: '2021-09-01'
    awarder: TEKNOFEST
    icon: teknofest
    summary: |2-
      - In this competition, our task was to detect various objects and areas from UAV footage, including vehicles (automobiles, trucks, motorbikes, buses, etc.), pedestrians, as well as specialized zones like Flying Car Parking (FCP) areas and Flying Ambulance Landing (FAL) areas.
      - Tested the SuperGlue model for detecting Flying Car Parking (FCP) and Flying Ambulance Landing (FAL) areas but found that the model underperformed due to the lack of distinctive features in these areas.
      - Increased the dataset of FCP and FAL areas synthetically by placing these regions in varied backgrounds and applying color and shape augmentations using "flip" (Synthetic Image Generator).
      - Integrated the augmented FCP and FAL areas as new classes into the YOLOR-D6 model, significantly improving detection performance with satisfying results.
  - title: TUBITAK Unmanned Aerial Vehicle Competition (7th Place)
    url: https://drive.google.com/file/d/1K4yKdk2IsfbGsOKdjIu-MPriVcouM4ma/view?usp=sharing
    date: '2020-09-01'
    awarder: TUBITAK (The Scientific and Technological Research Council of Turkey)
    icon: tubitak
    summary: |2-
      - Developed a color-based region detection algorithm for a rotary-wing UAV, enabling it to autonomously fly along a specified route, locate fire and water-intake areas through image processing, and extinguish the fire by releasing water.

certificates:
- title: METU Graduation Project Competition (3rd Place)
  url: https://www.coursera.org/learn/neural-networks-deep-learning
  date: '2024-06-25'
  awarder: METU Computer Engineering Department
  icon: metu-ceng
  summary: |
    - A robot dog simulation project (RoboDetection) aiding rescue teams in disaster zones. Controlled via a remote web interface, it can detect and track people while generating real-time 2D maps of the environment.
---

## About Me

Baris Sarper Tezcan recently graduated with a degree in Computer Engineering and is continuing his double major in Mathematics at Middle East Technical University, Turkey, with plans to complete it by the end of Fall 2024. His primary interests lie in data-efficient learning algorithms, including weakly supervised, semi-supervised, few-shot, and zero-shot learning, as well as computer vision and generative AI.

During his studies, Baris expanded his expertise by working on a research project in weakly supervised learning for remote sensing, under the supervision of <a href="https://user.ceng.metu.edu.tr/~gcinbis/" style="color: orange;">Assoc. Prof. Dr. R. Gokberk Cinbis</a>. He has also taken graduate-level courses, such as Deep Generative Models, and successfully implemented an ICCV 2023 paper that lacked an open-source version, further improving his technical and research skills.
