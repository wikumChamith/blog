---
title:  "GSOC-2023: Improving the OpenMRS Developer Experience: Updating the SDK Final Evaluation"
layout: post
---

## Project Summery

* Project Title: Improving the OpenMRS Developer Experience: Updating the SDK Final Evaluation
* Primary mentor: [Daniel Kayiwa](https://talk.openmrs.org/u/dkayiwa)
* Contributor: [Wikum Weerakutti](https://www.linkedin.com/in/wikum-weerakutti-a455261a6/)
* Project Link: [Wiki Page Link](https://wiki.openmrs.org/display/projects/GSoC+2023%3A+Improving+the+OpenMRS+Developer+Experience%3A+Updating+the+SDK)







## Overview

This project has successfully enhanced the OpenMRS SDK to cater to the evolving needs of OpenMRS development.
The project objectives included creating a version of the SDK to support OpenMRS 1.x releases based on Java 7, upgrading the SDK to leverage Java 8 features, and enhancing the documentation system for all plugins.
Additionally, the project has reworked the build-distro and setup commands to allow per-version customizations, enabling the creation of Docker images based on different Java versions depending on the OpenMRS version.
These accomplishments ensure the updated SDK provides robust support for newer OpenMRS versions while retaining a legacy interface for existing features

## Objectives

* Spin-off a version of the SDK to support OpenMRS 1.x releases based on Java 7: COMPLETED
* Revamp the SDK to take advantage of Java 8 features
  * Use lambda expressions: PR CREATED
  * Use the Streams API: PR CREATED
  * Use the new Date and Time API: COMPLETED
  * Use the Optional class: PR CREATED
* Upgrade the SDK to use a recent version of Maven as the core: COMPLETED
* Improve the documentation system for all plugins: COMPLETED
* Improve the build-distro and setup commands by allowing per-version customizations: PR CREATED

Additionally, I've been actively involved in the following tasks:

* Enabling users to set up OpenMRS 3 with the SDK.
* Optimizing SDK Cache Management.
* Implementing quality-of-life improvements.
* Resolving bug issues, and more.

## Contributions

* [JIRA issues](https://issues.openmrs.org/browse/SDK-307?jql=project%20%3D%20SDK%20AND%20assignee%20in%20(currentUser())%20ORDER%20BY%20assignee%20ASC%2C%20created%20ASC)
* [Pull Requests](https://github.com/openmrs/openmrs-sdk/pulls?page=1&q=is%3Apr+author%3A%40me)

## Weekly Blog Posts

1.  [Community Bonding Period](https://wikumchamith.github.io/blog/GSOC-2023-Community-Bonding-Period/)
2.  [Coding Week 01](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-01/)
3.  [Coding Week 02](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-02/)
4.  [Coding Week 03](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-03/)
5.  [Coding Week 04](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-04/)
6.  [Coding Week 05](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-05/)
7.  [Coding Week 06](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-06/)
8.  [Coding Week 07](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-07/)
9.  [Coding Week 08](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-08/)
10. [Coding Week 09](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-09/)
11. [Coding Week 10](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-10/)
12. [Coding Week 11](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-11/)
13. [Coding Week 12](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-12/)
14. [Coding Week 13](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-13/)
15. [Coding Week 14-16](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-14-16/)
16. [Coding Week 17](https://wikumchamith.github.io/blog/GSOC-2023-Coding-Week-17/)

## Resources

* [Project proposal](https://docs.google.com/document/d/1y3eSdBFVntc5K29vURG7ML9o0dKqxi4FjN1Ne8bCp7A/edit?usp=sharing)
* [Mid-term evaluation update video](https://www.youtube.com/watch?v=s_zOnU4dBqQ)
* [OpenMRS GSOC showcase presentation](https://www.youtube.com/watch?v=Vn0cUZndCJM)
* [Final video presentation]()

## Future Works

To further enhance the OpenMRS Developer Experience, I am actively working on incorporating Java 17 support for OpenMRS. 
This improvement is particularly valuable for newcomers who are already utilizing Java 17, making their onboarding process smoother and more efficient.

## Thoughts on GSoC

My journey during GSOC with OpenMRS has been incredibly enriching. This experience has allowed me to not only advance my technical abilities but has also been an opportunity for personal growth.

I want to express my heartfelt gratitude to my mentors, Daniel Kayiwa, Ian Bacher, and Joshua Nsereko. Their unwavering support and guidance were instrumental in my success.

I would also like to extend my appreciation to every member of the OpenMRS community for their outstanding contributions and dedication.

Thank you all for this incredible journey!







