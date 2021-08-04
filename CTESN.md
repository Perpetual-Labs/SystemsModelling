
CTESN is a learnable differential-algebraic equation [[DAE]] structure that can be trained on highly stiff time series to build a representation of a component.
> The CTESN is a continuous-time generalization of echo state networks (ESNs) (Lukoševicˇius 2012), a reservoir computing framework for learning a nonlinear map by projecting the inputs onto high-dimensional spaces through predefined dynamics of a nonlinear system (Lukoševicˇius and Jaeger 2009).[[rack21a]]

> **CTESNs are effective at learning the dynamics of systems with widely separated time scales** because their design eliminates the requirement of training via local optimization algorithms. Instead of using optimization, CTESNs are semi-implicit neu- ral ODEs where the first layer is fixed, which results in an implicit training process. [[rack21a]]


[[JuliaSim]] implements it and showcase it in [[rack21a]]. 