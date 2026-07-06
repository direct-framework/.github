# DIgital REsearch CompeTencies (DIRECT) Project

## Executive Summary

[DIRECT](https://directframework.com), the Digital Research Competencies Framework, is a community-led initiative that provides a shared language for the skills, competencies, and career pathways of digital research professionals. It is designed to support individuals, teams, institutions, and funders in recognising, developing, and sustaining the digital expertise that underpins modern research.
Digital research roles are increasingly central to research excellence, yet career pathways, training provision, and workforce planning remain fragmented. Existing skills frameworks often fail to reflect the realities of digital research work, particularly for research software engineers and the wider community of digital Research Technical Professionals (dRTPs).
DIRECT addresses this gap by offering an open, evolving competency framework, supported by role profiles, mapped training resources, and an open-source web tool.

[Use the skills and competencies framework in DIRECT Web tool](https://directframework.com).

[![Watch the video of project lead Dave Horsfall describing the DIRECT Framework, how it identifies skills and defines development pathways for anyone working in research software, serving as an important tool to help with career progression](https://github.com/direct-framework/digital-research-competencies-framework/blob/main/images/promo-video-screenshot.png?raw=true)](https://www.youtube.com/watch?v=NpQFhwqBgg4)

## Project Structure

The project is divided into two technical sub-projects with distinct set of activities:

- [DIRECT skills and competencies framework schema and data definitions](https://github.com/direct-framework/digital-research-competencies-framework)
- [DIRECT Web application](https://github.com/direct-framework/direct-webapp) - Django webapp to enable practical use of the framework (the [Web tool](https://directframework.com)), browsing the skills and competencies, self-assessment and creation of individual skill profiles as “competency wheels”, comparing profiles across a team, defining template skills for different dRTP roles, etc.
  
## The Problem Space

Digital research is now fundamental to almost all areas of research, from data-intensive science to computational humanities. Alongside this growth has been the emergence of specialist roles such as research software engineers, data managers, stewards and scientists, research and digital technologists, and other digital Research Technical Professionals.

Despite their importance, these roles often lack:

* Shared language for skills and competencies
* Alignment between training provision and role expectations
* Existence within university and research institutions’ job structures 
* Clear and consistent career pathways
* Recognition within institutional and funding structures

Existing skills and competency frameworks tend to be discipline-specific, academically focused, or designed for commercial engineering contexts. As a result, they often fail to capture the hybrid, collaborative, and evolving nature of digital research work. This creates challenges for individuals seeking progression, for managers supporting development, and for institutions planning strategically.

DIRECT exists to address this structural gap.

## How can DIRECT Help?

DIRECT is a competency framework designed specifically for digital research contexts.

At its core, DIRECT consists of:

* A structured set of digital research competencies, organised into thematic areas
* Scales that describe progression and depth of expertise
* Reference role profiles illustrating how competencies combine in practice
* Mappings to training and development resources
* An open-source web application that enables interaction with the framework
* Aman: community engagement? Bringing conversations together
* Sara: potentially repetitive, and this should be earlier?
* So perhaps drop this, and link to “usage” document
* Define strategy for how these documents will be available. 

DIRECT is intended to support reflection, planning, and development. It is not designed as a performance management or accreditation system, although it may inform those processes where appropriate.

The framework is deliberately flexible. It can be used at individual, team, institutional, or sector level, and is designed to evolve as digital research practices change.

### Position in the Digital Skills Ecosystem

DIRECT sits within a complex ecosystem of skills frameworks, professional standards, and training initiatives spanning academia, research infrastructure, and professional bodies.

Rather than replacing existing frameworks, DIRECT is designed to complement them by:

* Focusing specifically on digital research roles and practices
* Bridging individual development and institutional strategy
* Providing a community-owned, adaptable structure
* Enabling mapping and interoperability with other frameworks

DIRECT aligns with national and international priorities around digital skills, research sustainability, and workforce development. It provides a practical layer that connects high-level policy ambitions with day-to-day research practice.

## Code of Conduct

See our [Code of Conduct](../CODE_OF_CONDUCT.md).

## Vision

See our [vision statement](./VISION.md).

## Roadmap

See our [short and longer-term roadmaps](./ROADMAP/README.md).

## Use Cases and Beneficiaries

DIRECT supports a wide range of stakeholders.

### Individuals

* Reflect on current skills and experience
* Identify strengths and development areas
* Plan training and career progression

### Managers and Team Leads

* Support appraisals and development conversations
* Identify skills gaps within teams
* Plan recruitment and role development

### Institutions

* Develop consistent role profiles and career pathways
* Inform workforce and training strategies
* Support equality, diversity, and inclusion through transparent expectations

### Training Providers and Funders

* Align training provision with real-world needs
* Identify gaps in existing provision
* Support targeted investment in digital skills

## Governance

DIRECT is governed through open, community-led working groups with clear remits and transparent decision-making processes.
See our detailed governance process, including:

- [Governance model](./GOVERNANCE.md)
- [Current governance team](../GOVERNANCE.md#current-governance-membership)
- [Meeting schedule](../GOVERNANCE.md#meetings)

## Licence

Unless otherwise specified, all material and content in this and the related project repositories is licensed as follows:

- Code is licenced under the [3-clause BSD licence](https://opensource.org/license/bsd-3-clause/).
- Documentation, data and other written material is licensed under the [Creative Commons Attribution licence](https://creativecommons.org/licenses/by/4.0/) (CC-BY 4.0).

## Contributors

See [current and past project contributors](../CONTRIBUTORS.md).

## Contributing

DIRECT depends on the continued involvement of the digital research community.

We welcome contributions from individuals, institutions, training providers, and funders, whether through framework development, use case testing, training alignment, or governance support.

By working together, we can build a shared framework that recognises digital expertise, strengthens research communities, and supports the future of digital research.

Anyone is welcome to contribute suggestions, feedback, and/or PRs to address any open issues in the relevant repository. 
You can also open a new issue if your idea is not yet mentioned anywhere else.
All contributors agree to abide by our [Code of Conduct](../CODE_OF_CONDUCT.md).

TODO: Add link to CONTRIBUION GUIDELINES.

## History and Community Origins

Read a more detailed [history of the project](./HISTORY.md) and how it evolved.

## Documents

### Current working documents

* [Internal Google drive folder](https://drive.google.com/drive/u/0/folders/15pzFo9Vmf1C-PsBfiPyC3ZQBCGB92ssC) with various documents, presentations, etc.

### Documents no longer updated

- Collaborations Workshop 23 Hack Day
   * [CW23 Hack day report](https://docs.google.com/document/d/1ApTf8RcB86-RXrCJfCUMWDt6kRWSM0wVzBsPMCyhC8g)
   * [CW23 Hack day presentation](https://docs.google.com/presentation/d/15RBtaJ4W5bUWV7aHrwV0wX7op7hewl3B-w7vj6wieHg/edit#slide=id.g1e2424db41c_2_0)
   * [CW23 working HackMD document](https://hackmd.io/LwyTCm2LRwahi7yP8M7Brg?both)

## Contact

If you'd like to get in touch with the project team - email us at direct-framework@googlegroups.com.

We also use #direct-framework channel under the RSE Community Slack (ukrse.slack.com).

## Acknowledgements

The initial version of this project was created during the Software Sustainability Institute Collaborations Workshop
2023 (CW23) Hack Day. Subsequent development was guided by a number of unconference sessions and contributions by RSE and dRTP community members during RSECon23, RSECon24 and CW25 and various other community engagement events and workshops.

_This work is in part supported by the [DisCouRSE Network+](https://discourse-network.github.io/), which received funding through the UKRI
Digital Research Infrastructure Programme_.











