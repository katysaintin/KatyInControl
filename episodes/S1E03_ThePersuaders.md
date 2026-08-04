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
> Interview guests for Part 1:
>   — Bob Dalesio (EPICS co-founder, Osprey DCS) ✅ responded, recording to be scheduled
>   — Mike Thuot (LANL — original SCADA-for-science vision) ✅ in thread via Bob
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

🕓
It's 1985. Los Alamos National Laboratory, New Mexico.
Deep in the desert.
The team working on the Ground Test Accelerator needs a control system.
Not *a* control system. *The* control system.

🕓
But here's the part nobody tells you.

🕓
The development of EPICS was funded through the Strategic Defense Initiative —
Reagan's programme to put particle beam weapons in orbit.
Nicknamed, by everyone, the *Star Wars* program.

🕓
Bob Dalesio told me this himself.
He said it reminded him of elementary school —
children taught to hide under their desks in case of an atomic bomb.
His words: *"Both patently absurd solutions."*

🕓
And then — a man named Mike Thuot had a different idea.
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
*[INTERVIEW — BOB DALESIO & MIKE THUOT — Q1]*
*"What was the moment the idea shifted —*
*from a weapons programme to something that would serve science?"*

🕓
The idea: build a toolkit — modular, reusable, shareable.
Open source before open source had a name.
Channel Access — Jeff Hill's invention —
a protocol so well designed it still runs on production systems today.

🕓
In 1989, Marty Kraimer from Argonne came to LANL for six months.
Two teams. Two labs. Shared code.
Out of that meeting — EPICS was born.

🕓
*[INTERVIEW — BOB DALESIO & MIKE THUOT — Q2]*
*"What was the hardest thing to get right?*
*What nearly stopped EPICS before it could grow?"*

🕓
Today, EPICS runs on seven continents. Including Antarctica.
If that's not a Rebel Alliance, I don't know what is.

---

## ACT 3 — TANGO: THE EUROPEAN ORIGIN STORY

🕓
Grenoble, France. The European Synchrotron Radiation Facility — the ESRF.
1989. Same year as the LANL–Argonne meeting.
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
And Jens Meyer — who is in this episode.

🕓
Six people signed that founding paper.
Presented at ICALEPCS 1999, in Trieste, at Elettra.
The founding act of a community that now spans 50+ sites.

🕓
*[INTERVIEW — ANDY GÖTZ — Q1]*
*"The decision to rebuild everything as TANGO —*
*what drove it? How did you convince the ESRF?"*

🕓
*[INTERVIEW — JENS MEYER — Q1]*
*"Jens — you were in that room in 1999.*
*What do you remember of those early days?*
*What was it like to build something nobody had done before?"*

🕓
Then SOLEIL joined. Then ALBA. Then Elettra. Then DESY.
The Empire had found its builders.

🕓
*[INTERVIEW — ANDY GÖTZ — Q2]*
*"What was the key to making those early collaborations actually work?"*

---

## ACT 4 — THE FIRST MOMENTS

🕓
Now. The stories nobody writes in the papers.

🕓
EPICS, funded by a weapons programme.
Mike Thuot redirecting that budget toward science.
Bob comparing it to hiding under a school desk.

🕓
I think about Einstein. I think about Marie Curie.
Neither set out to build a weapon.
They were chasing a fascinating problem.
EPICS is what happens when scientists get to choose
what the technology becomes.

🕓
*[INTERVIEW — BOB DALESIO & MIKE THUOT — Q3]*
*"The first time you saw EPICS running on a real machine —*
*what did that moment feel like?"*

🕓
And then there's Andy's story.
A device server for a temperature sensor.
The demo is running. Andy approaches the sensor —
I'll let him tell you the rest.

🕓
*[INTERVIEW — ANDY GÖTZ — Q3: the temperature demo]*

🕓
*[INTERVIEW — JENS MEYER — Q3]*
*"Jens — do you have a moment like that?*
*A first time the system did something real,*
*and you thought: this is actually going to work?"*

🕓
That moment — a number changing on a screen, driven by a human hand —
is the moment every control system engineer lives for.
The first time the system *sees* the real world.

---

## WRAP-UP PART 1

🕓
We've met the people who built the blueprints.
Bob and Mike in the New Mexico desert.
Andy, Jens, Jean-Michel and their colleagues in Grenoble.

🕓
Two teams. Two continents. Two philosophies.
And one shared obsession: *make the machine work.*

🕓
In Part 2, we ask the harder question —
not where these systems came from,
but where they're going.
And who will carry them forward.

🕓
*May the uptime be with you, Padawan.*

---

## PRODUCTION CHECKLIST — PART 1

- [x] Script draft completed
- [x] Bob Dalesio contacted ✅
- [x] Mike Thuot in thread ✅
- [x] Andy Götz contacted ✅
- [x] Jens Meyer responded on mailing list ✅
- [x] SDI/Star Wars anecdote cleared for use (Bob Dalesio)
- [ ] Schedule recording — Bob + Mike (Zoom, 45 min)
- [ ] Schedule recording — Andy Götz (Zoom)
- [ ] Schedule recording — Jens Meyer (Zoom, before retirement)
- [ ] Insert interview segments at all placeholders
- [ ] Record narration (HeyGen digital twin)
- [ ] Edit + mix
- [ ] Export YouTube + HTML + PDF
- [ ] Post LinkedIn / EPICS Tech-Talk / TANGO mailing list

---

*© 2025 Katy Saintin — Katy In Control. CC BY-NC 4.0.*
