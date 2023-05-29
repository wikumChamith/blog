---
title:  "GSOC-2023: Community Bonding Period"
layout: post
---

I am thrilled to announce that I have been selected to participate in Google Summer of Code (GSOC) 2023, representing OpenMRS! This incredible opportunity is beyond exciting for me. 


## Orientation Session

First,  I participated in the orientation session for GSOC 2023 with OpenMRS, and let me tell you, it was absolutely fantastic! This session provided an incredible platform for me to meet and engage with mentors and fellow selected contributors. The atmosphere was brimming with enthusiasm and passion for open-source development. The mentors shared invaluable insights, providing us with comprehensive guidelines to ensure the success of our individual projects.

## First meeting with Mentors

The first meeting I had with my mentors, [Daniel](https://talk.openmrs.org/u/dkayiwa) and [Joshua](https://talk.openmrs.org/u/jnsereko), was very interesting. We discussed our plan for proceeding with the project. During the meeting, the mentors presented me with a new challenge: creating a feature that enables developers to deploy OpenMRS O3 using OpenMRS SDK.

## Building the O3

Before I began coding this feature, I needed to manually build the O3 to comprehend the building process. Despite encountering a few obstacles during the build, I ultimately succeeded in deploying the O3 by following these steps.

* Create a distro.properties file
    <script src="https://gist.github.com/wikumChamith/f901f639a46826a94aa0c0a4beb9885a.js"></script>
* Run mvn openmrs-sdk:setup -Ddistro=distro.properties
* Manually copy the [Initializer.omod](https://addons.openmrs.org/show/org.openmrs.module.initializer) file to the modules folder
* Copy the configuration folder to the OpenMRS application data folder
* Run mvn openmrs-sdk:run -DserverId=serverName

## Future

As the coding period begins my main objective is to implement this feature. I already created a draft PR for this. I hope that I will be able to quickly implement this with the support of my mentors.


