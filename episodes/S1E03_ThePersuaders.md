# S1E03 — The Persuaders!
## TANGO & EPICS: An Origin Story
### Katy In Control — Season 1, Episode 3
### Target duration: 7–8 minutes

---

> **Production notes**
> Tone: Same as E01 & E02 — cinematic narration, Star Wars analogies, pop culture hook.
> New narrative layer: "The Persuaders!" (Amicalement Vôtre, 1971) as the episode's spine.
> NEW: Anchor anecdote — EPICS funded by the US "Star Wars" program (SDI, Reagan 1983).
> Source: Bob Dalesio, personal communication, 2025. Quote cleared for use verbatim.
> Anchor anecdote 2: Andy Götz warming his hands before the first TANGO temperature demo.
> Interview guests confirmed:
>   — Bob Dalesio (EPICS co-founder, Osprey DCS) ✅ responded, recording to be scheduled
>   — Mike Thuot (LANL — had the original idea for a SCADA for science) ✅ included by Bob
>   — Andy Götz (TANGO project lead, ESRF) ✅ responded, invited Katy to TANGO meeting
> Format: recorded video call (Zoom preferred) — each guest chooses video or audio-only.
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
But here's the part nobody tells you.

🕓
The development of EPICS was funded through what was officially called
the Strategic Defense Initiative —
Reagan's programme to put particle beam weapons in orbit
to defend against nuclear missiles.
It was nicknamed, by everyone, the *Star Wars* program.

🕓
Bob Dalesio told me this himself.
He also said it reminded him of elementary school —
where children were taught to hide under their desks in case of an atomic bomb.
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
So yes — my podcast uses Star Wars as a pedagogical analogy.
And it turns out, EPICS was literally born from the Star Wars programme.
I could not have scripted this better if I'd tried.

🕓
*[INTERVIEW — BOB DALESIO & MIKE THUOT — Q1: The spark]*
*"Bob, Mike — what was the moment where the idea shifted from a weapons programme*
*to something that would serve science? What did that conversation look like?"*

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
thirty-six years later.

🕓
In 1989, something happened that changed everything.
Marty Kraimer from Argonne National Laboratory came to LANL for six months.
Two teams. Two labs. Different ideas. Shared code.
Out of that meeting — EPICS was born.

🕓
*[INTERVIEW — BOB DALESIO & MIKE THUOT — Q2: The obstacles]*
*"Those early years must have come with real friction — technical, political, cultural.*
*What was the hardest thing to get right?*
*What nearly stopped EPICS before it could grow?"*

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
*[INTERVIEW — ANDY GÖTZ — Q1: The big bet]*
*"Andy — in 1999, you had a working system. TACO worked.*
*The decision to rebuild everything from scratch, on CORBA, as TANGO —*
*that was a serious commitment. What drove it?*
*And how did you convince the ESRF that it was the right move?"*

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

🕓
*[INTERVIEW — ANDY GÖTZ — Q2: Building the community]*
*"Getting other institutions to co-develop TANGO wasn't just technical — it was organisational.*
*What was the key to making those early collaborations actually work?"*

---

## ACT 4 — THE ANECDOTES

🕓
Now. I promised you stories.
Two of them. One from each side.

🕓
Bob Dalesio told me something that made me stop mid-sentence.
EPICS was funded by the Star Wars programme —
the Strategic Defense Initiative —
a project to put weapons in orbit and end the Cold War.

🕓
Bob compared it to hiding under a school desk during an atomic bomb drill.
Absurd. Both solutions, absurd.
But Mike Thuot looked at that programme and thought:
*we could use this to build something for science.*

🕓
I think about Einstein. I think about Marie Curie.
Neither of them set out to build a weapon.
They were chasing a fascinating problem.
EPICS is what happens when scientists get to choose what the technology becomes.
Accelerators. Synchrotrons. Fusion reactors. Gravitational wave detectors.
Medical isotope production.
That's quite a legacy for a system born under a programme about lasers in space.

🕓
*[INTERVIEW — BOB DALESIO & MIKE THUOT — Q3: First moment]*
*"Do you remember the first time you saw EPICS running on a real machine —*
*and thought: this is actually going to work?*
*What did that moment feel like?"*

🕓
And then there's Andy's story.

🕓
It was one of the very first live demonstrations of TANGO.
The team had written a device server for a temperature sensor.
Sounds simple, right? Read a temperature. Display it on screen.

🕓
The moment of truth arrived. The demo was running.
Andy approached the sensor and —
I'll let him tell you the rest.

🕓
*[INTERVIEW — ANDY GÖTZ — Q3: The temperature demo]*
*"Andy — the story of the first TANGO temperature demo.*
*You warmed the sensor with your hands.*
*Can you tell that story in your own words?"*

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
*[INTERVIEW — BOB DALESIO — Q4: EPICS and TANGO today]*
*"Twenty-five years of coexistence. Rivals? Complements? Something else?*
*What surprised you most about how both communities evolved?"*

🕓
*[INTERVIEW — ANDY GÖTZ — Q4: Convergence]*
*"Where do you see the real differences between TANGO and EPICS in 2025 —*
*not just technically, but culturally?*
*And where are the two communities quietly converging?"*

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
*[INTERVIEW — BOB DALESIO & MIKE THUOT — Q5: To the next generation]*
*"If a young engineer came to you today and said:*
*'I want to work on control systems for big science' —*
*what would you tell them?*
*What do you wish someone had told you in 1985?"*

🕓
*[INTERVIEW — ANDY GÖTZ — Q5: The next chapter]*
*"TANGO V10 shipped in January 2025. Twenty-six years after the first paper.*
*What does the next ten years look like?*
*What does success mean for TANGO in 2035?"*

🕓
In our next episode, we go deeper — into the hardware layer.
How does a SCADA actually talk to a PLC?
What is OPC-UA, and why does it matter?
Same Death Star — but this time, we go all the way down to the Droids.

🕓
Until then —
*May the uptime be with you, Padawan.*

---

## INTERVIEW STATUS & GUEST NOTES

### Bob Dalesio — EPICS co-founder, Osprey DCS
**Status:** ✅ First contact established. Recording to be scheduled (Zoom preferred).
**Format:** Video call — video or audio-only at guest's discretion.
**Key quote already confirmed (cleared for use verbatim):**
> *"Appropriately enough, the development of EPICS was funded through the 'Star Wars' program.*
> *Putting accelerators into space to defend against nuclear war.*
> *It reminded me of elementary school, where we were taught to get under our desk in case of an atomic bomb.*
> *Both patently absurd solutions. But Mike wanted a SCADA system for science*
> *and I thought it sounded like a great challenge."*
> — Bob Dalesio, personal communication, 2025

**Note:** Bob has spontaneously included **Mike Thuot** (LANL) in the conversation.
His framing: *"The questions cannot be adequately answered by one person."*
Consider a joint session Bob + Mike, then Andy separately.
Bob also mentioned historical photos from the first LANL collaboration meeting —
request access and usage rights during the call.

---

### Mike Thuot — LANL (original SCADA-for-science vision)
**Status:** ✅ Included in thread by Bob Dalesio. Awaiting direct contact.
**Role in the story:** Had the original idea that a SCADA toolkit could serve science,
not just the SDI weapons programme. The conceptual spark before Bob's engineering.
**Suggested additional question:**
> *"Mike — you were the one who saw the potential for a scientific SCADA*
> *inside a weapons programme budget.*
> *What made you believe that was possible — and worth fighting for?"*

---

### Andy Götz — TANGO project lead, ESRF
**Status:** ✅ Responded positively. **Invited Katy to present at the next TANGO meeting.**
**Format:** TBD — Zoom or in-person segment recorded at TANGO meeting.
**Opportunity:** Record a live segment at the TANGO meeting if logistics allow.
**Note:** Temperature demo anecdote confirmed as a real story — awaiting Andy's
own words on camera or voice.
**Bonus:** TANGO meeting attendance = opportunity to collect additional community
testimonials for the "Your Stories" reserved slide in the TANGO/EPICS presentation.

---

## QUESTION MAPPING — FULL LIST

### Bob Dalesio & Mike Thuot

**Q1** *(Act 2 — The spark / the SDI redirect)*
> "Bob, Mike — what was the moment the idea shifted from a weapons programme
> to something that would serve science?
> What did that conversation look like?"

**Q2** *(Act 2 — The obstacles)*
> "Those early years must have come with real friction — technical, political, cultural.
> What was the hardest thing to get right?
> What nearly stopped EPICS before it could grow?"

**Q3** *(Act 4 — First moment)*
> "Do you remember the first time you saw EPICS running on a real machine —
> and thought: this is actually going to work?
> What did that feel like?"

**Q4** *(Act 5 — EPICS and TANGO today)*
> "Twenty-five years of coexistence.
> Do you see TANGO and EPICS as rivals, complements, or something else entirely?
> What surprised you most about how both communities evolved?"

**Q5** *(Wrap-up — To the next generation)*
> "If a young engineer came to you today and said:
> 'I want to work on control systems for big science' —
> what would you tell them?
> What do you wish someone had told you in 1985?"

---

### Andy Götz

**Q1** *(Act 3 — The big bet)*
> "Andy — in 1999, you had a working system. TACO worked.
> The decision to rebuild everything from scratch, on CORBA, as TANGO —
> that was a serious commitment. What drove it?
> And how did you convince the ESRF that it was the right move?"

**Q2** *(Act 3 — Building the community)*
> "Getting SOLEIL, ALBA, Elettra to co-develop TANGO wasn't just technical — it was organisational.
> What was the key to making those early collaborations actually work?"

**Q3** *(Act 4 — The temperature demo)*
> "The first TANGO temperature demo — warming the sensor with your hands.
> Can you tell that story in your own words?
> What was going through your mind in that moment?"

**Q4** *(Act 5 — Convergence)*
> "Where do you see the real differences between TANGO and EPICS in 2025 —
> not just technically, but culturally?
> And where are the two communities quietly converging?"

**Q5** *(Wrap-up — The next chapter)*
> "TANGO V10 shipped in January 2025. Twenty-six years after the first paper.
> What does the next ten years look like?
> What does success mean for TANGO in 2035?"

---

## PRODUCTION CHECKLIST

### Pre-production
- [x] Script draft completed
- [x] Bob Dalesio contacted — first response received
- [x] Mike Thuot introduced by Bob — awaiting direct contact
- [x] Andy Götz contacted — responded positively
- [x] SDI/Star Wars anecdote confirmed and cleared for use (Bob Dalesio)
- [ ] Schedule recording session — Bob + Mike (Zoom, 45–60 min)
- [ ] Schedule recording session — Andy Götz (Zoom or TANGO meeting in person)
- [ ] Request historical photos from Bob (LANL first collaboration meeting)
- [ ] Request usage rights for ICALEPCS 2019 MOCPR02 slides & photos

### Production
- [ ] Insert interview segments at all `[INTERVIEW]` placeholders
- [ ] Record narration (main script — HeyGen digital twin)
- [ ] Edit interview audio/video segments
- [ ] Add Star Wars / Persuaders visual overlays
- [ ] Add historical photos (LANL first meeting, ESRF 1999) with credits

### Post-production & distribution
- [ ] Export YouTube description + hashtags
- [ ] Export episode page (HTML static) + downloadable PDF
- [ ] Share on LinkedIn (Katy Saintin — hook post, no link in body)
- [ ] Share on EPICS Tech-Talk mailing list
- [ ] Share on TANGO Controls mailing list / forum
- [ ] Present TANGO vs EPICS deck at TANGO meeting (Andy Götz invitation)
- [ ] Collect community testimonials at TANGO meeting (slide 11 placeholders)
- [ ] Archive on GitHub (KatyInControl/episodes/)

---

## KEY SOURCES FOR THIS EPISODE

- Dalesio L.R., Johnson A.N., Kasemir K.-U. — *"The EPICS Collaboration Turns 30"*,
  ICALEPCS 2019, New York. [MOCPR02](https://proceedings.jacow.org/icalepcs2019/papers/mocpr02.pdf)
- Bob Dalesio, personal communication, 2025 — SDI/Star Wars anecdote (verbatim, cleared)
- Chaize J.-M., Götz A. et al. — *"TANGO an Object Oriented Control System based on CORBA"*,
  ICALEPCS 1999, Trieste.
- tango-controls.org/about-us — History & founders
- epics-controls.org — Collaboration history

---

*© 2025 Katy Saintin — Katy In Control. Educational content: CC BY-NC 4.0.*
