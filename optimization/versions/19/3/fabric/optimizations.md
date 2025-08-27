<!-- SECTION: adventure tools v.19.3.r1 -->

# Essential
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Better Fps - Render Distance](https://www.curseforge.com/minecraft/mc-mods/better-fps-render-distance-fabric) | Async, Very Many Players | Better FPS Render Distance is a mod which adds a few performance improvements to increase fps. | Client | Incompatible with Async, as Async is incompatible with this mod's dependancy (Cupboard). |
| [Cull Leaves](https://modrinth.com/mod/cull-leaves) | None | Adds culling to leaf blocks, providing a huge performance boost over vanilla. | Client | N/A |
| [Cull Less Leaves](https://modrinth.com/mod/qthuEuVy) | Unknown | Cull leaves while looking hot! | Client | Alternative for Cull Leaves that lets you keep more of the inside leaves |
| [Entity Culling](https://modrinth.com/mod/entityculling) | Unknown | Using async path-tracing to hide Block-/Entities that are not visible | Client | Has a very small chance to cause crashes in versions where Sodium is present. |
| [FerriteCore](https://modrinth.com/mod/ferrite-core) | Unknown | Memory usage optimizations | Both | N/A |
| [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) | Unknown | Speed up immediate mode rendering in Minecraft | Client | Effect is most noticable on CPU bottleneck and old CPU setups, according to the author | 
| [LazyDFU](https://modrinth.com/mod/lazydfu) | None | Makes the game boot faster by deferring non-essential initialization | Both | Patched on servers on 1.19.4+. Patched on clients starting with 1.21.x. |
| [Lithium](https://modrinth.com/mod/lithium) | Unknown | No-compromises game logic optimization mod. | Both | N/A |
| [Smooth Boot](https://modrinth.com/mod/smoothboot-fabric) | None | Improve Minecraft CPU scheduling | Both | N/A |
| [Sodium](https://modrinth.com/mod/sodium) | Unknown | The fastest rendering optimization mod for Minecraft. | Client | You should also install [Indium](https://modrinth.com/mod/indium) for better compatibiity. |
| [Starlight](https://modrinth.com/mod/starlight) | Unknown | Rewrites the light engine to fix lighting performance and lighting errors | Both | N/A |

# Situational
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [BetterBeds](https://modrinth.com/mod/better-beds) | None | Changes the renderer of the bed to use json models instead of a block entity renderer! | Client | Incompatible with Bedspreads. |
| [Debugify](https://modrinth.com/mod/debugify) | Unknown | Fixes Minecraft bugs found on the bug tracker | Both | This is mainly a bugfix mod, but some mods such as ForgetMeChunk and Entity Collision FPS Fix are included in this mod, so it counts. |
| [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) | Unknown | Reduce resource usage while Minecraft is in the background | Client | Also applies to battery mode and idle mode. Overrides Vanilla's "AFK Mode" setting. |
| [Memory Leak Fix](https://modrinth.com/mod/memoryleakfix) | Unknown | A mod that fixes random memory leaks for both the client and server | Both | Might cause mod conflicts. |
| [MoreCulling](https://modrinth.com/mod/moreculling) | Unknown | A mod that changes how multiple types of culling are handled in order to improve performance | Client | N/A |

# Edge case
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Faster Random](https://modrinth.com/mod/faster-random)  | Unknown | A significantly faster Random Generator implementation for Minecraft, with near vanilla parity. | Both | May cause higher RAM and I/O usage. |
| [Language Reload](https://modrinth.com/mod/language-reload) | Unknown | Reduces load times and adds fallbacks for languages | Client | N/A |
| [Sodium Extra](https://modrinth.com/mod/sodium-extra) | Unknown | A Sodium addon that adds features that shouldn't be in Sodium. | Client | Implements a more expanded version of OptiFine's particle disabling and animation settings. Also adds the ability to disable toasts |