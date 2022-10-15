# Dynamical System

A Dyn System is characterised by its state space S, and rules R which decide how a body can move in this state space.

At any given time T, the state space varies from s\_1 s\_2 \in S, satisfying the rules R of system.

## State Space
A collection of co-ordinates which describe the model well. can be anything which is suitable.

## Time
Poincare showed differential equations can be characterised by discrete time steps, i.e. recording the solution of DE at discrete times. (Poincare Section). This is important since one can only take finite no. of measurements at a time, computations is also limited to finite steps.

## Evolution Rule
Given a state s\_1 \in S, one can predict the next state according to an evolution rule.
Of two types, deterministic if new state is unique, (i.e. the Evolution rule is one-one), Stochastic if new state is random (i.e. one-many).

#Examples

f(x) = r*x*(1 - (x/K)) # Population Dynamics, discrete system, x\_n+1 = f(x\_n)

Cellular Automata, deterministic, discrete time and discrete phase space, dynamical system. 

http://www.scholarpedia.org/article/Dynamical_system
