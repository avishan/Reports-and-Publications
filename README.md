
Report title "Runtime Monitoring in Adaptive systems"
Abstract. By changing an environment, some adverse conditions may happen, which does not allow
the system to satisfy its high-level goals anymore. These adverse conditions, called obstacles, can be
resolved through countermeasures. Therefore, the system analyst performs obstacle analysis cycles to
identify obstacles, assess their likelihood and criticality, and finally propose proper countermeasures to
solve them. In this way, the system can be adapted to the new environment, and satisfaction rates of
its high-level goals stay higher than target levels. At requirements engineering time, experts estimate
the satisfaction rates of probabilistic obstacles and goals. However, these estimations can be inaccurate
since environment properties or assumptions might have changed, or some variables might be hard
costly to estimate at this time. Thus,monitoring the actual satisfaction rate of obstacles at system runtime helps obtain more information and better estimations. Based on this idea. This paper proposes
an obstacle-driven run-time adaptation approach that defers obstacle resolution to system run-time.
In the proposed approach, first, an AND/OR goal refinement tree is built to define systems’ goals
and obstacles. Then, a formal characterization of satisfaction rates of goals and obstacles is provided
in terms of observed states and behaviors. Next, by monitoring probabilistic obstacles at run-times,
the satisfaction rates of goals are obtained by uppropagation through obstacle/goal refinement tree.
Whenever a goal’s satisfaction rate decreases below its target level, more appropriate countermeasures
are chosen instead of current ones to increase the satisfaction rate of the system’s goals above the
required degree
