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