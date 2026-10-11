<!-- Generated file: edits are overwritten. -->

# Awesome 3D Prompts — 目录 2/2

[← Awesome 3D Prompts](../README.md) · [English](catalog.en.1.md) · [Русский](catalog.ru.1.md) · [日本語](catalog.ja.1.md) · **中文**

[← 上一页](catalog.zh.1.md) · 第 2 页，共 2 页

### [可漫步的动漫樱花小镇：商店街、神社与列车](https://wandy3d.com/zh/prompts/walkable-anime-cherry-blossom-town-with-shops-shrine-and-2103480085319942353?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/zh/prompts/walkable-anime-cherry-blossom-town-with-shops-shrine-and-2103480085319942353?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/walkable-anime-cherry-blossom-town-with-shops-shrine-and-2103480085319942353.webp" width="640" alt="可漫步的动漫樱花小镇：商店街、神社与列车"></a>

**Claude Opus 5.5** · 场景 · 作者 [Good FortuneX](https://x.com/pound75423) · 2026-09-25

Claude Opus 5.5依据一份结构化长提示词，用Three.js程序化生成了含商店街、神社和列车进站车站的小镇。

<details>
<summary>提示词</summary>

```text
Please use Three.js to build a "freely walkable 3D anime-style cherry blossom town" as a single HTML file, then publish it as a shareable web page.

[Technical constraints]
- Use only three.js r128 (UMD build) from cdnjs. Do not load any external models or images — generate all models, textures, and shop signs procedurally with code and Canvas.
- Use original content for all shop names, signs, and characters. Do not imitate any real brand or existing work.
- Use MeshStandardMaterial or MeshPhongMaterial. Avoid high metalness and environment reflection maps (on some computers they make objects render with no color).
- Merge static objects by material into a small number of meshes so it runs on ordinary computers; provide a High / Medium / Low quality switch.

[Scene: "桜ヶ丘 (Sakuragaoka)", a small Japanese town on a spring afternoon]
1. Shopping street: a north–south main street with 20+ shops on both sides (ramen shop, café, bicycle shop, bookstore, florist, Japanese sweets shop, drugstore, convenience store, etc.). Each shop has: a multi-line sign (shop name + English name + phone number), a striped awning with a scalloped valance, a recessed storefront with an interior that has visible depth, and a sidewalk display (fruit crates, magazine rack, food-sample case, a spinning barber pole). Upper floors have windows, AC units, balconies with hanging laundry, and rooftop TV antennas.
2. Street details: utility poles with lots of overhead wires, decorative street lamps with shopping-street banners, festival lantern strings, square sidewalk tiles with yellow tactile paving, drain grates, "止まれ" stop signs, and a bus stop.
3. Level crossing and trains: a double-track railway. When a train approaches, the crossing's red lights flash alternately, the bell rings, and the gates lower. A two-car commuter train stops at the station for about 14 seconds and then departs. The windows are transparent, so the seats and hand straps inside are visible.
4. Island-platform station: station name board, platform canopy, benches, and a vending machine.
5. Sakura plaza: a 100-year-old cherry tree with a circular bench around it.
6. Inari shrine: a large vermilion torii plus a row of small torii, stone lanterns, fox statues, a worship hall (copper-green roof, chigi, katsuogi, offering box, hanging bell), a purification fountain (temizuya), jizo statues, ema plaques, a sacred tree, and gravel ground.
7. Riverside levee: two rows of cherry trees forming a blossom tunnel, lanterns, a river, houses on the far bank, and distant mountains.

[How to build the cherry trees (key part)]
- Model them on Somei-Yoshino: the trunk splits low into 3–4 main limbs, which branch recursively three more levels. Branches spread outward and droop slightly at the tips, giving an overall umbrella shape.
- Build the canopy from tens of thousands of "blossom cluster cards": draw five-petal flowers on Canvas (notched petal tips, reddish centers, stamens) with a soft pink base layer behind the flowers. Use alphaTest and double-sided rendering for the cards.
- Add a few pink filler clumps inside the canopy for volume. The outer and upper parts are brighter; the inner and lower parts have warm rose-toned shadows.
- Use pale pink, not neon pink. The canopy sways gently in the wind, a carpet of fallen petals covers the ground under each tree, and petals keep falling through the air (done in a shader).

[Characters]
- 20+ anime-style students and townspeople: walking animation with knee and elbow joints, anime faces drawn on Canvas (large eyes, highlights, blush) that blink, bangs made of separate strands, a variety of hairstyles (long, bob, swinging ponytail, twin tails), sailor uniforms / blazer uniforms / casual clothes. Render characters with two-tone cel shading and a dark outline.
- People walk along the street, chat in the plaza, wait on the platform, pray at the shrine, and ride bicycles along the levee.

[Vehicles]
```

[……（以下省略，完整提示词见 Wandy3D）](https://wandy3d.com/zh/prompts/walkable-anime-cherry-blossom-town-with-shops-shrine-and-2103480085319942353?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

</details>

[在 Wandy3D 查看 ↗](https://wandy3d.com/zh/prompts/walkable-anime-cherry-blossom-town-with-shops-shrine-and-2103480085319942353?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [原帖](https://x.com/pound75423/status/2103480085319942353)

---

### [在Blender中制作的VRChat连衣裙，于Unity中跳舞展示](https://wandy3d.com/zh/prompts/vrchat-avatar-dress-modeled-in-blender-shown-dancing-in-2103456264785424530?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/zh/prompts/vrchat-avatar-dress-modeled-in-blender-shown-dancing-in-2103456264785424530?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/vrchat-avatar-dress-modeled-in-blender-shown-dancing-in-2103456264785424530.webp" width="640" alt="在Blender中制作的VRChat连衣裙，于Unity中跳舞展示"></a>

**Claude Fable 5.1** · 资产 · 作者 [のわ〜る👼🍆🐄](https://x.com/Noir4247) · 2026-09-25

对比示例：Claude Fable 5.1与GPT-6 Astra依据设计图在Blender中各做出一件绿色VRChat服装，未给权重与物理提示。

<details>
<summary>提示词</summary>

```text
VRChat用の衣装作って
```

</details>

[在 Wandy3D 查看 ↗](https://wandy3d.com/zh/prompts/vrchat-avatar-dress-modeled-in-blender-shown-dancing-in-2103456264785424530?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [原帖](https://x.com/Noir4247/status/2103456264785424530)

---

### [15秒动态设计作品集：动态字体与点阵画面](https://wandy3d.com/zh/prompts/15-second-motion-design-showreel-with-kinetic-type-and-dot-2103449416325890146?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/zh/prompts/15-second-motion-design-showreel-with-kinetic-type-and-dot-2103449416325890146?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/15-second-motion-design-showreel-with-kinetic-type-and-dot-2103449416325890146.webp" width="640" alt="15秒动态设计作品集：动态字体与点阵画面"></a>

**Claude Opus 5.5** · 动画 · 作者 [Ajith](https://x.com/ajith_io) · 2026-09-25

只用一句话让 Claude Opus 5.5 生成了作品集短片：动态文字、点阵球体、线框立方体和文字环，配色块不断切换。

<details>
<summary>提示词</summary>

```text
make a dynamic 15-second motion graphics video that shows what an incredible motion designer you are, like it's your showreel for a résumé. go all out.
```

</details>

[在 Wandy3D 查看 ↗](https://wandy3d.com/zh/prompts/15-second-motion-design-showreel-with-kinetic-type-and-dot-2103449416325890146?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [原帖](https://x.com/ajith_io/status/2103449416325890146)

---

### [WebGPU软体物理的可拖拽果冻火龙果](https://wandy3d.com/zh/prompts/interactive-webgpu-jelly-dragon-fruit-with-soft-body-physics-2103433535604265052?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/zh/prompts/interactive-webgpu-jelly-dragon-fruit-with-soft-body-physics-2103433535604265052?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/interactive-webgpu-jelly-dragon-fruit-with-soft-body-physics-2103433535604265052.webp" width="640" alt="WebGPU软体物理的可拖拽果冻火龙果"></a>

**Claude Opus 5.5** · 互动 · 作者 [Vib3Coded](https://x.com/vib3coded) · 2026-09-25

对比测试：Claude Opus 5.5与GPT-6 Astra各做了一个可拖拽的果冻火龙果，Opus偏弹、更亮，Astra更软。

<details>
<summary>提示词</summary>

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

[在 Wandy3D 查看 ↗](https://wandy3d.com/zh/prompts/interactive-webgpu-jelly-dragon-fruit-with-soft-body-physics-2103433535604265052?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [原帖](https://x.com/vib3coded/status/2103433535604265052)

---

### [20秒人生循环主题的动态图形作品集短片](https://wandy3d.com/zh/prompts/20-second-motion-graphics-showreel-about-the-cycle-of-life-2103428454355980558?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/zh/prompts/20-second-motion-graphics-showreel-about-the-cycle-of-life-2103428454355980558?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/20-second-motion-graphics-showreel-about-the-cycle-of-life-2103428454355980558.webp" width="640" alt="20秒人生循环主题的动态图形作品集短片"></a>

**Claude Opus 5.5** · 动画 · 作者 [Loïc](https://x.com/loicRambo) · 2026-09-25

Claude Opus 5.5 生成了可循环的2D动画短片:同一角色从童年、职场、家庭走到老年,画面带有心率读数。

<details>
<summary>提示词</summary>

```text
make a dynamic 20-second motion graphics and animation video that shows what an incredible motion designer and animator you are, like it's your showreel for a résumé. make it about the cycle of life showing the same individual going from childhood to adolescence to the 9-5 cycle, to family life to elder life and death, then cutting ready to loop to the beginning.  go all out , use whatever you need.
```

</details>

[在 Wandy3D 查看 ↗](https://wandy3d.com/zh/prompts/20-second-motion-graphics-showreel-about-the-cycle-of-life-2103428454355980558?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [原帖](https://x.com/loicRambo/status/2103428454355980558)

---

### [Three.js 月夜柏树沼泽:倒影水面与漂行小船](https://wandy3d.com/zh/prompts/moonlit-cypress-swamp-in-three-js-with-reflective-water-and-2103310302993621090?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/zh/prompts/moonlit-cypress-swamp-in-three-js-with-reflective-water-and-2103310302993621090?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/moonlit-cypress-swamp-in-three-js-with-reflective-water-and-2103310302993621090.webp" width="640" alt="Three.js 月夜柏树沼泽:倒影水面与漂行小船"></a>

**GPT-6 Astra** · 场景 · 作者 [YouWare](https://x.com/YouWareAI) · 2026-09-25

GPT-6 Astra 生成了宁静的网页世界:亮灯小船漂过雾气沼泽,重点是水面着色器,并带昼夜切换。

<details>
<summary>提示词</summary>

```text
Build a browser experience in Three.js called STILLWATER.  Tone: a moonlit swamp you get lost in. Not a game with enemies. Not photoreal Unreal. A quiet, expensive-looking web world where the water reflections are the feature. People should stare at the water for an unhealthy amount of time.  SETTING - Location title: THE DEEP SWAMP - Time on the HUD: 19:26 - First named place: Heron bend - Tagline under the place name: "Leave a little room for the wild." - Discovery toast when you arrive: "Discovered: Heron bend"  WORLD A flooded cypress swamp at moonrise / late dusk. - Tall knobby-kneed trees standing in black-green water - Spanish moss hanging in long strands - Lily pads clustered along the banks - Narrow winding channel that opens into a wider bend - Thick volumetric fog, teal-green distance, purple-pink cloudy sky - A bright moon with a long broken reflection path on the water - A few birds crossing the sky - Warm cabin light from the boat punching through the gloom  WATER (do not cheap out) This is the hero. - Real-time reflections of trees, moon, fog and boat lights - Gentle swell, not ocean waves - Lily pads that sit on the surface and bob - Shoreline foam / dark tannin water near roots - Screen-space or planar reflections good enough that the moon path feels cinematic - Keep 60fps. LOD the trees, instanced foliage.  BOAT A small weathered cabin skiff / workboat. - Hull number 86 on the stern - White cabin, dark blue hull, warm interior lamps - Idle drift through the channel, optional slow guided tour - HUD speed around 15.9 KNOTS - Mode label: GUIDED DRIFT Player can look around. Boat can be followed from a cinematic chase / side orbit.  CAMERA - Start on a three-quarter of the boat in the trees - Drift behind the stern down the moonlit lane - Occasional side slide past a foreground trunk - Drag to look - Optional PHOTO MODE Feel like a nature documentary, not an FPS.  UI — editorial, not gamey Top-left: small mark + STILLWATER Top-center: THE DEEP SWAMP / 19:26, a compass heading (e.g. 314°) Top-right: quiet utility icons Bottom-left:   EXPLORING STILLWATER   Heron bend   Leave a little room for the wild.   15.9 KNOTS    GUIDED DRIFT Bottom-right: PHOTO MODE, fps, Pause Center-bottom: small toast "Discovered: Heron bend" Tiny hint row: shaders / water / drag to look / photos / wildlife  Look: dark filmic grade, muted greens, magenta clouds, one moon highlight. Taste over realism. No bloated debug GUI.  TECH Three.js in the browser. Procedural / instanced nature. Custom water shader. Fog. Soft shadows or baked-looking dusk lighting. No asset-store swamp pack if you can author it.  DO NOT add combat, inventory, jump scares, or a treasure hunt. Something can lurk underwater later — not now.
```

</details>

[在 Wandy3D 查看 ↗](https://wandy3d.com/zh/prompts/moonlit-cypress-swamp-in-three-js-with-reflective-water-and-2103310302993621090?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [原帖](https://x.com/YouWareAI/status/2103310302993621090)

---

### [单个 Three.js HTML 实现的海上平台火箭发射电影](https://wandy3d.com/zh/prompts/cinematic-ocean-platform-rocket-launch-in-one-three-js-html-2103303449831964679?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/zh/prompts/cinematic-ocean-platform-rocket-launch-in-one-three-js-html-2103303449831964679?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/cinematic-ocean-platform-rocket-launch-in-one-three-js-html-2103303449831964679.webp" width="640" alt="单个 Three.js HTML 实现的海上平台火箭发射电影"></a>

**Claude Opus 5.5** · 动画 · 作者 [NinjaCodex](https://x.com/N1njaCodex) · 2026-09-25

同一提示词对比两个 Opus 版本;Claude Opus 5.5 的黎明发射包含分级、整流罩分离和卫星展开太阳能板。

<details>
<summary>提示词</summary>

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

[在 Wandy3D 查看 ↗](https://wandy3d.com/zh/prompts/cinematic-ocean-platform-rocket-launch-in-one-three-js-html-2103303449831964679?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [原帖](https://x.com/N1njaCodex/status/2103303449831964679)

---

### [Three.js 互动中世纪王国:吊桥、巡逻守卫与昼夜切换](https://wandy3d.com/zh/prompts/interactive-three-js-medieval-kingdom-with-drawbridge-guards-2103257873203462412?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts)

<a href="https://wandy3d.com/zh/prompts/interactive-three-js-medieval-kingdom-with-drawbridge-guards-2103257873203462412?utm_source=github&amp;utm_medium=referral&amp;utm_campaign=awesome_3d_prompts"><img src="../assets/previews/interactive-three-js-medieval-kingdom-with-drawbridge-guards-2103257873203462412.webp" width="640" alt="Three.js 互动中世纪王国:吊桥、巡逻守卫与昼夜切换"></a>

**Claude Opus 5.5** · 互动 · 作者 [Vib3Coded](https://x.com/vib3coded) · 2026-09-24

两个模型用同一城堡提示词的对比;Claude Opus 5.5 做出带红屋顶、护城河、村庄和群山的可探索王国。

<details>
<summary>提示词</summary>

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

[在 Wandy3D 查看 ↗](https://wandy3d.com/zh/prompts/interactive-three-js-medieval-kingdom-with-drawbridge-guards-2103257873203462412?utm_source=github&utm_medium=referral&utm_campaign=awesome_3d_prompts) · [原帖](https://x.com/vib3coded/status/2103257873203462412)

---

[← 上一页](catalog.zh.1.md) · 第 2 页，共 2 页

提示词、视频和图片的权利归原作者所有（[RIGHTS.md](../RIGHTS.md)）。我们撰写的文字采用 [CC BY 4.0](../LICENSE) 许可。知道有成果展示的好提示词？[推荐给我们](https://github.com/wornoxgames/awesome-3d-prompts/issues/new?template=suggest.md)。如果你是作者并希望修改或删除条目，请[联系我们](https://github.com/wornoxgames/awesome-3d-prompts/issues/new?template=removal.md)。
