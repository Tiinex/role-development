# Migration: Role Development Separation

## Summary

Role development work is being separated from the main `ai` repository into the dedicated:

`role-development`

repository.

## Reasoning

The `ai` repository is increasingly functioning as:

* a stable role container
* an operational runtime surface
* a maintained agent collection

while active role experimentation represents a different problem space.

Mixing:

* stable agents
* experimental calibration
* role evolution
* behavioral drift analysis
* exploratory lineage work

inside the same repository risks:

* semantic overload
* operational ambiguity
* continuity confusion

## New Separation

### `ai`

Intended for:

* maintained role artifacts
* operational agents
* deployable role surfaces
* stable continuity-facing role definitions

### `role-development`

Intended for:

* role experimentation
* calibration work
* lineage exploration
* role ancestry analysis
* compatibility testing
* migration experiments
* continuity-aware role evolution

## Operational Goal

This separation allows:

* stable runtime usage
* experimental development
* bounded role evolution
* inspectable calibration workflows

without destabilizing operational role surfaces.

## Additional Notes

This migration does NOT imply:

* finalized architecture
* canonical role hierarchy
* frozen runtime behavior

The structure remains experimental and subject to future calibration.

## Status

Experimental migration structure.
