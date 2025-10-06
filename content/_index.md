---
# Leave the homepage title empty to use the site title
title: Kshitij's webpage
date: 2025-01-06
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Computer Vision and Robotics Intern
          company: Bloomfield Robotics, Inc.
          company_url: 'https://bloomfield.ai/'
          company_logo: bloomfield
          location: Pittsburgh, PA, USA
          date_start: '2025-05-12'
          date_end: '2025-08-22'
          description: |2-
              • Created a novel visual odometry (VO) pipeline with GPS fusion for sparse stereo images, leveraging learning-based dense feature matching to generate high-fidelity 3D reconstructions of fruit crops and improving yield estimates.
              \
              • Experimentally validated the VO system, achieving robust performance with an Absolute Trajectory Error (ATE) of 2.5m and Relative Pose Error (RPE) of 0.5m over a 100m trajectory using only a sparse set of 300 images.
              \
              • Engineered a high-throughput stereo depth estimation pipeline using batch processing to parallelize a CUDA-accelerated high resolution stereo disparity estimation and I/O operations, boosting processing throughput by 44.4%.
        - title: Research Collaborator
          company: IIT Delhi
          company_url: 'https://home.iitd.ac.in/'
          company_logo: iitd
          location: Remote - New Delhi, India
          date_start: '2023-08-01'
          date_end: '2023-12-01'
          description: |2-
              • Designed a generative graph neural network enhanced with topological regularization, to improve mapping for autonomous driving by removing dynamic objects from sparse LiDAR point clouds without segmentation labels.
              \
              • Demonstrated superior performance against existing methods (44% lower Chamfer Distance than state-of-the-art) in three real-world and simulated datasets, against five distance metrics with 32 times sparse LiDAR scans.
              \
              • Contributed to an adversarial deep generative model for point injections on LiDAR scans, demonstrating superior performance in degrading map quality without compromising scan integrity on KITTI and CARLA-64 datasets.
          links:
            - icon: globe
              icon_pack: fas
              name: Website
              url: https://kshitijbhat.github.io/glidr/
            - icon: github
              icon_pack: fab
              name: Github
              url: https://github.com/KshitijBhat/GLiDR-CVPR24
          
        - title: Research Intern
          company: Lakehead University
          company_url: 'https://www.lakeheadu.ca/'
          company_logo: lakehead
          location: Thunder Bay, Ontario, Canada
          date_start: '2023-05-01'
          date_end: '2023-08-01'
          description: |2-
              • Engineered a four-wheel steering and driving (4WS) mobile robot platform using Design for Assembly (DFA) techniques, resulting in a modular and easily maintainable platform for kinodynamic navigation algorithm development.
              \
              • Developed C firmware for Raspberry Pi Pico microcontrollers, and integrated PID control to actuators and enabling joint state data collection and velocity feedback, enhancing navigational accuracy in unstructured environments.
              \
              •  Created hardware-agnostic C++ software to interface PID angle and velocity controllers using the ROS Control framework via serial communication, leading to general middleware suitable to any 4WS robot platform.
          links:
            - icon: github
              icon_pack: fab
              name: Github
              url: https://github.com/KshitijBhat/robot-4wsd

        - title: Summer Intern, Autonomy Software
          company: Ati Motors
          company_url: 'https://atimotors.com/'
          company_logo: ati
          location: Bengaluru, India
          date_start: '2022-05-01'
          date_end: '2022-07-01'
          description: |2-
              • Optimized Model Predictive Control (MPC) for Autonomous Mobile Robots (AMR) to achieve a 3x reduction in the turning radius, enabling sharp turns and in-place manoeuvres for space-constrained industrial units.
              \
              • Reformed MPC cost function optimization problem to consider physical motor constraints and latency, redesigned Jacobian matrix to speed up the solution compute time and validated it with comprehensive on-site testing.
              \
              •  Validated state-of-the-art 3D LiDAR-based factor graph SLAM algorithms on real-world datasets of warehouses and shop floors and shaped a post-processing routine for raw point cloud and IMU data in rosbags for easy integration.
    design:
      columns: '2'
  - block: collection
    content:
      title: Projects
      text: 
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3
  - block: collection
    id: featured-publications
    content:
      title: Featured publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    id: other-publications
    content:
      title: Other publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
#  - block: collection
   # id: talks
 #   content:
  #    title: Recent & Upcoming Talks
 #     filters:
 #       folders:
#          - event
#    design:
 #     columns: '2'
 #     view: compact
---
