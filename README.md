# 🎬 Awesome Seedance 3 — Prompts & API Guide

> A practical prompt library and API guide for ByteDance Seedance 3. Prompts are creative starting points; API availability, routes, and parameters are still being confirmed.

[![Seedance 3](https://img.shields.io/badge/Seedance-3-blue)](https://seed.bytedance.com)
[![Integration](https://img.shields.io/badge/API%20integration-in%20progress-6366f1)](https://muapi.ai/seedance-3)
[![Stars](https://img.shields.io/github/stars/SamurAIGPT/awesome-seedance-3-api-prompts?style=social)](https://github.com/SamurAIGPT/awesome-seedance-3-api-prompts)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Status

Seedance 3 API access through MuAPI is being prepared. This repository collects prompt patterns and examples that can be adapted when the endpoint is available. It does **not** claim unannounced API features, limits, pricing, or request schemas. Check the [MuAPI Seedance 3 page](https://muapi.ai/seedance-3) and [Seedance-3-API](https://github.com/Anil-matcha/Seedance-3-API) for integration updates.

## Prompting framework

Build prompts from concrete ingredients. Put the subject and action first, then specify the shot, environment, light, motion, and sound when relevant.

```text
[Subject] + [action] + [setting] + [shot and camera movement]
+ [lighting and visual style] + [timing] + [sound] + [constraints]
```

Example: “A red paper kite breaks free from a child's hand and climbs above a seaside cliff. Begin in a medium shot, then tilt up and track the kite into a wide view of the coast. Late-afternoon backlight, natural colors, steady camera. Wind and distant surf only. Keep the kite red; no titles or logos.”

Use only controls supported by the interface you call. A prompt cannot guarantee duration, resolution, frame rate, audio behavior, or reference limits.

## Prompt library

### Cinematic storytelling

**1. The last train**

```text
A tired traveler steps onto a nearly empty night train just before the doors close.
Start with a wide platform view, track beside them into the carriage, then settle on
their reflection in the window as city lights pass. Cool platform light shifts to warm
carriage light. Quiet, restrained drama; no text or music.
```

**2. Storm over the lighthouse**

```text
A lighthouse keeper opens the storm door and looks out over a violent ocean. Push
from behind the keeper toward the doorway; hold as waves crash against the rocks.
Blue-grey storm light, rain streaking across the lens, realistic water and wind.
Keep the interior dim and the keeper's silhouette readable.
```

**3. A small act of kindness**

```text
On a rainy city sidewalk, a cyclist stops to share an umbrella with an older stranger.
Observe from across the street in a patient medium-wide shot, then gently move closer
as they exchange a grateful smile. Overcast reflections, natural performances,
documentary realism. Rain and distant traffic only; no captions.
```

### Product and advertising

**4. Bottle on black glass**

```text
A dark glass fragrance bottle stands on reflective black glass. A narrow beam of light
travels slowly across it, revealing its silhouette and surface texture. Smooth, controlled
orbit; luxury studio lighting, deep shadows, crisp highlights. End on a still hero frame.
No invented label text.
```

**5. Fresh coffee, morning light**

```text
Close shot of espresso pouring into a ceramic cup; crema forms as steamed milk draws
a simple leaf. Slowly pull back to reveal the cup on a sunlit cafe counter. Warm window
light, gentle steam, tactile detail. Espresso machine hiss and cup sounds only.
```

**6. Running shoe in motion**

```text
A runner in a neutral outfit accelerates along an urban track at dawn. Low tracking
shot follows the shoes striking the ground, then rises to a side profile. Keep the same
shoe design and color throughout. Crisp directional light, believable motion. No logos.
```

### Nature and documentary

**7. Hummingbird in a garden**

```text
A hummingbird hovers beside a red flower, drinks briefly, then darts out of frame.
Macro telephoto composition, steady camera, shallow depth of field. Soft morning light,
fine feather detail, believable wing movement, quiet garden ambience. No extra birds.
```

**8. Glacier calving**

```text
A wide documentary view of a blue glacier beneath a pale overcast sky. Cracks spread,
a section breaks away and crashes into the water, sending a distant wave outward. Hold
the camera steady so the scale reads. Natural cold color, realistic ice and water; wind
and deep ice rumble only.
```

**9. Monsoon street**

```text
A quiet old-city lane fills with monsoon rain. Water ripples across stone paving, a
shopkeeper pulls in a chair, and a scooter passes at the far end. Static wide shot,
layered depth, muted earth colors and reflected lamps. Natural rain and street ambience;
no readable shop signs.
```

### Fashion and beauty

**10. Fabric in a breeze**

```text
A model in a flowing ivory linen outfit walks across a sunlit courtyard. Begin full
length, move in a gentle parallel track, then finish on fabric lifting in the breeze.
Keep outfit, face, and hair consistent. Soft natural light, understated editorial style.
```

**11. Skincare drop**

```text
Macro beauty shot of a clear serum drop sliding down a frosted glass bottle. A soft
highlight travels across the glass as the camera slowly pushes in. Clean pale background,
precise reflections, minimal styling. Do not add labels, lettering, or extra droplets.
```

### Sci-fi and fantasy

**12. Greenhouse on Mars**

```text
Inside a glass greenhouse on Mars, an astronaut gently waters a tomato plant. Begin
close on a drop falling into red soil, then reveal the curved habitat and rust-colored
landscape outside. Warm grow lights against cool exterior light. Keep the suit intact.
```

**13. The paper dragon**

```text
A folded paper dragon lifts from a desk and glides through a child's bedroom, weaving
between drawings before landing beside an open sketchbook. Follow at the dragon's height
in one graceful move. Cozy lamplight, handmade paper texture, whimsical stop-motion feel.
Preserve the same origami shape throughout.
```

### Motion and action

**14. Rooftop crossing**

```text
A skilled athlete runs across a low rooftop, vaults one gap, lands safely, and slows
to look toward the skyline. Side tracking shot keeps the full body visible; no impossible
flips or sudden cuts. Late-afternoon light, clear movement, realistic balance.
```

**15. Dance in a pool of light**

```text
A solo dancer performs a short contemporary phrase inside a circle of warm light on a
dark stage. The camera makes a slow half-orbit while keeping the full body in frame.
Fluid but plausible choreography, visible fabric movement, subtle footfalls. Keep costume
and lighting consistent; no audience.
```

### Animation and social formats

**16. Tiny delivery robot**

```text
A palm-sized yellow delivery robot rolls through a busy kitchen, avoids spilled flour,
and stops beside a waiting plate. Low camera at robot height, playful timing, rounded
handcrafted 3D design. Keep its single blue status light and body shape consistent; no text.
```

**17. Watercolor fox**

```text
A small watercolor fox walks across a snowy field, leaving delicate painted pawprints.
The camera pans slowly with it as pale winter trees appear in the distance. Visible paper
grain, soft pigment blooms, gentle storybook mood. Maintain the same fox design.
```

**18. Recipe opener (vertical)**

```text
Vertical close-up of hands assembling a vegetable wrap: spread sauce, layer crisp
vegetables, then roll it tightly. One overhead angle, bright window light, fast but legible
movements. Keep ingredients in frame; no labels, subtitles, or extra fingers.
```

**19. Travel reveal (vertical)**

```text
Begin close behind a traveler opening a wooden balcony shutter, then ease around their
shoulder to reveal a quiet coastal village at sunrise. Stable movement, natural colors,
a few seabirds in the distance. Leave uncluttered sky at the top for later editing.
```

### Multi-shot sequence

**20. From seed to harvest**

```text
Create a cohesive four-beat story in the same small garden, with consistent camera
direction and natural light progression:
1. Close-up: hands press a seed into dark soil.
2. Match cut: a sprout emerges after rain.
3. Medium shot: the plant grows beside a wooden stake.
4. Close-up: ripe tomatoes are picked and placed in a basket.
Grounded documentary style, no time-lapse distortions, no text.
```

## Reference-guided prompts

If the interface supports image or video references, explain what each reference should control. Confirm the provider's syntax and supported media before using tokens such as `@image1`.

**Product:** “Use the supplied image as the exact shape, color, and material reference for the backpack. Show it on a stone ledge during a light mountain drizzle. Slow push-in; droplets gather on the fabric and run off. Preserve seams and hardware. Do not invent a logo or alter proportions.”

**Character:** “Use the supplied portrait as the appearance reference for the traveler. Keep their face, short curly hair, olive jacket, and canvas bag consistent. They walk from a station platform into the concourse in a medium tracking shot. Soft morning light; no wardrobe changes.”

**Style:** “Use the supplied image only as a color and texture reference: dusty rose, deep teal, matte paper grain, and soft edge lighting. Show a quiet flower market at dawn. Do not reproduce the reference's people, objects, or composition.”

## Iteration tips

- Lead with one subject and one main action.
- Describe camera movement with one clear verb: lock off, pan, track, tilt, orbit, or push in.
- State important constraints directly: “one person,” “same jacket throughout,” or “no text.”
- Separate successive actions in time or with numbered beats.
- For reference-guided work, say what must stay the same and what may change.
- Change one prompt element at a time to see which edit helped.
- Treat aspect ratio, duration, resolution, audio, and seed as API settings only when documented by the endpoint.

## API access and related projects

- [Seedance 3 on MuAPI](https://muapi.ai/seedance-3) — integration status and updates
- [Seedance-3-API](https://github.com/Anil-matcha/Seedance-3-API) — companion developer project
- [Seedance 2.5 API prompts](https://github.com/Anil-matcha/awesome-seedance-2.5-api-prompts) — existing guide and prompt library
- [Seedance 2.5 API](https://github.com/SamurAIGPT/Seedance-2.5-API) — available Seedance API example
- [MuAPI video generation guide](https://muapi.ai/docs/video-generation) — shared asynchronous workflow docs

When Seedance 3 routes become available, add verified request examples, parameter tables, pricing, and playground links with their sources and verification dates.

## Contributing

Contributions are welcome. Add original prompts, improve clarity, or submit verified API details with a link to provider documentation. Label assumptions and unverified behavior clearly.

## License

MIT. See [LICENSE](LICENSE).
