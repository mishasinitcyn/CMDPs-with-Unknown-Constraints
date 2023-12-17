# Constrained Markov Decision Processes with Unknown Constraints are Feasible
by 
- Jesse Schneider
- Hanyang Hu
- Mikhail Sinitcyn

## Abstract:
Constrained Markov decision processes are a standard reinforcement learning
framework used when it is desirable to constrain the agent’s behavior, typically in
order to control costs accrued by the agent. It is almost always assumed that the
constraints placed upon the agent are known, yet situations do arise wherein the
constraints are unknown. In this work, we consider constrained Markov decision
processes with unknown constraints, and attempt to find a policy that respects
the unknown constraints. Assuming only very limited feedback when constraints
are violated, we show that such a policy can indeed be found via exploitation of
constrained Markov decision processes’ linear-programmatic structure. Furthermore, this can be done in polynomial time. We believe this result to be novel, and
we discuss the methods applied to achieve this result in detail. We also present a
simple example. Having done this, we consider the problem of finding a policy that
not only respects the unknown constraints, but a good, or possibly even optimal,
policy. With a different set of assumptions that provide more information, but still
with mostly unknown constraints, we present a procedure that can find not only
policies respecting the unknown constraints, but optimal policies. Furthermore,
the procedure’s asymptotic characteristics imply that it is more likely to find an
optimal policy over time. This procedure can also be performed in polynomial
time, and we believe this result to be novel as well.
