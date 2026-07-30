# Alessandro Cavani — aka Kalev

**IT Support Specialist → Security Operations (in progress)**

I opened my first computer at six, along with plenty of other things that were not meant to be opened. Two decades followed of taking PCs, laptops and electronics apart to work out how they ran, putting them back together, repairing them, occasionally breaking them for good. I had a method — take it apart, watch what happens, put it back, understand it — but nothing written down and nobody teaching me.

The last 2+ years in professional IT gave that method structure. I'm now moving toward security operations, doing it with what I didn't have at six: written procedure, documented decisions, and results verified before they are published.

---

## Shipped

| Project | What it is |
|---|---|
| [`LPIEngineSim`](https://github.com/KalevIT/LPIEngineSim) | Offline-first, accessibility-focused practice exam engine for LPI certifications. One config file per exam, exam sampling weighted by the published objectives, three CI gates. Ships an engine and 40 original questions — deliberately not a question dump |

I wanted a practice simulator for LPI Linux Essentials and found the available ones poor, so I built my own. In FLOSS certification study the tooling is often the weak part.

I specified the product and the constraints; an AI assistant wrote the code. I tested it against those requirements, verified it did what I had asked for, and directed the corrections where it did not.

It runs entirely offline: no server, no build step, no dependencies, and it works from a USB stick. Accessibility was a specification rather than a retrofit — screen readers, three colour-vision palettes, dyslexia-oriented type, hideable timer, keyboard-only navigation. Sampling is weighted by the published objectives and verified across 2,000 simulated runs.

Six architecture decision records cover what was on the table, what was advised, what was decided and what each choice cost. The full history is in the repository.

---

## In progress

|Project|What it is|
|---|---|
|[`Homelab`](https://github.com/KalevIT/Homelab)|A phase-based blue-team home lab on VMware Workstation Pro, documented as a build log rather than a tutorial collection|

A controlled environment to experiment in, learn ethically, and build skills that carry into the job. I build it hands-on, with an AI assistant as a tutor rather than a substitute — the whole point is being able to explain every decision afterwards.

Four standing rules: nothing is documented before it works, every claim carries a source, evidence lives separately from narrative, and everything is sanitised before it is committed.

Six phases, each with written exit criteria that have to be met before the next one opens:

|Phase|Focus|Status|
|---|---|---|
|0|Linux and command line foundations|In progress|
|1|Networking fundamentals + Windows client|Locked|
|2|Network segmentation and firewalling|Locked|
|3|Active Directory|Locked|
|4|Log collection and SIEM|Locked|
|5|Detection engineering|Locked|

The build log is public from Phase 0, not from the point where it starts looking good. Everything that went wrong on the way is in the repository.

---

## Learning path

|Status|Certification|
|---|---|
|Completed|LPI Linux Essentials 010-160 _(Apr 2026)_|
|Completed|Cambridge English B2 First _(Dec 2025)_|
|In progress|Google Cybersecurity Certificate — Coursera|
|Next|CompTIA Security+ SY0-701|
|Later|CompTIA CySA+|

---

## Tools I use professionally

`ServiceNow` · `Windows` · `Linux` · `Git` · `PowerShell (command-line use)`

Everything else is in the lab repository, described as what it is — in progress.

---

## Beyond the terminal

I shoot film and digital photography under the name **Kalev**. Same discipline:
observe carefully, understand the light, don't rush the shot.

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alessandro_Cavani-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alessandrocavaniprofile/)
