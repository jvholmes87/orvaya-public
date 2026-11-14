# Public Production Toolchain Register
Status: INITIAL / NOT YET VALIDATED

| Tool | Intended use | Status | Evidence |
|---|---|---|
| Unreal Engine | Cinematic 3D production | Proposed | Hardware and pipeline evaluation pending |
| MetaHuman | Digital character workflow | Proposed | Evaluation pending |
| Blender | 3D assets and rigging | Proposed | Evaluation pending |
| GitHub | Source and documentation control | In use | Orvaya repositories |
| ChatGPT | Planning and documentation assistance | In use | Initial governance drafts and repository setup |

Version, licensing, cost, test results and actual episode usage will be recorded as validated.

## Animation ecosystem intake — 2026-11-14
Source: founder-supplied list of 18 open-source repositories. This is an **evaluation backlog**, not an approved or installed software bill of materials. P0 = investigate first, P1 = evaluate next, P2 = optional, P3 = defer. GitHub URLs below are discovery pointers and have not all been independently validated.

| Candidate | Priority | Proposed use | Status | Repository |
|---|---|---|---|---|
| Blender | P0 | 3D modeling, rigging, character animation | Proposed / not tested | https://github.com/blender/blender |
| Remotion Skills | P0 | Agent guidance for programmatic video; assess Remotion separately | Proposed / not tested | https://github.com/remotion-dev/skills |
| Three.js | P0 | Interactive 3D website and preview tools | Proposed / not tested | https://github.com/mrdoob/three.js |
| Motion Canvas | P1 | Animated technical explainers | Proposed / not tested | https://github.com/motion-canvas/motion-canvas |
| Manim | P1 | Scientific and mathematical visualizations | Proposed / not tested | https://github.com/ManimCommunity/manim |
| Lottie Web | P1 | Vector animation playback on website | Proposed / not tested | https://github.com/airbnb/lottie-web |
| Anime.js | P1 | Web timelines and staggered motion | Proposed / not tested | https://github.com/juliangarnier/anime |
| Godot | P2 | Optional interactive simulation | Proposed / not tested | https://github.com/godotengine/godot |
| Babylon.js | P2 | Alternative web 3D engine | Proposed / not tested | https://github.com/BabylonJS/Babylon.js |
| Konva | P2 | Interactive canvas/storyboard tooling | Proposed / not tested | https://github.com/konvajs/konva |
| Two.js | P2 | 2D vector animation | Proposed / not tested | https://github.com/jonobr1/two.js |
| gifenc | P2 | Animated GIF encoding | Proposed / not tested | https://github.com/mattdesl/gifenc |
| Motion | P2 | Web layout transitions | Proposed / not tested | https://github.com/motiondivision/motion |
| Ola | P3 | Value interpolation | Proposed / not tested | https://github.com/franciscop/ola |
| Shifty | P3 | Tween playback | Proposed / not tested | https://github.com/jeremyckahn/shifty |
| TweenJS | P3 | Property tween sequences | Proposed / not tested | https://github.com/CreateJS/TweenJS |
| LUME | P3 | HTML-based 3D scenes | Proposed / not tested | https://github.com/lume/lume |
| Proton | P3 | Web particle effects | Proposed / not tested | https://github.com/drawcall/Proton |

### Evaluation gates
1. Confirm repository identity, maintenance status, license, and compatibility with commercial use.
2. Verify OS/GPU/runtime requirements and integration with Unreal Engine, Blender, GitHub Pages, and chosen editing workflow.
3. Produce a small reproducible proof of concept; record version, commands, test media, rendering performance, accessibility where applicable, and limitations.
4. Assess asset provenance, security, cost, learning curve, maintenance, and pipeline redundancy.
5. Founder approval is required to change a tool from Proposed to Approved or In use. Keep exact version and evidence links.

**Architecture note:** Remotion Skills is agent guidance rather than a standalone video editor. Multiple browser animation engines should not be adopted simultaneously without a demonstrated need. Unreal Engine and MetaHuman remain separately proposed.
