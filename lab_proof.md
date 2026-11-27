# Lab Proof: Green Software Practitioner

## Course completion

I took the course through the [Movement course overview](https://movement.greensoftware.foundation/spaces/19525645/page), where the Green Software Foundation now lists it. The older lab brief calls it LFC131, which the Linux Foundation launched with the Green Software Foundation. [LFC131 launch announcement](https://training.linuxfoundation.org/blog/new-course-brings-environmental-consciousness-to-software-development/) · [GSF education page](https://greensoftware.foundation/education/)

| Item | Result |
| --- | --- |
| Workflow | On Movement, I worked through the six sections and their quizzes, then took the **Final Quiz** under **Course Completion**. |
| Input | The English-language **Green Software Practitioner** course on Movement and my responses to its final quiz. |
| Evidence | [Certificate of completion (PDF)](1201b3f0-51d2-4f93-bcf4-6a5aabce83e4.pdf), [course access and completion record](course_access_evidence.md), and [Green Software Foundation award page](https://badges.greensoftware.foundation/awards/1201b3f0-51d2-4f93-bcf4-6a5aabce83e4). |
| Final output | I passed the final quiz. The Green Software Foundation issued my **Green Software Practitioner** credential on 25 November 2026. |
| Limitation | The public preview showed the lesson without recording my progress. The certificate records completion, and the exact quiz score is unavailable from it. |

## How the course complements the bootcamp

The bootcamp covers carbon, energy, hardware, and measurement. The course starts with carbon efficiency as the goal. I can work toward it by using less energy, running work when or where electricity is cleaner, and cutting the share of embodied hardware emissions per unit of work. The Measurement and Climate Commitments sections explain how to measure those changes and relate them to an organization’s targets. [GSF education page](https://greensoftware.foundation/education/)

| Bootcamp pillar | Application to the Northstar Home support assistant |
| --- | --- |
| Carbon | Compare emissions per correctly resolved support request. For batch index refreshes that can wait, test scheduling at times with lower grid carbon intensity while meeting the freshness deadline. |
| Energy | Reuse approved FAQ answers and route suitable requests to deterministic lookup. Check whether the same request mix can be resolved with less electricity while maintaining answer quality. |
| Hardware | Evaluate whether consolidation or reuse of existing capacity can reduce the embodied emissions allocated to the workload while meeting latency and capacity requirements. |
| Measurement | Use the same request mix, resolution criteria, and system boundary for the baseline and proposed workflow. Include energy spent on failed requests and retries in both cases. |

I’d use one correctly resolved support request as my functional unit and report grams of CO₂e per request. I’d include the emissions from electricity used for routing, caching, retrieval, inference, index refreshes, and the infrastructure that supports them. I’d also include the workload’s share of embodied hardware emissions.

The Northstar Home model estimates call counts from planning assumptions. To estimate SCI, I’d still need electricity use, grid carbon intensity for the time and place the work runs, and the share of embodied hardware emissions to assign to it. Carbon offsets do not lower SCI. [SCI specification](https://sci.greensoftware.foundation/)

## Credential scope

My credential confirms that I completed the green software fundamentals course and met the Green Software Foundation’s **85% passing threshold** on the final quiz. To show that a production system emits less, I’d need a comparable baseline, a record of what I included, and a method to measure or estimate emissions. [Credential criteria](https://badges.greensoftware.foundation/credentials/green-software-practitioner)

## Required Green Tech Assessment

For the required assessment, I chose **Path A: Northstar Home support assistant** and assessed the fictional system as a proposed design. The slide deck and analysis are in the [assessment repository](https://github.com/s-rostovskyi/lab-green-tech-assessment).
