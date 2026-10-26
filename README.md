# Babylon.js (babylon-js)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Babylon.js is an Apache-2.0 licensed, TypeScript-first open-source 3D engine and rendering framework sponsored by Microsoft and developed in the public BabylonJS GitHub organization. It targets WebGL, WebGPU, and WebXR in the browser, and DirectX, Metal, Vulkan, OpenGL, and OpenGL ES natively through Babylon Native — including a Babylon React Native binding for mobile. The framework ships as a family of scoped npm packages plus a rich tooling surface — Playground, Sandbox, Inspector, Spector.js, the Node Material / Geometry / Particle / Render-Graph editors, a community Editor, the Babylon Toolkit (Unity / Unreal exporters), DCC exporters for 3ds Max / Maya / Blender, and a public Snippet API at `snippet.babylonjs.com`.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/babylon-js/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Tags

 - 3D, Game Engine, Rendering, WebGL, WebGPU, WebXR, TypeScript, glTF, Open Source, Microsoft

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## At a glance

| | |
|---|---|
| License | Apache-2.0 |
| Sponsor | Microsoft |
| Primary language | TypeScript |
| Current version | 9.x (v9.9.1, May 2026) |
| Render backends | WebGL2, WebGPU; DirectX / Metal / Vulkan / OpenGL via Babylon Native |
| Package registry | npm (`@babylonjs/*` and `babylonjs`) |
| Governance | Community-led on forum.babylonjs.com; CoC via Contributor Covenant 1.4 |
| Source | [github.com/BabylonJS/Babylon.js](https://github.com/BabylonJS/Babylon.js) |

## APIs

### Babylon.js Core
The core Babylon.js engine and scene graph — Engine, Scene, cameras, lights, meshes, materials, textures, animation, post-processing, particles, physics integration, audio, and the WebGL2 / WebGPU backends. Published as `@babylonjs/core`.

- [Documentation — Scene](https://doc.babylonjs.com/features/featuresDeepDive/scene)
- [TypeDoc](https://doc.babylonjs.com/typedoc/modules/BABYLON)
- [npm — @babylonjs/core](https://www.npmjs.com/package/@babylonjs/core)
- [Source](https://github.com/BabylonJS/Babylon.js/tree/master/packages/dev/core)

### Babylon.js GUI
2D and 3D GUI library — buttons, sliders, panels, inputs, color pickers, and 3D holographic controls — rendered through a dynamic texture or as 3D meshes. Authored visually via the GUI Editor.

- [Documentation](https://doc.babylonjs.com/features/featuresDeepDive/gui)
- [GUI Editor](https://gui.babylonjs.com/)
- [npm — @babylonjs/gui](https://www.npmjs.com/package/@babylonjs/gui)

### Babylon.js Loaders
Asset importers for glTF 2.0 (with KHR extensions), OBJ, STL, USDZ, SPLAT (Gaussian splats), and more.

- [Documentation](https://doc.babylonjs.com/features/featuresDeepDive/importers)
- [npm — @babylonjs/loaders](https://www.npmjs.com/package/@babylonjs/loaders)

### Babylon.js Materials
Specialty materials — water, lava, fire, fur, terrain, cell, mix, gradient, sky, grid, normal, shadow-only — built on top of Babylon's Standard and PBR materials.

- [Documentation](https://doc.babylonjs.com/features/featuresDeepDive/materials)
- [npm — @babylonjs/materials](https://www.npmjs.com/package/@babylonjs/materials)

### Babylon.js Post-Processes
Additional post-processing effects beyond core — ASCII art, anaglyph, digital rain, ocean, and other stylized pipelines.

- [Documentation](https://doc.babylonjs.com/features/featuresDeepDive/postProcesses)
- [npm — @babylonjs/post-processes](https://www.npmjs.com/package/@babylonjs/post-processes)

### Babylon.js Procedural Textures
GPU-generated procedural textures — brick, cloud, fire, grass, marble, normal-map, perlin-noise, road, starfield, wood.

- [Documentation](https://doc.babylonjs.com/features/featuresDeepDive/materials/using/proceduralTextures)
- [npm — @babylonjs/procedural-textures](https://www.npmjs.com/package/@babylonjs/procedural-textures)

### Babylon.js Serializers
Scene exporters that serialize a live Babylon scene to glTF 2.0, OBJ, STL, or .babylon JSON.

- [Documentation](https://doc.babylonjs.com/features/featuresDeepDive/Exporters)
- [npm — @babylonjs/serializers](https://www.npmjs.com/package/@babylonjs/serializers)

### Babylon.js Inspector
Embeddable developer tool overlaying a live tree of every Babylon scene object with property editing, gizmos, and tweakable shaders.

- [Documentation](https://doc.babylonjs.com/toolsAndResources/inspector)
- [npm — @babylonjs/inspector](https://www.npmjs.com/package/@babylonjs/inspector)

### Babylon.js Node Editors
Visual node-graph authoring tools — Node Material Editor (NME), Node Geometry Editor (NGE), Node Particle Editor (NPE), and Node Render Graph Editor — producing serializable JSON graphs that the core engine evaluates at runtime.

- [Documentation](https://doc.babylonjs.com/toolsAndResources/nodeEditors)
- [Node Material Editor](https://nme.babylonjs.com/)
- [Node Geometry Editor](https://nge.babylonjs.com/)
- [Node Particle Editor](https://npe.babylonjs.com/)

### Babylon.js Playground
Hosted browser-based IDE for writing and sharing Babylon scenes as TypeScript snippets. Backed by the Snippet Server with shareable IDs and a public read API at `snippet.babylonjs.com`.

- [Documentation](https://doc.babylonjs.com/toolsAndResources/thePlayground)
- [Playground](https://playground.babylonjs.com/)
- [Snippet API](https://snippet.babylonjs.com/)

### Babylon.js Sandbox
Drop-in browser viewer for 3D assets — glTF/GLB, OBJ, STL, USDZ, SPLAT, .babylon — with Inspector integration, IBL environment, and animation playback. The reference glTF viewer for the Babylon pipeline.

- [Documentation](https://doc.babylonjs.com/toolsAndResources/sandbox)
- [Sandbox](https://sandbox.babylonjs.com/)

### Babylon.js Snippet API
Public REST endpoint at `https://snippet.babylonjs.com/` that stores and serves serialized JSON snippets for the Playground, Node Material Editor, Node Geometry Editor, Node Particle Editor, and GUI Editor. The same snippet IDs can be loaded at runtime via Babylon's snippet loaders to pull live assets into a scene.

- [Documentation — Snippet Server](https://doc.babylonjs.com/toolsAndResources/thePlayground/playgroundSnippet)

### Babylon Native
C++ host that runs the Babylon.js engine on top of native graphics APIs (DirectX, Metal, Vulkan, OpenGL, OpenGL ES) without a browser. Targets Windows, macOS, Linux, Android, and iOS.

- [Source](https://github.com/BabylonJS/BabylonNative)
- [Documentation](https://doc.babylonjs.com/communityExtensions/BabylonNative)

### Babylon React Native
React Native binding that runs Babylon Native on iOS and Android with a React component (`EngineView`) for embedding Babylon scenes in cross-platform mobile applications.

- [Source](https://github.com/BabylonJS/BabylonReactNative)
- [npm — @babylonjs/react-native](https://www.npmjs.com/package/@babylonjs/react-native)

### Babylon.js Editor
Community-maintained visual editor for authoring Babylon.js scenes — scene graph, materials, animations, GUI, scripting, post-processing, and asset pipeline — exporting to runnable Babylon.js projects.

- [Portal](https://editor.babylonjs.com/)
- [Source](https://github.com/BabylonJS/Editor)

### Babylon Toolkit
Community-maintained Unity and Unreal exporters and a runtime scripting layer that lets engines author scenes in Unity / Unreal and export them to Babylon.js for web delivery.

- [Source](https://github.com/BabylonJS/BabylonToolkit)

### Babylon.js Exporters
First-party DCC exporters for 3ds Max, Maya, and Blender that emit .babylon and glTF 2.0 assets compatible with the Babylon.js runtime, Sandbox, and Editor pipelines.

- [Source](https://github.com/BabylonJS/Exporters)
- [Documentation](https://doc.babylonjs.com/features/featuresDeepDive/Exporters)

### Spector.js
Browser extension and embeddable library that captures and inspects WebGL / WebGPU frames — every draw call, state change, shader, texture, and uniform — for any 3D web application.

- [Portal](https://spector.babylonjs.com/)
- [Source](https://github.com/BabylonJS/Spector.js)

## Common Properties

- [Portal — babylonjs.com](https://www.babylonjs.com/)
- [Documentation — doc.babylonjs.com](https://doc.babylonjs.com/)
- [GettingStarted](https://doc.babylonjs.com/setup/frameworkPackages/firstApp)
- [GitHubOrganization — BabylonJS](https://github.com/BabylonJS)
- [SourceCode — Babylon.js](https://github.com/BabylonJS/Babylon.js)
- [License — Apache-2.0](https://github.com/BabylonJS/Babylon.js/blob/master/license.md)
- [Code of Conduct](https://github.com/BabylonJS/Babylon.js/blob/master/CODE_OF_CONDUCT.md)
- [Contributing Guide](https://github.com/BabylonJS/Babylon.js/blob/master/contributing.md)
- [ChangeLog — What's New](https://doc.babylonjs.com/setup/support/whatsNew)
- [Releases](https://github.com/BabylonJS/Babylon.js/releases)
- [Issues](https://github.com/BabylonJS/Babylon.js/issues)
- [Forum — forum.babylonjs.com](https://forum.babylonjs.com/)
- [Blog — Medium](https://babylonjs.medium.com/)
- [YouTube](https://www.youtube.com/@BabylonJSEngine)
- [Twitter / X — @babylonjs](https://twitter.com/babylonjs)
- [TypeDoc](https://doc.babylonjs.com/typedoc/modules/BABYLON)
- [Sandbox — Playground](https://playground.babylonjs.com/)
- [Sandbox — Sandbox](https://sandbox.babylonjs.com/)
- [Sandbox — Node Material Editor](https://nme.babylonjs.com/)
- [Sandbox — Node Geometry Editor](https://nge.babylonjs.com/)
- [Sandbox — Node Particle Editor](https://npe.babylonjs.com/)
- [Sandbox — GUI Editor](https://gui.babylonjs.com/)
- [API — Snippet Server](https://snippet.babylonjs.com/)
- [Tool — Spector.js](https://spector.babylonjs.com/)
- [Tool — Babylon.js Editor](https://editor.babylonjs.com/)
- [Tool — Babylon Native](https://github.com/BabylonJS/BabylonNative)
- [Tool — Babylon React Native](https://github.com/BabylonJS/BabylonReactNative)
- [Tool — Babylon Toolkit (Unity / Unreal)](https://github.com/BabylonJS/BabylonToolkit)
- [Tool — DCC Exporters](https://github.com/BabylonJS/Exporters)
- [Integrations — Community Extensions](https://doc.babylonjs.com/communityExtensions)
- [Documentation — Physics](https://doc.babylonjs.com/features/featuresDeepDive/physics)
- [Documentation — WebXR](https://doc.babylonjs.com/features/featuresDeepDive/webXR)

## SDKs (npm)

- [`@babylonjs/core`](https://www.npmjs.com/package/@babylonjs/core)
- [`@babylonjs/gui`](https://www.npmjs.com/package/@babylonjs/gui)
- [`@babylonjs/loaders`](https://www.npmjs.com/package/@babylonjs/loaders)
- [`@babylonjs/materials`](https://www.npmjs.com/package/@babylonjs/materials)
- [`@babylonjs/post-processes`](https://www.npmjs.com/package/@babylonjs/post-processes)
- [`@babylonjs/procedural-textures`](https://www.npmjs.com/package/@babylonjs/procedural-textures)
- [`@babylonjs/serializers`](https://www.npmjs.com/package/@babylonjs/serializers)
- [`@babylonjs/inspector`](https://www.npmjs.com/package/@babylonjs/inspector)
- [`@babylonjs/node-editor`](https://www.npmjs.com/package/@babylonjs/node-editor)
- [`@babylonjs/react-native`](https://www.npmjs.com/package/@babylonjs/react-native)
- [`babylonjs`](https://www.npmjs.com/package/babylonjs) (UMD distribution)

## Features

- Cross-platform 3D engine — WebGL2, WebGPU, and (via Babylon Native) DirectX / Metal / Vulkan / OpenGL / OpenGL ES
- TypeScript-first SDK published as scoped `@babylonjs/*` ES modules with tree-shakeable imports
- Scene graph with cameras, lights, meshes, materials, textures, animations, particles, audio, and physics
- PBR materials with OpenPBR support, clustered and textured area lighting, and volumetric lighting (v9)
- Frame Graph, Dynamic IBL Shadows, and Render Graph-driven pipelines (v9)
- Node Material Editor, Node Geometry Editor, Node Particle Editor, and Node Render Graph Editor
- Procedural geometry with Node Geometry — runtime-evaluated graphs serialized as JSON
- Gaussian Splat rendering and 3D Tiles geospatial pipeline with PBR atmosphere (v9)
- glTF 2.0 first-class import and export with full KHR extension coverage
- GUI library with Inspector-driven authoring and 3D holographic controls
- WebXR / VR / AR support including hand tracking, controllers, anchors, and pass-through
- Physics integration with Havok (recommended), Ammo.js, Cannon.js, Oimo.js, and Recast
- Babylon Native — C++ host for running Babylon on Windows, macOS, Linux, Android, and iOS
- Babylon React Native (`@babylonjs/react-native`) for embedding Babylon scenes in mobile apps
- Inspector — runtime scene debugger with property editing, gizmos, and shader editing
- Spector.js — frame-by-frame WebGL / WebGPU capture and inspection tool
- Hosted Playground IDE and Sandbox asset viewer with shareable snippet IDs
- Snippet API at `snippet.babylonjs.com` powering shareable Playground / NME / NGE / GUI assets
- Babylon.js Editor — community-maintained visual scene editor
- Babylon Toolkit — Unity and Unreal exporters for the Babylon runtime
- First-party DCC exporters for 3ds Max, Maya, and Blender
- Apache-2.0 licensed, Microsoft-sponsored, community-governed via forum.babylonjs.com

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
