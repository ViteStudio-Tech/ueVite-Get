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

**UnrealEngineVite** is developed by **ViteStudio-Tech** in collaboration with independent developers, studios, and engine programmers. It is **not sponsored by, or affiliated with Epic Games, Inc.**

**Epic**, **Epic Games**, **Unreal**, **Unreal Engine**, and their respective logos are trademarks or registered trademarks of **Epic Games, Inc.** in the United States and other countries.



========================================

<img width="1993" height="1146" alt="image" src="https://github.com/user-attachments/assets/bfa1f4d2-2d8a-42f0-8b2c-13420bfe3a68" />


UE-Vite Fork 
========================================

## ⚙️ Introduction

**Unreal Engine Vite** is designed for professional game development and supports titles currently in active production. Its long-term focus is to maintain a continuously evolving, fully modern 9th gen engine, delivering industry-grade CPU and rendering throughput capable of competing with proprietary solutions, alongside ongoing performance, stability, and graphics-pipeline improvements tailored to contemporary console hardware targets.

* **The aim for this Engine Fork is to offer the most performant publicly available engine viable for commercial projects. Offering a base performance upgrade of up to 2.5x+ real game FPS vs ue5.7 intended feature set.**

* **On the features side, UE-Vite prioritizes battle-tested AAA technology over Epic’s UE5 in-house systems. This includes PhysX, DDGI, TressFX, SMAA, and other industry-standard solutions.**

* Epic’s UE 5.7/5.8 targets around 60 FPS at dynamic internal resolutions of 720p–1080p on PS5 using Lumen, Nanite, VSM, TSR, and Chaos, as demonstrated by shipped titles. Its virtualized approach geometry, shadowd, textures, and reconstructed resolution—adds processing, streaming, and memory overhead. Temporal reconstruction, denoising, and stochastic sampling introduce noise, ghosting, instability, and blur. Substrate, GPU Scene, RDG, heavier shader models, and feature expansion further increase base renderer overhead, shader permutations, bytecode, PSO counts, compilation time, and cache sizes versus UE4. Beyond Chaos, CPU costs include heavier scene maintenance, GPU Scene uploads, Lumen updates, Nanite streaming, VSM invalidation, World Partition, and render-thread/RHI workloads, compromising Visual clarity and gameplay responsiveness on the target hardware.

Furthermore, with the recent release of the Nintendo Switch 2, the rise of handheld systems considerably less powerful than the PlayStation 5, Valve hardware such as the Steam Machine and Steam Deck, and increasing hardware costs driven by AI demand, UE5’s performance targets appear increasingly misaligned with current and upcoming console hardware. Consequently, this rendering stack may be better suited to film, virtual production, and high-end PC environments than to sustainable, long-term video game development across mass-market hardware.

In contrast, Vite prioritizes high visual fidelity while maintaining strict frame-time budgets and high native resolutions across console-class hardware.

**To showcase Unreal Engine Vite’s GPU renderer**, a scene running in Vite with RT GI, RT Reflections, and Tessellation  outperforms the exact same scene on ue5.7 without any RT, Lumen, Nanite or Tessellation ! These results remain true at 4K Native for RTX 4080S and RDNA2 RX 6700(PS5 Equivalent); and Steam Deck Hardware at its native resolution.

[![Vite RT GI + RT Reflections ](https://img.youtube.com/vi/2vfG3W-Gy5E/maxresdefault.jpg)](https://youtu.be/2vfG3W-Gy5E)



## [Read the engine documentation](https://docs.vitestudiocom.net/)

[**Stay tuned on our Engine Community Discord**](https://discord.gg/n9zQrYFhMb)

[**See our work plan on Trello**](https://trello.com/b/JKyBFS5X/ue-vite-physx-vite-studio-fork)

[**Check out our sample projects**](https://github.com/ViteStudio-Tech)

[**Check ueVite's public Drive**](https://drive.google.com/drive/folders/16FOkb5u6GSqHiWeAm50NaxZ19QFBwZeI?usp=sharing)


If you’d like to be part of the forkers team, you can submit a PR or request the Forker role on the server. Our internal discussions include general resources about the Unreal Engine source.

**Contribute to Vite Engine Dev:**  https://ko-fi.com/vitestudio

**Receive Vite-related media updates** from https://x.com/theredpix


  ## ⚙️ Vite Performance Targets (All include Raytracing)

| PS5 Class Target | Description |
|------|-------------|
| **Stylized: 4K 120 fps** | This target includes RT DDGI, as demonstrated in the Stylized Demo. This is intended for competitive multiplayer titles. |
| **Performance High End: 4K 60fps** | Includes DDGI + RT Reflections + Tessellation as demonstrated in the Unreal Tournament Vite Demo. |
| **Fidelity High End: 4K 30 FPS** | Similar to the previous target, but scaled for large open-world titles with high geometric density. |
| **Fidelity Full RT Effects: 1440p 30FPS** | In addition to RT GI(DDGI) and RT reflections, this target includes RTAO and RT Shadows. |



| **Realtime PathTracing** | The Vite codebase includes NVIDIA's path-tracing technology featured in Black Myth: Wukong. 

  
## ⚙️ Tech Foundation

This fork was originally based on NvRTX 4.27 Caustics, which introduced several DX12, ray-tracing, and rendering improvements over Epic’s standard UE 4.27 branch. It also adds DLSS, NVIDIA Reflex, improved denoisers, and comprehensive ray-tracing support, including Engine-Side DDGI upgrades such as DDGI-lit ray-traced reflections.

The UE 4.27 Plus branch has been fully merged, alongside NVIDIA’s NvRTX 5.0 branch and rendering features from AMD’s engine branches. As of the June Major Release, Vite includes more than 250 backports from UE 5.0 through 5.7, with over 1,200 already integrated into the internal staging branches.

This work is being done by engine programmers with extensive knowledge of Unreal Engine’s source and years of hands-on experience with its codebase, ensuring that these integrations use appropriate code guards, properly manage shader permutations, and manually adapt the cherry-picked UE5 backports to the Vite codebase.

With PhysX and a combined DDGI+SSGI lighting pipeline, UE-Vite closely resembles the bespoke Unreal Engine build used for the launch of The Finals.


Killer features of this Engine 
========================================

* **Dynamic DDGI:** The star of this fork: An hyper-performant noise-free 9th gen Global Illumination alternative to Lumen. DDGI provides higher quality bounces and less leaking than Software Lumen; it's comparable with HWRT Lumen for bounces. RTXGI usually outperforms Lumen for 2x~ the FPS on several test scenes. For a test scene: 811FPS (RTXGI) VS 324fps(Lumen 5.7). Runs great on AMD hardware (RX 6600 Test scene: 245FPS 1080p native). 

DDGI implementations have been used across numerous AAA titles released on consoles, including Metro Exodus, Overwatch 2, The Finals, Control, The Witcher 3, Warhammer 40,000: Darktide, DOOM: The Dark Ages, Indiana Jones and the Great Circle, 007 First Light, Ghost of Yōtei, and Star Wars Outlaws, including its Switch 2 version. AAA engines such as Anvil and Snowdrop also use DDGI probes as part of their ray-traced GI pipelines. DDGI was designed to scale across a wide hardware range, beginning with GTX 1060 class GPUs.
<img width="1800" height="1013" alt="image" src="https://github.com/user-attachments/assets/005c2527-3011-4048-8552-6e76e2204924" />
 **Image: 811fps on RTX 4080S 1440p Native DDGI Dynamic**
<img width="1808" height="1010" alt="image" src="https://github.com/user-attachments/assets/a53249ff-868b-4656-8964-ca8f5d929e6d" />
 **Image: 324fps on **AMD** RX 6600 RDNA2 1080p Native RTXGI Dynamic**

* **Static DDGI**: DDGI also includes a Static Mode with virtually instantaneous bake times. This mode delivers higher bounce fidelity than traditional baked-lighting solutions and generally better coverage of moving objects, thanks to DDGI’s use of Spherical Harmonics to store and filter irradiance within the probe volumes. Viable for ultra-low-end GPUs without RT support.

* **Performant RT Reflections**: Vite features highly optimized RT Reflections; these  are capable of running at 4K Native 60 FPS on PS5 Level GPU as demonstrated in the Unreal Tournament Vite Demo. 

* **UE4 Era SSGI:** SSGI experienced both quality and performance regressions in UE5 due to its integration with Lumen, and it was no longer possible to be activated alongside DDGI. SSGI performs well alongside world-level GI solutions and is recommended to be used in tandem with DDGI to enhance coverage of high-frequency detail GI.
	
* **Vite PhysX:** PhysX 3 integration is fully stable and commercial-ready, as this based on UE4. Vite’s PhysX 3 libraries have been upgraded to support newer Clang versions, enabling significant compiler optimizations. PhysX Blast support has been added, and PhysX GPU-accelerated particles that can run across GPU vendors.
	<img width="2559" height="719" alt="image" src="https://i.postimg.cc/bNzYVZS7/image-4.png" />
	***Image: Chaos (5.7.3) 33.26fps VS PhysX (Vite) 157fps : ~4.74X end game FPS***
	<img width="1105" height="615" alt="image" src="https://github.com/user-attachments/assets/7eb53084-98ce-4fac-a2f6-049c5487b9a1" />
	***Image: PhysX running in fast-path by using Native PhysX Actors, about 2X faster than regular PhysX***
  
* **RTXDI:** This is a **less noisy alternative to MegaLights**. It's the standalone version, not the Lumen-integrated RTXDI present in 5.1 and later NvRTX UE versions. Enabling RTXGI + RTXDI will still result in scenes with better performance than standalone Lumen (Hardware).
	<img width="2350" height="1390" alt="image" src="https://github.com/user-attachments/assets/8978ec33-df26-4bbf-9f46-36feff4d1455" />

* **Tesselation:** Enables higher geometric detail based on distance or displacement maps, enabling smoother surfaces, better silhouettes, and high-frequency detail at runtime without incurring the large overhead of Nanite. 

* **Apex Destruction:** Destruction system of PhysX, a hyper-performant alternative to Chaos Destruction https://www.nvidia.com/en-us/drivers/apex-destruction/
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/77792a48-e9f6-42c9-a89d-e3d3c3e39df8" />

* **Apex Cloth:** APEX Clothing lets artists quickly generate characters with dynamic clothing to create an ultra-realistic interactive gaming experience https://www.nvidia.com/en-us/drivers/apex-clothing/

* **Full suite of RT Features:** RT Reflections, RTAO, RT Shadows, RT Skylight, RT Translucency, RT Caustics, RT Direct Lighting, Per Pixel RT GI (apart from DDGI) and PathTracing [Black Myth: Wukong used this rendering Stack].


Current Features
========================================

* The **JuneMajorRelease branch** of this fork **currently brings the following**:

	* **Vite PhysX 3.4** 
      * **Lib Upgrade** for compability with newer *Clang* versions and latest NDK Clang(Android). Resulting in meaningful performance increase (up to 2X in stress tests, usually 1.4x faster in Box Container Pile 10 test).  
      * **PhysX Blast** working alongside PhysX Apex Destruction
      * **PhysX Fixed Timestep** Opt In Feature, fully guarded for Zero overhead on regular path
  * Fully Merged ue4.27 Plus changes, nvrtx 4.27, nvrtx 5.0, DLSS, TressFX, FSR and AMD patches
  * Over **250 backports** from ue5.0-5.7 
  * **Calisto BRDF** (Single and Dual lobe GGX Specular, specular fresnel falloff)
  * **Toon Shading Model** inspired in Guilty Gear 
  * Up to MSVC 14.50 (VS26) compiler compliance for the highest Compiler performance and compatibility.
  * Engine-side DLSS Rendering Improved Support
  * Editor QoL backports
  * Added several ported/original/upgraded plugins bundled with the engine: FSR, Motion Matching, Houdini, ACL, **Kawaii Physics**, **PhysX Instanced subsystem**, Splash Damage Ability System and others. 
  * Several Rendering optimizations for RHI, RT Direct Lighting, RT shadows, Geometry Collection, Drawing, Eye adaptation, Shadow/Light Draw Distance, significantly sheaper SSAO, AMD Optimizations targeted for consoles 
  * Several CPU optimizations for Containers, friends usage, Hashmaps, NavMesh, Volumetric clouds, Game Thread, TaskGraph, improved SIMD, Improved Animation systems performance, Texture handling, Streaming, Audio systems performance  
  * Updated Classes for **easier backporting of UE5 codebases** (game framework/containers)
  * Improved ACES (Color Reproduction)
  * Shader Compilation Improvements
  * Debloated **Runtime PSOs** at Shipping
  * Optimized runtimes for Skeletal Meshes and Actors
  * Editor loading improvements
  * Modernized console systems 
  * Project Default Plugin debloat
  * Improved Performance of RT Reflections
  * Improved DDGI
  * **HBAO4+** Ambient Occlusion
  * Compute Based **SMAA**
  * Improved **FXAA** (Higher Image quality option)
  * Updated **TAA** for better temporal resolve 
  * Ported FSR2,FSR4 AMD AntiLag 2, DLSS 4.5
  * **IMGUI** Integration with Benchmarking Tools
  * **TressFX** integration 
  * Localized IBL
  * Oodle updates 
  * GAS Updates 
  * **SSAO** Fast Path
  * Several **CPU Optimizations** to Animation Systems
  * Several improvements/fixes for Mobile
  * Large ammount of toolchain, C++ updates, faster cooking, and code modernization patches.
  * Large ammount of Engine fixes, resolved memory leaks and stall fixes.
  * BAT System to quickly produce Installed Engine Builds and Debloat.
  * **Software Oclussion:** Noted as this was removed after 4.27
  * Nintendo Switch Specialized Renderer Base (5.0+ removed this)
<img width="813" height="1297" alt="image" src="https://github.com/user-attachments/assets/60a1991c-26ea-486e-980f-581d6fb00903" />


### Currently Work in Progress Features 

  * Update UI Flat Design (UE5-like)
  * Full C++ 20 support 
  * Further integration of specific UE5 Upgrades (Around 1000 backports pending to be in Release) 
  * Rendering features (Improved Mesh handling, GI, Shader Models, AO, Improved Specular Aliasing Handling) 
  * Further ACES Upgrades/Color Space/HDR Handling/Tonemappers
  * Large Level optimizations
  * Further Shader compilation Improvements
  * CACAO
  * PhysX Flex/Flow support: GPU-accelerated Particles for all GPUs, AMD Compute and NVIDIA CUDA paths 
  * Tesselated Water, for Ocean Rendering integrated in the RT Scene for Reflections
  * Improved performance of RTAO and RT Shadows
  * Engine Level Integration for Multi-Threaded Tick Aggregation: Improved Instruction Coherency
  * Core C++ lib upgrades
  * Core Engine Math Upgrade
  * Larger RT Rendering related changes
	
### Future Features 

	* AMD Single Pass Downsampler  https://github.com/GPUOpenSoftware/UnrealEngine/tree/FidelityFXSPD-4.26/UnrealEngine
	* Improved SSGI
	* Integration of a well-known ECS library
	



### Why use NvRTX 4.27 as a base?

We are using NvRTX 4.27 as our base version because it represents the **best Unreal Engine iteration featuring an Agnostic Ray-Tracing pipeline**, closer in design to that found in other AAA engines. 

From UE version 5.1, the default rendering path—including its Ray Tracing Scene construction and update pipeline—became increasingly integrated around Lumen, Nanite, Virtual Shadow Maps (VSM), and Temporal Super Resolution (TSR). BLAS/TLAS management was adapted to support GPU Scene, Nanite fallback or streamed ray-tracing geometry, culling, and Lumen HWRT, while ray hits increasingly relied on Lumen’s separate Surface Cache and mesh-card representation for lighting. This greater coupling made alternative RTGI and reflection integrations less straightforward. In parallel, as PhysX was deprecated and replaced by Chaos, the remaining PhysX-specific APIs and compatibility code were gradually removed.

**Important** Read this DOC: 4.27 VS 5.0  https://docs.google.com/document/d/1gA0MGkzeWWzKkgwBDOP5xRPouSKaOIW6xlPZ2q6BXO0/edit?usp=sharing

On top of this, this iteration of the engine also features the following non-trivial performance benefits:

* Materials/Shaders: 
	Starting with Unreal Engine 5.1, Shader Model 6 (SM6) became the preferred rendering path. As a result, the **general shader instruction count increased significantly** for both SM5/SM6 paths. Subsequent engine versions have continued to expand both the instruction count and the number of shader permutations even further. In contrast, Unreal Engine 4.27 provides lighter-weight shaders that deliver the same visual fidelity, resulting in faster GPU performance across the board.
  
<img width="2518" height="1231" alt="ShaderInsCount" src="https://github.com/user-attachments/assets/5bf7e5c8-1342-4cb6-a1af-a96fed1ddab6" />

* Physics System: 
	Chaos is significantly slower than #PhysX in many workloads, largely due to less efficient #SIMD utilization, comparatively poor #multithreading and generally less efficient engineering decisions. Internal stress tests show Chaos performing over 5× slower than PhysX in heavily physics-bound scenarios. This performance difference affects not only rigid-body simulation, but also physics queries, collision calculations and transforms. Resulting in a measurable CPU overhead even in projects that make little to no use of physics simulation. The substantial performance advantage of PhysX also enables significantly more complex and larger-scale cloth simulation and destruction effects within the same CPU budget.

* Character Movement Component: 
	 It has become increasingly expensive in newer versions of the engine. When compared to Unreal Engine 5.6, version 4.27 performs up to 2.2-2.8× faster in movement and collision calculations, even when not accounting for PhysX sweps speed improvement. This largely affects scenes with many enemies or players, decreasing the feasiblity of bigger scale simulation.

* Ram/Vram Usage:
	Overall memory usage has steadily increased with each engine iteration. In comparison, our Fork uses approximately 1GB of total less memory on average in a typical multiplayer map scene than version 5.7 (Stylized Demo).

* UI System Slate/Widget:
	Starting with UE5.0, Slate's rendering cost increased considerably, accompanied by a more complex system for handling Slate object updates, layout calculations,transformations and the rendering of it became more expensive in an attempt of increased UI rendering fidelity.

* Skeletal Meshes:
	Skeletal Meshes became more complex around 5.1/5.4, the base cost of a SKM in 4.27 is far lighter. *SKMs are often othe worst #CPU offenders.*
	
* World Tick and Game Thread Times:
	Newer iterations of UE5 increased the general cost for the Ticking systems and made Physics/Niagara/Controller ticks heavier to run.
	
* Render Thread Heaviness:
  	With the deeper integration UE5 Epic's features: Lumen/Nanite/VSM/Virtual Textures/TSR/Substrate/Chaos Cloth/Hair, the render thread became larger and more fragment, also PSOs have become increasingly heavier. Affecting the whole Renderer performance in any circumstance.

* Removal of Blueprint Nativization
  	Blueprint VM is a notoriously slow runtime. For simple gameplay logic, it is typically 50–80× slower than equivalent native C++ code, while algorithm code loads, such as bubble sort, node operations, or pathfinding, can be 150–400× slower. In Unreal Engine 4, this overhead was largely mitigated by Blueprint Nativization, which converted Blueprint bytecode into native C++ during packaging, producing code that was typically around 10× faster than Blueprint VM execution. Given that most Unreal Engine projects rely heavily on Blueprints, particularly through plugins and third-party code, this can make UE4’s Game Thread substantially faster in many real-world projects, reducing input latency, improving responsiveness and allowing for higher simulation scale.
	
* Volumetric effects, Fog and several other Engine Shaders
  	There is a large performance regression on the systems/materials that handle Volumetrics, Fog,Sky and many other default engine Shaders; increased shader complexity further beyond the base material cost increases
  <img width="2559" height="1386" alt="image" src="https://github.com/user-attachments/assets/5147cb2c-fa33-4ef7-83e8-59833c5b9dd4" />
<img width="2544" height="1156" alt="image" src="https://github.com/user-attachments/assets/2d913d08-15ad-478d-bb04-371ebdd986da" />

* General increased base costs for core classes, both Game/Render Logic in both execution cost and memory usage
<img width="686" height="732" alt="image" src="https://github.com/user-attachments/assets/bf6497f6-ed1b-48bb-b5ca-27a856da3842" />

Sheet: https://docs.google.com/spreadsheets/d/1TabQV7UTDLMHI9GVFCbMzXohax2Agm2qzET7tOOXN7w/edit?usp=sharing

### Isn't UE4 a deprecated codebase?

This is a good question. In reality Unreal Engine 4 continues to power several recent AAA releases: **Final Fantasy VII Rebirth (*UE4.26* 2024)**, **Stellar Blade (*UE4.26* 2024), Days Gone: Remastered (*UE4.11* 2025) Delta Force (*UE4.22* 2026), Mortal Kombat 1(*UE4.27* 2023), Mario & Luigi: Brothership (*UE4.26* 2024), Princess Peach: Showtime! (*UE4.26* 2024), Pikmin 4(*UE4.26* 2023) and Square Enix's Dragon Quest VII Reimagined (**UE4.27** 2026), the upcoming Final Fantasy VII: Revelation(*UE4.27* 2027)** All of these titles feature **PhysX**, of course. We understand that these productions remain on UE4 to retain specific features and meet their Performance/Fidelity targets. The plan is to continue upgrading the codebase, further optimize core systems, upgrade Rendering Core, improve the UI, and modernize the toolchains. UE4 also continues to be updated and supported by major studios, with updates available through the 4.27-plus branch. Furthermore, UE4 remains a priority for Nintendo platforms.

We know that performance targets can make or break a release, as they directly define a product's end feature set and the quality of the end user experience. For this, we have an all-around iterative optimization plan on this fork for every major feature that's introduced.

Building the Engine on Windows
========================================

### 0. Initial Setup
  * If you have never built from source, follow: https://dev.epicgames.com/documentation/en-us/unreal-engine/setting-up-visual-studio-development-environment-for-cplusplus-projects-in-unreal-engine?application_version=4.27
  	<img width="1234" height="626" alt="image" src="https://github.com/user-attachments/assets/d7c83761-c713-48f3-b6eb-139ebd5d774a" />

  * Use Latest VS22 with MSVC 14.44 / Windows 11 SDK 10.0.26100.0 (Latest 4.27 Plus reported Epic's Compliance)
  * GitDeps is already fixed on this fork, no change needed.
  * Run Setup.bat first, when asked to Override Changes on Setup startup, enter N.
  * Just before the linking phase begins, verify which toolchains are in use..
  * After the setup finishes downloading, run GenerateProjectFiles. 

Compiling this version of Unreal Engine from source requires a specific set of build tools. If you use a newer or different version, you will encounter compilation errors like error C4668: '__has_feature' is not defined.

Follow these instructions carefully to set up the correct build environment:

### 1. Required Tools

### How to Install the Required Components

 * Open the Visual Studio Installer. 
 * Find your Visual Studio 2026 installation and click Modify.
 * Go to the Individual components tab.
 * Uncheck boxes for conflicting MSVC versions
 *Toolchain Options:
	
	* Maximum stability: VS 19/22 Latest: MSVC 14.29 paired with Windows SDK 10.0.19041.0
	
    * Stable and High performance: VS 26 with MSVC 14.50 with Windows SDK 10.0.22621.0 (Tested by several Vite users during 6 months)
    * Epic's UE 4.27 Plus last toolchain update verified enough stability with VS 22 Latest: MSVC 14.44 with Windows SDK 10.0.26100
    
### Building with Visual Studio
 
 * Set starting project as UE4 if not setup already.
 * Engine should be built in Development Editor configuration

* If you encounter issues, match the following VS Settings:
<img width="344" height="1101" alt="image" src="https://github.com/user-attachments/assets/f88a1eda-8781-4b85-8d34-8b51864f81ae" />
<img width="326" height="827" alt="image" src="https://github.com/user-attachments/assets/21a087a9-becf-45ec-af0e-8af900738c8c" />

Download and import the [Vite VSConfig](https://drive.google.com/file/d/1NwpPUiM_7yVI_kjhW94kYxvVP42ViV3Q/view?usp=sharing) file.


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


Check the Vite GAS Sample project featuring DDGI:

https://github.com/ViteStudio-Tech/


***"I can't go back! I'm running a project on 5.1+"*** 
========================================

No worries! You can use the UE Downgrader Plugin to fully downgrade assets from version 5.8 or lower back to ue4.27/ueVite.

Downgrader: https://youtu.be/yXvJfDNfrSQ
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/7ac949c8-86dc-4484-a792-8232662f2a82" />

@ciprian5896 the creator of the Downgrader plugin is at our Vite Discord, he has so far provided direct help for several Vite related projects. At the same time Vite has many modernizations that make UE5 codebases to work with more ease than Vainilla 4.27, from containers code updates to GAS functionality.

<img width="448" height="480" alt="image" src="https://github.com/user-attachments/assets/78347429-297c-46fc-b57e-abf8706a8510" />


***Engine Documentation*** 
========================================

# [DDGI](https://docs.google.com/document/d/1kdZGRV6bRNjNvec1OzzEJd64NtLBDZ8hzQvFVzB2GfI/edit?tab=t.0)

# [Plugins](https://docs.google.com/document/d/1Rf1FeHm5RxIkDsPij3Pq1Uu5q0U5GPJe0Za-lAJYTD8/edit?usp=sharing)

# [Vite Engine Debloat Documentation / Reference](https://docs.google.com/document/d/1QKt7wYbLBl3Wo_OlIYwzWycES--glmhDFewghnd8ZUA/edit?usp=sharing)

# [Vite Engine Code Guidelines](https://docs.google.com/document/d/1pCirc9CxqUUMcfYyv6ANgM9NG5LFsMruyE6W-4WbG8M/edit?usp=sharing)


# **READMEs on this repo**
To access go to the specific public subfolder (ex: Plugins/Runtime/Nvidia/ RTXGI, RTXDI, Denoiser)

# [DDGI](https://github.com/GapingPixel/UE5-PhysX-Vite/tree/ue5Vite-release/Engine/Plugins/Runtime/Nvidia/RTXGI)

# [DLSS](https://github.com/GapingPixel/UE5-PhysX-Vite/tree/ue5Vite-release/Engine/Plugins/Runtime/Nvidia/DLSS)

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
* Tests are ideal on 4K Native Monitor/TV
------------------------------------------------------------------------------------------------

 
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



