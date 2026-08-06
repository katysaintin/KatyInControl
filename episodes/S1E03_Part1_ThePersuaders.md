# S1E03 — Part 1 : "The Persuaders!"
## TANGO & EPICS: An Origin Story
### Katy In Control — Season 1, Episode 3, Part 1
### Target duration: ~10 minutes (narration + interview excerpts)

---

> **Production notes**
> This is Part 1 of a two-part episode.
> Focus: human origins, founders, early anecdotes, the SDI/Star Wars story.
> Part 2 ("Biodiversity / Pass it on") covers convergence, transmission, and the future.
>
> ⚠️ TIMELINE CORRECTED by Bob Dalesio — email August 2026.
> Key correction: TCS was developed at CPRC (private company), NOT at LANL.
> Bob arrived at LANL in 1985 with the TCS codebase. GTACS = EPICS V1.
> LAACS = EPICS V2 (LEDA project). EPICS = V3, born from LANL + ANL collaboration.
> Marty Kraimer passed away in 2022 (confirmed by Greg White, SLAC, August 2026).
> Jeff Hill recently retired.
>
> Interview guests for Part 1:
>   — Bob Dalesio ✅ responded with detailed corrections + Marty Kraimer scene
>   — Mike Thuot (LANL) ✅ documents sent + anecdotes, validation pending
>   — Jens Meyer (ESRF — co-author founding paper 1999) ✅ responded on mailing list
>   — Andy Götz (TANGO project lead, ESRF) ✅ in thread, email sent
>
> Questions covered in Part 1: Q1, Q2, Q3 (spark, obstacles, first moment)
> Signature closing: *"May the uptime be with you."*

---

## COLD OPEN

🕓
Last episode, we toured the Death Star.
Hardware, communication bus, business logic.
We even met the Droids, the holographic network, and the Emperor himself.

🕓
And we looked at two very different ways to run that Death Star —
EPICS, with its Process Variables and Channel Access.
TANGO, with its Device Servers, Attributes, and Commands.

🕓
Same mission. Two blueprints. But here's the question nobody asks —
*Who drew those blueprints? And why?*

🕓
Today, we go back in time.
Not to a galaxy far, far away — but to the very real, very human story
of how two teams of engineers, on two different continents,
decided to solve the same problem — in their own way.

🕓
And I have to warn you —
the origin story of EPICS involves Star Wars.
Not the Jedi kind.
The other kind.

---

## ACT 1 — THE PERSUADERS

🕓
There's a British TV series from 1971 — *The Persuaders!*
Two men, wildly different in background and style,
forced to work on the same mission.

🕓
Brett Sinclair — British aristocrat, elegant, protocol-driven.
Danny Wilde — self-made American, street-smart, pragmatic.

🕓
They argue. They clash. They absolutely refuse to agree on anything.
And yet — episode after episode — they somehow solve the problem together.

🕓
TANGO and EPICS are Brett and Danny.
Born on different continents. Built on different philosophies.
Powering the same particle accelerators, the same synchrotrons,
sometimes literally on the same site.

🕓
So — how did they get here?

---

## ACT 2 — EPICS: THE AMERICAN ORIGIN STORY

### 2a — Before Los Alamos: the man who already had a system

🕓
Before EPICS. Before Los Alamos.
There was a small startup company called CPRC —
a subsidiary of Computer Products Inc.,
building industrial I/O systems for nuclear reactors and industrial applications.

🕓
In 1982, Bob Dalesio joined that startup as lead engineer.
And there, he built something called TCS.
*The Control System.*

🕓
Not a marketing name. Not an ambitious acronym.
Just: The Control System.
No ego. No branding. Just the description of what it did.

🕓
In 1985, Los Alamos National Laboratory issued a Request For Proposals
for a SCADA system for the Phoenix facility.
CPRC won the bid.
Bob came to Los Alamos — and he brought TCS with him.

🕓
He never really left.

---

### 2b — Star Wars, and a better idea

🕓
At Los Alamos, Bob joined the team building
the Ground Test Accelerator — the GTA.
A prototype for space-based neutral particle beam weapons.
The Star Wars program. Reagan's Strategic Defense Initiative.

🕓
Bob told me this himself.
He compared it to children hiding under school desks
during atomic bomb drills.
*"Both patently absurd solutions."*

🕓
But inside that programme —
Mike Thuot had a different idea.
He wanted a SCADA system. For science.
Not for war. For science.
And Bob thought: *that sounds like a great challenge.*

🕓
That's how EPICS began.
With someone refusing to let a weapons programme have the last word.

🕓
My podcast uses Star Wars as a pedagogical analogy.
EPICS was literally born from the Star Wars programme.
I could not have scripted this better if I'd tried.

🕓
*[INTERVIEW — MIKE THUOT — Q1: the moment the idea shifted]*

---

### 2c — Three names. Three lives. One codebase.

🕓
The system Bob built for the Ground Test Accelerator
was called GTACS — the Ground Test Accelerator Control System.
That was EPICS Version 1.
Channel Access, developed by Jeff Hill.
The IOC — the Input/Output Controller — developed by Bob.

🕓
Then came the second project: LEDA —
the Low Energy Demonstrator Accelerator.
Jeff and Bob kept developing Channel Access and the IOC.
This time, the published work appeared under a new name:
LAACS — Los Alamos Accelerator Control System.
EPICS Version 2.

🕓
But the Army didn't want the work publicly associated with the GTA programme.
So for a while — the system had to be presented without its real name.
A control system without an identity.

🕓
Then something happened that changed everything.

---

### 2d — The print-out that was four inches thick

🕓
The relationship between Los Alamos and Argonne National Laboratory
started at an ICALEPCS conference —
a meeting between Mike Thuot and Marty Knott from Argonne,
who was about to build the Advanced Photon Source.

🕓
Argonne sent Marty Kraimer to Los Alamos to study the IOC.
He was going to spend six weeks there.

🕓
Marty showed up at Bob's office.
In his hands — a print-out of the IOC source code.
Four inches thick.
With at least forty red annotations.

🕓
They sat down together and started going through it.
One question at a time.
Some were suggestions. Some were clarifications.
Some were, politely, pointing out things that could be better.

🕓
After hours — or maybe days — of sitting together like that,
Bob finally told Marty something.

🕓
He said: *we don't have to work together.*

🕓
Marty looked up, a little taken aback.
And said: *I think this is great.*
*I most definitely want to work together.*

🕓
From that moment — Marty, Jeff and Bob worked as one team.
And it became clear that the result of this collaboration
needed a new name.
Because Argonne engineers were now making very impactful improvements.

🕓
They landed on:
*Experimental Physics and Industrial Control System.*
EPICS.

🕓
Bob added "Industrial" himself —
from his background in oil fields, steel plants, nuclear reactors.
He knew this system was better at its core functions
than anything the industrial SCADA world had produced.

🕓
*[INTERVIEW — BOB DALESIO — on Marty Kraimer, the print-out, and letting go]*

🕓
Marty Kraimer passed away in 2022.
Jeff Hill recently retired.
Bob is still here — and he told me this story himself.

🕓
The code they wrote together in those weeks
is still running on production systems today.
That's the only kind of immortality engineers get.
And it's not a bad one.

> ⚠️ Note production: valider la formulation de cet hommage avec Bob avant enregistrement.

---

### 2e — The team, the trust, and what came after

🕓
Bob described the founding dynamic in three words:
*trust, shared goal, open discussions.*
Technical and political.

🕓
*"With the tone set — others that wanted to work in that environment joined us."*

🕓
And behind those engineers — management that understood.
Mike Thuot and Marty Knott didn't just allow the collaboration.
They protected it.
They gave their engineers the space to invest in something
whose results might not show for years.

🕓
Bob put it simply:
*"All of our best contributors come when the management shares the ideals
of a collaboration and they have dedicated and talented engineers
to join the core developers."*

🕓
That's not a technical insight. That's an organisational one.
And it's the part that never makes it into the papers.

🕓
There's a phrase I used at an EPICS Collaboration Meeting
that Bob Dalesio quoted back to me — on a slide, at Oak Ridge National Laboratory.

🕓
*"Alone we go faster. But together we go further."*

🕓
I didn't know it at the time, but I was describing
exactly what happened in Los Alamos in 1989.
And in Trieste. And at every ICALEPCS dinner since.

🕓
That is how you build a community.
Not with a governance document.
Not with a licence agreement.
With a tone. And an invitation.

🕓
EPICS 7 is running — with a new generation of outstanding core developers,
including Greg White at SLAC, who led the upgrade team.
And Bob calls the collaboration itself
*"the most valuable part of the whole thing."*

🕓
*[INTERVIEW — BOB DALESIO — Q5: what he'd tell a young engineer today]*

---

## ACT 3 — TANGO: THE EUROPEAN ORIGIN STORY

🕓
Grenoble, France. The European Synchrotron Radiation Facility — the ESRF.
1989. Same year as the Vancouver dinner.
But the approach? Completely different.

🕓
At ESRF, the concept of the *Device Server* was born.
Every piece of equipment becomes a network object —
a Device, with attributes, commands, and state.

🕓
That first idea became TACO — the ESRF's internal system through the 1990s.
By the late 1990s, it was showing its age.

🕓
In 1999, the team decided to rebuild everything from scratch.
On CORBA. In C++. With a clean, object-oriented design.
Andy Götz. Jean-Michel Chaize. Emmanuel Taurel.
Jens Meyer. And others.

🕓
Six people signed that founding paper.
Presented at ICALEPCS 1999, Trieste.
The founding act of a community that now spans 50+ sites.

🕓
*[INTERVIEW — ANDY GÖTZ — Q1: the decision to rebuild as TANGO]*

🕓
*[INTERVIEW — JENS MEYER — Q1: being there in 1999, what he remembers]*

---

## ACT 4 — THE FIRST MOMENTS

🕓
The stories nobody writes in the papers.

🕓
*[INTERVIEW — BOB DALESIO & MIKE THUOT — Q3]*
*"The first time you saw EPICS running on a real machine —*
*what did that feel like?"*

🕓
And then there's Andy's story.
A device server for a temperature sensor.
The demo is running. Andy approaches the sensor —
I'll let him tell you the rest.

🕓
*[INTERVIEW — ANDY GÖTZ — Q3: the temperature demo]*

🕓
*[INTERVIEW — JENS MEYER — Q3: his own first moment]*

🕓
That moment — a number changing on a screen, driven by a human hand —
is the moment every control system engineer lives for.
The first time the system *sees* the real world.

---

## WRAP-UP PART 1

🕓
We've met the people who drew the blueprints.

🕓
A lead engineer who arrived at Los Alamos with a system already in his bag.
A name that changed three times as the ambition grew.
A print-out four inches thick, and two men who decided to trust each other.
A word — *Industrial* — added by someone who had worked in oil fields and steel plants
and knew what reliability actually meant.
Management that protected a long-term vision when most wouldn't have.

🕓
And across the Atlantic — six people in Trieste
who decided to rebuild everything from scratch
because they believed in a better abstraction.

🕓
Two teams. Two continents. Two philosophies.
One shared obsession: *make the machine work.*

🕓
In Part 2 — the harder question.
Not where these systems came from.
But who carries them forward.

🕓
*May the uptime be with you, Padawan.*

---

## FACTUAL CORRECTIONS LOG
> Source: Bob Dalesio, email August 2026 — Greg White, SLAC, email August 2026

| Point | Version précédente | Version corrigée |
|---|---|---|
| Origine de TCS | Développé à LANL | Développé à CPRC (startup privée, 1982-85) |
| Arrivée de Bob à LANL | "contractor sent by a vendor" | Lead engineer sur le bid CPRC/Phoenix, arrivé en 1985 |
| Nom GTACS | = EPICS V1 | Confirmé — Channel Access (Hill) + IOC (Dalesio) |
| Nom LAACS | Renommage pour raisons militaires uniquement | LAACS = projet LEDA = EPICS V2, distinct de GTACS |
| Marty Knott vs Marty Kraimer | Confondus | Marty Knott (ANL, directeur APS) ≠ Marty Kraimer (ANL, développeur IOC) |
| Décès Marty Kraimer | "a few years ago" | 2022 (confirmé Greg White, SLAC, août 2026) |
| Statut Jeff Hill | Non mentionné | Récemment retraité (Bob Dalesio, email 2026) |
| Version actuelle EPICS | "EPICS 7" | V7 = V4 upward-compatible + V3, tournent ensemble dans l'IOC |
| EPICS 7 lead | Non mentionné | Greg White (SLAC) — à l'initiative de Bob Dalesio et Timo Korhonen |

---

## KEY ANECDOTES STATUS

| Anecdote | Source | Permission |
|---|---|---|
| EPICS funded by SDI / Star Wars | Bob Dalesio, email 2025 | ✅ cleared verbatim |
| TCS né chez CPRC, pas à LANL | Bob Dalesio, email 2026 | ✅ cleared |
| Le print-out 4 pouces / Marty Kraimer | Bob Dalesio, email 2026 | ✅ cleared verbatim |
| *"We don't have to work together"* | Bob Dalesio, email 2026 | ✅ cleared verbatim |
| *"Trust, shared goal, open discussions"* | Bob Dalesio, email 2026 | ✅ cleared verbatim |
| Management quote (Thuot + Knott) | Bob Dalesio, email 2026 | ✅ cleared verbatim |
| Vancouver dinner / Axel Daneels 120-160 MY | Mike Thuot, *The Roots of EPICS* + email | 🔲 pending |
| *"completely egoless programming"* (TCS) | Mike Thuot, *The Roots of EPICS*, 2005 | 🔲 pending |
| Andy Götz temperature demo | Andy Götz, LinkedIn + email | 🔲 pending |

---

## PRODUCTION CHECKLIST — PART 1

- [x] Script draft completed
- [x] Bob Dalesio — corrections reçues et intégrées ✅
- [x] Mike Thuot — documents reçus, synthèse + permission email envoyés ✅
- [x] Andy Götz contacté ✅
- [x] Jens Meyer répondu sur mailing list ✅
- [x] Greg White (SLAC) — répondu, décès Marty 2022 confirmé ✅
- [x] SDI/Star Wars anecdote cleared (Bob Dalesio)
- [x] Marty Kraimer scene cleared (Bob Dalesio, email 2026)
- [x] Marty Kraimer année de décès — 2022 (Greg White, août 2026)
- [ ] Validation + permissions confirmées par Mike
- [ ] Schedule recording — Bob + Mike (Zoom, 45 min)
- [ ] Schedule recording — Andy Götz (Zoom)
- [ ] Schedule recording — Jens Meyer (**priorité : avant retraite**)
- [ ] Schedule recording — Greg White (SLAC) — EPICS 7
- [ ] Tribute Marty Kraimer — valider formulation avec Bob
- [ ] Insérer segments interview aux placeholders
- [ ] Enregistrer narration (HeyGen digital twin)
- [ ] Montage + mix
- [ ] Export YouTube + HTML + PDF
- [ ] Post LinkedIn / EPICS Tech-Talk / TANGO mailing list

---

*© 2025 Katy Saintin — Katy In Control. CC BY-NC 4.0.*
