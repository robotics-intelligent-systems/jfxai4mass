# OpenTwin current CAD requirements baseline

Proposed engineering baseline, 9 October 2026. Source commit: `5b17496213385eb9b9bd3f5923c231a365667c88`.

## Current concepts

| Concept source in `MBSE/CAD` | Current Draw.io baseline | Specific IDs | Common allocation |
| --- | --- | --- | --- |
| `opentwin-modular-armor-truck-digital-twin-concept.jpg` | [Modular armor truck](opentwin-modular-armor-truck-high-level-requirements.drawio) | ARM-01–06 | COM-01–09 |
| `opentwin-explorer-mobile-fixed-habitat-digital-twin-concept.jpg` | [Explorer mobile and fixed habitat](opentwin-explorer-mobile-fixed-habitat-high-level-requirements.drawio) | EXP-01–07 | COM-01–09 |
| `opentwin-amphibious-ugv-agricultural-robot-digital-twin-concept.jpg` | [Amphibious UGV and agricultural robot](opentwin-amphibious-ugv-agricultural-robot-high-level-requirements.drawio) | UGV-01–10 | COM-01–09 |

[Common requirements and governance](opentwin-common-high-level-requirements.drawio) define shared obligations. The [machine-readable register](opentwin-high-level-requirements-register.json) contains all 32 requirements. Each concept diagram contains scope/provenance, concept requirements, and open acceptance parameters.

Requirements, allocations and role owners are proposed. Quantitative limits, actual individuals, safety targets and approval basis require review. No engineering test result is asserted. Concept features are interpreted as candidate needs rather than established performance. All TBDs must be resolved before G1; verification cannot close against an unspecified limit.

## Treatment of earlier diagrams

| Earlier content | Reuse / disposition |
| --- | --- |
| Generic truck R01–R08 | Mission/energy intent reused in COM-01/04 and ARM-01/05; protection panels and threat basis added in ARM-02/03. Previous R IDs remain historical. |
| Generic truck R09–R16 | Sensor and safety intent considered in COM-03/08 and ARM-04/06. Autonomous driving is an open decision, not a current artwork-derived obligation. |
| Generic truck R17–R24 | Twin, open interface, model, maintenance and configuration intent consolidated in COM-02/05/06/07/09. |
| Rescue FR-01–05 | Ground/water mobility, transition, buoyancy and stability intent adapted in UGV-01–04. Acceptance must use the agricultural carrier configuration. |
| Rescue FR-08–12 and NFRs | Modular interfaces, telemetry, local safety and resilience intent consolidated in COM-02/03/05/08 and UGV-08/10. |
| Rescue FR-06–07; H2 / EWD / HJ / CTRL detail | Rescue occupant capacity/boarding and selected hydrogen/hydrojet topology are not allocated to the agricultural concept. Water propulsion remains an open decision. |
| Flying-car R-01–R-11 | Common modular, simulation and twin intent retained in COM requirements. All-electric energy and aerial capability remain historical concept choices. |
| `car-control-framework.drawio` | Retained as an architecture reference; sparse labels are not treated as verifiable requirements. |
| Explorer | No directly corresponding earlier Draw.io baseline found; EXP requirements fill this coverage gap. |

Three earlier requirement files carry a visible legacy notice. They remain separate concepts; the current baseline is the four files linked above. Historical source-image references are preserved as history and are not presented as current CAD evidence. This crosswalk records thematic reuse, not one-to-one equivalence or verification closure.

## Verification workflow

For each configuration, assign COM requirements and its concept requirements to engineering elements. Specify measurable acceptance thresholds and scenarios, then record evidence IDs, measured results, versioned configuration, reviewer and pass/fail disposition. Use inspection, analysis, simulation and controlled tests appropriate to the acceptance text. A simulation result alone does not validate physical capability.

Candidate tools shown in CAD artwork remain replaceable: FreeCAD, Blender, CalculiX, OpenModelica, Project Chrono, ROS 2, OpenFOAM and Godot/gdext. No integration or performance is inferred from a tool label.
