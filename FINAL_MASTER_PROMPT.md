# FINAL MASTER PROMPT — MINECRAFT ENDLESS DREAM

You are an expert Three.js/WebGL engineer, real-time graphics programmer, technical artist, animation engineer, cinematic director and audio engineer. Build a functional, visually polished, browser-based 3D cinematic parkour experience for a personal collection, not a slideshow or fake video.

FIRST read PROJECT_RULES.md as the non-negotiable creative and engineering specification. All choices in it are locked. Build the app, not just a description. If working in Claude Artifacts, adapt to supported dependencies and browser APIs, and clearly state limits. Do not claim tests you did not run.

## Architecture
Build modular scene/renderer, character rig and animation, deterministic 20s cinematic timeline, automatic parkour path, procedural endless course generator, adaptive drone camera, lighting and volumetric cloud renderer, mirror portal shader, particle effects, audio mixer, UI and export manager. Use object pooling, instancing, LOD and adaptive resolution for browser performance.

## Character and course
Create Enhanced Steve with iconic blocky proportions, pixel textures, turquoise shirt, dark blue pants, articulated arms/legs and responsive Enhanced Parkour motion: sprint lean, jump preparation, takeoff, midair adjustment, precision landings and recovery. Avoid robotic movement or exaggerated acrobatics. Cinematic Mode uses a deterministic 20s handcrafted route with floating platforms, spiral stairs, rotating/disappearing blocks, edge landings and impossible-gravity moments. Endless Mode generates varied traversable segments and reuses discarded assets without abrupt resets.

## Camera and visual world
A single continuous Adaptive Cinematic Drone shot: smooth tracking, occasional wide reveal, dramatic but readable orbit, low-angle jumps, speed-ramped close-ups and stable portal entry. Preserve vertical 9:16 composition. Hybrid AAA Voxel terrain combines pixel block identity with PBR-like materials, shadows, fog, bloom, filmic tone mapping and atmospheric perspective where supported. Volumetric clouds should have convincing depth and respond to lighting; use efficient approximations if necessary. Transition lighting smoothly from golden-pink sunset through lavender twilight to deep-blue moonlit night across the cinematic. Add particles, jump trails, landing dust and restrained camera shake.

## Mirror Portal
A huge floating reflective mirror shows the sunset world while surrounding scene is night. At the ending, Steve leaps through; the mirror ripples with light, camera follows without a hard cut, and the view transitions seamlessly to the start environment. A visual loop does not restart Endless Mode music.

## 20-second cinematic choreography (initial timing, adjust only to measured audio accents)
- 0–4s: establish floating islands, Steve accelerates, drone reveals landscape.
- 4–9s: faster precision parkour and camera tracking.
- 9–14s: extreme jumps, dramatic speed ramps and magical environmental reaction.
- 14–17s: approach and frame Mirror Portal.
- 17–20s: final jump, ripple and seamless visual return to opening.

## Audio: essential
Use included BACKSOUND_13s-33s.mp3. This file is ALREADY the 20-second excerpt from original source 13.0–33.0 seconds; play from its beginning and DO NOT cut a second time. Dedicated music bus and SFX buses must coexist. Add real or browser-synthesized voxel footsteps, sprint, jump, landing, wind, floating island ambience, rotating/vanishing platforms, cinematic whooshes, portal resonance/ripple and magical shimmer. Provide separate music/SFX volume and mute. Avoid clipping. Standalone export should apply configurable fade-in ~0.5s and fade-out ~1.0s to music while retaining SFX. For Endless Mode, Continuous Music means the visual portal cycle never restarts music; if only this 20s clip exists, offer an explicitly labeled loop or stop-at-end fallback, and support loading a longer authorized music file later. Do not invent beat timestamps; analyze the supplied file when technically possible. Visual speed ramps must not change music playback rate.

## Hybrid player and export
Offer Cinematic Mode (deterministic 20s, replay, pause, export) and Endless Mode (ongoing procedural auto-parkour). Footage has no HUD; tap/click reveals minimal controls, settings live separately. Make mobile-responsive. Target 1080x1920, 60fps preferred with 30fps fallback, and combined music+SFX in exported 20s video. Implement real browser-compatible capture and audio mix; use WebM if MP4 not available, and disclose unsupported browser limitations. Do not claim export success before file creation.

## Acceptance and implementation order
Implement in coherent order: renderer/scene → Steve/parkour → camera/timeline → world/clouds/lighting → effects/portal → endless generation → audio/SFX → UI → export → optimize/test. Verify runtime behavior as far as environment permits. Do not replace 3D with screenshots, omit SFX, restart music at the portal, or mark unfinished features complete. Report in Indonesian and identify limitations truthfully. Do not ask for new creative decisions: the concept is final.
