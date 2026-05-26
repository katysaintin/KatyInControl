# S1E01 - Understand SCADA, you must, EPICS and TANGO revealed - 7 minutes

But before we explore both galaxies 
Let’s make sure we speak the same language.
Because in my experience, half of the debates between EPICS and TANGO people are actually debates about words, not technology.
So — what is a SCADA, really?

SCADA stands for Supervisory Control and Data Acquisition. But behind this acronym hides something much more fundamental: it’s the nervous system of your entire facility.

Think of it as the Force itself — invisible, everywhere, connecting everything. Your hardware, your operators, your data, your alarms. When it works, nobody notices. When it fails — everyone does.

A SCADA is not just software. It’s an architecture — three layers: hardware, communication bus, and business logic. It’s a protocol, a configuration system, a set of services like archiving and alarms. And crucially — it’s a community. Because no SCADA survives without the people behind it.


## SCADA explained with Star Wars

So… you still have absolutely no idea what that means. Don’t worry. Neither did I at first. So today, I’m going to explain it to you using the most universal reference in the universe — and I mean that literally — Star Wars.

Imagine the Death Star, and just think of it as the most complex control system ever built. That’s basically what a SCADA is. A system that monitors, controls, and manages everything happening in a facility, such as a power plant, a factory, a particle accelerator. Everything.”
“A SCADA has three main layers. And we’re going to walk through each one


## First layer : the hardware.

The physical world. The stuff you can actually touch.
Think of this as the Droids on the ground. They’re the ones doing the actual work — measuring things, opening doors, pushing buttons. They don’t think much. They just execute orders and report back what they see.
In the real world, this is your sensors, your motors, your valves, your industrial controllers. One sensor checks if a pipe is too hot. Another one measures pressure. Another one controls a pump. Just like a Droid reporting back to base — ‘All clear in corridor seven.’
They’re not smart. But without them, you are completely blind.

## Second layer : the communication bus.

And this one is my favourite analogy.
You know how in Star Wars, the Emperor can talk to Darth Vader from across the galaxy, through that holographic communication system ? That blue, flickering hologram thing ? That’s your communication bus.
It’s the invisible highway that carries information between the ground level — your sensors and machines — and the brain of the system. It goes both ways : data comes up, orders go down.
And here’s the thing — if that communication network goes down ? It’s like destroying Alderaan. For those who haven’t seen Star Wars — Alderaan is a peaceful, beautiful planet that gets completely wiped out in seconds, without warning. That’s exactly what happens to your system when the network fails. Everything stops. Instantly. 

No data, no control, no nothing.
So yeah — your network cables and communication protocols ? They’re more important than they look.”

## Third layer : the business logic. 

The brain. The decision maker.
This is the Emperor and Darth Vader. The Emperor sits at the top — he sees everything, knows everything, and decides everything. That’s your SCADA server. It collects all the data coming from the ground, processes it, and decides what to do.
Darth Vader is your real-time supervisor — he takes those decisions and makes sure they’re executed, immediately, with no discussion.
In practice, this is where the magic happens. This layer manages your alarms — like when Luke Skywalker triggers the Death Star’s alert system by flying too close. It stores your historical data — like the Jedi Archives, everything is recorded, even the things you’d rather forget. 

And it gives your operators a full dashboard to monitor everything — just like the Death Star control room, with all those blinking screens and consoles.

## Wrapup

So let’s bring it all together.
Your Droids collect data on the ground. That data travels through the holographic network — your communication bus. And it all ends up at the Emperor’s throne room — your SCADA server — where decisions are made and sent back down.
Hardware. Communication. Business logic.
Three layers. One Death Star. And hopefully — unlike in the movies — yours won’t be taken down by a single well-aimed shot from Luke Skywalker

## In the next episodes

If you want to go deeper on any of these layers, I’ll be interviewing the actual experts who build these systems — the people behind projects like Tango, EPICS, and SCADA platforms used in some of the world’s most advanced facilities. Stay tuned — and may the uptime be with you, Padawan

And that’s a wrap for this episode, young Padawan. I hope the Force of knowledge is a little stronger with you now — and that SCADA systems feel slightly less like the dark side of engineering.

In our next episode, we’ll see how these three layers come to life in two of the most powerful control frameworks in the galaxy — TANGO and EPICS. Same Death Star. Different blueprints.

