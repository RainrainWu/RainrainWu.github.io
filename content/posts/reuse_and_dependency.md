---
title: "Hidden Risk of Depedencies"
date: 2023-05-07T16:19:25+08:00
draft: true
categories: ["engineering"]
tags: []
---

Rapidly building new functionalities by utilizing existing components has become a common practice in software engineering, especially for practitioners of microservices architecture.

However, the interdependence between components is often underestimated, leading to higher-than-expected maintenance costs in the future.

<!--more-->

---

In fast-paced product teams, it's common to run into communication issues due to frequent updates to requirements, such as implementing a function not originally included or addressing specific edge cases.

One of the issues worth discussing is that different teams may prioritize the same problem differently. Progress can be easily blocked when the problem is not considered critical by all teams that own dependent components.

Ambiguous "short-term workarounds" are constantly introduced to address urgent needs, with the expectation that other teams will allocate resources to fulfill the demand ASAP.

But in reality, things often go awry. As time passes, the requirements keep piling up in the backlog, while the scope of the makeshift solutions continues to expand, blurring the division of responsibilities between components.

These counterintuitive tricks also invisibly increase the cost of team operations, including version updates, debugging, refactoring, handover, and other related tasks.

---

Prioritization can help reduce the side effects of interdependence. Blockers across components must be identified and addressed from a holistic view to ensure that the entire system functions as intended thoroughly.

Incorporating future changes into the design considerations of the solution is also a necessary step. Whenever a "short-term workaround" is unavoidable, it's essential to have a deprecation plan in place, which can limit the scope of its impact.
