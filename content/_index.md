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
        - title: Research Intern
          company: IIT Delhi
          company_url: 'https://home.iitd.ac.in/'
          company_logo: iitd
          location: Remote - New Delhi, India
          date_start: '2023-08-01'
          date_end: '2023-12-01'
          description: |2-
              • Assisted in the design of a generative graph neural network enhanced with topological regularization, to improve SLAM for autonomous driving by removing dynamic objects from sparse LiDAR point clouds.
              \
              • Demonstrated superior performance against existing methods (44% lower Chamfer Distance than state-of-the-art) in three real-world and simulated datasets, against five distance metrics with 32 times sparse LiDAR scans.
              \
              • Contributed to a deep generative model for adversarial point injections on LiDAR scans, demonstrating superior performance in degrading map quality without compromising scan integrity on KITTI and CARLA-64 datasets.
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
              •  Shaped a post-processing routine for raw point cloud and IMU data in Rosbags for easy integration and validation of state-of-the-art 3D-LiDAR-based SLAM algorithms on real-world datasets of warehouses and shop floors.
    design:
      columns: '2'
  # - block: collection
  #   content:
  #     title: Projects
  #     text: 
  #     filters:
  #       folders:
  #         - project
  #   design:
  #     view: article-grid
  #     fill_image: false
  #     columns: 3
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
