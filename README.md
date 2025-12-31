# Wheelchair lift linkage

Designed and prototyped a compact wheelchair add-on that assists a paraplegic user in transitioning from seated to an elevated, stable posture suitable for a golf swing using a one-DOF linkage mechanism.

## Overview

This project developed a linkage-based lifting mechanism to improve golf accessibility for a paraplegic wheelchair user. The goal was to create an add-on system that attaches to a standard wheelchair, lifts the user to a stable elevated posture, and supports a safe golf swing while remaining compact and practical to fabricate.

## Design goals

- Create a wheelchair-compatible add-on rather than replacing the entire wheelchair
- Achieve a controlled lift to an elevated posture suitable for a golf swing
- Maintain stability and user safety throughout the motion
- Keep the mechanism compact with realistic link lengths and joint locations
- Prototype the design using laser-cut components and pin joints

## Project visuals

### Assembly + bill of materials

![Assembly view]()

### CAD render

![Rendered assembly]()

### Physical prototype

![Laser-cut prototype]()

### Motion Demo

![assembly-movie.avi]()

## Mechanism design

We started by exploring simple four-bar concepts that could generate the required seated-to-standing motion while keeping the wheelchair area above the seat unobstructed for a golf swing. Early concepts were rejected when they produced unsafe body angles during motion or required a full wheelchair redesign instead of an add-on mechanism.

The final design is a six-bar lifting mechanism derived from a four-bar linkage with an added driving dyad. The mechanism was designed to have one degree of freedom and to regulate the rocker motion so the user’s posture transitions in a controlled range rather than following a full crank rotation.

Key design elements:

- Four-bar section used to generate the primary lift motion.
- Driving dyad added to limit the rocker travel and reduce the need for manual user control.
- Link lengths and pivot placement chosen to maintain stability in the elevated posture and avoid extreme joint angles.
- Feasibility checks performed using Grashof condition inequalities for both the driving dyad and the four-bar sections.

## Prototype and validation

A physical prototype was built to evaluate geometry, motion feasibility, and overall packaging on a wheelchair-scale layout. The prototype used laser-cut components and pin joints to represent the linkage structure and allow rapid iteration during assembly.

Validation focused on:

- confirming the mechanism follows the intended motion path from the seated posture to the elevated posture
- checking clearance and packaging for a wheelchair add-on configuration
- assessing whether the linkage can reach and hold a stable elevated position suitable for a golf swing

The prototype demonstrated the intended motion and helped identify practical considerations such as joint alignment, link interference, and the importance of rigid mounting points to minimize play in the mechanism.

## Repository contents

- docs/
  - final-report.pdf
- cad/
  - project-solution.zip
- media/
  - figures/
  - videos/
    - assembly-movie.avi

## Tools used

- CAD modeling and assembly (SolidWorks)
- Linkage synthesis and feasibility checks (Grashof condition analysis)
- Prototyping with laser-cut components and pin joints

## Collaborators

- [Matthew Lardieri](https://www.linkedin.com/in/matthew-lardieri-5b3334316/)
- [Mehdi Mrini](https://www.linkedin.com/in/mehdi-mrini-28779627a/)
- [Winston Nfor Kanjo Ndi](https://www.linkedin.com/in/winston-nfor-kanjo-ndi-825270225/)
