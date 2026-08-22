# Production rules

## Capacity audit

For each scene, calculate:

- spoken characters and intended delivery rate;
- named pauses and natural breaths;
- silent reactions that carry plot information;
- blocking and prop interaction time;
- establishing and transition time;
- number of speakers, locations, and fragile actions.

Classify the result as `fits`, `tight`, or `overloaded`. A clip is overloaded when natural performance, clear cuts, or stable lip-sync cannot coexist within 15 seconds.

## Stability priorities

Prioritize in this order unless the story demands otherwise:

1. Character identity and correct speaker.
2. Dialogue intelligibility and lip-sync.
3. Story beat and performance endpoint.
4. Screen direction and continuity.
5. Camera motion.
6. Background complexity and decorative atmosphere.

Reduce camera motion, crowd behavior, hand activity, and secondary effects before sacrificing identity or dialogue.

The supplied script outranks optimization. Resolve overload by splitting clips, never by deleting, rewriting, translating, reordering, or paraphrasing source content.

For premium overseas work, cultural authenticity and idiomatic performance are story-critical rather than decorative. A technically stable shot still fails when casting, dialogue, institution, location, or behavior contradicts the declared market.

## Shot grammar

- Establishing shot: 0.6-1.5 seconds for fast short drama, longer only when geography matters.
- Speaker shot: stable medium close-up or close-up, one named speaker, one mouth assignment.
- Listener reaction: 0.6-2 seconds depending on narrative weight.
- Evidence insert: 0.8-2 seconds, preserve exact geometry and placement.
- Internal monologue: lips closed; permit visual cutaways while one voice continues.
- Hard cut: state the exact local timestamp and destination shot.
- Handheld baseline: subtle operator breathing drift and minute corrective reframing; no shake effect, rapid jitter, digital wobble, or unmotivated floating.
- Every visual transition is a hard cut. No dissolve, fade, wipe, morph, occlusion transition, whip transition, flash, or generated seamless bridge.
- A hard cut must have a reason: speaker change, scripted look, action phase, information reveal, or completed dramatic thought. Maintain room tone and acoustic perspective across cuts in the same location.

## Dialogue and internal-monologue coverage

- Dialogue requires coverage that moves naturally between the active speaker, listener, relevant insert or two-shot, and back to the face carrying the next emotional turn. Never render a whole exchange as one static talking head or one unbroken two-shot.
- Cut to the new speaker before their audible line begins unless off-screen delivery is explicitly intended. Only that speaker moves their mouth.
- Let listener reactions develop during meaningful portions of the speaker's line, but do not manufacture a reaction that changes story intent.
- Internal monologue is voice-over: the character's lips remain closed. Carry the same uninterrupted voice across hard cuts to the character, evidence, props, another person, or environment, and return to the character for realization or resolution.
- Do not use formulaic ping-pong cutting. Vary shot duration and destination according to thought structure, emphasis, withheld information, and reaction value. Avoid holding one usable composition beyond roughly 4–5 seconds when a motivated alternative exists.
- Maintain continuous dialogue timing, voice identity, breath, room tone, acoustic perspective, eyelines, body position, gesture phase, and prop state across every hard cut.

## Over-the-shoulder coverage

- Use over-the-shoulder shots selectively in multi-character dialogue to preserve physical relationship, eyeline, distance, and power. Establish geography first unless the location and axis are already locked by accepted footage.
- Build matched reverse angles: same lens family, compatible camera height and subject size, correct look room, consistent shoulder mass, and opposite but matching eyelines without crossing the axis.
- The foreground character is identifiable by the correct hair and wardrobe but remains softly out of focus. Their shoulder and partial head frame the active speaker without obscuring eyes, mouth, hands, props, or key facial performance.
- In vertical framing, keep foreground occupancy restrained. Do not let a shoulder become a central wall, create a false third person, or force the speaker against the edge without usable look room.
- Maintain the foreground character's listening behavior subtly through breath or minute head movement, but never generate a second speaking mouth.
- Reject common AI failures: floating or detached shoulders, duplicate torsos, inconsistent wardrobe, wrong speaker attached to the foreground body, impossible neck direction, mismatched shoulder height, face blockage, and reverse angles that silently cross the 180-degree line.

## Naturalism and professional continuity

- Do not call attention to camera technique. Prefer readable coverage, motivated framing, and patient observation over showy movement.
- Do not cross the 180-degree line without a scripted geography reset. Match eye direction, head height, prop hand, body angle, action phase, light direction, background position, and sound perspective.
- Avoid false jump cuts between nearly identical sizes and angles. Make a meaningful framing or angle change while preserving spatial logic.
- Do not invent story actions or reactions that change intention or plot. Natural conversational performance is required: speakers and listeners may breathe, shift gaze or posture, move their head, and use restrained hand gestures when those behaviors express the written emotion without adding a new decision or fact.
- Treat each gesture as a continuous physical action with preparation, emphasis, and recovery. Track its phase, hand, height, direction, prop contact, and sleeve state across hard cuts.
- Keep skin, fabric, hair, glass, paper, metal, smoke, shadows, reflections, gravity, contact, and motion blur physically credible. Reject glossy AI surfaces and weightless movement.
- Keep ordinary Foley proportionate. Background ambience should make the location live without becoming a demonstration of sound design.

## Facial-performance continuity

- Parse every exact line into intent, resistance, subtext, pivot, and endpoint before assigning expression.
- Build the face over time: carry-in, involuntary onset, partial suppression, peak, release, and residual state. Do not snap between named emotions.
- Use a sparse combination of gaze, eyelids, brow tension, cheek tone, nostrils, jaw, lip corners, blink, swallow, and breath. Do not animate every region at once.
- Preserve slight human asymmetry and transitional frames. Reject mirrored eyebrow movement, frozen cheeks, rubber lips, floating teeth, glassy eyes, repetitive blinks, and a smile or frown pasted over speech.
- Protect lip-sync. Place jaw locks, lip presses, swallows, and mouth-covering behavior only where the phonemes and pauses permit them.
- Match facial state, tear or moisture level, skin color, muscle tension, gaze, blink phase, and breath phase across hard cuts. Preserve facial identity and age texture through the full expression range.

## Sun and exposure continuity

- Record sun azimuth, elevation, hardness, color, weather diffusion, camera relationship, and environmental bounce before coverage is designed.
- Backlit sun produces selective transmission through edge and flyaway hair while the face remains on the shadow side. Do not use a full-body glow outline or invisible frontal key.
- Any facial fill must have a plausible source such as open sky, pale ground, nearby wall, snow, water, window, or an explicitly present reflector. Preserve the backlit lighting ratio.
- Match nose shadow, cheek and jaw modeling, catchlight position, cast-shadow direction and length, contact shadows, hair rim intensity, exposure, and white balance across every hard cut.
- As actors or camera move, light changes continuously from geometry. Reject face-tracking highlights, sticky shadows, relighting at cuts, artificial HDR, clipped hair rims, crushed faces, and unsupported lens flare.

## Continuity ledger

Track immutable identity anchors separately from transient scene state.

Immutable anchors include face, apparent age, build, hair, signature wardrobe, and voice identity. Transient state includes pose, gaze, breath, injury phase, prop hand, current emotion, open motion vector, camera phase, and audio phase.

Accepted footage overrides planned state. Never build a continuation from a rejected take. Record the observed tail before finalizing the next prompt.

## Modification log categories

- `技术性调整`: duration, cuts, camera feasibility, lip-sync, stability, physics, continuity, or prompt precision without changing story meaning.
- `创作性调整`: dialogue wording, event order, motivation, reveal, character intention, or emotional outcome. Forbidden unless the user explicitly authorizes the individual change.
- `一致性修正`: names, voice identity, wardrobe, props, geography, or latest user-approved canon.
- `本地化调整`: target-language dialogue, names, institutions, currency, units, customs, humor, gestures, rating, or market-specific genre expectations.

For every item, state the original, revised version, reason, production effect, and story impact.
