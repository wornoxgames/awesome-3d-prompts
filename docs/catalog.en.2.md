<!-- Generated file: edits are overwritten. -->

# Awesome 3D Prompts — Catalog 2/2

[← Awesome 3D Prompts](../README.md) · **English** · [Русский](catalog.ru.1.md) · [日本語](catalog.ja.1.md) · [中文](catalog.zh.1.md)

[← Previous](catalog.en.1.md) · page 2 of 2

### [VRChat avatar dress modeled in Blender, shown dancing in Unity](https://wandy3d.com/prompts/vrchat-avatar-dress-modeled-in-blender-shown-dancing-in-2103456264785424530?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/prompts/vrchat-avatar-dress-modeled-in-blender-shown-dancing-in-2103456264785424530?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/vrchat-avatar-dress-modeled-in-blender-shown-dancing-in-2103456264785424530.webp" width="640" alt="VRChat avatar dress modeled in Blender, shown dancing in Unity"></a>

**Claude Fable 5.1** · Assets · by [のわ〜る👼🍆🐄](https://x.com/Noir4247) · 2026-09-25

A comparison: Claude Fable 5.1 and GPT-6 Astra each modeled a VRChat green dress in Blender from a design sketch, without weight or physics hints.

<details>
<summary>Prompt</summary>

```text
VRChat用の衣装作って
```

</details>

[View on Wandy3D ↗](https://wandy3d.com/prompts/vrchat-avatar-dress-modeled-in-blender-shown-dancing-in-2103456264785424530?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [Original post](https://x.com/Noir4247/status/2103456264785424530)

---

### [15-second motion design showreel with kinetic type and dot grids](https://wandy3d.com/prompts/15-second-motion-design-showreel-with-kinetic-type-and-dot-2103449416325890146?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/prompts/15-second-motion-design-showreel-with-kinetic-type-and-dot-2103449416325890146?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/15-second-motion-design-showreel-with-kinetic-type-and-dot-2103449416325890146.webp" width="640" alt="15-second motion design showreel with kinetic type and dot grids"></a>

**Claude Opus 5.5** · Animation · by [Ajith](https://x.com/ajith_io) · 2026-09-25

A one-sentence request to Claude Opus 5.5 returned a showreel: kinetic text, a dot sphere, a wireframe cube and a text ring on shifting color fields.

<details>
<summary>Prompt</summary>

```text
make a dynamic 15-second motion graphics video that shows what an incredible motion designer you are, like it's your showreel for a résumé. go all out.
```

</details>

[View on Wandy3D ↗](https://wandy3d.com/prompts/15-second-motion-design-showreel-with-kinetic-type-and-dot-2103449416325890146?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [Original post](https://x.com/ajith_io/status/2103449416325890146)

---

### [Interactive WebGPU jelly dragon fruit with soft-body physics](https://wandy3d.com/prompts/interactive-webgpu-jelly-dragon-fruit-with-soft-body-physics-2103433535604265052?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/prompts/interactive-webgpu-jelly-dragon-fruit-with-soft-body-physics-2103433535604265052?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/interactive-webgpu-jelly-dragon-fruit-with-soft-body-physics-2103433535604265052.webp" width="640" alt="Interactive WebGPU jelly dragon fruit with soft-body physics"></a>

**Claude Opus 5.5** · Interactive · by [Vib3Coded](https://x.com/vib3coded) · 2026-09-25

A side-by-side test: Claude Opus 5.5 and GPT-6 Astra each built a draggable jelly dragon fruit. Opus feels firmer and glossier, Astra softer.

<details>
<summary>Prompt</summary>

```text
Create an interactive 3D scene called “Pitaya Jelly” — a dragon fruit half made of soft, translucent jelly. Build the entire project in a single HTML file using genuine WebGPU rendering and WGSL shaders. Do not use premade models or image assets.

APPEARANCE

A large dragon fruit half resting cut-side up on a light studio surface.
Rich raspberry-pink skin, a thin pale inner rind, and pearly white flesh.
Approximately 250 tiny black seeds distributed naturally across the flesh.
12–14 fleshy peel petals around the fruit, transitioning from pink bases to green tips.
A glossy, wet surface with light refraction, small internal bubbles, and a soft contact shadow.
The material should look like soft gummy candy, not rigid plastic. Preserve saturated colors without blown-out highlights.

PHYSICS AND INTERACTION

Implement genuine soft-body deformation using a volumetric mesh with elastic connections and volume-preserving constraints, such as XPBD.
Users can grab the flesh with a mouse or finger, stretch it, and release it.
Deformation should concentrate around the grabbed point rather than simply translating the entire object.
After release, the fruit should wobble, jiggle, and gradually recover its original shape.
Make the peel petals individually draggable. They should be softer than the flesh, bending and springing back while remaining attached to the fruit.
Seeds must follow the deforming surface without floating away or sinking into the flesh.
Keep the simulation stable during strong pulls, with floor contact and protection against inverted elements.

VISUAL DESIGN

Use a minimal, light-themed studio interface with an editorial aesthetic: generous whitespace, thin borders, restrained controls, and no unnecessary decoration.

Top left:
“MATERIAL STUDIES / NO. 019”
A large italic serif heading on two lines:
“Pitaya Jelly.”

Below it:
“A little wild.”
“A little sweet.”
“A very soft dragon.”
On the right, add a floating panel titled “THE SPECIMEN” containing:

Density badge: ρ 1.04 g/cm³.
Three presets:
Pearl — white flesh and pink skin.
Ruby — raspberry-colored flesh and pink skin.
Gold — pale flesh and golden skin.
Firmness and Internal damping sliders with visible values.
“Give it a nudge” and “Reset” buttons.

“¼ speed” and “Show mesh” checkboxes.

A “Pause” button.
Also include:
A fullscreen button with an exit option.
A “WEBGPU · LIVE” status indicator.
Live readouts for mass, percentage of rest volume, and kinetic energy.
A short interaction hint: “Pull the flesh. Tug a petal. Let go.”
A collapsible “Inside the experiment” section explaining the implementation accurately.
TECHNICAL REQUIREMENTS
Deliver one self-contained file named pitaya-jelly-webgpu.html.

Use actual WebGPU rendering, not a Canvas 2D imitation.

Build all geometry procedurally.
Use thickness-aware refraction, Fresnel reflections, and soft studio lighting.
Use a fixed simulation timestep for consistent behavior.
Support desktop and touch interaction with a responsive layout.
Avoid expensive geometry reconstruction or shader compilation during dragging.

Show a clear fallback message when WebGPU is unavailable.

Verify dragging, release, shape recovery, presets, reset, pause, fullscreen, and mobile layout.
The main priorities are convincing jelly-like behavior, beautiful materials, and satisfying interaction. The result should feel like a polished, playable material experiment.
```

</details>

[View on Wandy3D ↗](https://wandy3d.com/prompts/interactive-webgpu-jelly-dragon-fruit-with-soft-body-physics-2103433535604265052?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [Original post](https://x.com/vib3coded/status/2103433535604265052)

---

### [20-second motion graphics showreel about the cycle of life](https://wandy3d.com/prompts/20-second-motion-graphics-showreel-about-the-cycle-of-life-2103428454355980558?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/prompts/20-second-motion-graphics-showreel-about-the-cycle-of-life-2103428454355980558?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/20-second-motion-graphics-showreel-about-the-cycle-of-life-2103428454355980558.webp" width="640" alt="20-second motion graphics showreel about the cycle of life"></a>

**Claude Opus 5.5** · Animation · by [Loïc](https://x.com/loicRambo) · 2026-09-25

Claude Opus 5.5 produced a looping 2D animated short that follows one character from childhood through office life and family to old age, with a live heart-rate readout.

<details>
<summary>Prompt</summary>

```text
make a dynamic 20-second motion graphics and animation video that shows what an incredible motion designer and animator you are, like it's your showreel for a résumé. make it about the cycle of life showing the same individual going from childhood to adolescence to the 9-5 cycle, to family life to elder life and death, then cutting ready to loop to the beginning.  go all out , use whatever you need.
```

</details>

[View on Wandy3D ↗](https://wandy3d.com/prompts/20-second-motion-graphics-showreel-about-the-cycle-of-life-2103428454355980558?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [Original post](https://x.com/loicRambo/status/2103428454355980558)

---

### [Moonlit cypress swamp in Three.js with reflective water and a drifting boat](https://wandy3d.com/prompts/moonlit-cypress-swamp-in-three-js-with-reflective-water-and-2103310302993621090?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/prompts/moonlit-cypress-swamp-in-three-js-with-reflective-water-and-2103310302993621090?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/moonlit-cypress-swamp-in-three-js-with-reflective-water-and-2103310302993621090.webp" width="640" alt="Moonlit cypress swamp in Three.js with reflective water and a drifting boat"></a>

**GPT-6 Astra** · Scenes · by [YouWare](https://x.com/YouWareAI) · 2026-09-25

GPT-6 Astra wrote a calm browser world where a lantern-lit skiff drifts through a foggy swamp; the star is the water shader, with a day-night cycle.

<details>
<summary>Prompt</summary>

```text
Build a browser experience in Three.js called STILLWATER.  Tone: a moonlit swamp you get lost in. Not a game with enemies. Not photoreal Unreal. A quiet, expensive-looking web world where the water reflections are the feature. People should stare at the water for an unhealthy amount of time.  SETTING - Location title: THE DEEP SWAMP - Time on the HUD: 19:26 - First named place: Heron bend - Tagline under the place name: "Leave a little room for the wild." - Discovery toast when you arrive: "Discovered: Heron bend"  WORLD A flooded cypress swamp at moonrise / late dusk. - Tall knobby-kneed trees standing in black-green water - Spanish moss hanging in long strands - Lily pads clustered along the banks - Narrow winding channel that opens into a wider bend - Thick volumetric fog, teal-green distance, purple-pink cloudy sky - A bright moon with a long broken reflection path on the water - A few birds crossing the sky - Warm cabin light from the boat punching through the gloom  WATER (do not cheap out) This is the hero. - Real-time reflections of trees, moon, fog and boat lights - Gentle swell, not ocean waves - Lily pads that sit on the surface and bob - Shoreline foam / dark tannin water near roots - Screen-space or planar reflections good enough that the moon path feels cinematic - Keep 60fps. LOD the trees, instanced foliage.  BOAT A small weathered cabin skiff / workboat. - Hull number 86 on the stern - White cabin, dark blue hull, warm interior lamps - Idle drift through the channel, optional slow guided tour - HUD speed around 15.9 KNOTS - Mode label: GUIDED DRIFT Player can look around. Boat can be followed from a cinematic chase / side orbit.  CAMERA - Start on a three-quarter of the boat in the trees - Drift behind the stern down the moonlit lane - Occasional side slide past a foreground trunk - Drag to look - Optional PHOTO MODE Feel like a nature documentary, not an FPS.  UI — editorial, not gamey Top-left: small mark + STILLWATER Top-center: THE DEEP SWAMP / 19:26, a compass heading (e.g. 314°) Top-right: quiet utility icons Bottom-left:   EXPLORING STILLWATER   Heron bend   Leave a little room for the wild.   15.9 KNOTS    GUIDED DRIFT Bottom-right: PHOTO MODE, fps, Pause Center-bottom: small toast "Discovered: Heron bend" Tiny hint row: shaders / water / drag to look / photos / wildlife  Look: dark filmic grade, muted greens, magenta clouds, one moon highlight. Taste over realism. No bloated debug GUI.  TECH Three.js in the browser. Procedural / instanced nature. Custom water shader. Fog. Soft shadows or baked-looking dusk lighting. No asset-store swamp pack if you can author it.  DO NOT add combat, inventory, jump scares, or a treasure hunt. Something can lurk underwater later — not now.
```

</details>

[View on Wandy3D ↗](https://wandy3d.com/prompts/moonlit-cypress-swamp-in-three-js-with-reflective-water-and-2103310302993621090?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [Original post](https://x.com/YouWareAI/status/2103310302993621090)

---

### [Cinematic ocean-platform rocket launch in one Three.js HTML file](https://wandy3d.com/prompts/cinematic-ocean-platform-rocket-launch-in-one-three-js-html-2103303449831964679?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/prompts/cinematic-ocean-platform-rocket-launch-in-one-three-js-html-2103303449831964679?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/cinematic-ocean-platform-rocket-launch-in-one-three-js-html-2103303449831964679.webp" width="640" alt="Cinematic ocean-platform rocket launch in one Three.js HTML file"></a>

**Claude Opus 5.5** · Animation · by [NinjaCodex](https://x.com/N1njaCodex) · 2026-09-25

Comparison of two Opus versions on one prompt; Claude Opus 5.5's dawn launch runs from liftoff through staging and fairing release to an unfolding satellite.

<details>
<summary>Prompt</summary>

```text
Create a cinematic, highly detailed, interactive 3D rocket launch from an ocean platform at dawn. Deliver the complete project in one HTML file that opens directly in Chrome. Use Three.js + WebGL and procedural assets. Embed assets wherever practical; a reliable CDN may be used for the rendering library.

ART DIRECTION
Create a dramatic transition from a dark, blue-violet ocean before sunrise to warm sunlight above the atmosphere. Use convincing proportions, detailed materials, atmospheric depth, and carefully composed camera angles. The result should feel like a polished miniature spaceflight film.
ROCKET AND LAUNCH PLATFORM
Build a convincing multistage rocket with a shaped nose cone, panel seams, structural rings, interstage connections, engine nozzles, and a payload fairing that separates into two halves.

Create a detailed floating launch platform with a support tower, retracting strongback, service arms, railings, ladders, pipes, equipment, floodlights, and blinking warning beacons. Keep all structures physically connected and correctly positioned.
LAUNCH SEQUENCE
Create an approximately 46-second sequence:

Establishing camera move around the platform.

Service arms and strongback retract.
Engines ignite, illuminating the rocket, platform, and nearby water.
Smoke spreads across the deck as the rocket lifts off and accelerates.
The camera follows the climb from the atmosphere toward space.
The first stage separates and falls away.
The second-stage engine ignites.
The fairing halves separate, revealing a satellite.
The engine shuts down, the satellite deploys, and its solar panels unfold.
Finish with an orbital view of the satellite against Earth’s curved horizon and sunrise.
Compress the flight timeline for presentation while maintaining coherent motion. Avoid sudden position changes, intersecting components, or disconnected effects.
OCEAN, ATMOSPHERE, AND EFFECTS
Use animated shader-driven ocean waves with Fresnel reflections and warm engine-light reflections. Create layered exhaust with a bright core, softer outer flame, and drifting smoke particles.
Smoke should expand, fade, and respond to wind. Exhaust must remain attached to the correct engine through staging. Transition smoothly from atmospheric haze to a dark star field and Earth’s illuminated limb.

CAMERA AND INTERACTION
Use smooth cinematic camera transitions: wide establishing view, low-angle ignition shot, ascent tracking, stage separation, and satellite close-up. Keep the main subject visible in both portrait and landscape layouts.

Include play/pause, replay, and a scrubber with event markers. Seeking must reconstruct the correct rocket configuration, particle state, camera position, and lighting. Replaying must reset the entire sequence cleanly.
Keep the interface minimal and unobtrusive. Allow it to be hidden for recording.

TECHNICAL QUALITY
Use frame-rate-independent animation and efficient particle systems. Reuse geometry and materials where appropriate, handle resizing correctly, and balance visual detail with smooth performance.

Test the final HTML in a desktop browser. Inspect the console and capture screenshots at ignition, liftoff, staging, and satellite deployment. Fix loading errors, clipping, geometry problems, broken seeking, and poor camera framing before delivering the file.
```

</details>

[View on Wandy3D ↗](https://wandy3d.com/prompts/cinematic-ocean-platform-rocket-launch-in-one-three-js-html-2103303449831964679?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [Original post](https://x.com/N1njaCodex/status/2103303449831964679)

---

### [Interactive Three.js medieval kingdom with drawbridge, guards and day-night](https://wandy3d.com/prompts/interactive-three-js-medieval-kingdom-with-drawbridge-guards-2103257873203462412?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/prompts/interactive-three-js-medieval-kingdom-with-drawbridge-guards-2103257873203462412?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/interactive-three-js-medieval-kingdom-with-drawbridge-guards-2103257873203462412.webp" width="640" alt="Interactive Three.js medieval kingdom with drawbridge, guards and day-night"></a>

**Claude Opus 5.5** · Interactive · by [Vib3Coded](https://x.com/vib3coded) · 2026-09-24

A comparison of two models given the same castle prompt; Claude Opus 5.5 built a red-roofed kingdom with moat, village and mountains that you can explore.

<details>
<summary>Prompt</summary>

```text
Build your own medieval kingdom.
Your kingdom represents Claude Opus 5.5. Design a magnificent, historically inspired castle that expresses this model’s identity through architecture, heraldry, colors and atmosphere. You have complete artistic freedom within a believable medieval setting.
Do not simply place a logo on a generic castle. Give your kingdom a distinctive architectural character and a coherent visual identity. Invent its coat of arms, royal colors and an original heraldic emblem. Display them on animated banners, shields, gate decorations and the clothing of the castle guards. Place the kingdom’s name above the main entrance.
Create a richly detailed, interactive 3D scene using Three.js and WebGL. Deliver everything in one standalone HTML file that opens directly in Chrome.
THE CASTLE
Build a convincing fortress with a central keep, towers, battlements, curtain walls, an impressive gatehouse, a working drawbridge and a courtyard.
Include carefully modeled stonework, arched windows, wooden doors, roof structures, stairs, balconies, iron fittings and small architectural details. Make the structures believable: towers need interiors or convincing depth, stairs must connect to accessible floors, and bridges must have proper supports.
Surround the castle with an attractive landscape that suits your kingdom: cliffs, hills, a river, a moat, forests or a small village. Design a strong composition that looks beautiful from multiple angles.
LIFE AND INTERACTION
Bring the kingdom to life with guards patrolling the walls, villagers moving through the courtyard, gently waving banners, chimney smoke, birds and flickering lanterns.
Let the viewer:
Open and close the drawbridge and main gate.
Follow a guard on patrol.
Switch between a cinematic overview, the courtyard and the battlements.
Rotate and zoom freely.
Change between daylight, sunset and night.
Keep characters on walkable surfaces. Prevent them from passing through walls, doors or one another.
LIGHTING AND ATMOSPHERE
Create cinematic lighting that reveals the architecture clearly. Use soft shadows, atmospheric depth, convincing water where appropriate and restrained post-processing.
At night, illuminate windows, torches and lanterns while preserving enough visibility to appreciate the castle.
Aim for a sophisticated, finished 3D artwork with distinctive architecture and abundant detail. Avoid a collection of obvious primitive shapes or repetitive towers with no architectural purpose.
TECHNICAL QUALITY
Generate assets procedurally wherever practical. Embed textures and other assets inside the HTML. No local server or build step should be required.
Use instancing and geometry batching where appropriate. Keep animation and camera interaction smooth. Provide a minimal, elegant English interface and a button to hide it.
Actually test the result in desktop Chrome. Capture screenshots, inspect the console, test every interaction and fix rendering errors, floating objects, geometry intersections and camera problems.
Make this a castle people would recognize as YOUR kingdom, even before reading its name.
Return the completed standalone HTML file.
```

</details>

[View on Wandy3D ↗](https://wandy3d.com/prompts/interactive-three-js-medieval-kingdom-with-drawbridge-guards-2103257873203462412?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [Original post](https://x.com/vib3coded/status/2103257873203462412)

---

[← Previous](catalog.en.1.md) · page 2 of 2

Prompts, videos and images belong to their authors ([RIGHTS.md](../RIGHTS.md)). Our editorial text is [CC BY 4.0](../LICENSE). Know a great prompt with a visible result? [Suggest it](https://github.com/wornoxgames/awesome-3d-prompts/issues/new?template=suggest.md). Are you an author and want an entry changed or removed? [Tell us](https://github.com/wornoxgames/awesome-3d-prompts/issues/new?template=removal.md).
