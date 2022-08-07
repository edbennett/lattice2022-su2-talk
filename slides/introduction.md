# Introduction

-

## Why SU(2) + 1 adjoint Dirac?

* Conformal window
* BSM strong dynamics
* Topological phase transitions

-

## Conformal window?

![Illustration of four possible forms for the beta function: one which heads straight down from zero; one which heads down, bends back up near to zero, but then bends back down again; one which heads down from zero, then turns around and crosses zero heading upward; and one which heads straight up from zero.](images/betafunctions.svg)

-

## What do we know?

* 1412.5994: Single value $\beta=2.05$
  * Scalar lightest state
  * Roughly constant mass ratios
  * Anomalous dimension $\gamma_*\approx 0.95$
* 1507.08892: Adds $\beta=2.2$
  * Constant mass ratios persist
* 1912.11723 (Bi et al.): $\beta=2.05, 2.2$
  * Consistent masses
  * Composite fermion $\approx$ hybrid fermion state
* 2103.10485: $\beta=2.05, 2.1, 2.15, 2.2$
  * $\gamma_*$ decreases with increasing $\beta$
  * Results poorly described by chiral perturbation theory
* Overall: hints of near-conformality

-

## Chiral symmetry

* 1 Dirac $\equiv$ 2 Majorana fermions
* Action symmetric on transforming Majorana flavours
* Majorana basis described by different quantum numbers
  * E.g. Connected Dirac bilinear $\overline{\psi}\gamma_5 \psi\equiv$ Majorana scalar baryon

-

## What don't we know?

* Chiral limit
* Continuum limit
  * Hadron masses
  * Mass anomalous dimension

-

## Simulation approach

* Unimproved Wilson gauge action
* Unimproved Wilson fermion action
  * Implemented with [HiRep](https://github.com/claudiopica/HiRep) and [Grid](https://github.com/paboyle/Grid)
* $\beta=2.05, 2.1, 2.15, 2.2, 2.25, 2.3, 2.4$
* $am_{2^+_{\mathsf{s}}} \in (0.28, 1.11)$
