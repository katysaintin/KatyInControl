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
> Closing image: the Keck Telescope — the same code, pointing at the stars.
>
> Interview guests for Part 2:
>   — Bob Dalesio (EPICS) ✅ — Q4, Q5
>   — Mike Thuot (LANL) ✅ — Q4, Q5
>   — Andy Götz (TANGO/ESRF) ✅ — Q4, Q5
>   — Jens Meyer (ESRF, founding paper 1999) ✅ — Q4, Q5
>   — Greg White (SLAC — EPICS 7 lead) ✅ — responded August 2026, interview proposed
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
I want to start with a number.
120 to 160 man-years.

🕓
That's how long it took each large science project in the world
to build its own control system — from scratch, alone, every time.
That figure was presented at ICALEPCS 1989, in Vancouver,
by Axel Daneels from CERN.

🕓
It's the number that triggered the dinner conversation.
The number that made Mike Thuot say: *there's a better way.*
The number that made EPICS necessary.

🕓
Transmission isn't just a nice idea.
It's the answer to 160 man-years wasted.
Every. Single. Time.

---

## ACT 1 — ONE WORD

🕓
In 2007, at ICALEPCS in Knoxville, Tennessee,
Andy Götz was preparing the traditional TANGO talk.
And he asked Jean-Michel Chaize a question.

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

## ACT 2 — TWO WORLDS TODAY

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
*And where are the two communities quietly converging?"*

🕓
*[INTERVIEW — JENS MEYER — Q4]*
*"Jens — you've watched both communities for over 25 years.*
*What does biodiversity actually look like in practice?"*

🕓
Bob Dalesio has a story that answers this question better than any definition.

🕓
One evening at the Keck Telescope in Hawaii.
Late. Something wasn't working.
Bob posted a question on Tech-Talk —
the EPICS mailing list.

🕓
He received an answer from Japan.
Within minutes.

*🎬 PAUSE*

🕓
That moment changed his understanding of what a collaboration is worth.
Not the architecture. Not the codebase.
The community.

🕓
In his words:
*"I realized that the collaboration was more valuable*
*than the architecture in the field."*

---

## ACT 3 — THE BRIDGE THAT EXISTS

🕓
Here's something most people in both communities don't know.

🕓
There is already a working bridge between TANGO and EPICS.
Not a concept. Not a roadmap slide. A bridge that runs.

🕓
Use the Tango database as a directory for EPICS IOCs
and their Process Variables.
Browse those PVs with Jive and ATKPanel — TANGO tools.
Display them in Phoebus — the EPICS control room client —
using the TANGO plugin, which I contributed to and corrected in 2025.

🕓
The best of both worlds. In a single interface.
Running on a laptop in a lab in Saclay.

🕓
*[BRIEF SCREEN DEMO OR VISUAL — POC Tango DB + Phoebus + TANGO plugin]*

🕓
The plugin exists. PR #3602, merged into Phoebus.
Tested at SOLEIL. Approved by the community.
The logo of IRFU is on controlsystemstudio.org — because of that work.

🕓
This is what cross-pollination looks like in practice.
Not a framework war. A proof of concept.
That someone built quietly, between two burnouts,
because it was the obvious thing to do.

---

## ACT 4 — TRANSMISSION

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
And on the EPICS side —
Mike Thuot kept files from 1996 in a drawer somewhere.
Documents that told the story of how a vendor's contractor
became the co-founder of an international collaboration.
How a system called TCS became EPICS.
How a dinner in Vancouver changed everything.

🕓
He sent them to me without hesitation.
Because he understood that if nobody keeps the story —
the story disappears.

🕓
And Marty Kraimer passed away in 2022.
With him went everything he hadn't yet written down.
That's what transmission failure looks like.
Not dramatically. Quietly.

🕓
*[INTERVIEW — JENS MEYER — Q5]*
*"Before you retire:*
*what do you wish the next generation understood about TANGO*
*that isn't written anywhere?"*

🕓
*[INTERVIEW — MIKE THUOT — Q5]*
*"You kept these documents for 30 years.*
*What made you hold on to them?*
*And what do you hope the next generation takes from the EPICS story?"*

🕓
*[INTERVIEW — ANDY GÖTZ — Q5]*
*"TANGO V10 shipped in January 2025.*
*What does success look like for TANGO in 2035?*
*And what keeps you up at night about transmission?"*

🕓
*[INTERVIEW — BOB DALESIO — Q5]*
*"If a young engineer came to you today and said:*
*'I want to work on control systems for big science' —*
*what would you tell them?*
*What do you wish someone had told you in 1985?"*

🕓
*[INTERVIEW — GREG WHITE — EPICS 7]*
*"Greg — you led the EPICS 7 upgrade team.*
*What does it mean to take a system built in 1989*
*and make it ready for the next thirty years —*
*without breaking what already works?"*

🕓
At ICALEPCS 2023 in Cape Town —
the first time our conference was held in Africa —
Andy Götz opened with a Zulu proverb.

🕓
*"Umuntu ngumuntu ngabantu."*

🕓
A person is a person through other persons.

*🎬 PAUSE*

🕓
Two conferences apart. Two different languages.
The same truth.

---

## ACT 5 — THE KECK TELESCOPE

🕓
I want to end with a detail from a 1996 paper.
A reliability table. Rows of accelerators, synchrotrons, detectors.
And then — one line that stops you.

🕓
*Keck II Telescope. 1,500 signals. 2 IOCs. Reliable.*

🕓
The same code born in the New Mexico desert.
Under a programme that wanted to put weapons in orbit.
Renamed three times because the ambition kept growing.
Built by a contractor who stayed, and a programmer who finally let go.

🕓
That code ended up pointing a telescope at the stars.
Not metaphorically. Literally.

🕓
I think that's the answer to the transmission question.
You don't always know, when you're writing the code,
what it will eventually look at.

🕓
You just make it work. And you pass it on.

---

## ACT 6 — THE BEE

🕓
I started this episode as the narrator.
I'm ending it as a character in the story.

🕓
For twenty years, I've worked between two ecosystems.
TANGO at SOLEIL. EPICS and MUSCADE at IRFU/CEA.
Both cultures. Both tools. Both communities.

🕓
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
And Jens Meyer reminded me —
when I thanked him for finally explaining what TACO stood for,
twenty-two years after I started working with it —
that the community is also the place where mysteries get solved.
Sometimes it just takes one email.
And the right person on the other end.

🕓
*Biodiversity.*

🕓
The bee doesn't choose a side.
The bee just carries what it finds from one flower to the next.
And something grows.

🕓
At the EPICS Collaboration Meeting at Oak Ridge National Laboratory,
I said one sentence.
Bob Dalesio — co-creator of EPICS — wrote it on a slide.

🕓
*"Alone we go faster. But together we go further."*

🕓
I didn't invent that idea.
Mike Thuot had it in Vancouver in 1989, over dinner.
Andy Götz had it in Grenoble in 1999, with five colleagues and a blank sheet.
Jean-Michel Chaize summed it up in one word in 2007.

🕓
I just said it out loud, in a room,
at the right moment.
That's what bees do.

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
Bob Dalesio has been doing this for forty years.
And after everything — the weapons programme budget,
the print-out covered in annotations,
the dinner in Vancouver,
the late night at the Keck Telescope —
this is what he took away.

🕓
*"The most valuable thing I learned from this collaboration*
*is that it is better to be successful than to be right."*

*🎬 PAUSE*

🕓
Forty years. One sentence.
EPICS is the proof that it works.

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
| Mike Thuot | LANL, vision origine | ✅ Documents + anecdotes reçus | Zoom à planifier |
| Andy Götz | TANGO lead, ESRF | ✅ Email envoyé | Zoom ou ICALEPCS |
| Jens Meyer | Co-auteur 1999, ESRF | ✅ Répondu mailing list | Zoom — **priorité retraite** |
| Greg White | SLAC — EPICS 7 lead | ✅ Répondu août 2026, interview proposée | Zoom |
| Jean-Michel Chaize | Co-auteur 1999, SOLEIL | 🔲 À contacter | Connaissance directe |

---

## KEY QUOTES STATUS

| Quote | Source | Permission |
|---|---|---|
| *"Both patently absurd solutions"* (SDI) | Bob Dalesio, email 2025 | ✅ cleared |
| *"completely egoless programming"* (TCS) | Mike Thuot, *The Roots of EPICS*, 2005 | 🔲 pending |
| *"a better way"* (Vancouver dinner) | Mike Thuot, email + *The Roots of EPICS* | 🔲 pending |
| Management quote (Thuot + Knott) | Bob Dalesio, email 2026 | ✅ cleared verbatim |
| *"Biodiversity"* (Chaize/Götz) | Andy Götz, LinkedIn 2025 | 🔲 pending Jean-Michel |
| *"the bee cross-pollinating"* | Andy Götz, LinkedIn 2025 | ✅ public post |
| Keck II Telescope (1996 table) | Thuot & Dalesio, LINAC96P | 🔲 pending |
| *"I had intended to quote you"* | Bob Dalesio, email 2026 | ✅ cleared |
| *"better to be successful than to be right"* | Bob Dalesio, email 2026 | ✅ cleared |
| *"collaboration more valuable than architecture"* (Keck) | Bob Dalesio, email 2026 | ✅ cleared |
| *"Umuntu ngumuntu ngabantu"* | Andy Götz, ICALEPCS 2023 Cape Town | ✅ public speech |
| *"Not very inspired. But easy to remember."* (TANGO name) | Jens Meyer, email 2026 | ✅ cleared |

---

## TECHNICAL ANCHOR — POC À DOCUMENTER

> **À faire avant la production de cet épisode.**

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
- [x] Citation "biodiversity" identifiée (Götz/Chaize, ICALEPCS 2007 Knoxville)
- [x] POC Tango DB + Phoebus fonctionnel
- [x] PR #3602 mergé et public
- [x] Keck Telescope anecdote identifiée (LINAC96P 1996)
- [x] Greg White (SLAC) — répondu, ajouté comme guest ✅
- [x] Marty Kraimer — année de décès 2022 confirmée et intégrée
- [x] Keck Telescope story intégrée (Bob Dalesio, email 2026) ✅
- [x] *"Better to be successful than to be right"* — Bob, intégrée wrap-up ✅
- [x] Proverbe Zulu Andy Götz (ICALEPCS 2023 Cape Town) intégré ✅
- [x] Jens — TACO mystery + community email intégré ✅
- [ ] Permissions confirmées Bob & Mike (Vancouver dinner, TCS quotes)
- [ ] Contacter Jean-Michel Chaize (SOLEIL)
- [ ] Documenter le POC (README + screen capture)
- [ ] Pousser le POC sur GitHub
- [ ] Enregistrements Q4+Q5 : Bob, Mike, Andy, Jens
- [ ] Enregistrement Greg White (EPICS 7)
- [ ] Enregistrement Jean-Michel Chaize (si accord)
- [ ] Démo visuelle POC (screen recording)
- [ ] Montage final Part 2
- [ ] Export YouTube + HTML + PDF
- [ ] Soumettre abstract POC à ICALEPCS / prochain TANGO meeting

---

*© 2025 Katy Saintin — Katy In Control. CC BY-NC 4.0.*
