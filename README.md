**English** · [Français](README.fr.md)

# The Worst Roommate

An urban psychological survival game. Every evening, you come home to the studio flat. Household chores become a ritual where anxiety builds up. Your choices shape a full week of dynamic events, with multiple endings and an unpredictable roommate.

- Genre: psychological survival, narrative
- Setting: an urban flat, everyday life going off the rails
- Game loop: 7 days (come home, manage, watch, rest)
- Engine: Unreal Engine 5
- Platform: PC
- Visual style: controlled PS1 look

Official page: https://lburdier.fr/projects/the-worst-roommate.html

## Design pillars

- Immersion through household sounds, cramped spaces and dim lighting
- Environmental storytelling: moved objects, rubbish, smells suggested by sound design
- Gradual tension; jumpscares kept in check and justified by the story
- Semi-procedural flat (layout, dirt, points of interest) so every run feels different

See: https://lburdier.fr/projects/the-worst-roommate.html#about

## Core mechanics

- Routines and chores: a dynamic checklist (dishes, bins, sorting, mopping) affecting smell, infestation and patience; clean rooms = less stress
- Suspicion system: a hidden gauge; searching / moving things / taking photos ↑; cooperating / notes / compromise ↓; reactions: silences, looks, slammed doors, messages
- Sanity and hallucinations: stress ⇒ tunnel vision, grain, aberrations, fake sounds; calm down with a hot shower, music, a call to a friend, warm light
- Roommate AI: semi-procedural schedules, comfort zones, mood triggers; behaviours: avoidance, passive-aggressive, sabotage, confrontation
- Contextual events: power cuts, water leaks, burning smells, night noises, parcels, visitors; several possible resolutions; built-in clue notebook
- Domestic stealth: walk without creaking, partial darkness, distractions (radio, microwave, tap); no weapons, only composure and method
- Evidence and narrative: photos, bills, logs, handwritten notes; used to negotiate, raise the alarm or trigger an ending; missing evidence = biased interpretation
- Time economy: short evenings; choose between tidying, investigating and sleeping; lack of sleep ⇒ paranoia

See: https://lburdier.fr/projects/the-worst-roommate.html#mechanics

## Key features and systems

- Multiple endings: at least 7, depending on order, evidence and conflict escalation
- Occasional QTEs, short and readable (no gratuitous punishment)
- AI: mood, routines, zones and contextual reactions
- Day / night cycle: 7 days, evolving events and tension
- Relationships: messages, notes, short dialogues, trust thresholds
- Diegetic PC and phone: journal, photo evidence, tasks, messaging
- Lasting consequences: scenes, AI, endings
- Generation: semi-procedural layout, clutter, breakdowns and points of interest
- Short cutscenes at key moments (fixed / handheld camera)
- Hallucinations driven by the stress bar

See: https://lburdier.fr/projects/the-worst-roommate.html#mechanics

## Character design and art direction

### Intent and PS1 style
- Limit fidelity to stimulate the imagination; readable silhouettes; focus on sound, light and timing
- Recipe: low-resolution textures, reduced palette, point filtering, subtle dithering, slight sub-pixel jitter for a vintage feel
- Diegetic UI: minimal menu styled like a transit card; journal on the phone; saves at routine checkpoints

See: https://lburdier.fr/projects/the-worst-roommate.html#style

### Characters
- Protagonist: slim silhouette, everyday clothes, restrained expressions; contained nervousness; sitting on the edge of the bed; cold palette with warm accents; smartphone as notebook; short animations, audible breathing
- The roommate: unsteady posture, messy hair, damaged glasses; states: neutral / irritable / absent / threatening; eyes out of the light; recognisable silhouette; jerky movements, micro-tremors; muffled voice, breathing on a distant mic

See: https://lburdier.fr/projects/the-worst-roommate.html#characters

### UE5 environments and visual pipeline
- Low-poly modelling for readable silhouettes
- Procedural flat generation (layout, clutter, lighting)
- 256–512 px textures, shared atlases, clean UV packing
- Stationary lighting, baked GI, targeted downsampling
- Post-process: grain, light vignette, slight chromatic aberration
- Audio: multichannel household foley, light reverb per room

See: https://lburdier.fr/projects/the-worst-roommate.html#environments

## Team

The Worst Roommate is a collaborative project.

- Lucas Burdier: Project lead, game designer and developer
  - Concept supervision, prototype development, art direction and narrative tone
- Léo Daurelle: 3D artist and level designer
  - Low-poly environments, flat scenes, UE5 lighting integration
- Léo Chérubin: 3D modeller
  - Low-poly 3D models

See: https://lburdier.fr/projects/the-worst-roommate.html#team

## Community and Discord

An official Discord server will open soon (not available yet). It will be the place to follow progress, get announcements, playtests and recruitment calls, share creations and join the community.

- Announcements: https://lburdier.fr/projects/the-worst-roommate.html#announcement
- Community section: https://lburdier.fr/projects/the-worst-roommate.html#team

## Tools and production pipeline

- 3D and animation: Blender, Maya, Substance 3D Painter, Leonardo AI
- Game engine: Unreal Engine 5 (lighting, Blueprints, behavioural AI); procedural flat management and daily event scripts
- Audio and narrative: DaVinci Resolve / Fairlight, FL Studio, ElevenLabs AI (in-game test voices)
- Organisation and collaboration: Miro, Discord
- Versioning and tracking: GitHub (branches per module; organised by game day; reviews through PRs)
- Rendering and optimisation: simplified pipeline, PSX-style compatibility, optimised UE5 integration with low-poly Nanite

See: https://lburdier.fr/projects/the-worst-roommate.html#production

## Roadmap

- Pre-production, GDD v1 (in progress): writing the GDD, core mechanics, moodboard, pipeline, prototype planning
- Vertical slice prototype (upcoming): one-evening loop, basic roommate AI, 2 contextual events
- Art pass (upcoming): PS1 texture pack, consistent lighting, first SFX
- Closed playtests (upcoming): UX iterations, comfort options, sanity / suspicion balancing
- Public demo (upcoming): one full evening, branching paths, 2 endings

See: https://lburdier.fr/projects/the-worst-roommate.html#roadmap

## FAQ

- Is the project paid? For now, contributions are voluntary (pre-production and prototyping). Credits will appear on official materials.
- How can I join the team? Through the contact form at the bottom of the page; mention your skills and a link to your portfolio or work.
- When can I play the demo? Once the prototype is finished; a masterclass will present the first scenes and mechanics.
- How long will development take? Several months, at a pace that depends on everyone's availability; the public roadmap is kept up to date.
- What is the spirit of The Worst Roommate? Everyday tension, isolation, perception, paranoia. Inspired by real events and flat-sharing experiences.

Links: https://lburdier.fr/projects/the-worst-roommate.html#faq | https://lburdier.fr/projects/the-worst-roommate.html#contact | https://lburdier.fr/projects/the-worst-roommate.html#announcement

---

© 2025 The Worst Roommate. Narrative psychological game in development. Website: https://lburdier.fr/projects/the-worst-roommate.html
