# S1E03 — The Persuaders!
## TANGO & EPICS: An Origin Story
### Katy In Control — Season 1, Episode 3
### Target duration: 7–8 minutes

---

> **Production notes**
> Tone: Same as E01 & E02 — cinematic narration, Star Wars analogies, pop culture hook.
> New narrative layer: "The Persuaders!" (Amicalement Vôtre, 1971) as the episode's spine.
> Anchor anecdote: Andy Götz warming his hands before the first TANGO temperature demo.
> Interview segments: Bob Dalesio (EPICS) and Andy Götz (TANGO) — answers to be inserted
> at marked placeholders `[INTERVIEW — BOB]` and `[INTERVIEW — ANDY]`.
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

---

## ACT 1 — THE PERSUADERS

🕓
There's a British TV series from 1971 — *The Persuaders!*
If you've never watched it, picture this:
two men, wildly different in background and style,
forced to work on the same mission.

🕓
Brett Sinclair — British aristocrat, educated at the finest schools,
elegant, protocol-driven, convinced that the *right way* is the *refined way.*

Danny Wilde — self-made American, street-smart, pragmatic,
gets things done with whatever tools are at hand,
no time for ceremony.

🕓
They argue. They clash. They absolutely refuse to agree on anything.
And yet — episode after episode — they somehow solve the problem together.

🕓
Sound familiar?

🕓
TANGO and EPICS are Brett and Danny.
Born on different continents. Built on different philosophies.
And yet — powering the same particle accelerators, the same synchrotrons,
sometimes literally on the same site.

🕓
So — how did they get here?

---

## ACT 2 — EPICS: THE AMERICAN ORIGIN STORY

🕓
It's 1985. Los Alamos National Laboratory, New Mexico.
Deep in the desert. Inside a concrete building —
the team working on the Ground Test Accelerator needs a control system.
Not *a* control system. *The* control system. One that could actually scale.

🕓
At the time, virtually every laboratory in the world was building
its own custom solution from scratch.
Every. Single. One.
Completely isolated efforts. Completely reinvented wheels.

🕓
Bob Dalesio, Jeff Hill, and their colleagues at LANL thought:
*there has to be a better way.*

🕓
The idea? Build a toolkit — modular, reusable, shareable.
Not a one-off system for one accelerator.
A *platform* that any facility could adopt, adapt, and contribute back to.
Radical concept for 1985. Open source before open source had a name.

🕓
Channel Access was born in those early days —
Jeff Hill's invention, described as a "software bus."
Think of it as the holographic communication network from Episode 1 —
a protocol so well designed it's still running on production systems today,
thirty years later.

🕓
In 1989, something happened that changed everything.
Marty Kraimer from Argonne National Laboratory came to LANL for six months.
Two teams. Two labs. Different ideas. Shared code.
Out of that meeting — EPICS was born.

🕓
*[INTERVIEW PLACEHOLDER — BOB DALESIO — see question 1]*

🕓
The name *Experimental Physics and Industrial Control System*
was chosen deliberately —
to signal that this was no longer one lab's project.
It was a collaboration. A movement.

🕓
And it spread fast.
By 1991, EPICS was presented at ICALEPCS in Tsukuba, Japan.
DESY joined. CEBAF joined. KEK joined.
The snowball had started rolling.

🕓
*[INTERVIEW PLACEHOLDER — BOB DALESIO — see question 2]*

🕓
One detail from those early years that stays with me:
Before 2004, every organization that wanted to use EPICS
had to *sign an agreement.*
Over a hundred organizations signed.
Over a hundred labs, on every continent, raised their hand and said:
*yes, we want in.*
In 2004 — it became fully open source. No agreement needed. Just contribute back.

🕓
Today, EPICS runs on seven continents.
*Including Antarctica.*
If that's not a Rebel Alliance, I don't know what is.

---

## ACT 3 — TANGO: THE EUROPEAN ORIGIN STORY

🕓
Now — across the Atlantic.
Grenoble, France. The European Synchrotron Radiation Facility — the ESRF.
One of the most powerful X-ray sources on the planet.

🕓
It's 1989. Same year as the LANL–Argonne meeting.
But the approach? Completely different.

🕓
At ESRF, the concept of the *Device Server* was proposed.
Instead of thinking in terms of signals and channels —
think in terms of *objects.*
Every piece of equipment becomes a network object.
A Device. With attributes, commands, and state.

🕓
That first idea became TACO —
the ESRF's internal control system through the 1990s.
It worked. It ran the accelerator complex.
But it was built on SUN/RPC, in C —
and by the late 1990s, it was showing its age.

🕓
In 1999, the team — Andy Götz, Jean-Michel Chaize, Emmanuel Taurel,
and their colleagues — decided to rebuild everything.
Not patch it. *Rebuild it.*
On CORBA. In C++. With a clean, object-oriented design.

🕓
And that's when TANGO was born.

🕓
*[INTERVIEW PLACEHOLDER — ANDY GÖTZ — see question 1]*

🕓
The first public presentation of TANGO was at ICALEPCS 1999,
in Trieste, Italy — hosted by Elettra, another synchrotron.
The paper was signed by six people: Chaize, Götz, Klotz, Meyer, Perez, and Taurel.
Six people. One paper. The founding act of a community that now spans 50+ sites.

🕓
And then — this is the part I love —
SOLEIL, the French national synchrotron, was being designed.
From the ground up.
And they called ESRF and said: *we're in.*
In 2002, SOLEIL and ESRF officially co-developed TANGO together.
Then ALBA in Spain. Elettra in Italy. DESY in Germany.
The Empire had found its builders.

---

## ACT 4 — THE ANECDOTE

🕓
Now. I promised you a story.

🕓
This one was shared with me by Andy Götz himself.

🕓
It was one of the very first live demonstrations of TANGO.
The team had written a device server for a temperature sensor.
Sounds simple, right? Read a temperature. Display it on screen.

🕓
The moment of truth: the demo is running.
Andy approaches the sensor and — I'll let him tell you the rest.

🕓
*[INTERVIEW PLACEHOLDER — ANDY GÖTZ — see question 3 — the temperature demo anecdote]*

🕓
That moment — a number changing on a screen, driven by a human hand —
is the exact same moment every control system engineer lives for.
The first time the system *sees* the real world.
It's not glamorous. But it's everything.

---

## ACT 5 — TWO WORLDS, ONE MISSION

🕓
So here we are. 2025.
EPICS is 36 years old. Running on every continent.
TANGO is 26. Adopted by 50+ sites across Europe, Asia, and beyond.

🕓
And they're not competitors anymore — if they ever really were.
They speak to each other. Literally.
TANGO ships a device server that can read EPICS Process Variables directly.
Some facilities run both, side by side.

🕓
At my lab — the IRFU at CEA — we have MUSCADE, our own in-house system,
supervising equipment from both worlds simultaneously.
Because the real world doesn't care which framework you chose in 1999.
It just needs the uptime.

🕓
*[INTERVIEW PLACEHOLDER — BOB DALESIO — see question 4]*
🕓
*[INTERVIEW PLACEHOLDER — ANDY GÖTZ — see question 4]*

---

## WRAP-UP

🕓
So — what's the lesson from Brett Sinclair and Danny Wilde?

🕓
They didn't succeed *despite* their differences.
They succeeded *because* of them.
The British aristocrat brought structure, precision, elegance.
The self-made American brought speed, pragmatism, resilience.
Together — they got the job done.

🕓
TANGO brought object-oriented thinking, commands, and device abstraction
to a world that didn't know it needed them.
EPICS brought a sharing culture, a software bus,
and a collaboration model that became a template for all of open science.
Together — they run the particle accelerators that map the structure of matter.
The fusion reactors that might power our future.
The telescopes that look back to the beginning of time.

🕓
And they were both built by human beings
who sat in rooms, argued about protocols,
and had one singular, shared obsession:
*make the machine work.*

🕓
*[INTERVIEW PLACEHOLDER — BOB DALESIO — see question 5]*
🕓
*[INTERVIEW PLACEHOLDER — ANDY GÖTZ — see question 5]*

🕓
In our next episode, we go deeper — into the hardware layer.
How does a SCADA actually talk to a PLC?
What is OPC-UA, and why does it matter?
Same Death Star — but this time, we go all the way down to the Droids.

🕓
Until then —
*May the uptime be with you, Padawan.*

---

## INTERVIEW PLACEHOLDERS — FULL QUESTION MAPPING

> Insert recorded or written answers at the corresponding `[INTERVIEW PLACEHOLDER]` markers above.

### For Bob Dalesio

**Q1** *(Act 2, after "EPICS was born")*
> "Bob — what was the spark? What made you and your colleagues think:
> *we need to share this, not keep it for ourselves*?
> Was there a specific moment, a specific conversation, where the idea clicked?"

**Q2** *(Act 2, after "The snowball had started rolling")*
> "Those early years must have come with real obstacles — technical, political, cultural.
> What was the hardest thing to get right?
> And what nearly killed the project before it could grow?"

**Q3** *(if Bob has an early demo anecdote of his own — optional insert)*
> "Do you remember your own 'first moment' — the first time you saw an EPICS system
> doing something real, on a real machine?
> What did it feel like?"

**Q4** *(Act 5, convergence section)*
> "TANGO and EPICS have coexisted for over 25 years now.
> Looking back — do you see them as rivals, as complements, or as something else entirely?
> And what surprised you most about how the community evolved?"

**Q5** *(Wrap-up)*
> "If a young engineer walked up to you today and said:
> 'I want to work on control systems for big science' —
> what would you tell them? What do you wish someone had told you in 1985?"

---

### For Andy Götz

**Q1** *(Act 3, after "TANGO was born")*
> "Andy — in 1999, you had a working system. TACO worked.
> The decision to rebuild everything from scratch, on CORBA, as TANGO —
> that's a big bet. What drove it?
> And how did you convince the ESRF that it was the right move?"

**Q2** *(Act 3, after the SOLEIL/ALBA expansion)*
> "Building an open-source community around a control system is one thing.
> Getting other institutions to commit to co-developing it is another.
> What was the key to making those early collaborations work?"

**Q3** *(Act 4 — the temperature anecdote)*
> "You've shared with me the story of the first TANGO temperature demo —
> where you warmed the sensor with your hands to make the reading change on screen.
> Can you tell that story in your own words?
> What was going through your mind in that moment?"

**Q4** *(Act 5, convergence section)*
> "TANGO and EPICS have both evolved enormously since 1999.
> Where do you see the real differences today — not just technically, but culturally?
> And where do you think the two communities are quietly converging?"

**Q5** *(Wrap-up)*
> "TANGO V10 came out in January 2025. Twenty-six years after the first paper.
> What does the next chapter look like?
> And what does 'success' mean for TANGO in 2035?"

---

## PRODUCTION CHECKLIST

- [ ] Record narration (main script)
- [ ] Conduct Bob Dalesio interview (written / visio / voice note — his choice)
- [ ] Conduct Andy Götz interview (written / visio / voice note — his choice)
- [ ] Insert interview segments at placeholders
- [ ] Record or generate HeyGen avatar sequences
- [ ] Add Star Wars / Persuaders visual overlays
- [ ] Export YouTube description + hashtags
- [ ] Export episode page (HTML) + PDF
- [ ] Share on LinkedIn + EPICS/TANGO forums + mailing lists

---

*© 2025 Katy Saintin — Katy In Control. Educational content: CC BY-NC 4.0.*
