# flowshop-with-RL

## Objectves
1. Using reinforcement learning to generate a schedule plan for a flowshop with multiple machines and jobs
2. Developing a policy to control the charging and discharging of a battery that is part of a microgrid that provides electricity to the flowshop

## Background
- Flowshop scheduling
  - Given makespan and amount of jobs and machines, need a scheduling before production 
  - We have 1 machine and 5 job
  - Need to overcome: how is the reinforcement learning approach being used and how it will be applied to generate the schedule plan

- Microgrid Management
  - sources of electricity: solar panels / wind turbines / utility grid / battery
  - battery can control the charging and discharging
  - the policy here is based on the electerity use of our production system to  control the charging and discharging of the battery
