---
title: "Signals Requiring a Dedicated SDET Team"
date: 2024-08-10T22:31:16+01:00
draft: false
categories: ["engineering"]
---

It's could be a great timing to establish a dedicated SDET team if the following stories keep occurring in your daily development. 


1. Can Hardly Take Care of Boundaries between Components

As the team grows, having different product lines and tribes is a fairly reasonable. However, issues can easily arise at the intersections of different functions due to information gaps.

<!--more-->

Encouraging developers to proactively put eyes on updates from other components is ineffective. This contradicts the rationale behind splitting teams and increase superficial sync-up meetings, which reduces overall capacity.

At this stage, it's essential to have a dedicated team that takes all components as a whole and ensures consistency across all external functionalities through concrete approach (i.e. regression tests).

2. Lost Track of Known Issues

Clarifying unexpected behaviors erodes engineers' time.

Incidents probably occurs only once or twice a week right after release at the early stage, but eventually escalates to the point where, after several iterations, complex business always require an engineer to be responsible for handling incoming issues.

Apparently, investigating repeated issues from scratch is a significant waste of time. While messages on Slack could be helpful in many cases, much of the discussion still takes place in in-person meetings or private messages.

Encouraging developers to oversee issue tracking can easily lead to frustration, as they are accustomed to fix issues and release ASAP. Managing a large number of unresolved issues falls entirely outside their expertise.

3. Test Implementation Effort Grows Significantly

Treating development and testing as 2 unrelated works could be the root cause, resulting in a lack of prior consideration for whether the design can be tested with reasonable effort.

Mindsets such as 'releasing the feature first and adding tests later' are essentially procrastination in scheduling. The typical outcome is 'next feature' takes priority, while 'testing the previous feature' remains indefinitely backlogged.

After several iterations, features often reach a point where no one fully understands their behavior. When issues arise, investigation becomes a nightmare, and test cases always play crucial roles as source of insight.

---

'How do you plan to test this?'

A solid software engineering team always think about this invaluable question early in the design phase.
