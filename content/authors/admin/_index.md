---
# Display name
# title: 吳健雄

# Name pronunciation (optional)
name_pronunciation: Baris Sarper Tezcan

# Full name (for SEO)
first_name: Barış Sarper
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
  - Video Understanding

education:
  - area: B.Sc. in Computer Engineering  
    institution: Middle East Technical University
    date_start: 2019-08-29
    date_end: 2024-06-25
    summary: |
      - CGPA: 3.91/4.0

      Courses included:
      - lorem ipsum dolor sit amet, consectetur adipiscing elit
      - lorem ipsum dolor sit amet, consectetur adipiscing elit
      - lorem ipsum dolor sit amet, consectetur adipiscing elit

  - area: Double Major in Mathematics
    institution: Middle East Technical University
    date_start: 2022-09-22
    date_end: 2025-01-27
    # maybe relevant math courses can be added here
    summary: |
      - CGPA: 3.82/4.0
      
      Courses included:
      - lorem ipsum dolor sit amet, consectetur adipiscing elit

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
    # TODO: update the summary
    summary: |
      Worked under supervision of <a href="https://user.ceng.metu.edu.tr/~gcinbis/" target="_blank" rel="noopener noreferrer">R. Gokberk Cinbis</a>.
      Responsibilities include:
      - Migrated infrastructure to a new data center
      - lorem ipsum dolor sit amet, consectetur adipiscing elit
      - lorem ipsum dolor sit amet, consectetur adipiscing elit

  - position: Computer Vision / Machine Learning Intern
    company_name: Kuartis
    company_url: https://kuartis.com/
    # company_logo: '' # kuartis logo can be added here
    date_start: 2023-07-01
    date_end: 2023-09-01
    summary: |2-
      Responsibilities include:
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

    # TODO: update the summary
    summary: |
      Responsibilities include:
      - Migrated infrastructure to a new data center
      - lorem ipsum dolor sit amet, consectetur adipiscing elit
      - lorem ipsum dolor sit amet, consectetur adipiscing elit
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
  - title: Neural Networks and Deep Learning
    url: https://www.coursera.org/learn/neural-networks-deep-learning
    date: '2023-11-25'
    awarder: Coursera
    icon: coursera
    summary: |
      I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.
  - title: Blockchain Fundamentals
    url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    date: '2023-07-01'
    awarder: edX
    icon: edx
    summary: |
      Learned:
      - Synthesize your own blockchain solutions
      - Gain an in-depth understanding of the specific mechanics of Bitcoin
      - Understand Bitcoin’s real-life applications and learn how to attack and destroy Bitcoin, Ethereum, smart contracts and Dapps, and alternatives to Bitcoin’s Proof-of-Work consensus algorithm
  - title: 'Object-Oriented Programming in R'
    url: https://www.datacamp.com/courses/object-oriented-programming-with-s3-and-r6-in-r
    certificate_url: https://www.datacamp.com
    date: '2023-01-21'
    awarder: datacamp
    icon: datacamp
    summary: |
      Object-oriented programming (OOP) lets you specify relationships between functions and the objects that they can act on, helping you manage complexity in your code. This is an intermediate level course, providing an introduction to OOP, using the S3 and R6 systems. S3 is a great day-to-day R programming tool that simplifies some of the functions that you write. R6 is especially useful for industry-specific analyses, working with web APIs, and building GUIs.

certificates:
  - title: Neural Networks and Deep Learning
    url: https://www.coursera.org/learn/neural-networks-deep-learning
    date: '2023-11-25'
    awarder: Coursera
    icon: coursera
    summary: |
      I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.  
---

## About Me

Chien Shiung Wu is a professor of artificial intelligence at the Stanford AI Lab. Her research interests include distributed robotics, mobile computing and programmable matter. She leads the Robotic Neurobiology group, which develops self-reconfiguring robots, systems of self-organizing robots, and mobile sensor networks.
