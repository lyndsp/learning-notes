# Unformed ideas

## Workshop with team on how to build and migrate AKS workloads

Involve whole team. Should we also involve someone from MCR? And Cloud Ops? And an EM / HoE?

- What assumptions are we making?
- What is not being said?

## Use an LLM + repos to quickly summarise what a workload does

Each time we come to a workload to migrate, we should have a standard prompt that helps us understand enough about a workload so we know how to migrate it.

## Track the DevX metrics for teams we're working with

When engaging with a team, we should get sight of their DevX metrics and track them to determine if there is a meaningful change that might relate to our engagement.

## Build and maintain personas as we meet new teams

Create a set of standard questions to ask a team to inform:

- Jobs to be done
- Personas
- User needs

See [how JLDP built personas for their platform](https://medium.com/john-lewis-software-engineering/building-for-our-users-data-driven-personas-to-shape-our-platform-f8670726b666)

## Team learning session

How is the team using LLMs? What's working, what's not? What questions or problems would people like to share?
Give the team data on how things are going, e.g. tickets, interactions, feedback, commits, PRs.
Give the team opportunity to reflect and feedback ahead of a retro.
What mistakes have we made over the past few weeks? What can we / have we learnt from these?

### From Ceri Newton-Sargunar (on being status informed)

What am I worried about, what risks am I seeing? - Then have them group these by:

- Things they can change
- Things they can change with help (who, when, how could help?)
- Things they can't change

Consider sharing this outside of the team, e.g. with SLT.

Wall of awesome:

- Things we should keep doing
- Kudos

## Meeting our users

(AoTB - Rachel Dubois)

Schedule a meeting with an AKS based domain team every week.
Explore, in the context of their domain and value production:

- What are the jobs to be done with their workload and AKS? - Turn this into a metric, e.g. X% of target group achieves valuable action X using our platform in period Y.
- What pains do they feel in working with AKS?
- What works well for them in using AKS?
- What would motivate them to switch to our product? - Establish a Product Market Fit where domain teams push to use our platform instead of being pulled.

## Requirements for running a workload on AKS abstract compute

- Start this document and regularly get feedback from teams / LLM review on workloads
- Establish a team's effort to make their workload ready for our platform.

## Define the AKS abstract compute product

Write our product strategy, vision and principles - Marty Cagan - Empowered

Go through the 5 steps from Rachel Dubois -> problem, hypothesis, segmentation, experiment, adjust.
Work our how much our team costs and determine RoI.

Use Rachel Duboi's slides from day 2:

- Assumption autopsy
- The silence audit
- The momentum trap

## AKS Abstract Service Design - From Kal's slides

- What is the ecosystem?
- What are all interactions? Human touch points, non-human touch points?
- What is the end to journey? Onboarding, adjustment, daily interaction, offboarding.

## ACR lessons

Retrospectively apply the above to platform managed ACRs.
Read [Community Driven Software Adoption](https://sre.google/resources/practices-and-processes/community-driven-software-adoption/)
