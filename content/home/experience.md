---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Project of Unmanned laboratory
    company: Institute of Biological Evidence in Xi’an Jiaotong University
    # company_url: ''
    # company_logo: org-gc
    # location: California
    date_start: 'Apr 2021'
    date_end: 'Present'
    description: |2-
    constructed a mobile manipulator and digital twin system for it to solve the problems of tedious experimental steps and long waiting time
        Responsibilities include:
        
        * Integrated a mobile manipulator with functions of map establishment, navigation and end-effector alignment
        * Created a virtual model for the digital twin of the mobile manipulator in Unity3D
        * Realized the two-way connections of data that ties the virtual and real products together through ROS (Robot Operating System) and Modbus communication protocol
        * Wrote scripts in Unity3D and realized simulation of collaborative manipulator before operation

  - title: Evaluation model for production and test process of aerospace liquid propulsion products
    company: China Academy of Aerospace Liquid Propulsion Technology
    # company_url: ''
    # company_logo: org-x
    # location: California
    date_start: 'Jun 2021'
    date_end: 'Sep 2022'
    description: Built evaluation model for its production and test process of aerospace liquid propulsion products to guide the construction of its manufacturing cells
        Responsibilities include:
        
        * Put forward partial evaluation elements and sub elements according to the theory of 5M1E
        * Investigated a number of cells in China Academy of Aerospace Liquid Propulsion Technology, such as engine assembly, casting, electroplating, etc., to iterate and optimize evaluation elements and criteria
        * Participated in writing “The technical scheme of the aerospace liquid propulsion process evaluation model” and “The work guide for construction of advanced manufacturing cells of aerospace liquid propulsion products”

  - title: Vision system of hull’s sub-assembly welding robot
    company: Shenzhen Youlian Shipyard
    # company_url: ''
    # company_logo: org-x
    # location: California
    date_start: 'Sep 2020'
    date_end: 'Oct 2021'
    description: Designed a vision system for its hull’s sub-assembly welding robot equipment and experimented on it, so as to achieve high efficiency, high quality and high Automated welding process
        Responsibilities include:
        
        * Installed laser transmitters and cameras on the gantry, which are used to scan the workpiece before welding
        * Analyzed images showing the situation of laser irradiation on the workpiece and designed an image recognition algorithm to recognize welding seams in images
        * Made the information file of welding seams, which is connected with the offline programming system to generate the executable file of the robot control system

  - title: Intern of NC Machine Tool operation
    company: Beijing Jingdiao Co., Ltd
    # company_url: ''
    # company_logo: org-x
    # location: California
    date_start: 'Sep 2020'
    date_end: 'Oct 2021'
    description: Experienced full production process of 3D modeling, programming, processing and assembly
        Responsibilities include:
        
        * Learned how to build 3D model and generate machining program in a CAM software named SurfMill
        * Used the SurfMill software and NC Machine Tool to complete the design and machining of a fingertip top toy
      
design:
  columns: '4'
---
