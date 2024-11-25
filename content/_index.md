---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'News'
      text: |-
        - [2024] Our paper "High-resolution infrastructure defect detection dataset sourced by unmanned systems and validated with deep learning approaches" is accepted to **Automation in Construction (AIC)**!
        
        - [2024] Our paper "CUBIT-Det: A high-definition infrastructure defect dataset fully evaluated with deep learning processes" is accepted to **IEEE International Conference on Control & Automation (ICCA)**!
        
        - [2024] Our paper "Det-Recon-Reg: An intelligent framework towards automated large-Scale infrastructure inspection" is accepted to **IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)**!
        
        - [2024] Our paper "SANet: Small but accurate detector for aerial flying object" is accepted to **IEEE International Conference on Robotics and Automation (ICRA)**!

        - [2023] Our paper "Multi-view stereo with learnable cost metric" is accepted to **IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)**!
  
  - block: collection
    id: papers
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: markdown
    content:
      title: 'Publications'
      text: |-
        ### Journal Articles
        1. **B. Zhao**, X. Zhou, G. Yang, J. Wen, J. Zhang, J. Dou, G. Li, X. Chen and B. M. Chen, "*High-resolution infrastructure defect detection dataset sourced by unmanned systems and validated with deep learning approaches*", **Automation in Construction (AIC)**, 2024.

        2. **B. Zhao**, Q. Duan, G. Yang, Z. Song, J. Wen, X. Liu, X. Chen and B. M. Chen, "*High-Performance Real-Time Defect Detector for UAV-Based Online Large-Scale Infrastructure Detection*", **IEEE Transactions on Automation Science and Engineering (T-ASE)**, 2024. (Under Review)

        3. **B. Zhao**<sup>1</sup>, G. Yang<sup>1</sup>, J. Zhang, J. Wen, X. Chen and B. M. Chen, "*Det-Recon-Reg: An Intelligent Framework Towards Automated Large-Scale Infrastructure Inspection*", **IEEE Transactions on Instrumentation and Measurement (T-IM)**, 2024. (Under Review) (<sup>1</sup>denotes co-first author)

        4. **B. Zhao**<sup>1</sup>, Q. Duan<sup>1</sup>, Z. Song, X. Zhang, X. Liu, X. Chen and B. M. Chen, "*VGS: Voxel Map based Surfel Gaussian Splatting for Scene Reconstruction*", **IEEE Transactions on Industrial Electronics (T-IE)**, 2024. (Under Review) (<sup>1</sup>denotes co-first author)

        5. J. Zhang, **B. Zhao**\*, G. Yang, X. Zhou, Y. Huang, C. Gao, X. Chen and B. M. Chen, "*Automated High-Precision Digital Twin Modeling of Building Façade Defects with Geobim-Assisted Registration*", **Advanced Engineering Informatics**, 2024. (Revised and Resubmitted) (\*denotes corresponding author)

        6. Q. Li, **B. Zhao**\*, X. Wang, G. Yang, Y. Chang, X. Chen and B. M. Chen, "*Autonomous Building Material Stock Estimation using 3D Modeling and Multilayer Perceptron: A Case of Hong Kong*", **Resources, Conservation & Recycling**, 2024. (Under Review) (\*denotes corresponding author)

        7. Q. Li, G. Yang, **B. Zhao**, X. Chen and B. M. Chen, "*Autonomous design framework for building integrated photovoltaics: data collection, 3D modeling, and deployment strategy*", **Applied Energy**, 2024.

        8. G. Yang, J. Wen, **B. Zhao**, Q. Li, X. Chen and B. M. Chen, "*Towards End-to-End Underwater Multi-View Stereo for Real-World Dense Scene Reconstruction*", **IEEE Transactions on Industrial Informatics (T-II)**, 2024. (Revised and Resubmitted)

        9. P. Zhou, S. Li, **B. Zhao**, B. Wahlberg, X. Hu, "*Nature-inspired dynamic control for pursuit-evasion of robots*", **Automatica**, 2024. (Under Review)

        10. J. Wen, G. Yang, **B. Zhao**, D. Huang, Y. Hu, B. Zhang, X. Chen and B. M. Chen, "*A semi-supervised domain-adaptive real-world underwater image enhancement method*", **IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT)**, 2024. (Under Review)

        11. G. Yang, K. Liu, J. Zhang, **B. Zhao**, Z. Zhao, X. Chen and B. M. Chen, "*Datasets and processing methods for boosting visual inspection of civil infrastructure: A comprehensive review and case study on crack classifications, segmentation, and detection*", **Construction and Building Materials**, 2022.

        12. J. Wen, J. Cui, G. Yang, **B. Zhao**, Y. Zhai, Z. Gao, L. Dou and B. M. Chen, "*WaterFormer: Global-Local transformer for underwater image enhancement with environment adaptor*", **IEEE Robotics and Automation Magazine (RA-M)**, 2024.

        13. G. Yang, R. Cao, J. Wen, **B. Zhao**, Q. Li, X. Chen, YH Liu and B. M. Chen, "*Multi-View Stereo with Geometric Encoding for Large-Scale Dense Scene Reconstruction*", **IEEE Transactions on Automation Science and Engineering (T-ASE)**, 2024. (Under Review)

        14. J. Wen, J. Cui, G. Yang, **B. Zhao**, Z. Gao, B. M. Chen, "*Progressive Domain-Adaptive Underwater Object Detection Assisted with Underwater Image Enhancement*", **Engineering Applications of Artificial Intelligence (EAAI)**, 2024. (Under Review)

        15. L. Long, Z. Gan, Z. Liu, **B. Zhao**, Q. Li, "*MSD-Det: Masonry Structures Damage Detection Dataset for Preventive Conservation of Heritage*", **Journal of Cultural Heritage**, 2024. (Under Review)

        16. Q. Li, L. Long, X. Li, G. Yang, C. Bian, **B. Zhao**, X. Chen and Ben M. Chen, "*Life cycle cost analysis of circular photovoltaic façade in dense urban environment using 3D modeling*", **Renewable Energy**, 2024.

        17. Q. Li, G. Yang, C. Gao, Y. Huang, J. Zhang, D. Huang, **B. Zhao**, X. Chen and B. M. Chen, "*Single drone-based 3D reconstruction approach to improve public engagement in conservation of heritage buildings: A case of Hakka Tulou*", **Journal of Building Engineering**, 2024.

        18. Y. He, H. Xu, C. Ren, X. Liu, W. Feng, L. Zuo, Z. Huang and **B. Zhao**, "*Research status of preparation methods of multi-component high entropy alloy*", **Nonferrous Metals Engineering**, 2020.

        ### Conference Papers
        1. **B. Zhao**, X. Zhou, G. Yang, J. Wen, J. Zhang, X. Chen and B. M. Chen, "*CUBIT-Det: A high-definition infrastructure defect dataset fully evaluated with deep learning processes*", **IEEE International Conference on Control & Automation (ICCA)**, Reykjavík, Iceland, 2024.

        2. **B. Zhao**, Q. Duan, G. Yang, Z. Song, J. Wen, X. Liu, H. Tang, Q. Li, X. Chen and B. M. Chen, "*Lightweight yet High-Performance Defect Detector for UAV-Based Large-Scale Infrastructure Real-Time Inspection*", **IEEE International Conference on Robotics and Automation (ICRA)**, Atlanta, USA, 2025. (Under Review)

        3. G. Yang<sup>1</sup>, **B. Zhao**<sup>1</sup>, J. Zhang, C. Gao, Y. Huang, J. Wen, Q. Li, X. Chen and B. M. Chen, "*Det-Recon-Reg: An intelligent framework towards automated large-Scale infrastructure inspection*", **IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)**, Abu Dhabi, UAE, 2024. (<sup>1</sup>denotes co-first author)

        4. X. Zhou, **B. Zhao**\*, G. Yang, J. Zhang, L. Li and B. M. Chen, "*SANet: Small but accurate detector for aerial flying object*", **IEEE International Conference on Robotics and Automation (ICRA)**, Yokohama, Japan, 2024. (\*denotes corresponding author)

        5. J. Wen, J. Cui, **B. Zhao**, B. Han, X. Liu, Z. Gao and B. M. Chen, "*EnYOLO: A Real-Time Framework for Domain-Adaptive Underwater Object Detection with Image Enhancement*", **IEEE International Conference on Robotics and Automation (ICRA)**, Yokohama, Japan, 2024.

        6. J. Wen, G. Yang, **B. Zhao**, D. Huang, Y. Hu, B. Zhang, X. Chen and B. M. Chen, "*I2D-UIE: Alleviating Inter- and Intra-Domain Shifts for Real-world Underwater Image Enhancement*", **IEEE International Conference on Robotics and Automation (ICRA)**, Atlanta, USA, 2025. (Under Review)

        7. G. Yang, J. Wen, **B. Zhao**, Q. Li, Y. Huang, X. Chen, A. Lam, and B. M. Chen, "*End-to-End Underwater Multi-View Stereo for Dense Scene Reconstruction*", **IEEE International Conference on Robotics and Automation (ICRA)**, Atlanta, USA, 2025. (Under Review)

        8. G. Yang, R. Cao, J. Wen, **B. Zhao**, Q. Li, Y. Huang, X. Chen, A. Lam, YH Liu and B. M. Chen, "*Multi-View Stereo with Geometric Encoding for Dense Scene Reconstruction*", **IEEE International Conference on Robotics and Automation (ICRA)**, Atlanta, USA, 2025. (Under Review)

        9. J. Wen, J. Cui, G. Yang, **B. Zhao**, Y. Zhai, Z. Gao, L. Dou and B. M. Chen, "*WaterFormer: Global-Local transformer for underwater image enhancement with environment adaptor*", **IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)**, Abu Dhabi, UAE, 2024.

        10. J. Wen, J. Cui, G. Yang, **B. Zhao**, Z. Gao and B. M. Chen, "*Underwater object detection integrated with image enhancement*", **IEEE International Conference on Real-time Computing and Robotics (RCAR)**, Alesund, Norway, 2024.

        11. G. Yang, X. Zhou, C. Gao, **B. Zhao**, J. Zhang, Y. Chen, X. Chen and B. M. Chen, "*Multi-view stereo with learnable cost metric*", **IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)**, Detroit, Michigan, USA, 2023.

        12. X. Zhou, G. Yang, Y. Chen, C. Gao, **B. Zhao**, L. Li and B. M. Chen, "*ADMNet: Anti-drone real-time detection and monitoring*", **IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)**, Detroit, Michigan, USA, 2023.
    design:
      columns: '1'
      spacing:
        padding: ["2rem", "0", "2rem", "0"]
  
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
