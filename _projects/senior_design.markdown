---
layout: project
title: "Data Prioritization Manager"
date: 2023-01-10
end_date: 2023-05-04
categories: [Software Development, Web Application, React]
description: This project is a web application created for LAS at NC State, using Django, React.js, and PostgreSQL to improve sorting efficiency
order: 2
---

## Project Overview
<a href="https://github.com/sethemory/NCSU_Senior_Design_Project">Github Repository</a>

In my senior design project at North Carolina State University, my team and I developed a data prioritization manager application for the Laboratory of Analytic Sciences (LAS) to enhance their data sorting efficiency. This project invodlved using the Django REST Framework, React.js, and PostgreSQL—a suite of technologies new to most of us, necessitating a rapid and collaborative learning process.

The project requirements from LAS were dynamic and open-ended, requiring us to adapt continually. Throughout the development, we maintained detailed logs of our activities, contributions, and time investment (approximately 10 hours weekly), ensuring transparency and structured progress. Regular updates and interactions with LAS were facilitated through Slack and weekly meetings, helping us align closely with their evolving needs.

My primary role was in frontend development, where I took initiative in designing and implementing all user-interface components. This involved not only crafting the interface but also ensuring these components communicated effectively with our backend via API integrations, which I tested rigorously. Additionally, I played a crucial role in developing the project’s final presentation poster, summarizing our problem analysis, the technological solutions we implemented, and our testing procedures.

The project culminated in a comprehensive suite of documentation, including a detailed project report, a user’s guide for end-users, and a developer guide to assist future contributions to the project. These documents are testament to our thorough approach and commitment to creating a sustainable and user-friendly solution.

## Project Description
Our project is a web-based application designed as a configuration manager for data storage methods, streamlining the process of managing data distribution through customizable rules and storage buckets.

![Image Title](\assets\images\Senior_Design\Dashboard.png)
<figcaption>Here is the dashboard homepage for the application.</figcaption>

User Access and Security: The system supports basic user authentication, where users log in with a username and password. Users are categorized into two roles: 'read' and 'write'. Users with read access can view all components of the system, including buckets and rules, while those with write access can also edit configurations and export them when needed.

Data Configuration Management: At the heart of the application are the 'buckets', which are storage entities defined by parameters like name, data size, and rules. These buckets follow specific rules that dictate the type of data stored, prioritization, and other settings, ensuring efficient data management. Rules can be as simple as IP filters or as complex as IP-port pair combinations, and are modifiable through user inputs or CSV uploads.

![Image Title](\assets\images\Senior_Design\buckets.png)
<figcaption>This page shows all the buckets within the system and some overview information about each bucket.</figcaption>

![Image Title](\assets\images\Senior_Design\rules.png)
<figcaption>This page shows all the rules within the system and some overview information about each rule.</figcaption>

Goals and Functionality: The main objective is to allow users, whether starting from scratch or modifying existing configurations, to manage how data is stored and prioritized effectively. This is achieved through an intuitive interface for creating and modifying the configurations of buckets and their associated rules.

![Image Title](\assets\images\Senior_Design\import-export.png)
<figcaption>Screenshot showing how the user could import or export files in the system.</figcaption>

This system not only provides a robust framework for data configuration but also ensures that later developers can enhance and expand the user and role management features.

<hr>

### Here is the Final Project Report
<iframe src="\assets\documents\Senior Design\LAS_FPR.pdf" class="embedded-pdf" allowfullscreen></iframe>

### Here is the User Guide that was created for the application
<iframe src="\assets\documents\Senior Design\LAS1_IPR.pdf" class="embedded-pdf" allowfullscreen></iframe>
