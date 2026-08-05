# S1E03 — Guest Biographies
## Appendix — Online Guide & PDF
### Katy In Control — Season 1, Episode 3 (Parts 1 & 2)

---

> **Editorial note**
> No Wikipedia page exists for any of the contributors listed below.
> These biographies have been compiled from publicly traceable sources
> (institutional pages, ICALEPCS proceedings, JACoW publications, GitHub, LinkedIn)
> and from information shared directly with Katy In Control during the preparation of this episode.
> Each biography has been submitted to its subject for validation before publication.
> Sources are listed at the end of each entry.

---

## Acknowledgements

*Episode 3 of Katy In Control would not exist without the generosity of the people listed below.
They answered emails, found documents in drawers, corrected mistakes in real time,
and trusted this project with their stories.
Thank you.*

*"Alone we go faster. But together we go further."*
— Katy Saintin, EPICS Collaboration Meeting, Oak Ridge National Laboratory
*(quoted by Bob Dalesio, co-creator of EPICS, on the meeting agenda slide)*

— Katy Saintin, IRFU/CEA Saclay

---

## BOB DALESIO
### EPICS Co-Founder — Lead Architect

Bob Dalesio is one of the principal architects of EPICS (Experimental Physics and Industrial Control System), the open-source control system framework now deployed at over 100 scientific facilities worldwide, on every continent including Antarctica.

Before joining Los Alamos National Laboratory, Bob built his expertise in the industrial SCADA world. From 1979 to 1982, he worked at EMC Controls developing the Emcon 3D system for oil fields and steel plants. From 1982 to 1985, he was lead engineer at CPRC (a subsidiary of Computer Products Inc.), where he designed TCS — *The Control System* — a modular, reusable SCADA toolkit for nuclear and industrial applications. In 1985, CPRC won a bid from Los Alamos National Laboratory for a control system for the Phoenix facility, and Bob arrived at LANL with TCS already in his toolkit.

At LANL, Bob led the development of GTACS (Ground Test Accelerator Control System) — the system that would become EPICS Version 1. Working alongside Jeff Hill, who designed the Channel Access protocol, Bob developed the IOC (Input/Output Controller), the core engine of the EPICS architecture. When Marty Kraimer from Argonne National Laboratory joined the team for six weeks — arriving with a four-inch print-out of the IOC code, covered in annotations — Bob and Marty eventually agreed to work together, and the resulting collaboration gave EPICS its name and its identity as a multi-laboratory project.

Bob Dalesio is also known for having brought the word "Industrial" to the EPICS acronym — from his background in oil fields, steel plants, and nuclear facilities, he knew the system was better at its core functions than anything the industrial SCADA world had produced.

After LANL, Bob co-founded Osprey DCS, a company dedicated to EPICS-based control systems for scientific facilities. He remained involved in the EPICS community through the launch of EPICS 7, and continues to advocate for the collaborative model he helped establish.

**In this episode**, Bob shared the origin story of EPICS directly with Katy In Control — including the SDI/Star Wars funding context, the scene with Marty Kraimer's annotated print-out, and a real-time timeline correction that improved the factual accuracy of this episode significantly.

**Sources & links**
- EPICS Wikipedia: https://en.wikipedia.org/wiki/EPICS
- Osprey DCS: https://ospreydcs.com
- OSTI 10193541 — *The EPICS Architecture* (1993): https://www.osti.gov/biblio/10193541
- *EPICS: A Control System Software Co-Development Success Story* — Dalesio et al.: https://epics.anl.gov/EpicsDocumentation/EpicsGeneral/epics_success.html
- Bob Dalesio, personal communications, 2025–2026 (used with permission)

---

## MIKE THUOT
### LANL — The Vision Behind EPICS

Mike Thuot is the person who had the original idea that a shared, modular, open-source SCADA system could serve the scientific community — and who turned a weapons programme budget into the seed funding for one of the most successful open-source collaborations in science.

Working at Los Alamos National Laboratory on the Ground Test Accelerator (GTA) — a prototype for the US Strategic Defense Initiative — Mike recognised that the engineering capabilities being developed had a far greater application than their original military purpose. His conviction that a SCADA system *for science* was both possible and necessary led him to champion what would become EPICS.

At the ICALEPCS conference in Vancouver in 1989, Mike's group heard Axel Daneels from CERN present a striking figure: between 120 and 160 man-years of effort were being spent by every large science project in the world to build its own control system — from scratch, alone, every time. That evening, over dinner, Mike and his colleagues met Marty Knott from Argonne National Laboratory and proposed *"a better way"*: a shared, open toolkit, built by all and for all.

That dinner conversation was the founding act of the EPICS collaboration.

Mike Thuot has described the culture of that founding team in terms that remain rare in engineering: *"Trust in a shared goal and open discussions on all issues, technical and political. With the tone set, others that wanted to work in that environment joined us."* He also coined the phrase "completely egoless programming" to describe Bob Dalesio's approach — a phrase that explains as much about why EPICS succeeded as any technical description.

**In this episode**, Mike generously shared original documents from his personal archives — including *The Roots of EPICS* (a speech delivered at the 15th anniversary of EPICS) and a pre-EPICS history document — which provided the factual foundation for Part 1 of this episode. He also connected Katy In Control directly with Bob Dalesio.

**Sources & links**
- Thuot M. — *The Roots of EPICS*, personal speech, ~2005 (shared with Katy In Control, 2026)
- Thuot M. — *Pre-EPICS History*, email document, 2019 (shared with Katy In Control, 2026)
- Thuot M., Dalesio L.R. et al. — *The Success and Future of EPICS*, LINAC96, 1996
- Mike Thuot, personal communications, 2026 (used with permission)

---

## ANDY GÖTZ
### TANGO Co-Creator — ESRF

Andy Götz is one of the principal architects of TANGO Controls, the object-oriented control system framework developed at the European Synchrotron Radiation Facility (ESRF) and now deployed at over 50 scientific sites worldwide.

Andy started his scientific career as a radio astronomer at Rhodes University in Grahamstown, South Africa, followed by a position at the Max Planck Institut für Radioastronomie in Bonn, Germany. In 1988, he joined the ESRF in Grenoble, France, initially working on accelerator control systems before moving to beamline controls, data processing, and data management. He managed the ESRF Software Group for 15 years.

In 1999, Andy was one of the six co-authors of the founding TANGO paper — *"TANGO: an Object Oriented Control System Based on CORBA"* — presented at ICALEPCS 1999 in Trieste, Italy. The paper introduced TANGO as a complete redesign of the ESRF's existing TACO system, built on CORBA and C++ with a clean object-oriented architecture in which every piece of equipment is modelled as a network object: a Device, with attributes, commands, and a state.

Beyond TANGO, Andy has been deeply involved in the open science movement. In 2019, he became coordinator of PaNOSC (Photons and Neutrons Open Science Cloud), a Horizon 2020 project. Since June 2024, he works part-time for the EOSC Association as editor of the EOSC Federation Handbook.

A South African by origin, Andy is known in the TANGO community for the African proverb that has become something of a motto: *"If you want to walk fast, walk alone. If you want to walk far, walk together."* — a phrase that captures the spirit of the TANGO collaboration as precisely as any technical document.

**In this episode**, Andy shared the anecdote of the first TANGO temperature demo — warming a sensor with his hands to make the reading change on screen — and invited Katy In Control to present at a TANGO meeting. He also shared Jean-Michel Chaize's "biodiversity" quote, which became the central thread of Part 2.

**Sources & links**
- EOSC Association biography: https://eosc.eu/staff/andy-gotz-0
- ResearchGate profile: https://www.researchgate.net/profile/Andy-Gotz
- GitHub: https://github.com/andygotz
- ICALEPCS 1999 founding paper: https://www.esrf.fr/computing/cs/tango/tango_doc/icaleps99/WA2I01.html
- tango-controls.org authors: https://tango-controls.readthedocs.io/en/latest/authors.html
- Andy Götz, personal communications, 2025–2026 (used with permission)

---

## JENS MEYER
### TANGO Co-Creator — ESRF

Jens Meyer is one of the six co-authors of the founding TANGO paper presented at ICALEPCS 1999 in Trieste, and has spent his career at the European Synchrotron Radiation Facility (ESRF) in Grenoble, where he is Head of the Beamline Control Unit.

Jens has been at the ESRF since the early days of both TACO and TANGO, contributing to the development of the beamline control infrastructure that now powers one of the world's most advanced synchrotron light sources. His name appears across more than two decades of ESRF publications on control systems, beamline modernisation, and experiments software — from the early TACO/TANGO transition to the development of BLISS, the experiments control system built for the ESRF Extremely Brilliant Source (EBS) upgrade.

As Head of the Beamline Control Unit, Jens oversees the control systems for the ESRF's experimental beamlines — the infrastructure that allows scientists from around the world to conduct experiments using some of the most intense X-ray beams on the planet.

Jens's career spans the full history of TANGO: from the device server concept that preceded TACO, through the 1999 redesign that created TANGO, through the replacement of CORBA by ZeroMQ in TANGO V8, to the current V10 release. He carries in his memory the decisions that were never written down — the *why* behind the architecture — and his perspective on the human story of TANGO is irreplaceable.

**In this episode**, Jens responded to Katy In Control's post on the TANGO mailing list and volunteered to share his recollections of the early days of TANGO — noting, with characteristic understatement, that he "still has some time before retirement." His contribution to Part 1 covers the first moments of TANGO from the inside, and his response to the transmission question in Part 2 is one of the most important passages of the episode.

**Sources & links**
- ICALEPCS 1999 founding paper (co-author): https://www.esrf.fr/computing/cs/tango/tango_doc/icaleps99/WA2I01.html
- BLISS paper (co-author, with Andy Götz): https://www.tandfonline.com/doi/full/10.1080/08940886.2023.2277141
- JACoW publications: https://jacow.org (search "J. Meyer ESRF")
- Jens Meyer, personal communications, 2026 (used with permission)

---

## IN MEMORIAM — MARTIN R. KRAIMER
### ANL / APS — The Engineer Who Let EPICS Grow

*Martin R. "Marty" Kraimer (Argonne National Laboratory) passed away several years ago.
He was not a guest in this episode — but he is in every line of it.*

Marty Kraimer spent his career at Argonne National Laboratory, where he was part of the team building the control system for the Advanced Photon Source (APS) — one of the most powerful X-ray light sources in the world. He came to the EPICS story as an evaluator sent to Los Alamos to study the IOC for the APS project, and he stayed as one of its principal architects.

When Marty arrived at Bob Dalesio's office in Los Alamos, he had with him a four-inch print-out of the IOC source code — covered in at least forty annotations. He planned to spend six weeks. What happened in those weeks, as Bob has described it, was less a technical review than a slow, careful negotiation of trust between two engineers who each had strong ideas and were willing to test them against each other.

Bob eventually told Marty they didn't have to work together.
Marty looked up and said: *"I think this is great. I most definitely want to work together."*

From that moment on, Marty, Jeff Hill, and Bob worked as one team.

Marty's technical contributions to EPICS were structural and lasting. During 1990 and 1991, he led the major revision of the IOC software at ANL/APS, with the primary goal of making record and device support extensible — the architectural decision that allowed EPICS to support an open-ended variety of hardware and protocols. He designed the data structures at the heart of that extensibility, and made the corresponding changes to the IOC resident software.

He also developed the interface between the EPICS database and the hardware drivers, contributed to the Alarm Server, and in 1996 led a cooperative effort with Bob Dalesio on runtime link modification. In 1999, he was one of the principal developers of the port of iocCore to non-vxWorks operating systems — Linux, Solaris, Windows — the work that opened EPICS to the modern computing world.

His name appears on the cover page of every edition of the EPICS Application Developer's Guide, alongside Jeff Hill and Bob Dalesio. It is the most widely read technical document in the EPICS community.

Marty Kraimer's contributions are not decorative. They are structural. The extensibility of the IOC, the portability of iocCore, the interface between the database and the hardware — these are the decisions that made EPICS what it is. They run, silently, on every site that uses EPICS today.

**Sources**
- Bob Dalesio, personal communications, 2026 (used with permission)
- EPICS Application Developer's Guide (all editions) — first author: Martin R. Kraimer
- EPICS Wikipedia: https://en.wikipedia.org/wiki/EPICS
- ResearchGate — Martin Kraimer publications: https://www.researchgate.net/scientific-contributions/Martin-Kraimer-9339807
- ANL/APS technical report 41280 (2002): https://publications.anl.gov/anlpubs/2002/01/41280.pdf
- *EPICS: A Control System Software Co-Development Success Story* — Dalesio et al.

---

## IN MEMORIAM — JEFF HILL
### LANL — Father of Channel Access

Jeff Hill (Los Alamos National Laboratory) recently retired. He is the inventor of Channel Access — the networking protocol at the heart of EPICS that allows clients and servers to communicate in real time across a distributed control system.

Bob Dalesio has described Channel Access as the defining conceptual contribution of the early EPICS era: a "software bus" so well designed that it is still running on production systems more than thirty years after it was first written. Jeff Hill developed Channel Access alongside Bob's work on the IOC, and the two together form the architectural core that every subsequent version of EPICS has built upon.

EPICS 7 introduced pvAccess — a successor protocol with structured data types — but Channel Access continues to run in parallel, a testament to Jeff Hill's original design.

**Sources**
- Bob Dalesio, personal communications, 2026
- EPICS Wikipedia: https://en.wikipedia.org/wiki/EPICS
- Hill J.O., Dalesio L.R. et al. — *Run-time environment and application tools for the ground test accelerator control system*, Nuclear Instruments and Methods, 1990

---

> **A note on validation**
> All biographies of living contributors have been shared with their subjects
> for factual review before publication.
> The *In Memoriam* sections for Marty Kraimer and Jeff Hill
> have been reviewed by Bob Dalesio.
> Katy In Control thanks each of them for their time and their trust.

---

*© 2025 Katy Saintin — Katy In Control. CC BY-NC 4.0.*
*Biographical content may be reproduced with attribution.*
