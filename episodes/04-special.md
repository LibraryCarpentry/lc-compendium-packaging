---
title: Special Cases
teaching: 0
exercises: 0
---

::::::::::::::::::::::::::::::::::::::: objectives

- Identify examples of restricted and proprietary materials that may be present in compendium packages
- Learn how to balance reproducibility goals with special cases of data restrictions/usage
- Create proper documentation for restricted and proprietary materials in compendium packages

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- What are some special cases to consider when publishing data and compendium packages?
- What are examples of restricted and proprietary materials in compendium packages?
- What are examples of complex computing research outputs that may be included in compendium packages?
- How can researchers balance reproducibility goals with proper handling of restricted and proprietary materials in compendium packages?

::::::::::::::::::::::::::::::::::::::::::::::::::

## Special Cases in Research Compendium Sharing

In Lesson 2: Episode 3, you learned about writing appropriate documentation for your research compendium (such as README files) to aid in its reuse, based on the characteristics of your data and code. When we are working with data that we have collected ourselves and the data has no ethical or legal restrictions that prevent us from sharing it, using the guidelines listed in this curriculum to create the final compendium package and its documentation can be relatively straightforward. However, many researchers may find themselves in a situation where their research materials pose additional considerations for the sharing process, which may influence how they arrange and prepare their research compendium for sharing. These situations may include:

1. Working with restricted data that has a high risk to harm an individual, group, geographical location, entity, etc. if released publicly.
2. Using data that is owned by a company/not created or owned by the researcher
3. Attempting to share complex research outputs such as software which may require additional documentation

In this episode, we will discuss restricted materials, proprietary materials, and complex computing outputs that may be included in compendium packages, and you will learn what additional considerations may need to be made when depositing these materials into a trustworthy repository.

## Restricted Materials

In the context of this curriculum, we can consider restricted materials to constitute data, software, and any other research ephemera that meets the definition of "restricted." The definition of "restricted" may vary across organizations and contexts. For example, the [Atomic Energy Act of 1954](https://www.directives.doe.gov/terms_definitions/restricted-data) defines restricted data as all information pertaining to the design, manufacture, or use of atomic weapons, the production of special nuclear material, the use of special <https://www.nia.nih.gov/research/dbsr/access-restricted-data>) define restricted data as "data that cannot be released directly to the public research community due to possible risk(s) to study participants as well as the confidentiality promised to them." Researchers should take special consideration in understanding what constitutes restricted data in their research context. What constitutes a restricted material may be influenced by:

1. Your organizational affiliation and where your organization is located
2. Who your collaborators (if any) are
3. Who is funding your research

## Proprietary Materials

Proprietary materials (such as data, software, etc.) are those which may be used in the research process to achieve a certain result, but are not owned by the researcher and thus generally cannot be shared openly in a compendium package. This may include data that is purchased or loaned from a company, software code developed by a private company, or other research tools in which the researcher has to specially request its use in their project.

## Complex Computing

Sharing a research compendium that contains complex computing materials such as software built by the researcher requires additional considerations for curating the package for reproducibility.

1. Does the repository where you are storing the research compendium have sufficient infrastructure for storing/providing access to your software?
2. Does your documentation adequately explain how reusers can install and use the software?
3. Does your documentation outline a clear plan about how reusers may be made aware of any updates made to the software?

:::::::::::::::::::::::::::::::::::::::::  callout

## Spotlight: Know Your (Repository's) Limits

Some repositories may not have the technical capability to host data and code where the access must be restricted and cannot be made publicly available with no access limitations. As you use the knowledge you learned from Lesson 4: Episode 3 to choose appropriate repositories, consider if a repository can host your restricted materials, proprietary materials, and complex computing products in a manner that balances reuse with protection of their special considerations.

::::::::::::::::::::::::::::::::::::::::::::::::::

Practice makes better. The more you exercise the better practices being exposed in the episodes, the more it will become engrained and natural to do. Here is another opportunity to put into practice what has been learned about READMEs, their functionality and importance.

::::::::::::::::::::::::::::::::::::::  discussion

## Discussion: Balancing Reproducibility with Proper Data Sharing Procedures

As you learned in Lesson 1 from the definitions of empirical, statistical, and computational reproducibility, the factors needed to achieve reproducibility varies depending on the research context. In each of the scenarios below, consider how the researcher might balance their goals in making their work reproducible while adhering to proper procedures around restricted materials.

**Scenario 1: Restricted Data with National Security Considerations**  
You work at a National Laboratory and are finishing up a research project which was dual-funded by the National Science Foundation (NSF) and a federal government agency. As a part of your NSF funding, you are required to share your research data from the project, but the federal agency which co-funded the project stipulates that the data has national security considerations and cannot be shared publicly. What do you do? Are there ways you can still share some of your research outputs to encourage reproducibility while satisfying the requirements of both organizations?

**Scenario 2: Data Purchased from a Company**  
You have just received a grant from a funding agency to study the television viewing habits of teenagers in your country, using a dataset you purchased from a media company that tracks television viewing patterns for various media networks. As of a year later, you have successfully completed your project and you are getting ready to put together your final research outputs and close out the grant project. You see that your data has to be shared in order to satisfy the grant's requirements, but you are not sure if you can share the data that you purchased from a company. What questions do you need to ask in this situation? What are some solutions to this problem, or possible compromises?

**Scenario 3: Sharing Lab-Built Software**  
You are a graduate researcher in the McMurray Lab, where you have been working on developing software that collects footage from eSports tournaments and prepares machine learning training data from the footage. The PI of the lab has asked you to develop the compendium package to share the software and associated documentation to satisfy mandates from the funder of the project. The software requires a very specific computing environment to function, and you are concerned about whether other people will be able to use the software properly after downloading it from the repository. What should you consider as you prepare the compendium package?

:::::::::::::::  solution

## Solution

While there are no discrete correct answers for each of these cases, there are a few possible considerations to explore for each of these scenarios.

**Scenario 1:** Is it possible to share a metadata-only description of your research data in a repository, and in the accompanying documentation include information on how the full dataset can be accessed from the federal agency? In this case, useful information about the data has still been shared with potential reusers, and they have been given guidance on the additional steps they need to take to access the full dataset since it cannot be fully publicly shared.

**Scenario 2:** In the same vein as Scenario 1, will the company allow you to share a metadata-only description of the purchased data in a repository, and in the accompanying documentation include information on how the full dataset can be purchased directly from the company? If this is not allowable, can the company offer any compromises on how their intellectual property can be protected while also allowing you to satisfy your data sharing requirements? Who might be possible representatives of the company who can help answer these questions? The company's legal department may be helpful in exploring this.

**Scenario 3:** Since the data requires extremely specific computing environments to function, make sure your README is incredibly detailed in describing what the reuser needs to do to create this computing environment, and be sure to list the contact information for who to contact from the research team in case the software malfunctions or becomes obsolete. While the goals of data curation are to reduce how often the original researchers need to be contacted by data reusers, in cases with complex computing, it may be unavoidable.

:::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::  challenge

## Exercise: Create a README for a Compendium Package with Special Cases of Data and Code

In Lesson 2: Episode 3, you learned about the specific elements needed in a README file. We will now ask you to apply this information towards creating a README file for a research compendium containing special cases of data and code. You will not be creating each section of the README, but rather discussing what major key areas need to be included in the document based on the below scenario.

Scenario: You and your lab have created software that can be used to analyze biological data from lobster populations to identify the geographic extent of overfished areas in the ocean. This software has the potential for wide-reaching impacts on policies around the commercial fishing industries and sustainability initiatives in coastal areas. Therefore, you and the other researchers want to share this software publicly to support its widespread reuse. However, you have concerns about sharing the software as it requires an extremely specific computing environment, and you are unsure if other researchers will be able to duplicate this computing environment without the specialized equipment used in your lab to run the software. At your weekly lab meeting, you and the team discuss what needs to be included in the README accompanying the software in order to support the reuse of the software.

The following questions are examples of what to consider when creating a README in this case of sharing complex computing products:

1. How will you clearly define the specific computing environment needed to run the software? Are there any specific
2. Will you include your contact information to allow researchers to get in touch if they have trouble running the software?
3. Do you plan to do regular updates of the software to make sure all dependencies and code continue to work? If so, how will you reflect this information in the README to ensure that researchers know how to access the latest version of the software?

:::::::::::::::  solution

## Solution

Discuss how you and the team will design the README for this complex computing product. What additional information will need to be included in the README given the complexity of the software? While there are no discrete correct answers for this challenge, your discussion may include the following:

1. How the complex computing environment (operating system and version number, other software dependencies needed, etc.) will be described in the README
2. Any sections you will add/omit to the README to support the effective reuse of the software
3. Any explanations/descriptions you will include in the README that gives explicit instructions on installing and using the software

:::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::::



:::::::::::::::::::::::::::::::::::::::: keypoints

- When putting together compendium packages, researchers should be aware of any restricted, proprietary, or complex computing materials they are working with.
- Restricted materials cannot be fully released to the public due to the high risk they can pose.
- Proprietary materials are those which are not owned by the researcher, and generally cannot be shared publicly.
- Complex computing materials such as software may require additional considerations when included in compendium packages, such as documentation outlining its development and use.
- When working with any of these special cases, researchers should allow for extra time in their process of compiling their compendium packages to ensure they are balancing reproducibility goals with proper precautions.

::::::::::::::::::::::::::::::::::::::::::::::::::


