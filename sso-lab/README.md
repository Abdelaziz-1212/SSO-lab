# SSO Monitoring Lab

Companion page for the talk "Optimal PMU Placement for Detecting, Classifying and Locating Sub-Synchronous Oscillations" (A. Abuelrub, Hamad Bin Khalifa University), IECON 2026 tutorial on sub-synchronous oscillations, Doha, 18 October 2026.

Open the page: https://abdelaziz-1212.github.io/sso-lab/

## What you can do

- **Place the PMUs (IEEE 33-bus feeder).** Tap buses to add or remove PMUs and check three requirements: detect every simulated SSO event, detect a source at any bus, and tell any two candidate plants apart after one PMU fails. The minimum is 11 PMUs.
- **Read an SSO.** Choose a weak-grid (Type-4), series-capacitor (DFIG) or stable case recorded at one PMU on the IEEE 34-node feeder, add measurement noise, and see the mode, its mirror component and the type decision.

## Data

Electromagnetic-transient simulations of IEEE test networks at 50 Hz. Requirement sets come from a two-stage integer program for PMU placement. The page runs entirely in the browser and sends no data anywhere.
