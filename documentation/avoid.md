# April Rivenend's "Mods with Problematic Notes"
(a.k.a. "avoid.md", like radk6's list  but different)

A lot of mods tend to do unpredictable things, and sometimes I can never pin that down. Sometimes, I need to warn a friend about a mod, but I can never form my thoughts together properly.  
This list basically aims to fix both problems.

## Optifine
Because being pinned at the top is something a lot of people probably want to do.

| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [OptiFine](https://optifine.net) | Several mods | b1.7.3+ (except 1.21.5) | Client | [Many reasons.](./optifine.md) | 

## Deprecated mods
Mods that are outdated or abandoned, and have usually been replaced with better mods.

### Replaced by newer mods
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Born In A Barn](https://modrinth.com/mod/born-in-a-barn) | PolyPatcher, Universal Tweaks | 1.8.9 - 1.12.2 | Server | Replaced by Universal Tweaks (1.12) or PolyPatcher (1.8 & 1.12) for 1.8.9 and 1.12.2 |
| [FastCraft](https://www.curseforge.com/minecraft/mc-mods/fastcraft) | Angelica | 1.7.10 | Both | Replaced by Angelica |
| [TexFix](https://modrinth.com/mod/texfix) | LoliASM | 1.8.9 (curseforge only), 1.10.2, 1.11.2, 1.12.2 | Client(?) | Replaced by LoliASM on 1.12. May still be relevant on 1.8-1.11. |
| [VanillaFix](https://modrinth.com/mod/vanillafix) | LoliASM | 1.12.2 | Unknown | Replaced by LoliASM |

### Abandoned by creator
N/A

## Useless mods
Mods that do almost nothing.

### Doesn't increase FPS at all
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [FPS to the Trash](https://modrinth.com/mod/fps-to-the-trash) | VulkanMod | 1.15+ | Client | Doesn't actually optimize the game, just tosses frames the monitor can't see |

### No meaningful impact
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [BetterFPS](https://legacy.curseforge.com/minecraft/mc-mods/betterfps) | Unknown | 1.7.10 - 1.12.2 | Both | Mod compat issues & questionable FPS impact |
| [Noxesium](https://modrinth.com/mod/noxesium) | Unknown | 1.19.x - 1.21.x | Client | Doesn't do much helpful for performance, mainly only for MCC Island / Championship users or servers that integrate this mod |

## Dangerous mods
Mods that YOU SHOULD AVOID AT ALL COSTS, for various reasons.

### Makes performance worse
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Unbinillium](https://www.curseforge.com/minecraft/mc-mods/unbinilium) | Unknown | 1.20.x - 1.21.0 | Unsure | AI generated performance mod that actually makes performance worse! Never use this. |

### Unstable
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Fastload](https://modrinth.com/mod/fastload) | Unknown | 1.18.x - 1.20.1 | Both | Buggy, has caused visual issues before. For versions before 1.21.9 (25w31a+), use Ksyxis instead |
| [FastBoot](https://modrinth.com/mod/fastboot) | Unknown | 1.16.2 - 1.21.2 | Client | Has caused crashes before (possible mod incompatibility) |

## Buggy mods

### Visual Issues
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Extended Hotbar](https://modrinth.com/mod/extended-hotbar) | Unknown | 1.20.1, 1.20.4, 1.21.0-1.21.1 | Client | UI issues |
| [Graphene](https://modrinth.com/mod/graphene) | Unknown | 1.19.4 - 1.21.5 | Both (???) | Derivative of MPEM + Visual bugs |

### Other / general bugs
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Shared Resources](https://modrinth.com/mod/shared-resources) | Unknown | 1.16.x - 1.21.4 | Client | Good idea in theory, but in practice is awfully buggy, fucked up all of my mod configurations, and prompted me with the first run screen more than once. Also caused me to lose my 1.20.1 configuration. |
| [STFU](https://modrinth.com/mod/shuttfup) | Unknown | 1.20.x - 1.21.x | Meant to replace a bunch of mods, but caused a bunch of issues in the process. :( |

### Causes crashes
N/A


## From bad experience

### Unpredictable
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [DashLoader](https://modrinth.com/mod/dashloader) | Unknown | 1.16.5 - 1.21.4 (excl. 1.20.2/3/5 & 1.21.2) | Client | Has caused issues before & is allegedly unnecessary for 1.20.1 and below if you use ModernFix. |
| [Moonlit Performance Enhancement Module](https://modrinth.com/mod/mpem) | Unknown | 1.19.4 - 1.21.1 | Both (???) | Has caused crashes on 1.20.1 envs |

## Other mods
Mods that are on here for other reasons. (i.e: buggy but inconsistent replication, unrecommended on very specific configs, etc)  
Some of these mods are **not dangerous**, and might just be here because they do things you might not expect.

### Issues in very specific configurations
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Reese's Sodium Options](https://modrinth.com/mod/reeses-sodium-options) | Non-sodium rendering engines | 1.16.5+ | Client | Causes crashes in **rare** scenarios (i.e: modded), otherwise safe |

### Might do things the user doesn't want
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [ResourcePackCached](https://modrinth.com/mod/resourcepackcached) |  Unknown | 1.20.x - 1.21.x | Client | Keeps server resources loaded, **even** if you don't want it to |


# Not dangerous (Visual issues, morality issues, etc)
| Name | Incompatibilities | Version | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Animated Doors](https://modrinth.com/datapack/animated-doors) | Unknown | 1.19.x - 1.20.4 | Both (Required) | Manual setup. Requires a datapack on the server & a resource pack on the client. |
| [CloseOnMove](https://modrinth.com/mod/closeonmove) | Unknown | 1.17.x - 1.21.x | Client | Also closes when using REI search. |
| [Fractional GUI](https://modrinth.com/mod/fractionalgui) | Unknown | 1.18.2, 1.19.2-1.21.5 | Client | Graphical issues (fraction scaling settings look poor). Broken in 1.21.6 |

# Modpacks
| Name | Description | Author | Notes |
| --- | :---: | :---: | :---: |
| [Bedrock Visualization](https://modrinth.com/modpack/bedrock-visualization) | A visualization of Minecraft BEDROCK EDITION | Kotanutly | Shader included and turned ON by default. Only the main menu resembles Bedrock. Has Essential pre-installed and GUI menus for Essential enabled. |
| [Fabulously Optimized](https://modrinth.com/modpack/fabulously-optimized) | Beautiful graphics, speedy performance and familiar features in a simple package. | FO Team | Designed mainly for OptiFine migrators and contains a lot of mods you may or may not need, incluidng some added optional stuff that doesn't come from OptiFine at all. **Safe to use** and won't cause problems if you use it, but you should really use a modpack that has *just* optimizations and add whatever the hell you want from there. |