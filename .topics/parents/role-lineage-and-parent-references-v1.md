# Role Lineage & Parent References

This topic exists to explore continuity-aware role evolution.

The goal is not creating strict inheritance systems.

The goal is enabling:

* inspectable role ancestry
* recoverable role development
* calibration traceability
* behavioral lineage awareness
* continuity-aware role experimentation

## Current Direction

`.agent.md` files may eventually support lightweight machine-readable metadata for:

* parent references
* role ancestry
* compatibility hints
* calibration lineage
* runtime compatibility

The current preferred direction is:

* keep role descriptions human-readable
* avoid metadata clutter inside role bodies
* use frontmatter only for machine-oriented continuity metadata
* avoid hidden behavioral inheritance

## Important Distinction

Parent references are intended as:

* provenance references
* calibration ancestry
* continuity hints

They are NOT intended as:

* invisible prompt injection
* hidden inheritance execution
* opaque runtime composition

## Operational Goal

A future runtime should be able to:

* inspect where a role evolved from
* compare related role variants
* analyze role drift
* reconstruct calibration lineage

while humans should still be able to:

* comfortably read role files
* inspect behavioral intent
* understand role evolution manually

## Status

Experimental.

This structure is still evolving through operational usage and calibration.
