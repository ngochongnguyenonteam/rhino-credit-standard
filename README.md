# Rhino Credit Standard and Specification (RCSS)

**Current version:** 1.1  
**Author:** Ngoc Hong Nguyen, Ph.D.  
**Date:** September 2026

The Rhino Credit Standard (RCS) is an open specification for representing relative contribution in team-based work under a fixed-sum constraint.

## Core principle

**The relative contributions of all members of a team must sum to exactly 100%.**

If one member receives a larger share of contribution, less remains for the others. RCSS treats relative contribution as a conserved quantity rather than as a set of independent ratings.

Fixed-total allocation itself is not new. RCSS formalizes the broader principle that the 100% invariant should be preserved throughout the measurement process.

## Current specification

- [RCSS Version 1.1](RCSS_v1.1.pdf)

RCSS v1.1 defines the baseline conservation and normalization requirements and includes optional experimental reference profiles for handling uncertain or noisy contribution evidence.

The specification is implementation-independent. It does not prescribe grading, compensation, promotion, or other downstream decisions.

## Reference implementation

[OnTeam](https://onteam.app) is a working implementation of the conservation principle for team-project assessment.

## Previous versions

Earlier versions are retained in this repository for version history.

## Feedback

Feedback and issues are welcome through GitHub Issues.

## Citation

RCSS v1.1 is currently maintained as a working open specification. A persistent citation for this version will be added when the v1.1 archival release is published.
