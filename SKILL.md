---
name: yongle-prompt
description: Develop premium international AI live-action short dramas from Chinese or English scripts for the PipiXia short-drama platform using Seedance 2.0, including localization, character and voice bibles, timed coverage, compact execution prompts, continuity control, and quality review. Use for overseas-market vertical drama, English-language adaptation, shot planning, prompt revision, or clips that must stay within 15 seconds.
---

# YongLe Prompt

Turn a script into premium international-market live-action short-drama coverage and executable Seedance 2.0 clips for the company's PipiXia short-drama platform workflow. Treat the user's script as locked source material, not as a draft to rewrite.

## Project defaults

- Target premium realistic live action: specific casting, natural skin and fabric texture, physically motivated light, restrained screen acting, stable anatomy, and production-designed environments.
- Use the PipiXia short-drama platform as the production environment and Seedance 2.0 as the generation model. Do not confuse this company workflow with unrelated products that share the PipiXia name.
- Do not invent undocumented platform controls, field names, limits, or node behavior. When the user supplies screenshots, field labels, presets, or platform rules, treat the latest supplied platform information as authoritative and update the execution format accordingly.
- Write all director and platform execution prompts in Chinese. Keep every scripted spoken line in its supplied English wording unless the user explicitly authorizes rewriting; do not translate, polish, shorten, or substitute dialogue to solve timing.
- Preserve the script exactly: dialogue, narration, specified actions and reactions, character relationships, event order, props, reveals, and outcomes. Technical shot division may redistribute the unchanged source across clips but may not change what happens. Natural performance behavior—breath, gaze, head movement, posture, weight shift, restrained hand gestures, and active listening—is required when it expresses the written emotion or conversational intent, but it must not create a new action, decision, relationship beat, prop event, destination, or plot fact.
- Require generated audio in every video prompt: spoken dialogue where present, room tone, environmental ambience, action Foley, cloth and prop sounds, and any motivated supernatural sound. Keep dialogue intelligible and acoustically integrated with the room.
- Preserve realistic background sound appropriate to the exact location and acoustic path. Include low-level distant pedestrians, traffic, carriage, neighboring-room activity, wind, machinery, birds, or building noise only when physically plausible. Background voices must be indistinct, semantically unintelligible, spatially distant, and mixed well below the principal dialogue so they add presence without creating new story content.
- Require a clean image with no subtitles and no screen text overlays: no Chinese or English subtitles, captions, title cards, lower thirds, speaker labels, watermarks, or explanatory UI. Text that physically belongs to a prop or set is allowed only when the script requires it, and should not be added as an overlay.
- Use visual hard cuts for every shot transition. Never use dissolves, fades, wipes, morphs, match-generated transformations, occlusion transitions, whip-pan transitions, flash transitions, or an AI-interpreted continuous take in place of the specified cut.
- Dialogue and internal-monologue passages require alternating coverage. Do not hold an entire exchange or voice-over on one face or one composition. Use motivated hard cuts among the active speaker, listener, relevant evidence or prop, and environment, then return to the face when the emotional turn or decision lands.
- In multi-character dialogue, use traditional over-the-shoulder coverage when it clarifies relationship, distance, eyeline, or power. Combine an establishing geography shot, matched over-the-shoulder speaker/listener angles, clean singles, reactions, and inserts as needed; do not reduce every exchange to isolated frontal close-ups.
- Naturalism is the highest aesthetic priority. Every decision in casting, performance, blocking, camera, light, production design, physical interaction, VFX, editing, and sound must feel observed rather than displayed. Do not add conspicuous technique merely to make the result look expensive.
- Treat lighting as physical cause and effect. Lock the position, height, color, hardness, intensity, and occlusion of the sun and every practical source, then derive hair light, facial shadow, cast shadow, reflections, exposure, and color response from that geometry in every angle.
- Enforce a hard maximum of 15 seconds per generated clip. Choose shorter clips when the dramatic beat benefits.
- Default to mobile-first 9:16 episodic drama only when the user has not specified a format. State the assumption; do not crop a composition designed for another ratio.
- Establish the target territory, audience, language, rating, genre promise, episode length, platform, and cultural setting before final prompts. If absent, make a clearly labeled working assumption rather than silently inventing cultural detail.
- Preserve the latest user correction over earlier pasted drafts. Flag name or continuity conflicts instead of silently reverting them.
- Changes are limited to technical coverage, clip boundaries, camera placement, and prompt precision. Never change script content for clarity, localization, historical accuracy, timing, or generation stability without explicit user permission.

## Required workflow

1. Read the full supplied scene before drafting prompts.
2. Identify the dramatic function, conflict, hidden intent, story outcome, and emotional progression.
3. Identify the target-market hook, genre contract, and realism risks without adapting the locked script.
4. Build or update character, voice, accent, scene, prop, wardrobe, screen-direction, line-level facial-performance, body-performance, and continuity records. Separate identity references from shot-specific states.
5. Measure dialogue, actions, pauses, reactions, and transitions against the available duration.
6. Split the scene into clips of at most 15 seconds. Give every clip one narrative job and a clear opening and ending state.
7. Design alternating coverage and the edit before writing prose prompts. Use only motivated hard cuts: cut to the active speaker before their line, alternate to the listener or relevant evidence at meaningful beats, and return for the emotional turn or endpoint. For internal monologue, keep the voice continuous over multiple relevant images while the character's lips remain closed.
8. Write exact shot IDs and local time ranges starting at zero for each generated clip. Mark every transition explicitly, such as `1.2秒直接硬切`.
9. Generate a Chinese Seedance 2.0 director prompt and a compact Chinese PipiXia-platform execution prompt while preserving scripted English dialogue verbatim. Every prompt must specify generated sound and explicitly forbid subtitles and overlay text.
10. Run the international live-action quality gate in [references/overseas-live-action.md](references/overseas-live-action.md). Reject or revise shots with identity drift, synthetic acting, cultural incoherence, broken eyelines, bad lip-sync, unstable hands, plastic skin, floating props, unreadable geography, or generic stock imagery.
11. End with a modification log comparing the user's source with the delivered version, including localization changes.
12. For connected clips, mark future prompts provisional until the previous accepted take or actual final frame is reviewed.

## Timing rules

- Do not equate the 15-second ceiling with a target duration.
- Budget Mandarin dialogue by actual delivery: roughly 3-4 characters per second for natural speech and 2-3 for slow emotional delivery, then add explicit pauses and reactions.
- Keep emotional pauses only when they change meaning. Remove decorative silence.
- Give physical actions preparation, execution, consequence, and a visible endpoint.
- If dialogue and performance cannot fit naturally, split the clip or propose a clearly logged dialogue compression. Never solve overload only by rushing speech.
- Read [references/production-rules.md](references/production-rules.md) for the complete capacity and stability checklist.

## Speaker and edit rules

- When the speaker changes, cut to the new speaker unless a deliberately motivated off-screen line is requested.
- Do not stage dialogue as isolated talking heads or an unbroken two-shot. Build a natural pattern of speaker single, listener reaction, relevant insert or two-shot, and return single as the content permits. The cut pattern must vary with meaning rather than repeat mechanically.
- For two or more visible characters, establish geography before close coverage, then use matched over-the-shoulder shots where appropriate. Keep the foreground listener's near shoulder and partial head softly out of focus while the speaking face, eyes, mouth, and motivated hand gesture remain unobstructed.
- Match over-the-shoulder pairs in camera height, lens family, subject size, look room, eye level, shoulder mass, screen direction, and distance to the axis. Preserve left/right geography and do not cross the 180-degree line between reverse angles.
- In 9:16, keep the foreground shoulder narrow enough to preserve the speaker's face and vertical body language; it should frame the relationship, not occupy the center or block the mouth, hands, prop, or emotional information.
- Use over-the-shoulder shots selectively: valuable for confrontation, persuasion, disclosure, interrogation, intimacy, and shifting power; avoid them for private internal monologue, decisive isolated realization, evidence inserts, or when the foreground body would obscure essential action.
- The speaking shot must name exactly who produces lip movement. State that all other visible characters keep their mouths closed.
- During meaningful parts of a line, hard-cut to the listener's active but quiet reaction, then return to the speaker for a verbal pivot, emphasis, or conclusion. Do not wait until every line is finished if the listener's evolving response is the dramatic information.
- For internal monologue, keep the character's lips closed at all times. Carry one continuous voice identity across hard cuts to the character, relevant evidence or prop, another character, and the environment, then return to the character at the key realization or final thought.
- Avoid holding the same dialogue or internal-monologue composition longer than roughly 4–5 seconds when another motivated coverage angle exists. This is a rhythm warning, not permission to add irrelevant inserts or cut away from essential lip-sync.
- Use direct hard cuts for every visual transition. State each exact cut time and destination shot. Do not hide cuts behind vague wording such as `随后看到`, and do not substitute fades, dissolves, wipes, morphs, occlusion tricks, whip pans, flashes, or seamless AI transitions.
- Make hard cuts feel natural through motivation and continuity: cut on a completed thought, a genuine look, a scripted action phase, a change of speaker, or a reveal. Preserve continuous room tone across the cut when the location is unchanged.
- Preserve dialogue, voice-over, breath, and room tone continuously across visual hard cuts. Do not restart a sentence, change voice identity, alter acoustic distance without camera motivation, or create an audible seam at the edit.
- Avoid common editorial failures: unmotivated cutting, axis crossing, mismatched eyelines, repeated or missing action phases, prop-hand jumps, light-direction changes, wardrobe drift, background resets, and jump cuts between nearly identical framings. When cutting on the same subject, change angle or scale enough to read as intentional while preserving geography.
- Maintain the 180-degree line, eyelines, left/right geography, prop placement, light direction, and action phase across cuts.
- Prefer separate generation nodes for fragile multi-shot sequences. If using one multi-shot generation, state the exact cut times and forbid continuous long-take interpretation.

## Performance and voice

- Translate emotions into visible behavior: breath interruption, blink rate, gaze shift, jaw tension, grip, posture, or a held pause.
- Before writing a performance prompt, interpret each exact line for literal meaning, objective, target, hidden intent, emotional resistance, status, incoming stimulus, verbal pivot, and what the character is trying not to reveal. Do not assign facial behavior from a generic emotion label alone.
- Give every spoken line and internal-thought beat a line-level facial-performance map: neutral carry-in, first involuntary response, gaze target and focus distance, upper- and lower-eyelid behavior, brow and glabella tension, cheek activation, nostril or breath change when justified, jaw and lip-corner state, blink or swallow placement, asymmetry, peak moment, release, and final held state.
- Describe only the few facial changes that a real person would show for that beat. Most changes should be small, partially suppressed, slightly asymmetric, and sequenced over time rather than switching the whole face at once. Preserve natural transitional frames between expressions.
- Coordinate facial expression with exact English phonemes and breath. Do not prescribe lip pressing, jaw clenching, smiling, swallowing, or mouth-covering gestures during syllables that require incompatible mouth shapes. Place those behaviors before the line, between phrases, on a pause, or after the line.
- Keep the eyes cognitively alive: focus on the correct person or object, allow brief thought-driven defocus or gaze shifts, vary blink timing with stress and processing, and preserve plausible saccades. Avoid glassy staring, synchronized eyebrow lifts, perpetual wide eyes, random blinking, and eye motion unrelated to thought.
- Preserve identity under expression. Facial bones, eye spacing, eyelid anatomy, nose, lips, teeth, skin texture, age lines, and facial volume must not reshape, beautify, smooth, or drift as emotion changes.
- Map every dialogue line through an opening state, emotional turn, and ending state. Give the speaker natural, culturally plausible body language that evolves with the thought: small hand emphasis, palm withdrawal, restrained dismissive gesture, head shake, nod, lean, recoil, weight shift, or change of interpersonal distance when appropriate.
- Do not leave speaking characters rigid or make them perform only with their mouths. Coordinate voice, breath, eyes, head, shoulders, hands, torso, and stance, while keeping gestures proportionate to framing, personality, status, period, and emotional intensity.
- Give listeners active but quiet behavior: eye focus, breath response, blink, slight head or posture adjustment, and only a motivated nod or shake. Listener behavior must not compete with the speaker or imply an unscripted agreement, refusal, suspicion, or decision.
- Use gestures as phrasing, not decoration. Prefer one clear primary gesture per emotional beat, allow it to prepare before the emphasized word and resolve naturally afterward, and avoid repetitive waving, symmetrical hand movement, random pointing, constant nodding, or gestures on every word.
- Track gesture phase and hand position across hard cuts. Never restart, duplicate, reverse, or teleport a hand movement; protect hand anatomy, object contact, sleeve response, and physical weight.
- Bind every line to a named character, voice identity, emotion strength, pace, emphasis, subtext, and mouth state.
- Treat timbre and delivery as separate layers. A cold character may deliver a superficially gentle line without losing the underlying voice identity.
- Preserve the same voice identity across the project while allowing story-state changes such as weakness, guilt, injury, or concealment.
- Avoid generic `电影感`, `高级感`, exaggerated villain delivery, theatrical ancient-drama cadence, plastic skin, and unsupported emotional adjectives.
- Favor proportionate behavior supported by the written emotion and dialogue intent. Avoid performance flourishes, decorative reactions, constant facial movement, posing, telegraphing, and pauses that announce the emotion.

## Camera and realism

- Default to authentic human-operated handheld cinematography. Use gentle breathing drift, minute reframing, natural operator inertia, and subtle weight transfer; the image may move slightly but must never shake, jitter, pulse, wobble electronically, or simulate a post-production shake filter.
- Keep handheld dialogue coverage sufficiently steady for faces and lip-sync. Camera motion must feel caused by a real operator holding a physical camera, not by floating, orbiting, gimbal-perfect, or synthetic movement.
- Give each shot a scale, angle, lens feel, camera move, speed, subject relationship, and endpoint.
- Use one motivated primary move per short shot. Split incompatible move stacks into separate shots.
- Keep dialogue and lip-sync shots stable; avoid orbits, rapid head turns, and busy hand choreography.
- Convert poetic atmosphere into physical light, material, weather, and sound. For example, render `烛火森冷` as warm practical flames contrasted with cool environmental light rather than blue flames unless fantasy is intended.
- Use wide shots to establish geography, medium close-ups for dialogue, close-ups for decisive reactions, and inserts for evidence or props.
- Build conventional coverage when performance and continuity matter: master or geography anchor, matching singles, listener reactions, and inserts. Do not force a whole scene into one generated take.
- For over-the-shoulder dialogue, prefer natural human perspective around 50–85mm-equivalent lens feel, modest depth separation rather than extreme blur, and slight handheld operator breathing that remains matched across the reverse angle. Keep the foreground shoulder physically connected to the correct character; reject floating shoulders, duplicate bodies, wrong wardrobe, impossible neck angles, and mismatched head positions.
- Specify production design through concrete architecture, materials, practical sources, weather, socioeconomic signals, and lived-in detail appropriate to the named territory. Do not use a vague “Western” look.
- Treat sound as authored storytelling: room tone, perspective-correct ambience, cloth and prop Foley, restrained score, dialogue separation, and intentional silence. Never rely on music to manufacture an emotion absent from performance.
- Preserve natural exposure, focus behavior, motion blur, lens perspective, skin response, contact shadows, reflections, material weight, gravity, and acoustic distance. Reject beautification that removes pores or fabric structure, over-shallow focus that hides geography, excessive backlight haze, fake anamorphic artifacts, and sound effects that call attention to ordinary movement.

## Physically grounded lighting

- For every exterior or sunlit interior shot, specify sun direction relative to the character and camera, sun height and softness, sky condition, environmental bounce, and the resulting facial key-to-shadow relationship.
- When a character is backlit by the sun, render a natural rim of transmitted light on individual hair strands and fine flyaway hairs only where the sun actually reaches them. Keep the face on the shadow side; do not invent frontal sunlight, symmetrical beauty light, or a glowing halo around the whole silhouette.
- Lift a backlit face only through physically plausible sky fill, ground bounce, nearby wall reflection, window spill, or an explicitly present reflector. Keep the source direction legible, preserve facial volume, and do not flatten the face or erase its shadow merely for beauty.
- When a character turns or moves, let highlight and shadow travel continuously across hair, forehead, nose, cheeks, jaw, clothing folds, and the environment according to the unchanged source position. Do not let lighting stick to the face or reset after a hard cut.
- Match cast-shadow direction, length, edge softness, contact darkness, reflected color, eye catchlights, hair transmission, skin subsurface response, specular highlights, lens flare, and exposure across coverage. Lens flare appears only when source and lens geometry support it and must remain restrained.
- Protect highlight roll-off and shadow detail without artificial HDR. Bright sun may approach clipping naturally; shadowed faces remain readable but visibly darker. Avoid crushed black faces, orange skin, teal shadows, overexposed hair rims, glowing edges, excessive haze, and studio-perfect fill in an uncontrolled exterior.

## International adaptation

- Read [references/overseas-live-action.md](references/overseas-live-action.md) whenever the project targets an overseas audience, uses English or another non-Chinese language, or requests premium international quality.
- Preserve names, address forms, institutions, money, law, work culture, dating norms, housing, food, gestures, humor, and terminology exactly as scripted. Report authenticity or localization risks without silently correcting them.
- Do not translate or adapt the script unless the user separately authorizes adaptation. Any authorized change must be logged; otherwise the modification log must show zero script-content changes.
- Define each voice by region, age impression, register, rhythm, pitch range, vocal texture, and code-switching rules. Do not request a celebrity imitation or use accent as caricature.
- Use references for quality attributes and production logic, not for copying a living creator's signature style, protected characters, or recognizable performers.

## Output contract

Default to a fast, production-facing response. When the user supplies one numbered scene or segment, return only:

1. One compact Chinese Seedance 2.0 / PipiXia execution prompt for that supplied segment, preserving all English dialogue verbatim.
2. Exact hard-cut timestamps or ordered shot beats inside that prompt, plus performance, sound, continuity, and no-subtitle constraints.
3. One short warning only if the locked material cannot fit the platform duration without technical splitting.

Do not output capacity essays, dramatic analysis, market briefs, character cards, clip maps, quality tables, modification logs, task-name lists, or repeated global rules unless the user explicitly asks for them. Perform that reasoning internally. Do not turn one user-labeled scene such as `38-1` into many separately presented deliverables merely because it contains several shots; keep the user-facing delivery unified and concise. If actual generation requires multiple clips, state the minimum split in one sentence and keep the prompts compact.

Use [references/output-template.md](references/output-template.md) only when the user requests a full production breakdown. Never omit exact cut points in either compact or full mode.
