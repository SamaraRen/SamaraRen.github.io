---
title: A Visibility-Based Approach to Computing Non-Deterministic Bouncing Strategies
authors:
- Alexandra Q Nilles
- Yingying Ren
- Israel Becerra
- Steven M LaValle
date: '2021-09-01'
publishDate: '2023-11-04T23:41:25.566748Z'
publication_types:
- article-journal
publication: '*The International Journal of Robotics Research*'
doi: 10.1177/0278364921992788
abstract: Inspired by motion patterns of some commercially available mobile robots,
  we investigate the power of robots that move forward in straight lines until colliding
  with an environment boundary, at which point they can rotate in place and move forward
  again; we visualize this as the robot ‘‘bouncing’’ off boundaries. We define bounce
  rules governing how the robot should reorient after reaching a boundary, such as
  reorienting relative to its heading prior to collision, or relative to the normal
  of the boundary. We then generate plans as sequences of rules, using the bounce
  visibility graph generated from a polygonal environment definition, while assuming
  we have unavoidable non-determinism in our actuation. Our planner can be queried
  to determine the feasibility of tasks such as reaching goal sets and patrolling
  (repeatedly visiting a sequence of goals). If the task is found feasible, the planner
  provides a sequence of non-deterministic interaction rules, which also provide information
  on how precisely the robot must execute the plan to succeed. We also show how to
  compute stable cyclic trajectories and use these to limit uncertainty in the robot’s
  position.
links:
- name: URL
  url: http://journals.sagepub.com/doi/10.1177/0278364921992788
---
