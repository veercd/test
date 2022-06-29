# AELF DAO Grants Program

- [:wave: Introduction](#wave-introduction)
- [:level_slider: Levels](#level_slider-levels)
- [:pencil: Process](#pencil-process)
  - [1. Application](#1-application)
  - [2. Application Review](#2-application-review)
  - [3. Milestone Delivery and Payment](#3-milestone-delivery-and-payment)
  - [Changes to a Grant after Approval](#changes-to-a-grant-after-approval)

## :wave: Introduction

For more information about the AELF DAO Grant, please visit the [website](https://web3.foundation/about/) .

## :level_slider: Levels

The W3F Grants Program offers different grant levels to help you best depending on your current stage.

### :egg: Level Extra <!-- omit in toc -->

- **Target:** -
- **Amount:** 
- **Requirements:** 2 approvals
- **Benefits:** Feedback during application process and evaluation, introduction to related teams/projects

### :hatching_chick: Level B <!-- omit in toc -->

- **Target:** -
- **Amount:** Up to $8,000-10,000
- **Requirements:** 2 approvals
- **Benefits:** Feedback during application process and evaluation, introduction to related teams/projects

### :hatched_chick: Level A <!-- omit in toc -->

- **Target:** -
- **Amount:** Up to $20,000
- **Requirements:** 2 approvals
- **Benefits:** Feedback during application process and evaluation, introduction to related teams/projects

### :baby_chick: Level A+<!-- omit in toc -->

- **Target:** -
- **Amount:** Up to $30,000
- **Requirements:** 3 approvals
- **Benefits:** All of the above + [co-promotion](./docs/announcement-guidelines.md#announcement-guidelines), [Grants Program badge](./docs/grant-badge-guidelines.md), fast track to [Substrate Builders Program](https://www.substrate.io/builders-program/)

### :rooster: Level S<!-- omit in toc -->

- **Target:** -
- **Amount:** Up to $50,000
- **Requirements:** Pitch call + 5 approvals (for >$100k: Web3 Foundation Council approval)
- **Benefits:** All of the above + VC introductions

### :chicken: Level SSS<!-- omit in toc -->

- **Target:** -
- **Amount:** Up to $500,000
- **Requirements:** Pitch call + 5 approvals (for >$100k: Web3 Foundation Council approval)
- **Benefits:** All of the above + VC introductions

## :pencil: Process

> **:loudspeaker:** The process below is independent of the [level](#level_slider-levels). 

### 1. Application

   1. [Fork](https://github.com/w3f/Grants-Program/fork) this repository.
   2. In the newly created fork, create a copy of the application template ([`applications/application-template.md`](applications/application-template.md)). If you're using the GitHub web interface, you will need to create a new file and copy the [contents](https://raw.githubusercontent.com/w3f/Grants-Program/master/applications/application-template.md) of the template inside the new one. Make sure you **do not modify the template file directly**. In the case of a maintenance application, use the maintenance template ([`maintenance template`](maintenance/maintenance-template.md)) instead.
   3. Name the new file after your project: `project_name.md`.
   4. Fill out the template with the details of your project. The more information you provide, the faster the review. Please refer to our [Interested Grant List](docs/interestlist.md) and make sure your deliverables present a similar same level of detail. To get an idea of what a strong application looks like . Naturally, if you're only applying for a smaller grant that only consists of, say, UI work, you don't need to provide as much detail.
   5. Once you're done, create a pull request. The pull request should only contain _one new file_—the Markdown file you created from the template.
   6. You will see a comment template that contains a checklist. You can leave it as is and tick the checkboxes once the pull request has been created. Please read through these items and check all of them.
   7. Sign off on the [terms and conditions](docs/T&Cs.md) presented by the [CLA assistant](https://github.com/claassistantio) bot as a Contributor License Agreement. You might need to reload the pull request to see its comment.

### 2. Application Review

   1. The AELF DAO can (and usually does) issue comments and request changes on the pull request.
   2. Clarifications and amendments made in the comments _need to be included in the application_. You may address feedback by directly modifying your application and leaving a comment once you're done. Generally, if you don't reply within 2 weeks, the application will be closed due to inactivity, but you're always free to reopen it as long as it hasn't been rejected.
   3. When all requested changes are addressed and the terms and conditions have been signed, someone will mark your application as `ready for review` and share it internally with the rest of the committee.
   4. The application will be accepted and merged as soon as it receives the required number of approvals (see [levels](#level_slider-levels)), or closed after two weeks of inactivity. Unless specified otherwise, the day on which it is accepted will be considered the starting date of the project, and will be used to estimate delivery dates.

### 3. Milestone Delivery and Payment

   1. Milestones are to be delivered on the [Grant Milestone Delivery](https://github.com/w3f/Grant-Milestone-Delivery/) repository following the [process](https://github.com/w3f/Grant-Milestone-Delivery#mailbox-milestone-delivery-process) described therein.

### Changes to a Grant after Approval

- Accepted grant applications can be amended at any time. However, this _necessitates a reevaluation by the committee_ and the same number of approvals as an application (according to the [levels](#level_slider-levels)). If your application has been accepted and, during development, you find that your project significantly deviates from the original specification, please open a new pull request that modifies the existing application. This also applies in case of significant delays.
- If your _delivery schedule_ significantly changes, please also open a pull request with an updated timeline.
- If your deliveries are significantly delayed and we cannot get a hold of you, we will terminate the grant (3 approvals required, regardless of level. If a member of the committee creates the termination PR, only 2 more approvals are required).
