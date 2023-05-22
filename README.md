# flux-generic-helm

NOTE: Experimental repository

## Intent

Experiment with GitOps lifeycle management around deploying resources with flux given a common `flux-generic` chart.

## Vision

Establish a lifecycle around composable platform applications and their dependencies in a manner that does not "lock" users into certain assumptions.

## Thoughts
- Start with the basics and prove-out the idea
    - Should this only map to a single gitrepo/helmrelease (or similar)?
    - OR should this allow for orchestrating a generic umbrella?
- helm release
    - Establish a method of overriding values
    - Establish a method of appending values w/ precedence 