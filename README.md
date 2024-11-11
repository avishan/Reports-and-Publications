
Report title "Runtime Monitoring in Adaptive systems"
This report discusses an approach to adapting a system in response to changing environments that create obstacles, which prevent the system from achieving its high-level goals. The process involves identifying and addressing these obstacles by implementing countermeasures that maintain the satisfaction rates of the system’s goals above target levels. Traditionally, estimates of these satisfaction rates are made during requirements engineering, but they can be inaccurate due to environmental changes or estimation challenges. To improve accuracy, this approach suggests monitoring the system at runtime to measure actual satisfaction rates.

The proposed obstacle-driven, run-time adaptation approach involves several steps:

    Goal and Obstacle Definition: An AND/OR goal refinement tree is created to clearly outline system goals and potential obstacles.
    Satisfaction Rate Characterization: Goals and obstacles are formally characterized by observed states and behaviors.
    Real-time Monitoring: The satisfaction rates of probabilistic obstacles are monitored at runtime, and these rates are propagated through the goal refinement tree.
    Dynamic Countermeasures: When a goal's satisfaction rate falls below the target level, alternative countermeasures are applied to restore goal satisfaction to acceptable levels.

This method enables the system to respond dynamically to obstacles in real time, maintaining its performance and adapting to new conditions efficiently.
