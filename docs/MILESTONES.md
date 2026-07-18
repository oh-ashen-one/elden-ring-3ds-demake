# Development and footage log

Record real builds while they exist. Do not reconstruct fake broken-build footage later.

| Milestone | Build/commit | What changed | Honest visible problems | Metrics | Capture request |
| --- | --- | --- | --- | --- | --- |
| M0 Toolchain probe | local source toolchain | devkitARM detected; official 3DS libraries/tools built into a user-writable prefix because system install needs an administrator password | System-wide packages still pending | libctru/citro3d/citro2d/3dstools/picasso/3dslink built | Terminal/toolchain establishing shot |
| M1 Native foundation | `2b210e1` | Core state machines, procedural renderer, dual-screen UI, audio and tests | Awaiting physical rendering validation | Host tests and native cross-build pass | First boot, malformed poses, camera issues |
| M2 Connected slice | `89a5202` | Interior reveal, vista NPC and masked fog transition | Visual handoff timing is unverified on device | Visible/culled-object and measured per-zone linear-memory peaks implemented | Door handoff and outdoor reveal |
| M3 Boss | `89a5202` | Lock-on, stamina combat and Ashen Warden; expanded rigid hierarchy | Hit readability and performance are unverified on device | CI run `29656291832` passed; Azahar boot smoke rendered both screens after UI-state fix | Boss behaviors and failures |
| M4 Content/architecture hardening | pending next commit | Generated registry and zones, Blender/tex3ds pipeline, 15-bone clips, indexed rendering, lifecycle/session handling, deeper validation and smoke flows | New textured renderer still needs physical visual/performance review | Local audit, 9-asset validation, 53 static props, deterministic host tests, native artifact verifier | Asset conversion, atlas before/after, debug overlay and zone handoffs |
| M5 Hardware candidate | pending | Optimization and acceptance build | Must be recorded honestly | Three-run report | Uncut Homebrew Launcher-to-game proof |
