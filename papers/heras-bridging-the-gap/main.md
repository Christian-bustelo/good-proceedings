---
title: 'Bridging the gap: simplifying HPC access for data science users at Universidad de Sonora with Open OnDemand'
abstract: |
  The University of Sonora (UNISON), through its High Performance Computing Area (ACARUS), has successfully integrated Open OnDemand to address the increasing demand for high-performance computing (HPC) resources among researchers and students, particularly in data science fields where users often lack deep technical expertise in HPC systems. By providing an intuitive web-based interface, Open OnDemand has empowered non-specialized users to harness advanced computational resources, facilitating significant progress in data-driven research and interdisciplinary collaboration.

  This paper presents the implementation strategy at ACARUS, highlighting user-centered customization, training initiatives, and the resulting increase in HPC adoption. Beyond institutional benefits, the experience positions ACARUS and UNISON as a regional reference for democratizing HPC access across Mexico and Latin America, offering a replicable model for inclusive and scalable research infrastructure.
---


# Introduction

Since 2001, the University of Sonora has been committed to establishing and strengthening its High Performance Computing Area (ACARUS), in response to the growing demand for advanced technological infrastructure to support complex, interdisciplinary research projects. From its inception, ACARUS has positioned itself as a vital technological hub, providing researchers, faculty, and students with access to cutting-edge computing resources that enable high-speed and memory-intensive scientific computation [@uson2023].

Over the years, ACARUS has continuously evolved—expanding its computational capacity and diversifying its services to support research in diverse fields such as physics, chemistry, biology, artificial intelligence, and data science. Through its focus on innovation and collaboration, ACARUS has become a cornerstone of scientific and academic progress not only at the University of Sonora, but across Mexico.

The impact of ACARUS is rooted in two key pillars: first, the availability of high-performance computing equipment capable of supporting advanced research; second, the provision of industry-standard software tools that allow students and faculty to develop technical skills aligned with the demands of both academic and industrial sectors. This dual focus equips users with a competitive advantage in research and the job market alike.

As scientific computing technologies and software development rapidly advance, ACARUS faces the ongoing challenge of maintaining and updating its infrastructure. In the medium term, trends in supercomputing point toward increasingly specialized solutions for processing-intensive tasks in higher education institutions. The University of Sonora, through ACARUS, plays a strategic role in mediating and fostering inter-institutional collaboration.

Today, ACARUS stands as a leading center for technological, scientific, and industrial innovation in northern Mexico. It supports the development of a knowledge-based economy by facilitating interdisciplinary research and inter-institutional cooperation. Its current portfolio of services includes:

- Specialized technical support: guidance on scientific software installation, code optimization, environment setup, and HPC troubleshooting.

- Training and capacity building: workshops and courses in parallel programming, cluster administration, scientific computing, and AI.

- Supercomputing access: infrastructure optimized for simulations, modeling, big data analytics, and machine learning.

- Teaching resources: physical and virtual environments for courses in data science, AI, and computational sciences.

- Data storage: secure, scalable systems for managing large volumes of research data with controlled access.

- Cloud computing: on-demand private cloud services for remote access to scientific computing resources.

- Virtual machines: customized environments for development, testing, and software execution.

- Digital repositories: structured platforms to store and share datasets, code, publications, and models—promoting reproducibility and open science.

In 2022, the University of Sonora became the first Latin American institution to implement Open OnDemand, an open-source HPC access platform [@10.1145/2949550.2949644]. This milestone was shared with collaborators across the Mexican Supercomputing Network (RedMexSu) and SCALAC (Advanced Computing System for Latin America and the Caribbean), further strengthening regional partnerships [@scalac2023; @redmexsu2023].

High-performance computing (HPC) systems are essential for modern research, yet their complexity often limits access to users without computational backgrounds. At the University of Sonora, Open OnDemand has significantly improved accessibility, particularly for students and researchers in data science. By providing a user-friendly, web-based interface, Open OnDemand has helped democratize access to HPC resources, reducing barriers to entry and fostering interdisciplinary collaboration [@10.21105/joss.00622; @10.1145/3626203.3670538].

Before its implementation, many promising data science projects were delayed or abandoned—not due to lack of scientific merit, but because users struggled with traditional HPC systems. Open OnDemand addressed this gap by:

- Customizing the platform for non-specialized users, emphasizing ease of use and intuitive navigation.

- Enabling seamless access to HPC tools for machine learning, big data analytics, and modeling.

- Providing simplified workflows through features such as graphical job submission, remote visualization, and file management.

As a result, ACARUS has empowered a new generation of researchers to harness HPC capabilities efficiently, allowing them to focus on innovation rather than infrastructure.

# Results

## Implementation at Universidad de Sonora.

The implementation of Open OnDemand at the University of Sonora was not simply a technical deployment; it was a strategic initiative focused on the needs of its user community. The rollout prioritized customization, training, and user support, resulting in an accessible and user-centered high-performance computing (HPC) environment:

- Customization – the interface was adapted to prominently feature tools commonly used by data scientists, such as Python, R, TensorFlow, and Jupyter Notebooks.

- Training – targeted workshops and tutorials were organized to introduce Open OnDemand to new users, lowering the entry barrier for running HPC jobs.

- Support – ongoing personalized assistance was provided to help researchers transition their existing workflows into the HPC ecosystem.

This implementation approach ensured that the platform was not only operational but also aligned with the skills and goals of its users, particularly students and researchers in data-intensive fields.

## User-centric benefits.

Open OnDemand's web-based interface significantly reduced the complexity traditionally associated with HPC systems. By eliminating the need for command-line proficiency, the tool accelerated adoption, especially among students and researchers in data science and artificial intelligence.

Key features such as graphical job submission, remote visualization, and intuitive file management have lowered technical barriers, allowing users to focus on scientific goals rather than infrastructure configuration. As a result, both novice and experienced users have increasingly adopted the platform.

@fig:profiles and @fig:users are graphs showing the increase in registered users and job submissions since the introduction of Open OnDemand in July 2022.

:::{figure} fig-profiles.png
:label: fig:profiles

Total number of ACARUS users by user profile, July 2022 to July 2024: a comparative analysis.
:::


:::{figure} fig-users.png
:label: fig:users

Total number of ACARUS users (2001–2024)
:::

This upward trend began after a brief training session and reflects the platform’s impact on engagement and productivity in the ACARUS user base.

## Empowering data science projects.

One illustrative success case is the research project titled: “Exploration and Development of Tools for the Integration of AI Models into the Processes of CERN-CMS Experiment and Their Study Using ParticleNet.”. The project focused on training a multilayer neural network to classify particle decay patterns using datasets from CERN’s CMS experiment (@fig:training). By leveraging ACARUS infrastructure via Open OnDemand, researchers were able to:

- Access HPC resources and scientific software efficiently.

- Conduct model training and testing using complex physics datasets.

- Lower technical entry barriers for researchers new to supercomputing.

This initiative illustrates how Open OnDemand facilitates interdisciplinary research and supports advanced applications in particle physics and AI.

:::{figure} fig-training.png
:label: fig:training

Training a multilayer neural network in the context of particle physics, to classify particle decays.
:::

With the anticipated exponential growth of CMS data between 2026 and 2038, this type of work becomes increasingly critical for managing data complexity and accelerating discovery.

## Broader institutional benefits.

The deployment of Open OnDemand has generated institution-wide benefits, including:

- User growth: the number of active HPC users doubled from the previous year.

- Cross-disciplinary collaboration: researchers from diverse fields now share computing resources and datasets more easily.

- Improved efficiency: support requests related to technical issues have decreased, freeing users to concentrate on scientific tasks.

## Lessons learned.

From this experience, several key insights emerged:

- Early engagement is essential – understanding the specific needs of data science researchers allowed for a more targeted and relevant platform rollout.

- Training amplifies impact – even with a simplified interface, structured onboarding was critical for user confidence and effectiveness.

- Iterative development pays off – user feedback loops led to continuous improvements, increasing usability and functionality over time.

The platform’s success demonstrates that lowering technical barriers in HPC environments is a catalyst for both research innovation and community growth.

## Future directions

To further expand the platform’s value, the following improvements are in development:

- Integration of specialized tools for machine learning and big data workflows.

- Role-specific dashboards tailored to user profiles such as faculty, students, and system admins.

- Federated management of remote HPC systems across institutions.

- Collaborations across Mexico and Latin America to share best practices and promote equitable access to HPC resources.

These initiatives aim to ensure that HPC is accessible regardless of a user’s technical background or institutional capacity, aligning with broader goals of technological inclusion and academic innovation.

# Conclusions

At ACARUS, the high-performance computing center of University of Sonora, the implementation of Open OnDemand has significantly reduced technical and knowledge barriers, enabling a broader and more diverse group of users—especially in data science—to access HPC resources efficiently.

This platform has enhanced productivity, usability, and satisfaction among researchers and students, fostering a more inclusive and interdisciplinary research environment. Its adoption has not only simplified supercomputing workflows but also empowered emerging research groups with limited HPC experience to undertake complex scientific challenges.

In the context of Mexico and Latin America, ACARUS stands out as a pioneering example of how web-based access tools like Open OnDemand can democratize supercomputing. This positions Universidad de Sonora as a regional leader in promoting equitable access to advanced computational resources.

Looking ahead, continued growth in Open OnDemand usage at ACARUS is expected to drive innovation, support impactful research, and further strengthen our role as a strategic hub for scientific and technological development in Latin America.

In summary, Open OnDemand at ACARUS has become a key enabler of high-impact research in Mexico, helping bridge the HPC gap across institutions and disciplines throughout the region.