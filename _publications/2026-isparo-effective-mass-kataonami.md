---
title: "Effective-Mass-Aware Posture Optimization for Low-Impact Contact in Space Robotic Manipulators Using MPC"
collection: publications
category: conferences
permalink: /publication/2026-isparo-effective-mass-kataonami
excerpt: 'Online posture optimization using effective-mass-aware MPC for low-impact spacecraft contact, achieving a 55.4% reduction in effective mass and a 52.9% reduction in maximum contact force in MuJoCo simulations.'
date: 2026-01-01
venue: '2026 International Conference on Space Robotics (iSpaRo)'
paperurl: ''
citation: 'Teruhiro Kataonami, Akiyoshi Uchida, Keisuke Takehana, Kenta Iizuka, and Toshinori Kuwahara. (2026). &quot;Effective-Mass-Aware Posture Optimization for Low-Impact Contact in Space Robotic Manipulators Using MPC.&quot; <i>2026 International Conference on Space Robotics (iSpaRo)</i>.'
---

In on-orbit servicing of uncooperative targets, reducing the contact force during contact is important. The contact force depends on the effective mass, which represents the apparent inertia of the robot along the contact direction and varies with the manipulator configuration. Previous studies on effective-mass-based configuration optimization have mainly focused on offline static approaches; however, free-flying space robots require online optimization that accounts for the coupled motion of the base and manipulator.

In this study, the effective mass along the contact direction is incorporated into the MPC objective function, and an online posture optimization method is proposed to reduce the effective mass during the approach while maintaining end-effector trajectory tracking. Simulation results show that the effective mass decreased from 12.96 kg to 5.77 kg, corresponding to a reduction of approximately 55.4%. The model-based maximum contact force was reduced by approximately 37.4%, while the maximum contact force obtained in the MuJoCo simulation was reduced by approximately 52.9%. Furthermore, the effective mass achieved by the proposed MPC was close to the mean value of 5.61 kg obtained by offline static optimization using PSO. These results demonstrate that the proposed method enables online effective-mass-based posture optimization within the MPC framework while simultaneously performing end-effector trajectory tracking and accounting for control constraints. It also achieves effective-mass reduction close to that obtained by offline static optimization.
