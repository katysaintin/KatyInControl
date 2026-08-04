# S1E03 — Part 2 : "Biodiversity"
## What we pass on, and to whom.
### Katy In Control — Season 1, Episode 3, Part 2
### Target duration: ~10 minutes (narration + interview excerpts)

---

> **Production notes**
> This is Part 2 of a two-part episode.
> Central thread: **transmission** — of knowledge, of culture, of code.
> The question is no longer "where did these systems come from?"
> but "who carries them forward, and how?"
>
> Narrative frame: Jean-Michel Chaize's "biodiversity" quote as the spine.
> The bee metaphor (Andy Götz, LinkedIn) as Katy's role in the story.
> Technical anchor: the Tango DB + Phoebus POC — the bridge that exists.
>
> Interview guests for Part 2:
>   — Bob Dalesio (EPICS) ✅ — Q4, Q5
>   — Mike Thuot (LANL) ✅ — Q4, Q5
>   — Andy Götz (TANGO/ESRF) ✅ — Q4, Q5
>   — Jens Meyer (ESRF, founding paper 1999) ✅ — Q4, Q5
>   — Jean-Michel Chaize (ESRF/SOLEIL) 🔲 — to contact (biodiversity quote)
>
> Questions covered in Part 2: Q4, Q5 (convergence, transmission, next generation)
> Signature closing: *"May the uptime be with you."*

---

## COLD OPEN

🕓
In Part 1, we met the people who drew the blueprints.
Bob and Mike in New Mexico. Andy, Jens and their colleagues in Grenoble.
Two teams. Two systems. Born the same year, on opposite sides of the Atlantic.

🕓
Now the harder question.

🕓
Not where they came from.
But where they're going.
And — more importantly — who carries them forward.

🕓
I want to start with a question that was asked in 2007.
At ICALEPCS, in Knoxville, Tennessee.
Andy Götz was preparing the traditional TANGO talk.
And he asked Jean-Michel Chaize:

🕓
*"Why do we need TANGO when there is EPICS?"*

🕓
Jean-Michel's answer was one word.

🕓
*"Biodiversity."*

🕓
I've been thinking about that word ever since Andy told me.
Because biodiversity doesn't just mean variety.
It means that different species occupy different niches —
and that something connects them.
Cross-pollination.

🕓
Andy's words, not mine:
*"It would be a first if you could be the bee*
*cross-pollinating between the two communities."*

🕓
So. Let's talk about bees.

---

## ACT 1 — TWO WORLDS TODAY

🕓
EPICS and TANGO have coexisted for 25 years.
They've evolved in parallel, borrowed from each other,
and sometimes — quietly — started speaking the same language.

🕓
OPC-UA, adopted on both sides.
Python, the lingua franca of both communities.
REST interfaces, moving in the same direction.
And at my lab — IRFU/CEA —
MUSCADE supervises equipment from both ecosystems simultaneously.

🕓
*[INTERVIEW — BOB DALESIO — Q4]*
*"Twenty-five years of coexistence.*
*Rivals? Complements? Something else entirely?*
*What surprised you most about how both communities evolved?"*

🕓
*[INTERVIEW — ANDY GÖTZ — Q4]*
*"Where do you see the real differences between TANGO and EPICS in 2025 —*
*not just technically, but culturally?*
*And where are the two communities quietly converging —*
*whether they admit it or not?"*

🕓
*[INTERVIEW — JENS MEYER — Q4]*
*"Jens — you've watched both communities for over 25 years.*
*From where you stand today, what does biodiversity actually look like in practice?"*

---

## ACT 2 — THE BRIDGE THAT EXISTS

🕓
Here's something most people in both communities don't know.

🕓
There is already a working bridge between TANGO and EPICS.
Not a concept. Not a roadmap slide.
A bridge that runs.

🕓
Use the Tango database as a directory for EPICS IOCs and their Process Variables.
Browse those PVs with Jive and ATKPanel — TANGO tools.
Display them in Phoebus — the EPICS control room client —
using the TANGO plugin, which I contributed to and corrected in 2025.

🕓
The best of both worlds.
In a single interface.
Running on a laptop in a lab in Saclay.

🕓
This is what cross-pollination looks like in practice.
Not a framework war. A proof of concept.
That someone built quietly, between two burnouts,
because it was the obvious thing to do.

🕓
*[BRIEF SCREEN DEMO OR VISUAL — POC Tango DB + Phoebus + TANGO plugin]*

🕓
The plugin exists. PR #3602, merged into Phoebus.
Tested at SOLEIL. Approved by the community.
The logo of IRFU is on controlsystemstudio.org — because of that work.

---

## ACT 3 — TRANSMISSION

🕓
Jens Meyer told me he still has some time before retirement.

🕓
I want to sit with that sentence for a moment.

🕓
Jens was in Trieste in 1999.
He signed the founding paper.
He has watched TANGO grow from six people
to fifty facilities on four continents.

🕓
When he retires, what happens to what he carries?
The decisions that were never written down.
The failed experiments that shaped the architecture.
The conversations that happened between the talks.

🕓
This is the real problem of transmission in scientific software.
Not the code — code survives in repositories.
The *judgment*. The *why*.
Why CORBA and not RPC. Why objects and not registers.
Why six people in Trieste decided to bet everything on a new protocol.

🕓
*[INTERVIEW — JENS MEYER — Q5]*
*"Jens — before you retire:*
*what do you wish the next generation understood about TANGO*
*that isn't written anywhere?"*

🕓
*[INTERVIEW — ANDY GÖTZ — Q5]*
*"TANGO V10 shipped in January 2025.*
*What does success look like for TANGO in 2035?*
*And what keeps you up at night about transmission?"*

🕓
*[INTERVIEW — BOB DALESIO & MIKE THUOT — Q5]*
*"If a young engineer came to you today and said:*
*'I want to work on control systems for big science' —*
*what would you tell them?*
*What do you wish someone had told you in 1985?"*

---

## ACT 4 — THE BEE

🕓
I started this episode as the narrator.
I'm ending it as a character in the story.

🕓
For twenty years, I've worked between two ecosystems.
TANGO at SOLEIL. EPICS and MUSCADE at IRFU/CEA.
Both cultures. Both tools. Both communities.

🕓
I've written device servers and IOCs.
I've sat in rooms where nobody spoke the same language —
not just technically, but humanly.
Automation engineers on one side. IT developers on the other.
Same building. Almost zero overlap.

🕓
The bridge isn't difficult to build.
It's difficult to justify — to people who don't see why it matters.

🕓
But Bob Dalesio saw it.
Andy Götz sees it.
Jean-Michel Chaize named it in one word, eighteen years ago.

🕓
*Biodiversity.*

🕓
The bee doesn't choose a side.
The bee just carries what it finds from one flower to the next.
And something grows.

---

## WRAP-UP

🕓
TANGO brought elegance, objects, and the discipline of abstraction.
EPICS brought community, a software bus,
and a collaboration model that became a template for open science.

🕓
Together — they run the machines that map the structure of matter.
The fusion reactors that might power our future.
The telescopes that look back to the beginning of time.

🕓
And they will keep running —
as long as someone keeps passing the knowledge forward.

🕓
In our next episode, we go into the hardware layer.
How does a SCADA talk to a PLC?
What is OPC-UA, and why does it matter?
Same Death Star — all the way down to the Droids.

🕓
Until then —
*May the uptime be with you, Padawan.*

---

## CONTACTS STATUS — PART 2

| Guest | Role | Status | Format |
|---|---|---|---|
| Bob Dalesio | EPICS co-founder | ✅ In thread | Zoom à planifier |
| Mike Thuot | LANL, vision origine | ✅ In thread via Bob | Zoom à planifier |
| Andy Götz | TANGO lead, ESRF | ✅ Email envoyé | Zoom ou ICALEPCS |
| Jens Meyer | Co-auteur 1999, ESRF | ✅ Répondu mailing list | Zoom — **priorité retraite** |
| Jean-Michel Chaize | Co-auteur 1999, SOLEIL | 🔲 À contacter | Connaissance directe |

> **Note Jean-Michel** : travaille désormais à SOLEIL. Contact direct possible.
> Demander l'autorisation d'utiliser la citation "biodiversity" (ICALEPCS 2007, Knoxville)
> et s'il accepte de la développer pour l'épisode.

---

## TECHNICAL ANCHOR — POC À DOCUMENTER

> **À faire avant la production de cet épisode.**

Le POC Tango DB + Phoebus est la preuve concrète du fil conducteur "biodiversité".
Il doit être documenté, même sommairement, pour :
- servir de démo visuelle dans l'épisode (screen capture ou courte démo live)
- être publié sur GitHub (repo KatyInControl ou repo dédié)
- être soumis comme contribution technique à ICALEPCS ou TANGO meeting

**Composants du POC :**
- Tango DB comme annuaire d'IOCs EPICS + PVs associés
- Jive + ATKPanel pour browser les PVs côté TANGO
- Plugin TANGO dans Phoebus (PR #3602, mergé, testé SOLEIL, corrigé 2025)
- Interface unifiée — meilleur des deux mondes

**Liens publics déjà tracés :**
- https://github.com/ControlSystemStudio/phoebus/pull/3602
- https://www.controlsystemstudio.org (logo IRFU visible)

---

## PRODUCTION CHECKLIST — PART 2

- [x] Script draft completed
- [x] Citation "biodiversity" (Chaize/Götz) identifiée et localisée
- [x] POC Tango DB + Phoebus fonctionnel (laptop Saclay)
- [x] PR #3602 mergé et public
- [ ] Contacter Jean-Michel Chaize (SOLEIL) — autorisation citation + interview
- [ ] Documenter le POC (README minimal + screen capture)
- [ ] Pousser le POC sur GitHub
- [ ] Enregistrements Q4+Q5 : Bob, Mike, Andy, Jens
- [ ] Enregistrement Jean-Michel Chaize (si accord)
- [ ] Démo visuelle POC (screen recording)
- [ ] Montage final Part 2
- [ ] Export YouTube + HTML + PDF
- [ ] Soumettre abstract POC à ICALEPCS / prochain TANGO meeting

---

## KEY QUOTE — TO USE VERBATIM (with permission)

> *"Why do we need TANGO when there is EPICS?"*
> *"Biodiversity."*
> — Jean-Michel Chaize, ICALEPCS 2007, Knoxville
> *(reported by Andy Götz, LinkedIn, 2025 — permission to be confirmed with J.-M. Chaize)*

---

*© 2025 Katy Saintin — Katy In Control. CC BY-NC 4.0.*
