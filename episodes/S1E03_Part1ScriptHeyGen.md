# 🎬 lines = CapCut production notes — DO NOT read aloud

Last time, we visited the Death Star.
Hardware. Communication bus. Business logic.
We even met the Droids, the holographic network, and the Emperor himself.

But here's the question nobody ever asks —
Who drew those blueprints? And why?

Today, we go back in time.
Not to a galaxy far, far away.
Into labs. Conference corridors. And a dinner that changed history.

Oh — and fair warning.
This origin story involves space.

Star Wars.
Star Trek.

... ...

Both of them.
Not as analogies.
As actual historical facts.

...

Yeah. Really.

But before we go any further —
let's put the lightsaber down for a moment.

Because to understand how all of this started,
we're taking a detour through the TV shows of our nostalgic years.

There we go. Far from Star Wars.

...

Well. Almost.

Because as it turns out —
Star Wars never really left.
Not as an analogy.
And not as... funding.

But we'll get to that.

The Persuaders! — British TV series, 1971.
If you don't know it — picture James Bond
meeting an American who refuses to wear a tuxedo.
And since Roger Moore IS James Bond at the time...
you get the idea.

Brett Sinclair — British aristocrat.
Elegant. Precise. Convinced that the right way to do things
is HIS way to do things.

Danny Wilde — self-made American.
Pragmatic. Efficient. Convinced that if it works, it's the right method.
Tuxedo optional.

Together — they bicker about everything.
But they never really fight.
It's a friendly rivalry. Permanent.
Slightly exhausting for everyone around them.
And they solve every problem. Together.

TANGO and EPICS are Brett and Danny.

EPICS asks: Does it work?
TANGO asks: Is it beautiful?

A friendly rivalry that has been going on since 1989.

So — how did we get here?

New Mexico. 1982.
A small startup called CPRC. Based in Maryland.
Nuclear reactors. Industrial applications. Serious stuff.

A young engineer joins as lead developer.
He builds a toolkit — modular, reusable, practical.
He calls it TCS.
The Control System.

No branding. No marketing.
Just: what it does.

Danny Wilde would have approved.

In 1985, Los Alamos National Laboratory needs a control system.
CPRC wins the bid.
Bob Dalesio shows up at the lab.
With TCS already in his bag.
He never really left.

Now. The project Bob joined at Los Alamos —
the Ground Test Accelerator —
was part of Reagan's Strategic Defense Initiative.

You know it as the Star Wars program.

Not the Jedi kind.

... ...

The other one.
Neutral particle beam weapons. In orbit.
To identify and neutralise nuclear warheads among their decoys.

Bob compared it to hiding under a school desk
during an atomic bomb drill.
"Both patently absurd solutions."

But inside that programme —
Mike Thuot had a completely different idea.
He didn't want to build weapons.
He wanted a SCADA system. For science.

And Bob thought —
that sounds like a great challenge.

That's how it started.
Not with a grand vision.
With one engineer thinking: yeah, I'll take that problem.

The system went through three names.
TCS. Then GTACS. Then LAACS —
because the Army didn't want the work
publicly linked to the weapons programme.

Then something happened that changed everything.

At a conference in Vancouver in 1989 —
a researcher from CERN stood up
and put a number on the screen.

120 to 160 man-years.

That's how long it took every major science project in the world
to build its own control system.
From scratch. Alone. Every time.

Translation: everybody reinvented the wheel.

... ...

A VERY expensive wheel.

That evening, over dinner,
Mike Thuot's group met Marty Knott from Argonne National Laboratory.
And they said: there's a better way.

A shared toolkit. Open. Built by everyone. For everyone.
No more 160 man-years, alone, in the dark.

That dinner conversation was the founding act of the EPICS collaboration.

Argonne sent Marty Kraimer to Los Alamos to study the system.
Six weeks planned.

Marty walked into Bob's office
with a four-inch print-out of the source code.
At least forty annotations in red.

Some people bring coffee.
Marty brought forty red comments.

They went through it together.
One question at a time.

After what felt like hours — or maybe days —
Bob looked up and said:

"We don't have to work together."

... ...

...which is probably not the sentence Marty expected.

Marty looked up, slightly surprised.
And said: I think this is great.
I MOST DEFINITELY want to work together.

From that moment — they were a team.

I know this because Bob Dalesio told me himself.
He described Marty as patient. Very patient.
Because Bob had not yet decided if anyone —
and here I quote — "even Marty" —
would be allowed to modify his database code.

It was Mike Thuot who sat down with Bob
and presented him with two futures.
"Your code stays yours. It runs on this one project.
Or — you let qualified people work with you.
And it runs on everything."

Bob made the right choice.
And the rest is EPICS.

The result clearly needed a new name.
Something that reflected both labs.
Something bigger than Los Alamos.

Experimental Physics and Industrial Control System.

Bob added "Industrial" himself —
from his years in oil fields, steel plants, nuclear reactors.
He knew this system was better than anything the industrial world had built.

EPICS. Finally.

Marty Kraimer passed away in 2022.
Jeff Hill — who invented Channel Access,
the networking protocol at the heart of EPICS —
recently retired.
Bob is heading towards retirement too.

The code they wrote together
is still running on production systems today.
That's the only kind of immortality engineers get.
And honestly — it's not a bad one.

Meanwhile... in Grenoble.

The European Synchrotron Radiation Facility — the ESRF.
One of the most powerful X-ray sources on the planet.
Nestled at the foot of the Alps.
Funded by seventeen European countries.
Very. European.

And yes — the Alps are right there.
I know this because the last time I visited,
Andy, Manu and Pascal mentioned — casually —
that they sometimes go skiing between two meetings.

Between. Two. Meetings.

I suspect there is a hidden TANGO protocol called SkiAccess.
But I haven't found it in the documentation yet.

...

If Los Alamos was Danny Wilde —
desert, pragmatism, let's just make it work —
Grenoble is very much Brett Sinclair.
Elegant surroundings. High standards.
A very strong opinion about the right way to do things.
And apparently — excellent ski conditions year-round.

Danny fixes the engine.
Brett writes the owner's manual.

Same year as the Vancouver dinner. 1989.
Different continent. Completely different mindset.

At ESRF, the question wasn't
"how do we share what we've built?"

It was:
"How do we model the world?"

Their answer: every piece of equipment is an object.
Not a signal. Not a register. An OBJECT —
with attributes, commands, and a state.
They called it a Device Server.

Now — a word about acronyms.

Scientists are either very good at acronyms,
or catastrophically bad at them.
There is no middle ground.

The working theory is that they find the word first —
and then reverse-engineer a meaning.
Nobody has officially confirmed this.
But nobody has officially denied it either.

Exhibit A: TACO.
Telescope and Accelerator Control Objects.
The ESRF's first control system. Born in 1991.

I joined SOLEIL in 2004.
I worked with TACO for years.
In French, "taco" also means an old, battered car.
A jalopy. Something you wouldn't trust on a motorway.

It also means the Mexican food.
I never knew which one the team had in mind.
And I had absolutely no idea what the acronym actually stood for.

Jens Meyer just told me.
Thirteen years later.

... ...

Mystery. Solved.

Then came TANGO.
Telescope and Accelerator Next Generation Objects.

Inspired — NOT by Star Wars, as Jens was careful to point out —
but by Star Trek: The Next Generation.

Jens's verdict:
"Not very inspired.
But easy to remember.
And nobody cares what it stands for."

...

Meanwhile, at Los Alamos —
Bob Dalesio had named his system TCS.
The Control System.
No Star Trek. No Star Wars. No food references.
Just: what it does.

Star Wars funded EPICS.
Star Trek inspired the name of TANGO.
And I'm explaining both of them with a Death Star analogy.

I could not have planned this.

And the synchrotron where I learned all of this?

Which stands for —

Which means, for our English-speaking friends:
Optimised Source of Intermediate Energy Light — from LURE.

And LURE —

Which means:
Laboratory for the Use of Electromagnetic Radiation.

...

It's acronyms all the way down.

TACO became the ESRF's internal control system through the 1990s.
It worked. It ran the accelerators.
But by the late 1990s — it was showing its age.
Built in C. On SUN/RPC.

Which, if you don't know what that means —
just imagine trying to run TikTok on a Minitel.

If you're under thirty...

...

...ask your parents what a Minitel was.

So in 1999, the team made a decision.
Not a patch. Not an upgrade.
A complete rebuild. From scratch.

Andy Götz. Jean-Michel Chaize. Emmanuel Taurel.
Jens Meyer. And two others.
Six people. One blank sheet.

Jens Meyer joined the ESRF in 1991 —
years before TANGO existed.
In 1991, nobody had a clear idea of which technology to use.
Communication protocols were mainly homemade.
They tried a lot of things.

Which means the decision to rebuild everything as TANGO in 1999
was not a leap of faith.
It was the result of ten years of trying, failing, and learning.
They knew what they wanted
because they had already built what they didn't.

They presented the result at ICALEPCS 1999 —
in Trieste, Italy. At Elettra, another synchrotron.
Six names on one paper.
The founding act of a community
that now spans fifty facilities worldwide.

And then — this is the part I love —
SOLEIL, the French national synchrotron,
was being designed from scratch.
They called ESRF and said: we're in.
Then ALBA in Spain. Elettra in Italy. DESY in Germany.

Brett Sinclair had found his team.

Now. The stories nobody writes in the papers.

Every control system engineer has one.
That moment.
The first time the system does something real.
On a real machine.
And you think —

... ...

this is actually going to work.

Mike Thuot kept the documents.
Files from 1996. Speeches from the fifteenth anniversary of EPICS.
He sent them to me without hesitation.

Bob described that era simply:
"Trust in a shared goal.
Open discussions on all issues — technical and political.
With the tone set, others that wanted to work
in that environment joined us."

Not a manifesto. Not a governance document.
A tone. And an invitation.

And then there's Andy's story.

It was one of the very first live demos of TANGO.
The team had written a device server for a temperature sensor.

Simple, right?
Read a temperature. Display it on screen.

Except — nothing was moving on screen.
The sensor was reading room temperature.
Stable. Flat. Boring.

So Andy did what any self-respecting engineer
would do in that situation.

... ...

He grabbed the sensor with both hands.
And waited.

And on the screen —
a number started to change.

This story reached me through two people
who were both in the room that day.
Andy Götz, who grabbed the sensor.
And Alain Buteau — my mentor at SOLEIL —
who watched it happen.

Alain was the one who told me first.
Laughing, the way you laugh at something
you've never forgotten in twenty-five years.

Sometimes innovation starts with sophisticated mathematics.

...

Sometimes...

...

...you just warm the sensor with your hands.

That moment.
A number changing on a screen.
Driven by a pair of human hands wrapped around a sensor.

It's not glamorous.
Nobody writes a proceedings article about it.

But every engineer in this community
has lived a version of that moment.

The first time the system sees the real world.

That's why we do this.

So. What have we learned today?

On one side — a startup engineer from New Mexico.
A system called TCS. A weapons programme budget.
And a dinner in Vancouver that changed everything.

On the other — six people in Trieste.
A blank sheet. A bet on objects.
And ski slopes ten minutes from the office.

Two teams. Two continents. Two philosophies.
One shared obsession.

Make the machine work.

Brett and Danny didn't succeed despite their differences.
They succeeded because of them.

And so did EPICS and TANGO.

In Part 2 —
we ask the harder question.

Not where these systems came from.
But who carries them forward.

Because Jens Meyer told me something
that I haven't been able to stop thinking about.
He still has some time before retirement.

Bob Dalesio too.
Jeff Hill just retired.
Marty Kraimer passed away in 2022.

This generation built the systems
that run the world's accelerators.
The synchrotrons. The fusion reactors. The telescopes.

And they're passing the baton.
Right now.
Not in ten years.
NOW.

Which means this is exactly the right moment
to sit down with them and ask —
what do you wish you'd written down?

That's what Part 2 is about.
And there's one word in it —
said in 2007, in a conference room in Knoxville —
that explains everything.

You'll see.

In the meantime —
there's a new generation of Padawans out there.
Engineers, students, curious minds
who've never heard of Channel Access.
Who don't know what a Device Server is.
Who have no idea that the system controlling their synchrotron
was born in a New Mexico desert,
under a weapons programme,
over dinner drinks in Vancouver.

Bob, Mike, Andy, Jens —
they are the Masters.

... ...

And it's time to train a new generation of Padawans.

That's why we're here.

May the uptime be with you, Padawan.