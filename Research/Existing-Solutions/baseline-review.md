# Existing Solutions / Baseline

The VISTRA blueprint defines the benchmark baseline as:
YOLOv8 detection + the same VO/SLAM + A* on a binary occupancy grid + a fixed-distance stop rule.

VISTRA design additions:
- uncertainty-propagating traversability
- D* Lite global replanning
- DWA local scoring
- TTC predictive safety
- NCS confidence governor
- Recovery Manager
- fault injection
- side-by-side comparison

This describes the planned comparison. It does not state which system will perform better until experiments are complete.
