# Studio Charter: Movie Script Analyzer

> Filled in live during the **Studio Charter** session in week 3. Every section below is committed in the same commit at the end of that class block. See [Studio Charter (single-session inception)](https://courses.lpcordova.phd/data510/project-framework/charter-inception.html) for the script and time-boxes.

**Owner team:** Dylan Ray
**Owner Product Lead:** Dylan Ray
**Peer Stakeholder POs:** Sophia Rabbanian, Tiffany Truong,	Courtney St. Onge
**Instructor / Sponsor:** Lucas Cordova (`LucasCordova` on GitHub)
**GitHub repo:** (https://github.com/DylanR-hash/data510-capstone/edit/main/README.md)
**GitHub Projects board:** 	https://github.com/users/DylanR-hash/projects/1
**Discord category:** Group 11
**Studio Session:** 1
**Studio formed:** 5/25/26

## Vision

My movie script analyzer would be a tool to help studios evaluate movie scripts for usability. It would also be used to help movie writers improve their scripts to increase the chances that their idea will get picked up by a big studio.

## Mission

Able to help screen writers to be able to improve their scripts and have a higher chance of the studio buying their idea. Also gives the studio a better way to figure out how to choose a script out of a batch of different ideas to increase the chances of a good one being found.  

## Context

- **Users / affected parties:**
- Benefits:
- Improve writing
- More cohesive idea of the story
- Risk:
- Might not improve what the studio may want
- May take a beat to analyse a longer script
- The more obscure the idea, the model may not like it if there is nothing to compare to
- Who Might Use: Studio executives, screenwriters, writing professors/teachers
- **Data sources (proposed):**
- https://www.simplyscripts.com/movie-scripts.html#google_vignette(Where I am downloading the scripts)
- **Constraints:**
- The amount of time I can focus on this one project
- How well the model will take to different scripts
- How much data can my computer hold of movie scripts
- **Ethics risks:**
- Taking scripts from writers without their permission
- Might not correlate to profit even if the script is good

## Success criteria by milestone

- **M1, proposal (W4):** Have an idea of what is needed to start the project
- **M2, data summary (W7):** Be able to read and analyze a short script created by AI
- **M3, poster rough draft (W10):** Able to do it on real script
- **M4, write-up rough draft (W12):** <measurable criterion>
- **M5, final write-up and poster (W14):** <measurable criterion>

## Working agreements (internal to owner team)

- **Sync rhythm:** Working by myself
- **Code review:** Myself
- **Decision rule:** Me

## Working agreements (triad with peer POs)

- **Studio Brief due:** Submit the Brief before 6 pm on Monday before class
- **Studio Critique due:** Submit the Critique before 6 pm on Monday before class
- **Priority conflict resolution:** We will discuss and collaborate on a solution, and each person will discuss their problem and why it's important  

## Response SLAs (Service Level Agreements)

A **Service Level Agreement** is a written promise the triad makes about *how fast* each side responds when a specific signal arrives. Every row must have an answer before this Charter is committed. See [Response SLAs](https://courses.lpcordova.phd/data510/project-framework/charter-inception.html#response-slas-service-level-agreements) for the full definition.

| When this signal arrives... | Who responds | By when |
|-----------------------------|--------------|---------|
| Peer PO files a **Studio Brief** (commits to `studio/briefs/...`, links in `#<project>-studio`) | Owner team | <e.g., acknowledge in `#<project>-studio` within 24 hours, with a first-pass adopt / defer / decline call for each item> |
| Peer PO files a **Studio Critique** | Owner team | <e.g., respond in `#<project>-studio` within 24 hours and capture follow-up items into the backlog> |
| Owner team posts an **Iteration Review** in `README.md` | Both peer POs | <e.g., read before filing the next Brief and Critique> |
| Owner team flags a **blocker** in `#<project>-blockers` | Instructor, plus any tagged peer PO | <e.g., responds by the next Studio Session at the latest; faster if online> |
| Anyone asks a clarifying question in `#<project>-general` | Whoever is tagged (default: owner team) | <e.g., reply within 48 hours, even if the reply is "we will look at this next iteration"> |

## Definition of Ready (PBI)

A PBI is ready to be pulled out of `Backlog` and moved into `Create` when it has:

- A one-sentence hypothesis or user story.
- A named **Create**, **Observe**, **Analyze** triple.
- A milestone tag (`M1-proposal`, `M2-data-summary`, `M3-poster-draft`, `M4-writeup-draft`, `M5-final`, `infra`, `ethics`).
- A T-shirt size estimate (S, M, L, XL).
- WIP slack on the board: `Create + Observe + Analyze` is below the team's WIP cap (owners + 1).

## Definition of Done (PBI)

A PBI is done, and may be moved from `Analyze` into `Done`, when:

- The Create artifact is in the repo or linked from the issue.
- The Observe results are recorded somewhere referenceable (notebook output, processed dataset, draft results section).
- The Analyze writeup names a next step (continue, pivot, kill, or decompose into new PBIs).
- A peer PO has either signed off in `#<project>-studio` or filed a Studio Critique covering it.
- The card is linked under *Completed PBIs* in the next Iteration Review in `README.md`.

## Context map

> Optional. Replace this block with a Mermaid `flowchart LR` showing how users, data, constraints, and ethics risks flow into the owner team and out to the capstone outcome. See the [`charter-inception.qmd` template](https://courses.lpcordova.phd/data510/project-framework/charter-inception.html) for a starting Mermaid diagram.

## Stakeholder alignment memo (one-page summary)

### Why we exist
My movie script analyzer would be a tool to help studios evaluate movie scripts for usability. It would also be used to help movie writers improve their scripts to increase the chances that their idea will get picked up by a big studio.

### What we will deliver to peer POs every week
- An Iteration Review in this `README.md` by <day / time>
- A summary of which Studio Brief items we adopted, deferred, or declined and why

### What we need from peer POs every week
- A Studio Brief by <day / time> next class (next iteration's requirements, questions, risks)
- A Studio Critique by <day / time> next class (assessment of last week's delivery)

### How to reach us
- Discord category: `#<project>-general` (day-to-day), `#<project>-studio` (Briefs and Critiques), `#<project>-blockers` (impediments)
- GitHub repo: <link>
- GitHub Projects board: <link>
