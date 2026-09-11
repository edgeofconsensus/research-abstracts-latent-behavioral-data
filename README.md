# Toward a New Representation for High-Frequency Sensorimotor Decision Streams

This project explores whether a new data type can be defined to better represent continuous streams of latent behavioral dynamics.

The current README is intentionally conceptual and serves as a starting point for discussion. Criticism, alternative interpretations, mathematical formalizations, related work, implementation ideas, and experimental validation are welcome.

This proposal does not introduce a new machine learning model. Instead, it explores the possibility that a fundamentally different class of behavioral data exists but has not yet been formally represented.

The central hypothesis is that during rapid sequences of sensorimotor micro-decisions — for example, continuous high-speed audio manipulation involving tempo, pitch, time-stretching, synchronization, and related operations — a high-frequency information stream is generated whose structure may not be adequately captured by existing data representations.

Extreme audio editing is considered not as a unique source of such data, but as one of the most accessible environments for observing dense sequences of sensorimotor decisions. The proposed architecture is domain-independent and may generalize to any activity that produces a comparable class of high-frequency behavioral streams. Audio is used primarily as a practical experimental environment for identifying, calibrating, and studying this potential data type.

The underlying challenge may therefore lie not in the dimensionality of the feature space, but in the absence of an appropriate representation of the behavioral stream itself. The objective is to investigate mathematical representations that capture latent functional states through the structure of sequential decision-making rather than through isolated parameter values.

If such a representation exists, sufficiently large longitudinal datasets could be used to test whether trajectories within the resulting latent state space have stable descriptive or predictive value.

Within this conceptual framework, the nervous system can be modeled abstractly as an evolving latent state influenced by multiple internal and external factors. One possible component is an abstract latent variable, τ, representing remaining progression along an unchanged trajectory. This variable is introduced solely as a modeling construct and is not intended to represent a known biological mechanism or directly measurable physiological quantity.

The primary objective is therefore not to build a predictive system, but to determine whether the proposed class of behavioral data exists, can be formally represented, and provides a useful framework for studying latent functional states.

## Open-stream hypothesis

A potentially important distinction is between a completed recording and an open stream whose present boundary continuously advances.

The proposed object may require a known starting point together with a continuously updated present, without a predefined terminal boundary. Under this view, a completed segment with both a fixed start and a fixed end is not assumed to be equivalent to the live process that generated it. It may preserve an observable trace of that process while losing information that depends on the continuous maintenance of context during generation.

This is not simply ordinary streaming of a known file format. The hypothesis is that the representation itself may be updated as new micro-decisions arrive, so that the informational object is partly defined by the ongoing evolution of its own internal context.

This suggests a distinction among three levels:

- the observable event stream;
- the continuously evolving internal representation of that stream;
- the completed record or projection that remains after the open process ends.

A key question is therefore whether the relevant structure can be reconstructed fully from a finished record, or whether some properties exist only while the stream remains open and causally extended toward the present.

## Evolution without state-difference primacy

A further hypothesis is that the process should not necessarily be described primarily through repeated comparisons between discrete states.

Instead of defining evolution only as the difference between successive snapshots, the evolution may be encoded in the way the process continuously extends its own trajectory. In that case, each new event is informative not merely because it changes a state, but because it constitutes a continuation that is constrained by the accumulated history of prior events.

This motivates investigating representations in which the continuity and self-consistency of trajectory extension are first-class objects, rather than secondary quantities derived from state-to-state comparison.

The phrase "self-confirming evolution" is currently only an intuition: it refers to the possibility that evidence of evolution is carried by the ongoing structure of the process itself, not by an external retrospective comparison of independently defined states. This idea requires formalization and may ultimately reduce to known dynamical-system concepts; that possibility should be treated as a baseline rather than excluded in advance.

## Research boundary

At the current stage, the proposal does not claim that a new data type has been demonstrated, that the proposed latent variables correspond to biological mechanisms, or that the representation has validated predictive value.

It also does not yet claim that open-endedness is necessary, that a completed record cannot fully reconstruct the process, or that evolution can be represented without state comparison. These are newly identified hypotheses to be tested against conventional sequential, state-space, dynamical-system, and streaming representations.

A useful next stage must define measurable observables, competing conventional representations, negative controls, and falsification criteria. The hypothesis becomes interesting only if the proposed stream representation captures reproducible structure that simpler representations fail to explain.

## Status

Concept-stage research note. Open for mathematical formalization, related-work comparison, implementation design, controlled data collection, and experimental falsification.

## Discussion

Relevant directions include:

- data representations;
- stream structures;
- mathematical formalisms;
- baseline comparisons;
- falsification criteria;
- related research directions.
