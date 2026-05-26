# S1E02 Same Death Star, Different blueprintsTANGO & EPICS are

Previously , in the episode 1
🕓 We explored the three layers of a SCADA system — through the lens of Star Wars. Droids on the ground, holographic networks in the middle, and the Emperor pulling all the strings at the top.
🕓 Now, We’re going to look at two of the most powerful control frameworks used in big science facilities around the world — EPICS and TANGO. And we’re going to compare them, side by side, layer by layer

## [LAYER 1 — Hardware — The Droids]
🕓
Let’s start at the ground level. The Droids. The sensors and actuators that measure and act on the physical world.
In both EPICS and TANGO, this is where the real universe begins — the raw data coming from your equipment. A temperature. A pressure. A beam position, and so on.
But here’s where the two systems start speaking different languages.

🕓In EPICS, that raw measurement has a name — it’s called a Process Variable, or PV. Short, simple, efficient. Very much like a Droid serial number — R2-D2, C-3PO. You know exactly what you’re talking about, no ambiguity.

🕓In TANGO, the equivalent is called an Attribute. Same idea — a value you can read from the physical world — but the philosophy behind it is slightly different, as we’ll see in a moment.

🕓So remember : Droids report data. In EPICS, that data point is a PV. In TANGO, it’s an Attribute. Two names, same mission — tell the rest of the system what’s happening on the ground

## [LAYER 2 — Communication Bus — The Holographic Network]
🕓
Now, how does that data travel up the chain ? Through the holographic network — the communication bus. And this is where EPICS and TANGO really start to diverge.🕓

On the EPICS side, the protocol is called Channel Access — or its newer version, PV Access.🕓
Channel Access is the classic. It’s been around since the late 1980s, and it’s still powering some of the largest physics facilities on the planet. 
🕓Here’s how it works : imagine the Emperor’s hologram network is always on standby. A client — say, Luke Skywalker at his console — subscribes to a channel. He says : ‘I want to know every time the temperature in reactor four changes.’ And from that moment on, the network pushes updates to him automatically, the moment something changes. That’s called a publish

subscribe model. Efficient, responsive, and very scalable.


🕓PV Access is the modern evolution — faster, more flexible, better suited for complex data structures. Think of it as upgrading from that flickering blue hologram to a full HD transmission.

🕓On the TANGO side, things get philosophically interesting. TANGO has used two different communication approaches over the years.🕓
The first one is CORBA. Now, CORBA is a bit like sending a messenger droid across the galaxy and waiting for it to come back. It works on a polling model — the client regularly asks : ‘Hey, what’s the current value ?’ And the server answers. It’s reliable, structured, very formal — very Imperial, if you will. But it can feel a little slow when you need real-time responsiveness.🕓
The second one — and the more modern approach — is ZeroMQ, or ZMQ. This one is event-driven. Instead of constantly asking for updates, the server says : ‘Something just changed — here’s the new value, right now.’ No waiting. 

No polling. Pure reactivity. It’s like switching from sending messenger droids to having a direct Force connection between sender and receiver. 🕓 Such as EPICS transmission indeed.

🕓So to summarize the network layer : EPICS talks through Channel Access — subscribe and receive. TANGO started with CORBA — ask and wait — and evolved toward ZMQ — feel the change the moment it happens.

## 🕓[LAYER 3 — Business Logic — Darth Vader & The Emperor]🕓
“And now — the brain. Darth Vader and the Emperor. The layer that makes all the decisions.🕓
On the EPICS side, this is called an IOC — an Input Output Controller.
Think of it as Darth Vader’s command ship. It’s a software program — running on a server — that acts as the bridge between the physical world and the rest of the system. The IOC knows about all the Process Variables under its responsibility. It makes them accessible to anyone on the network — either in read, or in write. You want to know the current temperature ? The IOC gives it to you. You want to change a setpoint ? You write to the IOC, it handles the rest. 

We’ll get into the details of how that works in a future episode — there’s a lot to unpack there.🕓
It’s powerful, it’s robust, and it’s been battle-tested in some of the most demanding environments on the planet — particle accelerators, fusion reactors, space telescopes.

🕓On the TANGO side, the equivalent is called a Device Server — or simply a Device.
Same core idea — a program that sits between the hardware and the network, exposing data for reading and writing. Your Attributes are accessible, just like EPICS PVs.
But here’s where TANGO adds something extra — something EPICS doesn’t have natively. TANGO Devices don’t just expose data. They also expose Commands.🕓
And Commands are powerful. 
A Command can be something simple — like a write shortcut : ‘Turn on’, ‘Turn off’. One call, one action. But a Command can also trigger a full sequence of operations — a complex choreography of actions happening in the right order, at the right time. 

Think of it as the difference between telling a Stormtrooper ‘fire’ — simple, direct — versus telling Darth Vader ‘execute Order 66’ — which sets an entire chain of events in motion across the galaxy.
That’s the TANGO Command. One call. Potentially a lot of consequences.”

## 🕓[WRAP UP] 🕓
“So here’s your side-by-side summary :
At the hardware level — EPICS measures Process Variables, TANGO measures Attributes. Same Droids, different name tags.🕓
At the network level — EPICS uses Channel Access, subscribe and receive. TANGO uses CORBA for structured polling, and ZMQ for real-time events. Same holographic network, different transmission protocols.🕓
At the brain level — EPICS runs IOCs, powerful controllers that expose PVs either in read or in write. TANGO runs Device Servers, which do the same — but go one step further with Commands that can trigger simple actions or complex sequences.🕓
Same mission. Same three layers. Two different ways of running the Death Star.


And speaking of origins — in the next episode, we’re going to travel back in time. Because every great system has an origin story. Where did TANGO come from ? Who built EPICS, and why ? Two frameworks, two histories, two teams of people who decided to solve the same problem — in their own way. That story is coming up next.🕓
May the uptime be with you Padawan.” 🕓
