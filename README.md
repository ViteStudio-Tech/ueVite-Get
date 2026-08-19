<img width="1536" height="400" alt="ViteStudioBanner" src="https://github.com/user-attachments/assets/f6f14728-f902-4267-bb58-e27b4b2bf9dd" />


# UnrealEngineVite-Access
Repository Access Instructions for UnrealEngineVite-PhysX

# Accessing the UnrealEngineVite Repository

To access the **UnrealEngineVite** repository, you must first have a free **Epic Games** account linked to your **GitHub** account.

## Step 1 – Create an Epic Games Account

If you don't already have one, create a free account at:

**https://www.unrealengine.com/**

## Step 2 – Link Your GitHub Account

Follow Epic Games' official instructions to connect your GitHub account:

**https://www.unrealengine.com/en-US/ue-on-github**

> **Important:** Use the GitHub account that you want to access the Vite repository with.

## Step 3 – Accept the GitHub Invitation

After linking your accounts, Epic Games will send you an invitation to join the **EpicGames** GitHub organization.

You **must accept this invitation** before you can access Unreal Engine source repositories.

## Step 4 – Access to Vite

After your request has been approved, you'll be able to access the repository here:

https://github.com/GapingPixel/UnrealEngineVite-PhysX

**UnrealEngineVite Repository**

> **Note:** You must be signed in to GitHub using the linked account for the repository link to work.

---

## Disclaimer

**UnrealEngineVite** is developed by **ViteStudio-Tech** in collaboration with independent developers. It is **not sponsored by, or affiliated with Epic Games, Inc.**

**Epic**, **Epic Games**, **Unreal**, **Unreal Engine**, and their respective logos are trademarks or registered trademarks of **Epic Games, Inc.** in the United States and other countries.



=============

<img width="2559" height="1264" alt="image" src="https://github.com/user-attachments/assets/d441276f-dcb5-4029-b501-ac59f05c3258" />


[![Community](https://img.shields.io/badge/Community-Discord-5865F2?logo=discord&logoColor=white)](https://discord.gg/MKWsMg2eG) [![Docs](https://img.shields.io/badge/Documentation-Vite-2088FF?logo=readthedocs&logoColor=white)](https://docs.vitestudiocom.net/) [![Samples](https://img.shields.io/badge/Sample%20Projects-Explore-2EA44F?logo=github&logoColor=white)](https://github.com/ViteStudio-Tech)[![Support Vite](https://img.shields.io/badge/Support-Ko--fi-FF5E5B?logo=kofi&logoColor=white)](https://ko-fi.com/vitestudio) [![YT](https://img.shields.io/badge/YouTube-Unreal%20Engine%20Vite-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/@UnrealEngineVite) [![Updates](https://img.shields.io/badge/Updates-@theredpix-000000?logo=x&logoColor=white)](https://x.com/theredpix)

<small><em>For serious inquiries, contact <a href="mailto:vila@vitestudiocom.net">vila@vitestudiocom.net</a></em></small>

UE-Vite Fork 
=============

## ⚙️ Introduction

**Unreal Engine Vite** is made for professional game development and supports titles currently in active production. Its long-term focus is to maintain a continuously evolving, fully modern 9th-gen engine, delivering industry-grade Simulation and Rendering throughput 
capable of competing with proprietary solutions, alongside ongoing performance, stability, and graphics-pipeline improvements tailored to contemporary console hardware targets.

* **The aim for this Engine Fork is to offer the Most Performant Public Engine viable for commercial projects. Offering a base performance upgrade of up to 2.5x+ real game FPS vs UE5.7 intended feature set.**

* **On the features side, UE-Vite prioritizes battle-tested AAA technology over Epic’s UE5 in-house systems. This includes PhysX with its all-encompassing set of SDK Features (Destruction, Cloth, Vehicles, Particles), DDGI, Standard Full Raytracing, TressFX, HBAO4+, SMAA, Pathtracing, and other industry-standard solutions.**

* **Epic's UE 5.7/5.8** targets around 60 FPS at low **dynamic internal resolutions of 720p–1080p** on PS5 using Lumen, Nanite, VSM, TSR, and Chaos, as demonstrated by shipped titles. Its virtualized approach to geometry, shadows, textures, and reconstructed resolution adds processing, streaming, and memory overhead. Temporal reconstruction, denoising, and stochastic sampling introduce noise, ghosting, instability, and blur. Substrate, GPU Scene, RDG, heavier shader models, and feature expansion further increase base renderer overhead, shader permutations, bytecode, PSO counts, compilation time, and cache sizes versus UE4. Beyond Chaos, CPU costs include heavier scene maintenance, GPU Scene uploads, Lumen updates, Nanite streaming, VSM invalidation, World Partition, and render-thread/RHI workloads, compromising Visual clarity and gameplay responsiveness on the target hardware. The few "UE5" titles that do represent acceptable performance results are **not** publicly available Epic's UE5, but **private company** Engine forks that consist of reverting to UE4-era features such as Embark's [DDGI, SSGI, PhysX 3] (The Finals and Arc Riders), and Riot's [Modified Early UE4 Era Forward Mobile Renderer] (Valorant, 2XKO). Other non-Epic Unreal Engine private iterations include Havok as a full replacement for Chaos (Microsoft Tech).

Furthermore, the recent release of the **Nintendo Switch 2**, the rise of handheld devices with substantially less processing power than the PlayStation 5, Valve hardware such as the Steam Machine and Steam Deck, and rising component costs driven by AI demand all suggest that UE5’s performance targets are becoming increasingly misaligned with current and emerging mass-market hardware. Consequently, its rendering stack may be better suited to film, virtual production, and high-end PC experiences than to sustainable, long-term game development across a broad range of consumer devices.

In contrast to UE5, Vite’s mission is to deliver the highest Visual Fidelity relative to computational cost, maintaining strict frame-time budgets and high native resolutions while running Ray-Tracing on console-class hardware.

**To showcase Unreal Engine Vite's Renderer**, a scene running in Vite with RT GI, RT Reflections, and Tessellation outperforms the exact same scene on UE5.7 without any RT, Lumen, Nanite, or Tessellation! These results remain true at 4K Native for RTX 4080S, RDNA2 RX 6700(PS5 Equivalent) and Steam Deck Hardware at its native resolution. 
Demonstration in video/demos:

[![Vite RT GI + RT Reflections + Tessellation ](https://img.youtube.com/vi/2vfG3W-Gy5E/maxresdefault.jpg)](https://youtu.be/2vfG3W-Gy5E)


## [Read the engine documentation](https://docs.vitestudiocom.net/)

[**Stay tuned on our Engine Community Discord**](https://discord.gg/n9zQrYFhMb)

[**See our work plan on Trello**](https://trello.com/b/JKyBFS5X/ue-vite-physx-vite-studio-fork)

[**Check out our sample projects**](https://github.com/ViteStudio-Tech)

[**Check ueVite's public Drive**](https://drive.google.com/drive/folders/16FOkb5u6GSqHiWeAm50NaxZ19QFBwZeI?usp=sharing)

[**Check Vite Youtube Channel**](https://www.youtube.com/@UnrealEngineVite)

If you’d like to be part of the forkers team, you can submit a PR or request the Forker role on the server. Our internal discussions include general resources about the Unreal Engine source.

**Contribute to Vite Engine Dev:**  https://ko-fi.com/vitestudio

**Receive Vite-related media updates** from https://x.com/theredpix


  ## ⚙️ Vite Performance Targets (All include Raytracing)

| PS5 Class Target | Description |
|------|-------------|
| **Stylized: 4K 120 fps** | This target includes RT DDGI, as demonstrated in the Stylized Demo. This is intended for competitive multiplayer titles. |
| **Performance High End: 4K 60fps** | Includes DDGI + RT Reflections + Tessellation as demonstrated in the Unreal Tournament Vite Demo. |
| **Fidelity High End: 4K 30 FPS** | Similar to the previous target, but scaled for larger-scale titles with high geometric density. |
| **Fidelity Full RT Effects: 1440p 30 FPS** | In addition to RT GI(DDGI) and RT reflections, this target includes RTAO and RT Shadows. |

Note: All referenced resolutions are native, with no upscaling used in any benchmark. PS5-class refers to PC GPUs with comparable performance, such as AMD’s RDNA 2 RX 6700, NVIDIA’s Turing RTX 2070S or Blackwell RTX 5050.

<img width="459" height="284" alt="image" src="https://github.com/user-attachments/assets/cc4104ee-0a16-49ad-a34a-098b1bb85e72" />
<img width="454" height="253" alt="image" src="https://github.com/user-attachments/assets/553ce7f0-ac03-4f07-a09f-046d3098afa4" />

<small>*Worth noting: the 12GB RTX 3060 is the most popular GPU; it delivers only about 93% of the PS5 GPU’s performance.*</small>

| **Realtime PathTracing** | The Vite codebase includes NVIDIA's path-tracing technology featured in Black Myth: Wukong, from the NvRTX 5.0 lineage. *Outside console targets. 

*CPU-wise, the PS5 CPU is equivalent to a laptop Zen 2 8-core or Ryzen 4700s (exact same silicon) / Ryzen 3600.*
  
## ⚙️ Tech Foundation

This fork upstream comes directly from Epic and is based on 4.27 Plus, merged with NvRTX 4.27; the latter introduced several DX12, ray-tracing, and rendering improvements over Epic’s standard UE 4.27 branch. It also adds DLSS, NVIDIA Reflex, improved denoisers, and comprehensive ray-tracing support, including Engine-Side DDGI upgrades such as DDGI-lit ray-traced reflections.

Beyond these foundations, Vite also incorporates rendering features and optimizations from NvRTX 5.0, along with selected technologies from AMD’s Unreal Engine branches. As of the July Major release, Vite contains more than 300 backports from Epic's Unreal Engine 5.0 through 5.8, with over 1,000 additional integrations already present in its internal staging branches.

The core of the engine work is being done by Engine Programmers with extensive knowledge of Unreal Engine’s source and years of hands-on experience with its codebase, ensuring that the integrations use appropriate code guards, properly manage shader permutations, and manually adapt the cherry-picked UE5 backports to the Vite codebase.

Vite’s major engine releases undergo multiple internal staging phases before going public, during which they are validated against a comprehensive suite of tests and large-scale projects to ensure compatibility with existing Unreal Engine 4.27 projects, general stability, and compatibility with Vite.

Killer features of this Engine 
========================================

* **Dynamic DDGI:** The star of this fork: An hyper-performant noise-free 9th gen Global Illumination alternative to Lumen. DDGI provides higher-quality bounces and less leaking than Software Lumen; it's comparable to HWRT Lumen for bounces. RTXGI usually outperforms Lumen by ~2x FPS on several test scenes. For a test scene: 811FPS (RTXGI) vs. 324 FPS (Lumen 5.7). Runs great on AMD hardware (RX 6600 Test scene: 245FPS 1080p native). 

DDGI implementations have been used across numerous AAA titles released on consoles, including Metro Exodus, Overwatch 2, The Finals, Control, The Witcher 3, Warhammer 40,000: Darktide, DOOM: The Dark Ages, Indiana Jones and the Great Circle, 007 First Light, Ghost of Yōtei, and Star Wars Outlaws, including its Switch 2 version. AAA engines such as Anvil and Snowdrop also use DDGI probes as part of their ray-traced GI pipelines. DDGI was designed to scale across a wide hardware range, beginning with GTX 1060-class GPUs.
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/005c2527-3011-4048-8552-6e76e2204924" />
 **Image: 811fps on RTX 4080S 1440p Native DDGI Dynamic**
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/a53249ff-868b-4656-8964-ca8f5d929e6d" />
 **Image: 324fps on **AMD** RX 6600 RDNA2 1080p Native RTXGI Dynamic**

* **Static DDGI**: DDGI also includes a Static Mode with virtually instantaneous bake times. It can deliver higher overall indirect-bounce fidelity and better lighting coverage for movable objects compared to traditional bakes, at the same time it can also be used with Lightmass in conjunction. Static DDGI can provide better directional and visibility-aware volumetric lighting than VLM, particularly for movable objects. During authoring, RTXGI performs actual ray-traced traversal of the scene geometry to populate its probes. The resulting directional irradiance and visibility data are stored as mapped probe textures and serialized before the final game build. Static DDGI can then reproduce this lighting at runtime without performing additional ray tracing. This makes Static DDGI viable on low-end GPUs without hardware RT support, with testing performed on hardware as low as the GCN4 RX 570.

* **Performant RT Reflections**: Vite features highly optimized RT Reflections; these are capable of running at 4K Native 60 FPS on PS5-level GPU as demonstrated in the Unreal Tournament Vite Demo. 

* **UE4 Era SSGI:** SSGI experienced both quality and performance regressions in UE5 due to its integration with Lumen, and it was no longer possible to be activated alongside DDGI. SSGI performs well alongside world-level GI solutions and is recommended to be used in tandem with DDGI to enhance coverage of high-frequency detail GI.
	
* **Vite PhysX:** PhysX integration is fully stable and commercial-ready, as it is based on UE4. Vite’s PhysX 3 libraries have been upgraded to support newer Clang versions, enabling significant compiler optimizations. PhysX Blast support has been added, and PhysX GPU-accelerated particles can run across GPU vendors.
	<img width="2559" height="719" alt="image" src="https://i.postimg.cc/bNzYVZS7/image-4.png" />
	***Image: Chaos (5.7.3) 33.26fps VS PhysX (Vite) 157fps : ~4.74X end game FPS***
	<img width="1105" height="615" alt="image" src="https://github.com/user-attachments/assets/7eb53084-98ce-4fac-a2f6-049c5487b9a1" />
	***Image: PhysX running in fast-path by using Native PhysX Actors, about 2X faster than regular PhysX***
  
* **RTXDI:** This is a **less noisy alternative to MegaLights**. It's the standalone version, not the Lumen-integrated RTXDI present in 5.1 and later NvRTX UE versions. Enabling DDGI + RTXDI will still result in scenes with better performance than standalone Lumen (Hardware).
	<img width="2350" height="1390" alt="image" src="https://github.com/user-attachments/assets/8978ec33-df26-4bbf-9f46-36feff4d1455" />

* **Tesselation:** Enables higher geometric detail based on distance or displacement maps, enabling smoother surfaces, better silhouettes, and high-frequency detail at runtime without incurring the large overhead of Nanite. 

* **Apex Destruction:** Destruction system of PhysX, a hyper-performant alternative to Chaos Destruction https://www.nvidia.com/en-us/drivers/apex-destruction/ [Instructive Video from Vite User](https://youtu.be/Stn7eL1TFBg) 
<img width="640" height="360" alt="image" src="https://github.com/user-attachments/assets/77792a48-e9f6-42c9-a89d-e3d3c3e39df8" />

* **Apex Cloth:** APEX Clothing lets artists quickly generate characters with dynamic clothing to create an ultra-realistic interactive gaming experience https://www.nvidia.com/en-us/drivers/apex-clothing/ [Official Documentation](https://archive.docs.nvidia.com/gameworks/content/gameworkslibrary/physx/apexsdk/APEX_Clothing/Clothing_Module_Doc.html)

* **PhysX Blast:** The Latest Destruction system for PhysX, official [NVIDIA Implementation](https://archive.docs.nvidia.com/gameworks/content/gameworkslibrary/blast/1.1/authoring_docs/BlastUe4_QuickStart.html)
	<img width="640" height="360" alt="image" src="https://github.com/user-attachments/assets/fd860254-8faf-463c-a66e-9d05d6916304" />

* **Full suite of RT Features:** RT Reflections, RTAO, RT Shadows, RT Skylight, RT Translucency, RT Caustics, RT Direct Lighting, Per-Pixel RT GI (apart from DDGI) and PathTracing [Black Myth: Wukong used this rendering Stack].


Current Features
========================================

The `JulyMajorRelease` branch currently includes the following features, integrations, optimizations, and compatibility updates.

### Engine Foundation and Upstream Integrations

- Complete integration of changes from:
  - Unreal Engine 4.27 Plus
  - All three NVIDIA NvRTX 4.27 branches
  - NVIDIA NvRTX 5.0
  - AMD Unreal Engine branches and patches, including RDNA console-focused optimizations
  - Intel Unreal Engine technologies, including XeSS and Intel GPA
- More than **300 backports from Unreal Engine 5.0 through 5.8**
- Updated engine classes and containers to simplify the backporting of UE5 code while preserving compatibility with large UE4 projects
- Broad C++ modernization across the engine
- General third-party library updates
- Updated Oodle libraries
- Removal of obsolete platform code, including HoloLens and Lumin support
- Numerous engine fixes addressing memory leaks, stalls, and other runtime and editor issues

### Physics and Destruction

#### Vite PhysX 

- SDK Lib Upgrade for compatibility with newer Clang versions and the latest NDK Clang(Android). Resulting in a meaningful performance increase (up to 2X in stress tests, usually 1.4x faster in Box Container Pile 10 test).  
- PhysX Blast; working alongside PhysX Apex Destruction (Updated SDK), implemented with an engine-side patch to improve the rendering of Blast Instances
- PhysX Fixed Timestep: Opt-in feature, fully guarded for zero overhead on regular path
- PhysX Instanced Subsystem: High-performance PhysX instancing focused on efficiently simulating and managing large numbers of physics bodies. Designed for massive scale

### Rendering Architecture and Performance

- Significant optimizations across:
  - Render Thread
  - RHI Thread
  - Render Dependency Graph
  - Ray-traced direct lighting
  - Ray-traced reflections
  - Geometry Collections
  - Eye adaptation
  - Shadow and light draw distances
- Substantially less expensive SSAO
- RDNA-focused AMD optimizations targeting console hardware
- Runtime PSO debloating in Shipping builds
- Improved texture handling and streaming
- Localized image-based lighting (IBL)
- Tunnable Per-Object Shadow Draw Distance & Point Light Draw Distance Rendering Feature
- Engine-level switches for opting individual rendering features in or out

### Lighting, Shading, and Materials

- **Callisto BRDF**
  - Single-lobe and dual-lobe GGX specular models
  - Improved specular Fresnel falloff
- **Toon Shading Model** inspired by *Guilty Gear*
- Improved DDGI
- Improved ACES color reproduction and encoding
- **HBAO4+** ambient occlusion
- Material Switch graph node providing discrete selector and multiplexer behavior
- TressFX integration

### Anti-Aliasing, Upscaling, and Frame Generation

- Engine-side improvements to DLSS integration and rendering support
- Ported and integrated technologies:  (They come with an Engine-side patch, not just naive plugin addition)
  - AMD FSR 2
  - AMD FSR 4
  - AMD Anti-Lag 2
  - NVIDIA DLSS 4.5 
  - NVIDIA DLSS Ray Reconstruction
  - Intel XeSS 
- Corresponding Frame Generation modes for supported upscalers
- Bespoke, Vite's own **SMAA**
  - Faster than other morphological anti-aliasing alternatives in internal testing
- Improved **FXAA** with a higher-image-quality mode
- Updated **TAA** for improved temporal reconstruction

### CPU and Runtime Performance

- Several CPU optimizations for Containers, friends usage, Hashmaps, NavMesh, Volumetric clouds, Game Thread, TaskGraph, improved SIMD, Improved Animation systems performance, Texture handling, Streaming, Audio systems performance beyond the gains from Compiler Upgrade.
- Additional performance gains beyond those provided by the compiler upgrade
- Optimized Skeletal Mesh and Actor runtime behavior
  - **Important, review the**  [engine default changes](https://vitestudio-tech.github.io/UnrealEngineVite-Docs/engine-defaults.html)

### Animation and Gameplay Systems

- Animation system performance improvements
- Updated animation features
- Improved animation compression
- Motion Matching 
- Animation Compression Library integration
- GAS updates
- Splash Damage’s Ability System integration
- Kawaii Physics integration

### Editor, Build System, and Developer Tools

- Support for MSVC 14.50 with Visual Studio 2026
- Editor quality-of-life backports and original Vite improvements
- Faster editor loading
- Shader-compilation improvements
- Faster cooking
- Faster Hot Reload
- Modernized console and command systems
- Project-default plugin debloating while preserving project compatibility
- IMGUI integration with benchmarking utilities
- Updated Intel GPA integration
- Automated batch-file system for:
  - Quickly producing Installed Engine Builds
  - Debloating packaged engine installations

### Plugins

Several bundled engine plugins have been ported, upgraded, or developed specifically for Vite, including:

- FSR 1, FSR 2, and FSR 4 [Upgrade]
- DLSS 4.5 + DLSS Ray Reconstruction [Upgrade]
- Intel XeSS [Upgrade]
- Intel Graphics Performance Analyzers [Port]
- Motion Matching [Upgrade]
- Houdini [Port]
- IMGUI with benchmarking utilities for Shipping Build [New]
- Animation Compression Library [Port]
- Kawaii Physics [Upgrade from Original Creator]
- PhysX Instanced Subsystem [New]
- Splash Damage’s Ability System [Port]
- RenderDoc [Port]
- Animation Budget Allocator [Port]
- Cable Component [Port]
- Significance Manager [Port]
- Sun Position [Port]

### Mobile Forward+

- Numerous mobile-platform improvements and fixes
- Faster Eye adaptation
- Most of the Rendering features and improvements already listed also apply to Forward, except, of course, RayTracing.
- Updates to the Forward+ renderer that apply for Mobile & Nintendo Switch
- Nintendo Switch specialized-renderer compatibility foundation
  - Preserves functionality that was removed from later UE5 versions
- Software Occlusion support
  - Retained because this functionality was removed after Unreal Engine 4.27
 
### OLD ueVite 2025 [High-level History](https://docs.google.com/document/d/1OgsPJ-eOEnQsWoSXT8CwEJdEn_u6hGM4P6UcMmjaGw4/edit?usp=sharing) of Commits

<img width="1044" height="1329" alt="image" src="https://github.com/user-attachments/assets/f5a9ce1b-7daf-423c-ab29-c004d578d371" />


### Experimental Features in Internal Staging

> The following features are already functional but are experimental/ pending in merge and are **not** included in the public release.

#### Editor and User Interface

- Updated flat-design user interface inspired by UE5

#### Core Engine and Toolchain

- Full C++20 support
- Clang 22+ support
- Core C++ library upgrades
- Low-level memory-management library upgrades
- Core engine mathematics upgrades
- Approximately 1,000 additional UE5 backports pending integration into a public release

#### CPU Architecture and Performance

- Vite ECS framework integrated directly into Unreal Engine’s source code, based on Flecs
- Engine-level multithreaded tick aggregation for improved instruction-cache coherency
- Large-level performance optimizations
- Further shader-compilation improvements

#### Physics and GPU Simulation

- Vite PhysX++ with a complete PhysX SDK upgrade
- PhysX Flex and Flow support
  - GPU-accelerated particles across supported hardware
  - AMD compute path
  - NVIDIA CUDA path
- PhysX Hairworks
- Other Physics Solution for Visual Effect Rendering 

#### Rendering and Materials

- Improved mesh processing and handling
- Additional global-illumination systems and improvements
- New and upgraded shading models
- Improved ambient occlusion
- AMD CACAO integration
- Improved handling of specular aliasing
- Enhanced screen-space reflections
- Further ACES upgrades
- Improved color-space and HDR handling
- Additional tone-mapping options
- Upgraded **TAA** Image Quality, better Material Colour handling, and better preserved Texture sharpness 

#### Ray Tracing

- Broader ray-tracing upgrades and optimizations
- Improved ray-traced ambient occlusion performance
- Improved ray-traced shadow performance
- General SDK and core algorithm improvements 
- Tessellated ocean water integrated into the ray-tracing scene for reflections

#### Asset and Content Pipelines

- Upgraded Houdini support
- Upgraded offline LOD generation using Vite's own Tech

	
### Future Features 

	* AMD Single Pass Downsampler  https://github.com/GPUOpenSoftware/UnrealEngine/tree/FidelityFXSPD-4.26/UnrealEngine
	* Improved SSGI
	* Further Upgrades to Forward+ Renderer (Mobile)
	* Apple Silicon Upgrade
	* Original Level Editor 
	


### Why use NvRTX 4.27 as a base?

We are using NvRTX 4.27 as our base version because it represents the **best Unreal Engine iteration featuring an Agnostic Ray-Tracing pipeline**, closer in design to that found in other AAA 9th-Gen engines. 

From UE version 5.1, the default rendering path—including its Ray Tracing Scene construction and update pipeline—became increasingly integrated around Lumen, Nanite, Virtual Shadow Maps (VSM), and Temporal Super Resolution (TSR). BLAS/TLAS management was adapted to support GPU Scene, Nanite fallback or streamed ray-tracing geometry, culling, and Lumen HWRT, while ray hits increasingly relied on Lumen’s separate Surface Cache and mesh-card representation for lighting. This greater coupling made alternative RTGI and reflection integrations less straightforward. In parallel, as PhysX was deprecated and replaced by Chaos, the remaining PhysX-specific APIs and compatibility code were gradually removed.

> **Vite is not behind:** it incorporates modern NVIDIA’s October 2022 **NvRTX 5 Ray-Tracing technology**, which does **not exist** in Epic’s UE5 branches and NvRTX 5.1+. Later NvRTX releases integrated their rendering features into **Lumen** and **Nanite**, whereas NvRTX 4.27 & 5 represented a *distinct ninth-generation ray-tracing foundation*.

** Important Read ** [DOC: 4.27 VS 5.0](https://docs.google.com/document/d/1gA0MGkzeWWzKkgwBDOP5xRPouSKaOIW6xlPZ2q6BXO0/edit?usp=sharing)  

On top of this, this iteration of the engine also features the following non-trivial performance benefits:

* Materials/Shaders: 
	Starting with Unreal Engine 5.1, Epic's SM6 *mode* became the preferred rendering path. As a result, the **general shader instruction count increased significantly** for both SM5/SM6 paths. Subsequent engine versions have continued to expand both the instruction count and the number of shader permutations even further. In contrast, Unreal Engine 4.27 provides lighter-weight shaders that deliver the same visual fidelity, resulting in faster GPU performance across the board. Vite does use Shader Model 6, hence the Ray Tracing features; however, this is different from the selectable User Level SM5/6 in UE5.
  
<img width="2518" height="1231" alt="ShaderInsCount" src="https://github.com/user-attachments/assets/5bf7e5c8-1342-4cb6-a1af-a96fed1ddab6" />

* Physics System: 
	Chaos is significantly slower than #PhysX in many workloads, largely due to less efficient #SIMD utilization, comparatively poor #multithreading, and generally less efficient engineering decisions. Internal stress tests show Chaos performing over 5× slower than VITE PhysX in heavily physics-bound scenarios. This performance difference affects not only rigid-body simulation, but also physics queries, collision calculations, and transforms. This results in measurable CPU overhead even in projects that make little to no use of physics simulation. The substantial performance advantage of PhysX also enables significantly more complex and larger-scale cloth simulation and destruction effects within the same CPU budget.

* Character Movement Component: 
	 It has become increasingly expensive in newer versions of the engine. When compared to Unreal Engine 5.7, version 4.27 performs up to 2.2-2.8× faster in movement and collision calculations, even when not accounting for PhysX sweps speed improvement. This largely affects scenes with many enemies or players, decreasing the feasibility of bigger-scale simulation. See 400 CMC Bench Demo (VITE is 3x end FPS faster here).

* RAM/VRAM Usage:
	Overall memory usage has steadily increased with each engine iteration. In comparison, our Fork uses approximately 1.5 GB less total memory on average in a typical multiplayer map scene than version 5.7 (Stylized Demo).

* UI System Slate/Widget:
	Starting with UE5.0, Slate's rendering cost increased considerably, accompanied by a more complex system for handling Slate object updates, layout calculations, transformations, and rendering; it became more expensive in an attempt to increase UI rendering fidelity.

* Skeletal Meshes:
	Skeletal Meshes became more complex around 5.1/5.4; the base cost of an SKM in 4.27 is far lighter. *SKMs are often the worst #CPU offenders.* Expect to be able to allocate around 50% more SKMs in a given Budget in Vite.
	
* World Tick and Game Thread Times:
	Newer iterations of UE5 increased the general cost for the Ticking systems and made Physics/Niagara/Controller ticks heavier to run.
	
* Render Thread Heaviness:
  	With the deeper integration of UE5 Epic's features: Lumen/Nanite/VSM/Virtual Textures/TSR/Substrate/Chaos Cloth/Hair, the render thread became larger and more fragmented; also, PSOs have become increasingly heavier. Affecting the whole Renderer performance in any circumstance.

* Removal of Blueprint Nativization
  	Blueprint VM is a notoriously slow runtime. For simple gameplay logic, it is typically 35–85× slower than equivalent native C++ code, while algorithm code loads, such as bubble sort, node operations, or pathfinding, can be 100–400× slower. In Unreal Engine 4, this overhead was largely mitigated by Blueprint Nativization, which converted Blueprint bytecode into native C++ during packaging, producing code that was typically around 10× faster than Blueprint VM execution. Given that most Unreal Engine projects rely heavily on Blueprints, particularly through plugins and third-party code, this can make UE4’s Game Thread substantially faster in many real-world projects, reducing input latency, improving responsiveness, and allowing for higher simulation scale.
	
* Volumetric effects, Fog, and several other Engine Shaders
  	There is a large performance regression on the systems/materials that handle Volumetrics, Fog, Sky, and many other default engine Shaders; increased shader complexity further beyond the base material cost increases
  <img width="2559" height="1386" alt="image" src="https://github.com/user-attachments/assets/5147cb2c-fa33-4ef7-83e8-59833c5b9dd4" />
<img width="2544" height="1156" alt="image" src="https://github.com/user-attachments/assets/2d913d08-15ad-478d-bb04-371ebdd986da" />

* General increased base costs for core classes, both Game/Render Logic in both execution cost and memory usage
<img width="686" height="732" alt="image" src="https://github.com/user-attachments/assets/bf6497f6-ed1b-48bb-b5ca-27a856da3842" />


## Performance Analysis and Supporting Data

| Resource | Description |
|---|---|
| [Read the UE 4.27 vs. UE 5.0 comparison](https://docs.google.com/document/d/1gA0MGkzeWWzKkgwBDOP5xRPouSKaOIW6xlPZ2q6BXO0/edit?usp=sharing) | GPU Rendering Benchmark between Unreal Engine 4.27 and Unreal Engine 5.0. |
| [See the Size of Class spreadsheet](https://docs.google.com/spreadsheets/d/1qfS04ke1cVGDGBFVLoAjeqE4IzW5QVJ-JAbvFbUw_SY/edit?usp=sharing) | Detailed data and comparisons among Highly Frequently used Classes in Unreal. |
| [Read the Sheet's accompanying article](https://x.com/theredpix/status/2084725568487014642) | Discussion and conclusions based on the supporting data. |

## Comprehensive Physics Benchmark

<img width="1280" height="1475" alt="Performance benchmark results" src="https://github.com/user-attachments/assets/abedb9a5-cfc7-4054-866e-946ee25dfd5b" />

<small><em>*Unity DOTS was benchmarked in Unsafe Mode.</em></small><br>
<small><em>*This benchmark evaluates performance only; simulation quality and SDK capabilities should be assessed separately.</em></small>
<small><em>*PhysX Vite already received a major upgrade internally; expect better results from the Improved iteration.</em></small>


### Isn't UE4 a deprecated codebase?

This is a good question. In reality Unreal Engine 4 continues to power several recent AAA releases: **Final Fantasy VII Rebirth (*UE4.26* 2024)**, **Stellar Blade (*UE4.26* 2024), Days Gone: Remastered (*UE4.11* 2025) Delta Force (*UE4.22* 2026), Mortal Kombat 1(*UE4.27* 2023), Mario & Luigi: Brothership (*UE4.26* 2024), Princess Peach: Showtime! (*UE4.26* 2024), Pikmin 4 (*UE4.26* 2023), Little Nightmares III (*UE 4.27* 2025), Persona 3 Reload(*UE 4.27* 2024), Microsoft's South of Midnight(*4.27* 2025), Sony's Lost Soul Aside(*4.27* 2025), Square Enix's Dragon Quest VII Reimagined (**UE4.27** 2026) and the upcoming Final Fantasy VII: Revelation (*UE4.27* 2027)**. All of these titles feature **PhysX**, of course. We understand that these productions remain on UE4 to retain specific features and meet their Performance/Fidelity targets. The plan is to continue upgrading the codebase, further optimize core systems, upgrade Rendering Core, improve the UI, and modernize the toolchains. UE4 also continues to be updated and supported by major studios, with updates available through the 4.27-plus branch. Furthermore, UE4 remains a priority for Nintendo platforms. Vite is made to be fully compatible with UE4 projects; this is a core priority when we evaluate Staging branches internally. 

We know that performance targets can make or break a release, as they directly define a product's end feature set and the quality of the end user experience. For this, we have an all-around iterative optimization plan on this fork for every major feature that's introduced.

### Introductory Video to Vite — December 2025

[![Community video published in December 2025](https://img.youtube.com/vi/PcF7Hjs1GjE/hqdefault.jpg)](https://youtu.be/PcF7Hjs1GjE)

* An 8-month-old video created by a YouTube content creator, made in mid-December, coincides with the Vite Fork Major Rebase. Click the thumbnail to watch.*

Building the Engine on Windows
========================================

## Prerequisites

Download [Visual Studio 2022 Community](https://aka.ms/vs/17/release/vs_community.exe).

If you have never built Unreal Engine from source, first read Epic Games’ guide:

[Building Unreal Engine from Source](https://dev.epicgames.com/documentation/unreal-engine/building-unreal-engine-from-source?application_version=4.27)

## Visual Studio configurations

Download and import the appropriate Visual Studio configuration:

- [Vite Visual Studio 2022 configuration](https://drive.google.com/file/d/10N842rrpYgLnaJI3xbkds40dngoZhX9A/view?usp=sharing)
- [Vite Visual Studio 2026 configuration](https://drive.google.com/file/d/1lEflVyfb-Aej6U5d5j00EDk7N-Hmqa1U/view?usp=sharing)

![Visual Studio configuration](https://github.com/user-attachments/assets/d7c83761-c713-48f3-b6eb-139ebd5d774a)

### Required toolchain

Use one of the following configurations:

- Visual Studio 2026 with MSVC 14.50
- Visual Studio 2022 with MSVC 14.44
* Windows 11 SDK 10.0.26100 used for both

> If you are getting an NTDDI issue, it means that the Visual Studio Installation is dated and needs to reinstall the SDK 10.0.26100 fully. (delete from *C:\Program Files (x86)\Windows Kits\10* and from VS Components, reinstall again after) -Subversion difference

### Setup procedure

1. Run `Setup.bat`.
2. Wait for the setup process to finish downloading all required dependencies.
3. Run `GenerateProjectFiles.bat`.
4. Open the generated solution (`.sln`) in Visual Studio.
5. In Solution Explorer, right-click the `UE4` project and select **Set as Startup Project**.
6. Select the **Development Editor** build configuration. (May need to modify BuildConfiguration.xml)
7. Build the `UE4` project.

### Installing .NET Framework 4.5

If .NET Framework 4.5 is missing, run `ViteSetup.bat`. It will install the required framework automatically.

Close the script immediately after the .NET Framework installation finishes.

## Build configuration

Update your `BuildConfiguration.xml` file with the following configuration:

```xml
<?xml version="1.0" encoding="utf-8"?>
<Configuration xmlns="https://www.unrealengine.com/BuildConfiguration">
    <WindowsPlatform>
        <!-- Recommended Vite toolchain, battle-tested with MSVC 14.50 for more than 7 months across several users. -->
        <CompilerVersion>14.50</CompilerVersion>

        <!-- Visual Studio 2022 option: latest toolchain compliant with Epic's UE 4.27 Plus branch. -->
        <!--<CompilerVersion>14.44</CompilerVersion>-->

        <!-- Original UE 4.27 toolchain:
             Visual Studio 2019, Windows 10 SDK 10.0.18362, and Clang 11.0.0. -->
        <!--<CompilerVersion>14.29</CompilerVersion>-->

        <!-- Optional Windows SDK overrides. -->
        <!--<WindowsSdkVersion>10.0.18362.0</WindowsSdkVersion>-->
        <!--<WindowsSdkVersion>10.0.22621.0</WindowsSdkVersion>-->
        <!--<WindowsSdkVersion>10.0.26100.0</WindowsSdkVersion>-->

        <!-- Optional explicit compiler selection. -->
        <!--<Compiler>VisualStudio2022</Compiler>-->
    </WindowsPlatform>
</Configuration>
```
## VS Settings
<img width="344" height="1101" alt="image" src="https://github.com/user-attachments/assets/f88a1eda-8781-4b85-8d34-8b51864f81ae" />
<img width="326" height="827" alt="image" src="https://github.com/user-attachments/assets/21a087a9-becf-45ec-af0e-8af900738c8c" />


### Installed Build Automation

`RunUAT.bat` at the repository root runs Unreal Automation Tool with `Engine/Build/InstalledEngineBuild.xml` and the `Make Installed Build Win64` BuildGraph target. It creates a Win64 installed build using `Development` and `Shipping` game configurations, disables non-Windows target platforms, skips the prebuilt DDC, and writes the result to `LocalBuilds/Engine/Windows/`.

### LocalBuilds Packaging Tools

The `LocalBuilds/` folder contains the Windows helper files used to prepare and distribute a local binary build of UE Vite Fork. After `RunUAT.bat` has generated `LocalBuilds/Engine/Windows/`, these scripts can compress that installed build for distribution. Generated archives are written to `LocalBuilds/Engine/`, which is ignored by Git. Compression scripts use `C:\Program Files\7-Zip\7z.exe` by default, or the `SEVEN_ZIP` environment variable when set.

| File | Purpose |
|------|---------|
| `CompressBuild.bat` | Creates `UE_ViteFork.7z` from `LocalBuilds/Engine/Windows/`, excluding debug symbols, feature packs, samples, and templates. |
| `CompressBuildSeparate.bat` | Creates the lean `UE_ViteFork.7z` archive and a separate `ExcludedPlugins.7z` archive for plugins listed in `ExcludedPlugins.txt`. |
| `CompressBuildSymbols.bat` | Creates `UE_ViteFork.7z` while keeping debug symbols, still excluding feature packs, samples, and templates. |
| `CompressBuildSymbolsSeparate.bat` | Creates a symbol-included `UE_ViteFork.7z` archive and a separate `ExcludedPlugins.7z` archive. |
| `ExcludedPdbs.txt` | Lists `.pdb` debug symbol files omitted by the non-symbol compression scripts. |
| `ExcludedPlugins.txt` | Lists plugins omitted from the lean archive and optionally packed into `ExcludedPlugins.7z`. |
| `MakeShortcut.bat` | Creates a `UEViteFork.lnk` shortcut pointing to `Engine/Binaries/Win64/UE4Editor.exe` inside the local binary build. |
| `RegistryAdd.bat` | Registers the current folder as the `UEViteFork` engine association under the current user's Unreal Engine build registry key. |
| `RegistryRemove.bat` | Removes the `UEViteFork` engine association from the current user's Unreal Engine build registry key. |



Notes for Projects
========================================

For implementation examples and reference material, review the following Project Samples:

- PhysX Blast & Apex 
- Third-Person Shooter 
- Stanford-University-CS193U-Unreal-ThirdPerson 
- Gameplay Ability System (GAS) 
- Callisto BRDF Face 
- Upscaler Test
- Cube Bench
- NVIDIA Attic

These projects are available from the [ViteStudio-Tech GitHub organization](https://github.com/ViteStudio-Tech/).


***"I can't go back! I'm running a project on 5.1+"*** 
========================================

No worries! You can use the UE Downgrader Plugin to fully downgrade assets from version 5.8 or lower back to ue4.27/ueVite.

Downgrader: https://youtu.be/yXvJfDNfrSQ
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/7ac949c8-86dc-4484-a792-8232662f2a82" />

@ciprian5896, the creator of the Downgrader plugin, is on our Vite Discord; he has so far provided direct help for several Vite-related projects. At the same time, Vite has many modernizations that make UE5 codebases easier to port than Vanilla 4.27, from container code updates to GAS functionality.

<img width="448" height="480" alt="image" src="https://github.com/user-attachments/assets/78347429-297c-46fc-b57e-abf8706a8510" />


***Engine Documentation*** 
========================================

# [DDGI]( https://vitestudio-tech.github.io/UnrealEngineVite-Docs/ddgi-dynamic.html )

# [Plugins]( https://vitestudio-tech.github.io/UnrealEngineVite-Docs/plugins.html )

# [Vite Engine Debloat & Modularity Documentation]( https://vitestudio-tech.github.io/UnrealEngineVite-Docs/compile-time-switches.html )

# [Vite Engine Code Guidelines]( https://vitestudio-tech.github.io/UnrealEngineVite-Docs/contributing.html#the-three-rules-that-reject-most-pull-requests )


# **READMEs on this repo**
To access, go to the specific public subfolder (ex: Plugins/Runtime/Nvidia/RTXGI, Denoiser, Upscalers)

# [DDGI](https://github.com/GapingPixel/UnrealEngineVite-PhysX/blob/ueVite26-JulyMajor-release/Engine/Plugins/Runtime/Nvidia/RTXGI/README.md)

# [DLSS](https://github.com/GapingPixel/UnrealEngineVite-PhysX/blob/ueVite26-JulyMajor-release/Engine/Plugins/Runtime/Nvidia/DLSS)

# [RTXDI](https://github.com/GapingPixel/UnrealEngineVite-PhysX/tree/ueVite26-JulyMajor-release/Docs/RTXDI)

# [PhysX Blast](https://github.com/GapingPixel/UnrealEngineVite-PhysX/blob/ueVite26-JulyMajor-release/Engine/Plugins/GameWorks/Blast/Documentation/BlastMeshEditor.md)

# [PhysX Clang Upgrade](https://github.com/GapingPixel/UnrealEngineVite-PhysX/blob/ueVite26-MarchMajorRelease/Engine/Source/ThirdParty/PhysX3/README_build_android.md)


Tech-Demos
========================================

Check our Announcements Channel to download playable demos: https://discord.gg/xKpyUCyqQW


Unreal Tournament Vite Demo (RT GI + RT Reflections):
https://drive.usercontent.google.com/download?id=1GRHXf20t_Mu0pS78yHG-vDoAlE_HPfKE&export=download&authuser=0


Stylized RT GI Demo(DDGI): Latest UE5-Vite
https://shorturl.at/Xp29v

﻿
400 AI Characters CMC Bench:
https://t.co/e8ZtUo9LIY

﻿
Physics Simulation Cube Stress Bench:
https://shorturl.at/iauKA

-----------------------------------------------------------------------

UE5-Vite vs Initial UE4-Vite RT GI

https://shorturl.at/NnvgE

We are looking for Testers with the following hardware:  Check Discord: ⁠🎥⏐showcase 

* **AMD:**  RDNA2 6600-**6700**(this matches PS5) / Integrated RDNA2-3.5 / **Steam Deck**(Rog Ally or other handheld)
* **Nvidia:** GTX 1650 and **GTX 1060**/GTX 1660(any GTX 1XXX with 6GB or more)/ RTX 2050/3050 - MX550/MX570(integrated Turing/Ampere)
* Users with Zen 2 CPUs, such as Ryzen 7 2700x, 2600, or Zen 3 3600, 3700.
* Users with Handheld Devices such as Steam Deck, ROG Xbox Ally
* Tests are ideal on a 4K Native Monitor/TV
------------------------------------------------------------------------------------------------

 rtx-dlss-4.27
=============
*A branch for practical optimizations and enhancements for ray tracing features in UE4.*

This branch captures enhancements to the DXR support found in UE 4.27. It attempts to demonstrate tweaks that might be desirable when looking at real-time performance of ray traced effects. While we work closely with Epic, we offer no guarantees that any of these will be integrated into core UE4. Most of these changes strive to maintain identical quality with the core release, but some offer additional compromises in image quality settings. Everything that produces a compromise is an optional feature that can be disabled. Below is a catalog of many of the offerings available. All optimizations were tested against content that has been made publicly available in the UE4 Marketplace. Typically, the testing was done by forcing ray tracing on for samples that were not originally built for ray tracing, so it should apply to problems commonly seen in today’s content. As optimizations or equivalent solution are adopted into mainline UE4, they are dropped from the RTX branches, so if an item present in RTX-4.26 is missing here, it is likely already be present in 4.27 core.

Direct Optimizations
====================

This class of optimizations faithfully implement the algorithms exactly as found in UE 4.27, but they apply transforms which can allow them to operate more efficiently. Generally, this class of optimizations are simply on by default as they have no impact on quality. Some may have configuration parameters, to control concerns like memory overhead.

### Low bounce count reflections specialization

Specialize the reflections shader with a compile-time constant number of bounces and loop unrolling. This enables better code generation and scheduling for the common case encountered in games. Presently, only the single bounce case is specialized. The measured gain for reflection costs on the RealisticRendering showcase sample is roughly 10%.

Commits:
  * 1df96f85285ddb5acd56fcbd30a0051191026441
  * 11098a483fa7725c029fea591d43c7ae4316eb14

### Translucency masking

This capability rasterizes primitives that wish to participate in ray traced translucency into the stencil buffer. By marking these locations, the ray generation shader knows where it can skip shooting rays. This frequently improves translucency costs by 30%, but obviously the results are very content dependent. It works with both normal ray traced translucency and hybrid translucency. This is controlled by the following CVar.

  r.RayTracing.Translucency.Mask [0/1]

Commits:
  * 62ea7be82f23ba55d0a33f63380223417020e7b8
  * f7880de8cefba358e2dee8d86f4ba8c0cecabf8e

### Optimized Instanced Static Mesh Culling

This optimization addresses efficiency tied to the handling of instanced static mesh (ISM) objects including foliage. In scenes with heavy ISM loads, it can substantially reduce CPU load.

Commit:
  * 05704a30341c8a53517922c64faba17d1744a1ba

### Auto instancing for ray traced static

Reduces the cost of SBT setup by identifying duplicate static mesh instances, and collapsing them into real instances rather than replicated nodes in the BVH. This is functionality similar to the raster instancing support.

  r.RayTracing.AutoInstance [0/1]
  
Commit:
  * 972befa7c4b24ec532f3c65d2834d236377152a4
  
### Solid angle culling for instanced static meshes 

Uses the projected solid angle of the bounding sphere to cull instances for instanced static meshes such as foliage. This produces a much more desirable result, as the culling is based on apparent size to the viewer as opposed to a distance.

  r.RayTracing.Geometry.InstancedStaticMeshes.CullAngle <float> - solid angle at which to cull in degrees, negative values mean to revert to dinstance culling

Commit:
  * 7e3eb27bff2081ac910354196e145e4c895ff4f7

Quality Tradeoffs
=================

These provide options to improve performance while making small compromises to image quality. They are similar in nature to many of the quality features already available in the engine. Most of these are configured to be on by default, but generally with a low threshold where the difference is hard identify for most content.

### Shadow Ray Scissoring and Denoising

This provides the option to increase performance by scissoring of the shadow rays to the screen space light scissor rectangle. This interacts with the shadow denoiser which might require access to data outside of the scissor rectangle. The default denoiser however also scissors the denoising to the screen space light rectangles, suggesting a low chance of artifacts. The following CVar allows to configure this.

  r.RayTracing.Shadow.Scissor [0/1/2]

Commits:
  * b7319c04434264c0a41d0a029f621932259e46e1

### Shadow Light Prioritization

This change adds a pair of CVars (r.RayTracing.Shadow.MaxLights and r.RayTracing.Shadow.MaxDenoisedLights) which allow the user to clamp the number of lights receiving ray traced shadows and the number being denoised. Setting either to -1 (the default) means that there is no maximum, preserving the original engine behavior. The MaxLights value is a soft cap on the number of ray traced shadowing lights, as it will not deny lights that need dynamic shadows as those are expected to be no worse than shadow maps. The clamp on the number of lights is applied after they undergo a priority sort to try to enforce the discarded lights to be the ones that are smaller on the screen or further away from the viewer. It is important to note that the lights still have any static shadowing, that they'd normally have under rasterization. These controls can help maintain performance with content where the casts ray traced shadow property has not been well curated on lights.

Commits:
  * b7319c04434264c0a41d0a029f621932259e46e1

#### Sharp Shadow Fallback

With this CVar enabled, shadows for area lights using ray tracing will fallback to sharp shadows rather than noisy shadows. Depending on the scene one or the other fallback may be more or less visually distracting.

  r.RayTracing.Shadow.FallbackToSharp [0/1]

Commits:
  * b7319c04434264c0a41d0a029f621932259e46e1

### Light Prioritization

This change selects lights for the ray traced light list based on a priority metric. Without this support, the first MAX_LIGHTS (256 in the current build) lights are selected to be used in ray traced effects with no provisions for whether they have any importance. This change attempts to select lights that are closer to the viewer and brighter among other criteria in an effort to select useful lights. Selecting a smaller set of relatively important lights can offer improved performance with equal or better visual quality than simply selecting the first 256 lights in the scene's list.

  r.RayTracing.Lighting.MaxLights - maximum number of lights to use for ray traced effects
    -1 - engine maximum and apply no priority (256 is engine max)
    <N> - allow N lights and select based on the priority heuristic
    default = 256 - select engine maximum number of lights via the priority heuristic

  r.RayTracing.Lighting.MaxShadowLights - maximum number of lights to cast shadows in ray traced effects (Lights not casting shadows are those ranked with a lower priority)
    <N> - allow N lights and select based on the priority heuristic
    default = 256 - select engine maximum number of lights via the priority heuristic

Additionally, the ranking heuristic can be tweaked by the following variables. They have been set to values known to work well for game content, but as it is a heuristic, nothing is completely fool-proof.

  r.RayTracing.Lighting.Priority.FrustumBoost - Prioritization boost given for RT lights touching frustum camera (0..inf)
    default = 0.5
  r.RayTracing.Lighting.Priority.AheadBoost - Prioritization boost given for RT light origins in cone ahead of camera (0..inf)
	  default = 1.0f
  r.RayTracing.Lighting.Priority.BehindBoost - Prioritization boost given for RT light origins in cone behind camera (0..inf)
	  default = 1.0f
  r.RayTracing.Lighting.Priority.DistPow - Exponent of light prioritization distance-weight damping
	  default = 2.0f (falloff with square of distance)
  r.RayTracing.Lighting.Priority.LumPow - Exponent of light prioritization luminance-weight damping
    default = 0.5f

Commits:
  * 2c7c9abf57401f7b94bcf301771f0aeb6367b06e

### Roughness Multiplier for Reflections

This enhancement allows trading smoother reflections for reduced reflection noise and improved GPU performance without making changes to the materials themselves.

During raytracing, once the roughness falls within the ray tracing threshold, the roughness can be multiplied by constant, e.g. zero. This results in smooth reflections, but also reduces the reflection noise and improves ray coherency and GPU performance. The surface area of the object which is reflected by the means of ray tracing remains the same.
The main strength of this approach is that it eliminates the need to adjust all materials to achieve a similar effect, thus saving content authoring effort.

The folling cvars can be used to tune this enhancement. They default to 1.0, i.e. regular behavior
  * r.RayTracing.Translucency.RoughnessMultiplier [0.0 ... 1.0]
  * r.RayTracing.Reflections.RoughnessMultiplier [0.0 ... 1.0]

Commits:
  * ceab0eb78ec8e8795a4132108cee3937b4e4584e


rtx-dlss-caustics-4.27
=============
*A branch for practical optimizations and enhancements for ray tracing features in UE4.*

This branch captures enhancements to the DXR support found in UE 4.27. It attempts to demonstrate tweaks that might be desirable when looking at real-time performance of ray traced effects. While we work closely with Epic, we offer no guarantees that any of these will be integrated into core UE4. Most of these changes strive to maintain identical quality with the core release, but some offer additional compromises in image quality settings. Everything that produces a compromise is an optional feature that can be disabled. Below is a catalog of many of the offerings available. All optimizations were tested against content that has been made publicly available in the UE4 Marketplace. Typically, the testing was done by forcing ray tracing on for samples that were not originally built for ray tracing, so it should apply to problems commonly seen in today’s content. As optimizations or equivalent solution are adopted into mainline UE4, they are dropped from the RTX branches, so if an item present in RTX-4.26 is missing here, it is likely already be present in 4.27 core.

NVIDIA DLSS Unreal Engine Integration
=====================================
The NVIDIA RTX Caustics branch contains a series of new RTX features and enhancements over existing techniques, which are experimental at the current stage and subject to future changes. This early access branch is provided for trial purpose without technical supports.

The current branch is based on UE4.27.1 All features and optimizations included in the UE4 NVRTX branch, e.g. DLSS, enhanced translucency, debug & visualization, are also included in this branch. For usages of these NVRTX features and installation steps, please refer to:  
https://github.com/NvRTX/UnrealEngine

All code and art assets of the RTX features provided in this branch are under the GameWorks license:  
https://developer.nvidia.com/gameworks-source-sdk-eula

## Experimental RTX Features for Unreal Engine 4

This document will describe the following features briefly in sections:
* Ray traced mesh caustics: a real-time implementation for generating caustics around metallic and translucent meshes.
* Ray traced water caustics: a real-time implementation for generating caustics by water surfaces.
* Enhanced translucency: on the base hybrid translucency, allowing mixing raster and ray traced translucent objects meanwhile keeping all the benefits of ray traced translucency, e.g. reflection, refraction & OIT.
* Multi-bounce refraction optimization: performance optimized for multi-bounce refraction/reflection binary tree, and adding absorption and total internal reflection.
* Restir GI: new super efficient GI sampling algorithm, support emissive materials as light source, and adding a new SVGF based GI denoiser.
* DLSS tweaking: allowing to render particles after DLSS via a flag, and also fixing the inconsistent DOF blur radius. 

The sample projects and demos are placed on Google drive.  
Folders with all project files:  
https://drive.google.com/drive/folders/1MfJ1rLqwx8acdscFfQtaYOR2Cdm1WPz9?usp=sharing
Folders with all packaged demos:  
https://drive.google.com/drive/folders/1yHFOtmZWVDof8GbfZJMeazfb927ahTDn?usp=sharing


Enhanced Features
=================
These are features that are strictly enhancements to the base UE 4.27.1 release. They add new capabilities that may make your project better.

## Mesh Caustics

### Introduction

Mesh caustics can render interactive caustics for translucent or metallic objects. For caustics from water surface, please refer to “Water Caustics” section. The mesh caustics feature supports:

  * All 4 light types in UE4
  * Multiple light sources
  * Both reflective and refractive caustics
  * Dispersion
  * Soft caustics

### Getting Started

To enable mesh caustics, take the following steps:

  1. Enable raytracing in UE4.
  2. Enable mesh caustics by checking “Enabled” option in “Ray Tracing Mesh Caustics” in post process volume, or simply by setting “r.RayTracing.MeshCaustics.Enable” to 1.
  3. In light properties, check “Cast Mesh Caustics”.
  4. For metallic materials casting mesh caustics, check “Cast Ray Traced Reflection Caustics”. For translucent objects, check “Cast Ray Traced Reflection Caustics” for reflective caustics and check “Cast Ray Traced Refraction Caustics” for refractive caustics.

For additional introduction of the mesh caustics, please check the document:  
[Introducing to Mesh Caustics](Images/rtx_caustics_ue4_part1.pdf)

## Sample Maps
The following sample maps are provided for testing the mesh caustics feature:

* The classic POV-Ray Glasses scene that contains large amount refractions:  
[Project files](https://drive.google.com/file/d/1Ya7_Q_HaHfLIs_xAUSr85tjbjY9aMsXy/view?usp=sharing)  
[Packaged runnable demo](https://drive.google.com/file/d/1DIwPosfmTZU9uPWi-9JVHWx_75pe40Lz/view?usp=sharing)  
![POV-Ray Glasses screenshot](Images/povray_glasses_s.jpg)  

* The demonstration of light dispersion through prism refraction:  
[Project files](https://drive.google.com/file/d/1JSl4dASv5SEk4jx_TjEKDEJFBuIscBIn/view?usp=sharing)  
[Packaged runnable demo](https://drive.google.com/file/d/1eu2hgg5k32P4Nkf1fJpBIObbyFb9SbTZ/view?usp=sharing)  
![Dispersion screenshot](Images/prism_dispersion_s.jpg)

### Additional Feature Settings
Following CVars control additional features. The actual value is controlled by post process volume when CVars is set to -1.

#### Reflective Caustics For Translucent Objects
  * To enable reflective caustics for transparent objects
    * r.RayTracing.MeshCaustics.EnableTranslucentReflection 1  
	
#### Reflective Caustics Mode For Multiple Translucent Objects
  * To enable continuous reflective caustics among numerous translucent objects
    * r.RayTracing.MeshCaustics.TranslucentReflectionMode
	* 0: Refractive Caustics Only
	* 1: Refractive Caustics, Reflective Caustics for first bounce
	* 2: Reflective Caustics, Reflective Caustics for arbitrary bounces
			
	
#### Dispersion
  * To enable dispersion, one should set “Ray Traced Caustics Dispersion Amount” to value greater than 0, then use
    * r.RayTracing.MeshCaustics.EnableDispersion 1 
  * Ray Traced Mesh Caustics Dispersion Amount is located in material root node. 
  * To expose Mesh Caustics Dispersion Amount for each material instance, you need to check Ray Traced Caustics Use CustomData 0 As Dispersion Amount, and then connect a scalar value to Custom Data 0 channel, so this parameter can be tweaked during engine run time
  * To adjust color samples used for dispersion
    * r.RayTracing.MeshCaustics.DispersionSamples

#### Soft Caustics
  * To enable soft caustics, one can set “Mesh Caustics Softness” in light settings to value greater than 0. The following CVar control sample count for soft caustics:
    * r.RayTracing.MeshCaustics.SoftCausticsSample
  * To enable advanced algorithm for soft caustics
    * r.RayTracing.MeshCaustics.EnableAdvancedSoftCaustics

### Performance Tuning

The key to achieve high performance is to limit photon count. In order to know photon count, one can set view mode to “Ray Tracing Debug -> Mesh Caustics Debug Data” in UE Editor, then set “Debug Light Data Type” to “Photon Count”. For normal cases, about 100k photon can produce decent results. If the photon count is too high, increase the value of “Adaptive Photon Size” and decrease the value of “Adaptive Variance Gain” in post process volume. Also, pay attention to “Final Cull Threshold” and “Mid Cull Threshold”. Increase both until caustics start to disappear.

CVars below have significant impact on performance, one should tweak them carefully to achieve balance between image quality and performance. 

  * Culling rays with low contribution can improve performance, following CVars control culling thresholds.
    * r.RayTracing.MeshCaustics.FinalCullColorThreshold
    * r.RayTracing.MeshCaustics.MidCullColorThreshold
  * To use small buffer to draw caustics onto
    * r.RayTracing.MeshCaustics.BufferScale
      * -1: Controlled by post process volume
      * 0: Full Resolution
      * 1: Half Resolution
      * 2: ¼ Resolution  
  * r.RayTracing.MeshCaustics.AdaptivePhotonSize adjusts target screen-space photon size, smaller value produces more detailed results with higher render cost.
  * r.RayTracing.MeshCaustics.AdaptiveVarianceGain can suppress flickering by being set to greater value
  * Another way to reduce flickering is to use temporal filtering
    * Set r.RayTracing.MeshCaustics.EnableTemporalFilter to 1 to enable temporal filtering
    * r.RayTracing.MeshCaustics.TemporalStrength controls the strength of temporal filtering. A greater value will make the result stable, but may introduce lag or ghosting effect.
  * r.RayTracing.MeshCaustics.MaxTraceDepth limits maximum ray bounce, which can increase performance for translucent objects.
  
## Water Caustics
Water Caustics can render interactive caustics for both large and small water area like sea and pond. The water caustics feature supports:
  * All 4 light types in UE4
  * Multiple light sources
  * Both reflective and refractive caustics
  * Dispersion
  * Soft caustics
  * Cascaded Caustics Maps
  
### Getting Started
To enable water interactive caustics, take the following steps:
  1. Enable raytracing in UE4.
  2. Select water Caustics Type "Photon Difference Scattering" or "Procedural Caustic Mesh" in post process volume, or simply by setting “r.RayTracing.WaterCaustics.Type 1/2".
  3. In light properties, check “Cast Water Caustics”.
  4. Go to water surface static mesh actor properties panel, check Evaluate Ray Tracing Water Caustics flag under Ray Tracing tab. The water surface actor corresponding material should be Translucent Blend Mode.
  5. "Photon Difference Scattering" (PDS) algorithm is flexible and good to render water caustics for all the light types currently supported in UE4. It requires relatively high resolution caustics maps to generate sharp caustics patterns, so if it's used to cover large area water surfaces like sea and big lake, Cascaded Caustics Maps should be enabled at the same time, which ensures high quality caustics in the distance near the camera and closer but efficient caustics rendering along the distance going far away from the camera.
  6. "Procedural Caustic Mesh" (PCM) can produce very sharp water caustics even with relatively low resolution caustics maps. It doesn't work with Cascaded Caustics Maps, because it can provide sharp enough caustics patterns with the regular caustics maps covering large water surfaces. In most cases this approach is faster than PDS, but it doesn't support area lights, and might leave artifacts on the edges of the caustics receivers.

For additional introduction of the mesh caustics, please check the document:  
[Introducing to Water Caustics](Images/rtx_caustics_ue4_part2.pdf)

#### Reflective and Refractive  Water Caustics
  * To enable reflective and refractive water caustics > Go to Process Volume > Increase Max Reflection/Refraction Ray Distance, when max ray distance is set 0, it means it can not cast any Water Caustics effect.
  	* r.RayTracing.WaterCaustics.MaxReflectionRayDistance
	* r.RayTracing.WaterCaustics.MaxRefractionRayDistance
	
#### Dispersion	
  * To enable water caustics dispersion: go to post process volume > increase Dispersion Intensity value and tweak Dispersion Offset

#### Cascaded Caustics Maps
  * r.RayTracing.WaterCaustics.Type 1 (only this type support cascade)
  * Select Directional Light > Increase Num Water Caustics Map Cascade > Currently, cascaded water caustics map support 4 levels
  * r.RayTracing.WaterCaustics.MapCascades 
  
#### Water Caustics Capture Range/Map size/ Relative Performance tuning
  * Go to post process volume > Enable Directional Lighting Follow Camera flag > increase Directional Lighting Range, just like scene capture range, the larger value represent larger capture range, need high resolution caustics maps to fill, or it might lower the solution of the caustics which results in blurry caustics patterns.
  * Use "r.RayTracing.WaterCaustics.UseSceneLightDir 0" to decouple the direction of the light and the direction along which the caustics map is captured. This ensures the caustics maps are always captured from the top of the camera, not from the direction of the light. It only works with directional lights.
  * The default water caustics map size is set to 2048, sometimes 1024 is eough to render small water pond, thus save lots of performance. The following CVARs are used to set the size of the caustics maps.
		* r.RayTracing.WaterCaustics.MapSizeX 2048
		* r.RayTracing.WaterCaustics.MapSizeY 2048
  * Water Caustics map will be denoised by default 2 iterations, we can decrease it to 0 to get sharper result, the following CVAR set the number of the iterations of the denoiser.
		* r.RayTracing.WaterCaustics.NumDenoisePasses
  * Only let 1 dynamic light to cast water caustics will save lots of performance, light distance culling and intensity fade is fully supported 
  * The following CVAR is used to show the photons as points for debug purpose.
		* r.RayTracing.WaterCaustics.ShowPhoton 0/1
  * r.RayTracing.WaterCaustics.PhotonScale 3(default value) to scale the initial size of the photons in PDS.
  * Water caustics can be rendered into a half-res, even quater-res caustics buffer to improve the performance. Go to post process volume > Set the Caustics Buffer Scale to adjust the size of the caustics buffer. It also can be set by the following CVAR:
		* r.RayTracing.WaterCaustics.BufferScale 
			* 1: Full Res
			* 2: Half Res
			* 4: Quater Res
 
#### Water Caustics artistic and artifacts tweaking
  * Water Caustics Focus has dependency on mesh/normal strength: Basically, the water mesh surface has large wave/ the normal map has large values will produce more dramatic water caustics  
  * Sometimes, refractive/reflective water caustics has some cracks/seams on the surface has frequent normal variation, these values will ignore surface normal:
		* r.RayTracing.WaterCaustics.RefractBackFaceCullingThreshold -0.5
		* r.RayTracing.WaterCaustics.ReflectBackFaceCullingThreshold -0.5

## Sample Maps
* The Swimming Pool scene with one directional light for demonstrating water caustics:  
[Project files](https://drive.google.com/file/d/1W_ugQVsE18H8zg2gCXZvaJJ987_yoX1W/view?usp=sharing)  
[Packaged runnable demo](https://drive.google.com/file/d/1himFGDfUwyN28BWtuXIkubXpKtYNr1OG/view?usp=sharing)  
![Swimming Pool screenshot](Images/swimming_pool_s.jpg)      
	
## Enhanced Restir GI

### Introduction
Enhanced GI consists of following features:
  * A new GI Denoiser
  * A new Final Gather Sampler
  * Support emissive materials
  * Support 1/4 and 1/8 resolution
  * Support Metallic materials based on GI contribution
  * Support Spherical Harmonics to improve Normal details
  * Support Sky Light occlusion, direct lighting, and indirect lighting in Final Gather


The new GI denoiser can replace the existing one and achieve a smoother denoise result. It supports:
  * Both brute force GI and final gather GI
  * Diffuse indirect illumination only

The new Final Gather Sampler(r.RayTracing.GlobalIllumination.FinalGather.UseReservoirResampling 0/1) can significantly reduce sampler noise, produce much stabilized GI result before denoiser, thus use less sampler per pixel count to achieve much higher quality even under 1 spp.

With emissive materials supported, one can use emissive materials to light the scene without adding light sources. This feature works well in scenes with any size emissive objects, e.g. emissive large light boxes or small lamps. Emissive texture is also supported.

### Getting Started
To enable new GI denoiser, one should take the following steps:
  1. Enable raytracing GI in UE4.
  2. In post process volume settings, set "GI Denoise Type" to "New Denoiser". Another way is to set CVar "r.DiffuseIndirect.Denoiser" to 2.
  3. Emissive objects will affect GI automatically.
  4. r.RayTracing.GlobalIllumination.FinalGather.UseReservoirResampling 0/1 toggle the old and new Final Gather Sampler.
  5. r.RayTracing.GlobalIllumination.FinalGather.ReservoirUpdateInterval -1/5 to set frames check on GI samples in order to accelerate Final Gather GI sampling update schedule. 
  6. r.RayTracing.GlobalIllumination.EvalSkyLight 0/1 Enable global SkyLight contribution in Global-Illumination. The Affect Global-Illumination flag should be set as true under SkyLight Actor.
  7. r.RayTracing.GlobalIllumination.FinalGather.SkyLightIntensity controls the global skylight direct lighting intensity.
  8. r.RayTracing.GlobalIllumination.FinalGather.SkyLightIndirectMultiplier controls the global skylight indirect lighting intensity.


### Parameter Tweaking
The new GI denoiser only has mild performance cost, thus image quality control is the main focus. In the core of the denoiser is an SVGF filter, which consists of a temporal and a spatial filter. Each filter uses geometric feature to steer filter strength. Therefore, the key to parameter tweaking is to ensure those tolerance parameters properly set so that the denoiser can capture enough samples to suppress noise without introducing artifacts.

CVars below have a significant impact on denoise quality.
  * r.RayTracing.GIDenoise.ATrousNormalTolerance or "Spatial Filter Normal Tolerance" in post process volume controls filtering strength for curved surfaces. Greater values result in smoother but less detailed result. Setting it to 50 can suppress most noise.  
  * r.DiffuseIndirect.ApplyAO or "Apply AO to indirect light" in post process volume applies AO to indirect lighting result, which significantly increases lighting details. Highly recommend to enable it.
  * r.RayTracing.GIDenoise.ATrousDepthTolerance or "Spatial Filter Depth Tolerance" in post process volume controls filtering strength for objects occupying wide depth range. Greater values result in smoother result but may introduce ghosting.
  * r.RayTracing.GIDenoise.ColorClamp or "Color Clamp" in post process volume suppresses flickering effect introduced by outliers. Smaller values improve stability, but introduce bias and cause darker results. 50 can be a good choice.
  * r.RayTracing.GIDenoise.HistoryLength or "History Length" in post process volume controls temporal filter strength. Greater values result in stabler result but may introduce lag.
  * r.RayTracing.GIDenoise.ATrousIteration or "Spatial Filter Iteration" in post process volume controls number of spatial filter passes. Higher values introduce smoother result but also high cost. 2 can be a good choise.
  * r.RayTracing.GIDenoise.ATrousAOTolerance or "Spatial Filter Hit Distance Gain" in post process volume captures contact details. Lower values preserve more contact details (e.g., lighting around table legs) but may introduce noise. 
  * r.RayTracing.GIDenoise.DiffuseBoost control the intensity of denoised GI.
  * r.RayTracing.GIDenoise.UseSH decide whether to use Spherical Harmonics to improve normal details.
  * r.RayTracing.GIDenoise..SHSharpness provide normal intensity based on GI contribution.

  

Although the new denoiser can work with all raytracing GI solutions in UE4, it works best with the final gather GI. In usual cases, 4 samples per pixel and r.RayTracing.GlobalIllumination.ScreenPercentage set to 12.5 can produce decent results.

## Sample Maps
* The Abandoned Apartment scene shows the enhanced RTGI:  
[Project files](https://drive.google.com/file/d/1c4wayLmGHCMeuZJ_ZoNdgnYyMqdKLQix/view?usp=sharing)  
[Packaged runnable demo](https://drive.google.com/file/d/1FGxOCRdRD-7Br3T1OkEdXS1XH1WKvgD5/view?usp=sharing)  
![Abandoned Apartment screenshot](Images/abandoned_apartment_s.jpg)  

* The attic scene shows every feature introduced in the enhanced RTGI V2 with stunning visual quality and silky smooth runtime performance:  
[Project files](https://drive.google.com/file/d/1Pe1jBFDp1MSVx5GCdRoftoVfuK5xeCrk/view?usp=sharing)  
[Packaged runnable demo](https://drive.google.com/file/d/1p6sRXnc72iRZsscyhOaYSCV_g5VvRgtr/view?usp=sharing)  
![Attic RTGI V2 screenshot](Images/Attic_RTGI_V2_s.jpg)  

## Enhanced Translucent Absorption

This enhancement includes quality and performance improvement to translucent objects. It consists of following features:
  * Absorption for translucent objects. With this feature, with the same material, thicker objects appears less transparent.
  * Throughput culling. Ray paths with low throughput are culled.

### Getting Started

Absorption is a per material option, that is, objects with absorption can render with objects without. To enable absorption, one should take the following steps:
  1. Ensure raytracing translucency is enabled.
  2. Enable absorption by setting r.RayTracing.Translucency.EnableAbsorption to 1 or check "Enable Absorption" in post process volume.
  3. Choose the material you want to expose absorption, check "Ray Traced Translucency Absorption" in material editor.

To use throughput culling, one can tweak the following parameters:
  * r.RayTracing.Translucency.MinRefractionThroughput or "Min. Refraction Throughput" controls refraction ray culling. Higher values cause less refraction rays, but may introduce artifacts.
  * r.RayTracing.Translucency.MinReflectionThroughput or "Min. Reflection Throughput" controls reflection ray culling. Higher values cause less reflection rays, but may introduce artifacts.

When enable Translucent Absorption, some area occluded by actors will fill with background color to save the last bounce, thus leave double shading artifacts on transparent reflection. 
Turn on "r.RayTracing.PrimaryRays.AbsorptionForceShadingOnOpaqueObjects 0/1" will eliminate this artifact.

### Add option to enable fully ray traced translucency in ray traced reflection
Base UE4 only blends the emissive colors of the reflected translucent meshes when rendering the ray traced reflection effect. This makes translucent objects look strange in the reflected image. Our option allows the engine to render fully ray traced translucent objects in the reflection to improve the visual quality.
CVars to enable this enhancement
  * r.RayTracing.Reflections.ReflectedTranslucencyMode - Sets the method to render the reflected translucent objects (default 0)
  * 0 - emissive only
  * 1 - enable shading
  * 2 - enable shading & refraction
  * 3 - enable shading, refraction & absorption
  * r.RayTracing.Reflections.ReflectedTranslucencyMaxBounces - Sets the maximum number of ray traced translucency bounces (default 8)
  * r.RayTracing.Reflections.ReflectedTranslucencyTransmissionThreshold - Stops ray traced translucency process if the accumulated transmission is lower than this threshold (default 0.1)

## Enhanced Translucency

This enhancement provides two features that allows the mixing of raster and ray traced translucency. To enable this feature, please go to project settings, and then enable Hybrid Translucency check box.

CVars controlling this functionality:

  * r.RayTracing.HybridTranslucencySupport - controls enabling shader support for hybrid translucency (tied to render property)
  * r.RayTracing.Translucency - controls which hybrid translucency  mode is used instead of regular ray tracing translucency 
  * 0 – Vanilla UE4 raytraced translucency off
  * 1 - Vanilla UE4 raytraced translucency On
  * 2 – Hybrid Translucency 1, RT Translucent Reflection ONLY
  * 3 - Hybrid Translucency 2, RT Translucent Reflection & Refraction 

  * r.RayTracing.Translucency.HybridLayers - controls how many levels of overlapping ray traced translucency are tracked for hybrid

  * r.RayTracing.Translucency.HybridDepthThreshold - separation distance at which geometry is considered a different layer of translucency. Units are in world space. (If this value is too small, you may not see the hybrid translucency applied, or z-fighting like artifacts, too big and layers placed one over another will errantly merge)

Method 1: r.RayTracing.Translucency 2

This enhancement provides a feature that allows the mixing of raster and the reflection of ray traced translucency. Today, ray traced translucency forces all translucency to be rendered via ray tracing. This will cause unsupported primitive types like Cascade particles to disappear. Furthermore, the refraction behaviors often can interact in non-intuitive ways for content authored for rasterization. Hybrid translucency traces numerous layers to an off-screen surface, then composites the ray traced layers as part of normal raster translucency. It loses the OIT support and refraction of fully ray traced translucency, but it is no worse than raster in these areas while delivering the reflections and shading of ray traced translucency. This functionality requires enabling the hybrid rendering property for your project, as it permutes the base translucency shaders to enable the capability.

Commits:
  * d95224fced2ce87522c3e83dfa216ee57bd405b3
  * 4d121953ef96a787cff8078fb545be23712c6c17

Method 2: r.RayTracing.Translucency 3

This enhancement provides a feature that allows the mixing of raster and fully ray traced translucency (including reflection, refraction and OIT support). That means Cascade particles can coexist with ray traced translucency without losing any advantages that ray traced translucency brings. The only limitation of this feature is that cascade particles occluded by ray traced translucent meshes don't get distorted in the refraction when the particles are seen through those meshes, but the result still looks fine because particles are dynamic so that this limitation is hard to observe. 

To render translucent meshes, we strongly recommend by enable Ray Traced Translucency 3(Hybrid Translucent method 2), and Translucent Absorption together to get the best translucent visual result so far. Additionally, Order Independence Translucency is automatically supported under this mode. 

In UE4.27, when RT Refraction is enabled under method 2, per material IOR is now bind with PBR based refraction index input, Refraction mode input should be Index Of Refraction. The following CVARs can provide best visual quality under HT2 mode:

	* r.RayTracing.Translucency.Refraction 1
	* r.RayTracing.Translucency.HybridLayers 5
	* r.RayTracing.Translucency.MaxRefractionRays 5


Another advantage of this method is that it allows the users to determine whether to render a translucent static mesh in ray tracing pipeline or not. The translucent meshes that are not visible in ray tracing will be rendered in rasterization. This allows the users to mix the ray traced and raster translucent meshes in the same scene, which is impossible to achieve with the previous methods and may potentially improve the performance because it can reduce the workload of the ray tracing pipeline.

	* r.RayTracing.Translucency.HybridDepthThreshold doesn't work in this mode. Using r.RayTracing.Translucency.PrimaryRayBias instead to apply depth bias when determining which layer of ray traced translucency is in front of the geometry. 

	* Cascade and Niagara particle emitters with Opaque Mesh spawned may be disappeared when it is fully occluded by ray traced translucent meshes, because some particle types can not generate BVH data which is prerequisite for Hardware Ray Tracing. It’s a known issue with ray traced translucency in the vanilla UE4, HT2 doesn’t change this behavior because HT2 only works with translucent objects.

## Sample Maps

* The Office scene mixes particle effects, reflections & refractions on translucent objects, mesh caustics and RTGI:  
[Project files](https://drive.google.com/file/d/1lAO4m7UQWhiqfsazhR-oH3i6fxHjJ8s4/view?usp=sharing)  
[Packaged runnable demo](https://drive.google.com/file/d/10DKmpt77Ybh17qUOVspsn1u2-mtTB6Ei/view?usp=sharing)  
![Office screenshot](Images/office_s.jpg)  

## Half Resolution Translucency 

This enhancement on enhanced translucency method 1 allows it to be rendered at a lower resolution by tracing every other line, then performing a smart rescaling at application time.

    * r.RayTracing.Translucency 2 (Enhanced Translucency Method 1)

    * r.RayTracing.Translucency.HalfRes - whether to render the hybrid translucency at half resolution
    * 0 - full resolution
    * 1 - half resolution vertically (interleaved sampling)
    * 2 - half resolution checkerboard (4 tap reconstruction)
    * 3 - half resolution checkerboard (2 tap vertical reconstruction)

## Half Resolution Primary Refraction Ray 

    * r.RayTracing.Translucency 3 (Enhanced Translucency Method 2)

This enhancement on Enhanced Translucency Method 2 allows it to be rendered at a lower refraction ray, then performing a smart rescaling at application time. Raytraced Refraction should be enabled under this mode. It doesn't work with hybrid translucency mode 1 which only support translucent reflection.

  * r.RayTracing.Translucency.HalfRes - whether to render the hybrid reflected and refracted translucency at half resolution

  * The following reconstruction techniques are recommended to be used under TAA circumstance, some of them should be carefully tweaked when DLSSS is enabled, these pixel level reconstruction techniques may introduce artifacts amplified by DLSS.
    * 0 - full resolution
    * 1 - half resolution checkerboard (reconstructing with weighted colors)
    * 2 - half resolution checkerboard (interframe checkerboard)
    * 3 - half resolution checkerboard (reconstructing with average colors)

## Optimization in Multi-Bounce Refraction

When multiple translucent objects like window glass are overlapped with each other in player view frustum, it requires lots of refraction rays in order to bounce and go through multi-layered translucent meshes, otherwise, it will produce some black pixels when refraction ray miss hit internally. Adding more primary refraction rays can eliminate refraction artifacts thus improve render quality, but it will drastically increase performance overhead. In order to balance max refraction ray count and eliminate black pixels that caused by missing refraction rays. We implemented a feature that can automatically sample background pixels when refraction rays are not enough.

    * r.RayTracing.PrimaryRays.RefractionBackgroundSampleFallback 0/1

## Depth Of field effect based on RT primary ray

In traditional rasterization pipeline, camera Depth Of Field effect is very hard to handle translucency objects correctly and accurately, it is a big challenge when cascade particles inserting with translucent glass walls. Now, with the help of raytracing, such cinematic camera effects is achievable in this branch. 

Enhanced Translucency(Method 2), RT translucent reflection and refraction, and translucent absorption are highly recommended to be enabled under RT depth of field circumstance.

To enable this cinematic RT DOF, you should take the following steps:

1. Go to cine camera view in viewport, apply depth of field effect like old days.

2. In order to accurately apply RT DOF to your scene, you need to collect all the translucent object materials including translucent particles under camera view frustum.

3. For each translucent material> Go to root material > Check Output Translucency Depth flag> Make sure Translucency Depth Opacity Threshold is smaller than your material instance opacity parameter

4. r.RayTracing.PrimaryRays.IncludeDOF 1

5. Dlss is automatically supported



