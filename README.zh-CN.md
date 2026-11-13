# 开源游戏清单（中文版）

> 一份把**开源游戏**与**商业游戏的开源重制版**收集在一起的清单。英文原版：[bobeff/open-source-games](https://github.com/bobeff/open-source-games)。

**语言 / Language：** [English](README.md) ｜ **简体中文**

## 这份清单是什么

- 收录 **164 个条目**（其中 155 个是游戏，9 个是"更多清单"链接），分成 **18 个品类**：从《Doom》《Quake》的源码移植，到《OpenMW》《OpenRCT2》这样的重制引擎，再到完全原创的开源游戏。
- 每个条目长这样：**游戏名**（官网链接）— 一句话介绍 — [[source]] 源码地址。
- 标了 **引擎：** 的，表示该项目使用的引擎（引擎本身通常也附源码链接）；标了 **界面：** 的表示界面库。
- 相当一部分条目属于三种特殊形态：**重实现（re-implementation）**、**逆向工程（reverse engineering）**、**源码移植（source port）**——它们通常需要你自备原版游戏资产才能运行。

## 中文导读：这份清单能怎么用

1. **找灵感**：想做一个塔防、城市建造或 roguelike，先看别人把同一个玩法做到了什么程度。
2. **找底子**：想快速上架（比如 TapTap 小游戏），挑一个玩法闭环小、协议宽松（MIT/Apache）的项目改造，比从零写快得多。
3. **学引擎**：想研究某个类型怎么实现，直接读源码往往比读教程有效。

## 阅读约定

- **游戏名保持英文原文**，方便你直接搜索、对照英文版与源码仓库；介绍文字译为中文。
- 分类沿用英文原版的结构与顺序，条目位置未做调整，方便与英文版逐条对照。
- 本中文版是社区翻译，若与英文版有出入，**以英文版为准**。

## 协议与使用提醒

- 本清单本身采用 **CC0-1.0**，可自由复制、修改、商用，无需署名。
- 但**每个项目的代码协议各不相同**：MIT/Apache-2.0 最宽松（可闭源商用）；MPL-2.0 是文件级 copyleft（改动的文件需开源）；GPL 系列有传染性（衍生作品需整体开源）。**改造或商用前请逐个确认。**
- **美术、音乐等素材往往与代码分开授权**，有的甚至来自原版商业游戏（如 OpenMW、OpenRA 需要你自备原版资产），不要想当然。
- 游戏名称与商标归各自权利人所有。

## 分类速览

| 品类 | 条目数 |
|---|---|
| [动作游戏](#动作游戏) | 1 |
| [冒险游戏](#冒险游戏) | 6 |
| [商业与经营模拟游戏](#商业与经营模拟游戏) | 5 |
| [城市建造游戏](#城市建造游戏) | 8 |
| [第一人称游戏](#第一人称游戏) | 33 |
| [平台游戏](#平台游戏) | 9 |
| [解谜游戏](#解谜游戏) | 3 |
| [竞速游戏](#竞速游戏) | 12 |
| [即时战略游戏](#即时战略游戏) | 21 |
| [类 Rogue 游戏](#类-rogue-游戏) | 7 |
| [角色扮演游戏](#角色扮演游戏) | 23 |
| [沙盒游戏](#沙盒游戏) | 1 |
| [射击游戏](#射击游戏) | 2 |
| [体育游戏](#体育游戏) | 2 |
| [第三人称游戏](#第三人称游戏) | 8 |
| [塔防游戏](#塔防游戏) | 1 |
| [回合制策略游戏](#回合制策略游戏) | 13 |
| [其他清单](#其他清单) | 9 |

## 目录

- [动作游戏](#动作游戏)
- [冒险游戏](#冒险游戏)
- [商业与经营模拟游戏](#商业与经营模拟游戏)
- [城市建造游戏](#城市建造游戏)
- [第一人称游戏](#第一人称游戏)
- [平台游戏](#平台游戏)
- [解谜游戏](#解谜游戏)
- [竞速游戏](#竞速游戏)
- [即时战略游戏](#即时战略游戏)
- [类 Rogue 游戏](#类-rogue-游戏)
- [角色扮演游戏](#角色扮演游戏)
- [沙盒游戏](#沙盒游戏)
- [射击游戏](#射击游戏)
- [体育游戏](#体育游戏)
- [第三人称游戏](#第三人称游戏)
- [塔防游戏](#塔防游戏)
- [回合制策略游戏](#回合制策略游戏)
- [其他清单](#其他清单)


## 动作游戏

- **[Hypersomnia](https://hypersomnia.io)** - 竞技性俯视射击游戏，节奏极快、像素怀旧风，自带地图编辑器。 [[source]](https://github.com/TeamHypersomnia/Hypersomnia)

## 冒险游戏

- **[Dead Ascend](https://blackgrain.dk/games/deadascend)** - 丧尸题材冒险解谜游戏，逃生途中处处有反转。 [[source]](https://github.com/larpon/DeadAscend)

- **[Endless Sky](https://endless-sky.github.io)** - 太空探索、贸易与战斗游戏。 [[source]](https://github.com/endless-sky/endless-sky)

- **[Pioneer](https://pioneerspacesim.net)** - 设定在 33 世纪之交银河系中的太空冒险游戏。 [[source]](https://github.com/pioneerspacesim/pioneer)

- **[ScummVM](https://www.scummvm.org)** - 可运行多款经典图形冒险与角色扮演游戏的开源程序。 [[source]](https://github.com/scummvm/scummvm)

- **[The Legend of Zelda: Twilight Princess](https://zsrtp.link)** - 逆向工程项目，把 *[Twilight Princess](https://en.wikipedia.org/wiki/The_Legend_of_Zelda:_Twilight_Princess)* 反编译成人类可读、可修改的源码。 [[source]](https://github.com/zeldaret/tp)

- **Zelda 3** - *[The Legend of Zelda: A Link to the Past](https://en.wikipedia.org/wiki/The_Legend_of_Zelda:_A_Link_to_the_Past)* 的逆向工程克隆版。 [[source]](https://github.com/snesrev/zelda3)

## 商业与经营模拟游戏

- **[CorsixTH](https://corsixth.com)** - [Theme Hospital](https://en.wikipedia.org/wiki/Theme_Hospital) 的开源克隆。 [[source]](https://github.com/CorsixTH/CorsixTH)

- **[Hurry Curry!](https://hurrycurry.org)** - 快节奏多人合作烹饪游戏。 [[source]](https://codeberg.org/hurrycurry/hurrycurry)

- **[OpenLoco](https://openloco.io)** - [Chris Sawyer](https://en.wikipedia.org/wiki/Chris_Sawyer) 的 [Locomotion](https://en.wikipedia.org/wiki/Chris_Sawyer%27s_Locomotion) 的开源重制实现。 [[source]](https://github.com/OpenLoco/OpenLoco)

- **[OpenRCT2](https://openrct2.org)** - *[RollerCoaster Tycoon 2](https://en.wikipedia.org/wiki/RollerCoaster_Tycoon_2)* 的开源重制实现。 [[source]](https://github.com/OpenRCT2/OpenRCT2)

- **[OpenTTD](https://www.openttd.org)** - 基于 *[Transport Tycoon Deluxe](https://en.wikipedia.org/wiki/Transport_Tycoon)* 的开源模拟游戏。 [[source]](https://github.com/OpenTTD/OpenTTD)

## 城市建造游戏

- **[Akhenaten](https://dalerank.itch.io/akhenaten)** - 战略型城市建造游戏，沿用 *[Pharaoh + Cleopatra](https://en.wikipedia.org/wiki/Pharaoh_(video_game)* 的素材与玩法机制，玩家扮演古埃及文明的统治者兼市长。 [[source]](https://github.com/dalerank/Akhenaten)

- **[Citybound](https://aeplay.org/citybound)** - 城市建造游戏，用微观模型生动模拟一座城市如何由千万个体的交互生长出来。 [[source]](https://github.com/citybound/citybound)

- **[Cytopia](https://cytopia.itch.io/cytopia)** - 免费开源的复古像素风城市建造游戏。 [[source]](https://github.com/CytopiaTeam/Cytopia)

- **Egregoria** - Egregoria 是一款独立城市建造游戏，灵感主要来自 *[Cities: Skylines](https://en.wikipedia.org/wiki/Cities:_Skylines)*。 [[source]](https://github.com/Uriopass/Egregoria)

- **[IsoCity](https://iso-city.com)** - 等距视角城市建造模拟游戏，技术栈为 NextJS、TypeScript 与 TailwindCSS。 [[source]](https://github.com/amilich/isometric-city)

- **Julius** - *[Caesar III](https://en.wikipedia.org/wiki/Caesar_III)* 的开源重制实现。 [[source]](https://github.com/bvschaik/julius)

- **[micropolisJS](http://www.graememcc.co.uk/micropolisJS)** - 开源城市模拟游戏 *[Micropolis](https://mvolution.itch.io/micropolis)* 的手写 JavaScript 移植版。 [[source]](https://github.com/graememcc/micropolisJS)

- **[Unknown Horizons](https://unknown-horizons.org)** - 侧重经济与城市建造的 2D 实时策略模拟游戏。

  - **原始版：** [[source]](https://github.com/unknown-horizons/unknown-horizons) **引擎：[FIFE](https://www.fifengine.net/)** [[source]](https://github.com/fifengine/fifengine)

  - **Godot 移植版：** [[source]](https://github.com/unknown-horizons/godot-port) **引擎：[Godot](https://godotengine.org)** [[source]](https://github.com/godotengine/godot)

## 第一人称游戏

- **[.kkrieger](https://en.wikipedia.org/wiki/.kkrieger)** - 由德国 demo 团队 .theprodukkt（[Farbrausch](https://en.wikipedia.org/wiki/Farbrausch) 的前分支）制作的第一人称射击游戏，2004 年 4 月在 [Breakpoint](https://en.wikipedia.org/wiki/Breakpoint_(demoparty)) 的 96k 游戏竞赛中夺得第一名。 [[source]](https://github.com/farbrausch/fr_public/tree/master/werkkzeug3_kkrieger)

- **[Anarch](https://drummyfish.gitlab.io/anarch)** - 这不是 90 年代风格的复古射击游戏，这就是 90 年代的射击游戏。 [[source]](https://gitlab.com/drummyfish/anarch)

- **[AssaultCube](https://assault.cubers.net)** - 免费多人第一人称射击游戏。[[source]](https://github.com/assaultcube/AC) **引擎：[CUBE](http://cubeengine.com)** [[source]](https://github.com/bsegovia/cube)

- **[Cube 2: Sauerbraten](http://sauerbraten.org)** - 免费的多人与单人第一人称射击游戏。[[source]](https://sourceforge.net/projects/sauerbraten) **引擎：[CUBE](https://www.redeclipse.net)** [[source]](https://github.com/bsegovia/cube)

- **[Descent 3](https://en.wikipedia.org/wiki/Descent_3)** - 第一人称射击游戏。 [[source]](https://github.com/kevinbentley/Descent3)

- **[Liblast](https://libla.st)** - 用 Godot 4 引擎与全开源工具链制作的自由软件多人 FPS。[[source]](https://codeberg.org/liblast/liblast) **引擎：[Godot](https://godotengine.org)** [[source]](https://github.com/godotengine/godot)

- **[Red Eclipse](https://www.redeclipse.net)** - 面向现代玩家的老派竞技场射击游戏。[[source]](https://github.com/redeclipse/base) **引擎：[CUBE](https://www.redeclipse.net)** [[source]](https://github.com/bsegovia/cube)

- **Surreal Engine** - [Unreal Tournament](https://en.wikipedia.org/wiki/Unreal_Tournament) 引擎重实现。 [[source]](https://github.com/dpjudas/SurrealEngine)

- **[The Dark Mod](https://www.thedarkmod.com/main)** - 第一人称潜行游戏。 [[source]](https://svn.thedarkmod.com/publicsvn/darkmod_src/trunk)

- **[Xonotic](https://xonotic.org)** - 令人上瘾的竞技场风格第一人称射击游戏，移动手感干脆利落，武器种类丰富。 [[source]](https://gitlab.com/xonotic/xonotic)

### *[Aliens Versus Predator](https://en.wikipedia.org/wiki/Aliens_Versus_Predator_(1999_video_game)) 游戏的源码移植版*

- **AvP Forever** - 项目专注于维护 *Aliens versus Predator (1999)* 现存的游戏源码。 [[source]](https://github.com/dreamer/avp-forever)

- **avpmp** - 原始 AvP Linux 移植版的分支，扩展了多人模式等功能。 [[source]](https://github.com/mbait/avpmp)

- **NakedAVP** - 把 *Aliens vs Predator Classic (2000)* 移植到现代系统的版本，基于 icculus 为 Linux、macOS、Windows 做的移植，使用 [SDL3](https://libsdl.org/)（[[source]](https://github.com/libsdl-org/SDL)）。 [[source]](https://github.com/atsb/NakedAVP)

### *基于 [Build engine](https://en.wikipedia.org/wiki/Build_(game_engine)) [[source]](https://advsys.net/ken/buildsrc) 引擎的游戏*

- **[Duke Nukem 3D](https://en.wikipedia.org/wiki/Duke_Nukem_3D)** - 由 [3D Realms Entertainment, Inc](https://en.wikipedia.org/wiki/3D_Realms) 出品。 [[source]](https://github.com/videogamepreservation/dukenukem3d)

- **Shadow Warrior** - [Shadow Warrior](https://en.wikipedia.org/wiki/Shadow_Warrior_(1997_video_game)) 的官方源码发布。 [[source]](https://github.com/Azarien/shadow-warrior)

#### *源码移植与重实现*

- **BuildGDX** - [[source]](https://github.com/vogonsorg/BuildGDX)

- **[EDuke32](https://voidpoint.io/terminx/eduke32)** - EDuke32 官方 Git 仓库：EDuke32、[Ion Fury](https://en.wikipedia.org/wiki/Ion_Fury)、VoidSW、Mapster32 以及基于 Build 引擎的相关项目源码都在这里。

- **[JFDuke3D](https://www.jonof.id.au/jfduke3d)** - [3D Realms](https://en.wikipedia.org/wiki/3D_Realms) 游戏 [Duke Nukem 3D](https://en.wikipedia.org/wiki/Duke_Nukem_3D) 的移植版。 [[source]](https://github.com/jonof/jfduke3d)

- **[JFShadowWarrior](https://www.jonof.id.au/jfsw)** - [3D Realms](https://en.wikipedia.org/wiki/3D_Realms) 游戏 [Shadow Warrior](https://en.wikipedia.org/wiki/Shadow_Warrior_(1997_video_game)) 的移植版。

- **[NBlood](https://github.com/NBlood/NBlood)** - 用 EDuke32 引擎技术与开发原则对 Build 系游戏做的逆向移植（NBlood/Rednukem/PCExhumed）。 [[source]](https://github.com/NBlood/NBlood)

- **NuBuildGDX** - BuildGDX 的分支，目标是稳定性、修 bug 与性能。 [[source]](https://github.com/atsb/NuBuildGDX)

- **[Raze](https://github.com/ZDoom/Raze)** - 由 GZDoom 技术驱动的 Build 引擎移植版，目前支持 [Duke Nukem 3D](https://en.wikipedia.org/wiki/Duke_Nukem_3D)、[Blood](https://en.wikipedia.org/wiki/Blood_(video_game))、[Shadow Warrior](https://en.wikipedia.org/wiki/Shadow_Warrior_(1997_video_game))、[Redneck Rampage](https://en.wikipedia.org/wiki/Redneck_Rampage) 与 [Powerslave](https://en.wikipedia.org/wiki/PowerSlave)/Exhumed。

### *[id Software](https://en.wikipedia.org/wiki/Id_Software) 游戏*

- **[Doom](https://en.wikipedia.org/wiki/Doom_(1993_video_game))** - [[source]](https://github.com/id-Software/DOOM)

- **DOOM64-RE** - [Doom 64](https://en.wikipedia.org/wiki/Doom_64) 的完整逆向工程。 [[source]](https://github.com/Erick194/DOOM64-RE)

- **[Doom 3](https://en.wikipedia.org/wiki/Doom_3) BFG Edition** - [[source]](https://github.com/id-Software/DOOM-3-BFG)

- **[Quake](https://en.wikipedia.org/wiki/Quake_(video_game))** - [[source]](https://github.com/id-Software/Quake)

- **[Quake II](https://en.wikipedia.org/wiki/Quake_II)** - [[source]](https://github.com/id-Software/Quake-2)

- **[Quake III Arena](https://en.wikipedia.org/wiki/Quake_III_Arena)** - [[source]](https://github.com/id-Software/Quake-III-Arena)

- **[Wolfenstein 3D](https://en.wikipedia.org/wiki/Wolfenstein_3D)** - [[source]](https://github.com/id-Software/wolf3d)

#### *源码移植与重实现*

- **[Catacomb 3-D](https://en.wikipedia.org/wiki/Catacomb_3-D)**

  - **CatacombGL** - Catacomb 3D 与 Catacomb 冒险系列的源码移植。 [[source]](https://github.com/ArnoAnsems/CatacombGL)

- **[Doom](https://en.wikipedia.org/wiki/Doom_(1993_video_game))**

  - **[Chocolate Doom](https://www.chocolate-doom.org)** - 忠实还原 1990 年代 Doom 游玩体验的 Doom 源码移植。 [[source]](https://github.com/chocolate-doom/chocolate-doom)

  - **[ZDoom](https://zdoom.org)** - 面向所有 Doom 引擎游戏、以功能丰富为目标的移植版。 [[source]](https://github.com/UZDoom/UZDoom)

- **[Quake](https://en.wikipedia.org/wiki/Quake_(video_game))**

  - **Chocolate Quake** - 纯粹主义的 Quake 源码移植，还原 v1.09 及更早版本的原汁原味。 [[source]](https://github.com/Henrique194/chocolate-quake)

  - **[FTEQW](https://www.fteqw.org)** - 用于游玩与 mod idTech 系游戏的强大引擎。 [[source]](https://github.com/fte-team/fteqw)

- **[Wolfenstein 3D](https://en.wikipedia.org/wiki/Wolfenstein_3D)**

  - **ECWolf** - 基于 Wolf4SDL 的 Wolfenstein 3D 引擎移植版。 [[source]](https://bitbucket.org/ecwolf/ecwolf)

  - **Wolf4SDL** - id Software 经典 FPS《Wolfenstein 3D》移植到跨平台多媒体库 SDL 的开源版本。 [[source]](https://github.com/lazd/wolf4sdl)

## 平台游戏

- **[Commander Keen](https://en.wikipedia.org/wiki/Commander_Keen)**

  - **Commander-Genius** - Commander Keen（1-6、Dreams）与 [Cosmo's Cosmic](https://en.wikipedia.org/wiki/Cosmo%27s_Cosmic_Adventure) 系列的开源解释器，可游玩原版章节及部分 mod。 [[source]](https://gitlab.com/Dringgstein/Commander-Genius)

  - **[Commander Keen in Keen Dreams](https://en.wikipedia.org/wiki/Commander_Keen_in_Keen_Dreams)** - id Software 开发的横版卷轴平台游戏。 [[source]](https://github.com/keendreams/keen)

  - **Omnispeak** - [Commander Keen in Goodbye Galaxy](https://en.wikipedia.org/wiki/Commander_Keen_in_Goodbye,_Galaxy) 的开源重实现。 [[source]](https://github.com/sulix/omnispeak)

- **[DDraceNetwork](https://ddnet.tw)** - 合作向 2D 在线平台游戏。 [[source]](https://github.com/ddnet/ddnet)

- **[Fish Folk](https://fishfolk.org) Games**

  - **[Jumpy](https://fishfolk.org/games/jumpy)** - 战术 2D 射击游戏。[[source]](https://github.com/fishfolk/jumpy) **引擎：[Bevy](https://bevy.org/)** [[source]](https://github.com/bevyengine/bevy)

  - **[Punchy](https://github.com/fishfolk/punchy)** - 用 Bevy 制作的 2.5D 横版格斗游戏。**引擎：[Bevy](https://bevy.org/)** [[source]](https://github.com/bevyengine/bevy)

- **[Frogatto & Friends](https://frogatto.com)** - 动作冒险平台游戏，主角是一只古怪的青蛙。[[source]](https://github.com/frogatto/frogatto) **引擎：Anura** [[source]](https://github.com/anura-engine/anura)

- **[OpenGOAL](https://opengoal.dev)** - 本项目把 [Jak & Daxter Series](https://en.wikipedia.org/wiki/Jak_and_Daxter) 移植到 PC。 [[source]](https://github.com/water111/jak-project)

- **Rigel Engine** - 本项目是 [Duke Nukem II](https://en.wikipedia.org/wiki/Duke_Nukem_II) 的重实现，原作由 Apogee Software 于 1993 年为 MS-DOS 发行。 [[source]](https://github.com/lethal-guitar/RigelEngine)

- **[Sonic Robo Blast 2](https://www.srb2.org)** - 基于 Doom 引擎的 3D 索尼克同人开源游戏。 [[source]](https://git.do.srb2.org/STJr/SRB2)

- **Super Mario 64** - [Super Mario 64](https://en.wikipedia.org/wiki/Super_Mario_64) 的完整反编译。 [[source]](https://github.com/n64decomp/sm64)

- **[VVVVVV](https://thelettervsixtim.es/)** - [[source]](https://github.com/TerryCavanagh/VVVVVV)

## 解谜游戏

- **[BlockOut II](http://www.blockout.net/blockout2)** - 对 1989 年 California Dreams 发行的 DOS 游戏 BlockOut® 的免费改编。 [[source]](https://sourceforge.net/projects/blockout/files/blockout/BlockOut%202.5)

- **Portal64** - [Portal](https://en.wikipedia.org/wiki/Portal_(video_game)) 的 demake（为更老平台做的重制版），面向 Nintendo 64。 [[source]](https://github.com/mwpenny/portal64-still-alive)

- **[Whatajong](https://whatajong.com)** - [[source]](https://github.com/masylum/whatajong)

## 竞速游戏

- **[Dust Racing 2D](https://github.com/juzzlin/DustRacing2D)** - 传统俯视视角赛车游戏，含关卡编辑器。 [[source]](https://github.com/cflavio/yorg)

- **[ManiaDrive](http://maniadrive.raydium.org)** - [TrackMania](https://en.wikipedia.org/wiki/TrackMania) 的免费克隆，原作是 [Nadéo](https://en.wikipedia.org/wiki/Nadeo) 工作室的经典作品。[[source]](http://maniadrive.raydium.org/index.php?downloads=yes) **引擎：[Raydium](https://raydium.org)** [[source]](https://raydium.org/data.php)

- **[Rigs of Rods](https://www.rigsofrods.org)** - 开源物理沙盒模拟游戏，可实时模拟车辆的运动与形变。[[source]](https://github.com/RigsOfRods/rigs-of-rods) **引擎：[OGRE](https://www.ogre3d.org)** [[source]](https://github.com/OGRECave) **界面：[Dear ImGui](https://www.dearimgui.com)** [[source]](https://github.com/ocornut/imgui)

- **[RVGL](https://re-volt.io)** - [Re-Volt](https://en.wikipedia.org/wiki/Re-Volt) 的跨平台重写/移植版，可在 Windows 与 GNU/Linux 上原生运行。 [[source]](https://gitlab.com/re-volt)

- **[Speed Dreams](https://www.speed-dreams.net)** - 免费开源的赛车模拟器。 [[source]](https://forge.a-lec.org/xavi/speed-dreams-code)

- **[Stunt Rally](https://stuntrally.tuxfamily.org)** - 带科幻元素、自带赛道编辑器的 3D 竞速游戏。 [[source]](https://github.com/stuntrally/stuntrally3)

- **[SuperTuxKart](https://supertuxkart.net)** - 免费卡丁车竞速游戏，主打乐趣而非真实卡丁车物理。 [[source]](https://github.com/supertuxkart/stk-code)

- **[TORCS - The Open Racing Car Simulator](https://torcs.sourceforge.net)** - 高可移植性的多平台赛车模拟，可用作普通赛车游戏、AI 赛车游戏与研究平台。 [[source]](https://sourceforge.net/projects/torcs)

- **[Trigger Rally](https://trigger-rally.sourceforge.io)** - 快节奏单人竞速游戏，支持 Linux 与 Windows。 [[source]](https://sourceforge.net/projects/trigger-rally)

- **[VDrift](https://vdrift.net)** - 跨平台开源驾驶模拟，以漂移竞速为核心设计。 [[source]](https://github.com/VDrift/vdrift)

- **[Yorg](https://ya2.itch.io/yorg)** - Yorg（Yorg's an Open Racing Game）是 Ya2 用 Panda3D 开发的免费开源竞速游戏，支持 Windows、OSX 与 Linux。[[source]](https://github.com/cflavio/yorg) **引擎：[Panda3D](https://www.panda3d.org)** [[source]](https://github.com/panda3d/panda3d)

- **[wipEout](https://phoboslab.org/log/2023/08/rewriting-wipeout)** - 1995 年 PSX 游戏 [Wipeout](https://en.wikipedia.org/wiki/Wipeout_(video_game)) 的重实现。 [[source]](https://github.com/phoboslab/wipeout-rewrite)

## 即时战略游戏

- **[0 A.D.](https://play0ad.com)** - 免费开源的古战争题材游戏。 [[source]](https://gitea.wildfiregames.com/0ad/0ad)

- **[BAR](https://www.beyondallreason.info)** - Beyond All Reason。[[source]](https://github.com/beyond-all-reason/Beyond-All-Reason) **引擎：[Spring](https://springrts.com)** [[source]](https://github.com/spring/spring)

- **[Dune II The Maker](https://dune2themaker.fundynamic.com)** - 《沙丘 2》重制版。 [[source]](https://github.com/stefanhendriks/Dune-II---The-Maker)

- **Freeserf.net** - [BlueByte](https://en.wikipedia.org/wiki/Ubisoft_Blue_Byte) 出品的 [The Settlers I](https://en.wikipedia.org/wiki/The_Settlers) 的忠实重制版。 [[source]](https://github.com/Pyrdacor/freeserf.net)

- **[Keeper FX](https://keeperfx.net)** - [Dungeon Keeper](https://en.wikipedia.org/wiki/Dungeon_Keeper) 的开源重制与粉丝扩展版。 [[source]](https://github.com/dkfans/keeperfx)

- **[Mindustry](https://mindustrygame.github.io)** - 沙盒塔防游戏。 [[source]](https://github.com/Anuken/Mindustry)

- **[OpenAge](https://openage.sft.mx)** - 免费（自由软件意义）跨平台 RTS 游戏引擎，提供 [Age of Empires](https://en.wikipedia.org/wiki/Age_of_Empires) 的机制。 [[source]](https://github.com/SFTtech/openage)

- **[OpenHV](https://www.openhv.net)** - 开源像素科幻即时战略游戏。 [[source]](https://github.com/OpenHV/OpenHV)

- **[OpenRA](https://www.openra.net)** - [Command & Conquer](https://en.wikipedia.org/wiki/Command_%26_Conquer)、[Dune 2000](https://en.wikipedia.org/wiki/Dune_2000) 与 [Red Alert](https://en.wikipedia.org/wiki/Command_%26_Conquer:_Red_Alert) 面向现代平台的重制。 [[source]](https://github.com/OpenRA/OpenRA)

- **Permafrost Engine** - 用 C 语言编写的 OpenGL 3.3 即时战略游戏引擎。 [[source]](https://github.com/eduard-permyakov/permafrost-engine)

- **Standard Of Iron** - 用 C++20、Qt 6 与 OpenGL 3.3 Core 构建的现代 RTS 游戏引擎。 [[source]](https://github.com/djeada/Standard-of-Iron)

- **[Warzone 2100](https://wz2100.net)** - 免费开源 3D 即时战略游戏，含剧情驱动单人战役、在线多人、离线遭遇战等。 [[source]](https://github.com/Warzone2100/warzone2100)

- **[Widelands](https://www.widelands.org)** - 免费开源即时战略游戏。 [[source]](https://github.com/widelands/widelands)

- **[Zero-K](https://zero-k.info/)** - 有物理弹道、智能单位与强大 UI 的 RTS 游戏。[[source]](https://github.com/ZeroK-RTS/Zero-K) **引擎：[Spring](https://springrts.com)** [[source]](https://github.com/spring/spring)

### *[Blizzard Entertainment](https://en.wikipedia.org/wiki/Blizzard_Entertainment) 游戏重实现*

- **OpenBW** - 免费开源的最佳战争游戏。**[Brood War API](https://bwapi.github.io)** [[source]](https://github.com/OpenBW/bwapi) [[source]](https://github.com/OpenBW/openbw)

- **[Strategus](https://stratagus.com)** Engine Games [[source]](https://github.com/Wargus/stratagus)

  - **[War1gus](https://stratagus.com/war1gus.html)** - [Warcraft: Orcs & Humans](https://en.wikipedia.org/wiki/Warcraft:_Orcs_%26_Humans) 的重实现，可在现代平台游玩。 [[source]](https://github.com/Wargus/war1gus)

  - **[Wargus](https://stratagus.com)** - [Warcraft II: Tides of Darkness](https://en.wikipedia.org/wiki/Warcraft_II:_Tides_of_Darkness)、资料片 [Beyond the Dark Portal](https://en.wikipedia.org/wiki/Warcraft_II:_Beyond_the_Dark_Portal) 与 Aleonas Tales 的导入器与脚本。 [[source]](https://github.com/Wargus/wargus)

  - **[Wyrmsun](https://andrettin.github.io)** - 融合神话、历史与虚构元素的策略游戏。 [[source]](https://github.com/Andrettin/Wyrmsun)

  - **[Stargus](https://stratagus.com/stratagus.html)** - [Starcraft](https://en.wikipedia.org/wiki/StarCraft) 的导入器与脚本。 [[source]](https://github.com/Wargus/stargus)

- **Warsmash Mod Engine** - 用于改善《魔兽争霸 III》mod 制作的模拟引擎。[[source]](https://github.com/Retera/WarsmashModEngine) **引擎：[LibGDX](https://libgdx.com)** [[source]](https://github.com/libgdx/libgdx)

### *[Command & Conquer](https://en.wikipedia.org/wiki/Command_%26_Conquer) 系列的 [Westwood Studios](https://en.wikipedia.org/wiki/Westwood_Studios) 与 [EA](https://en.wikipedia.org/wiki/Electronic_Arts) 游戏*

- **Command & Conquer Remastered Collection** - [Command & Conquer Remastered Collection](https://en.wikipedia.org/wiki/Command_%26_Conquer_Remastered_Collection) 的 TiberianDawn.dll、RedAlert.dll 与地图编辑器。 [[source]](https://github.com/electronicarts/CnC_Remastered_Collection)

- **Generals** - [Command & Conquer Generals](https://en.wikipedia.org/wiki/Command_%26_Conquer:_Generals) 及其资料片 [Zero Hour](https://en.wikipedia.org/wiki/Command_%26_Conquer:_Generals_%E2%80%93_Zero_Hour)。 [[source]](https://github.com/electronicarts/CnC_Generals_Zero_Hour)

- **[Red Alert](https://en.wikipedia.org/wiki/Command_%26_Conquer:_Red_Alert)** - [[source]](https://github.com/electronicarts/CnC_Red_Alert)

- **[Tiberian Dawn](https://en.wikipedia.org/wiki/Command_%26_Conquer_(1995_video_game))** - [[source]](https://github.com/electronicarts/CnC_Tiberian_Dawn)

## 类 Rogue 游戏

- **[Brogue CE](https://sites.google.com/site/broguegame/)** - Brogue 是一款极简、回合制、程序生成的 roguelike：你深入险恶地牢，只为取回 Amulet of Yendor。 [[source]](https://github.com/tmewett/BrogueCE)

- **[Cataclysm: Dark Days Ahead](https://cataclysmdda.org)** - 末日废土背景的回合制生存游戏。 [[source]](https://github.com/CleverRaven/Cataclysm-DDA)

- **[Dungeon Crawl Stone Soup](https://crawl.develz.org)** - 开源 roguelike 冒险：穿越满是危险怪物的地牢，寻找传说中的 Orb of Zot。 [[source]](https://github.com/crawl/crawl)

- **[NetHack](https://nethack.org)** - 单人地牢探索游戏。 [[source]](https://github.com/NetHack/NetHack)

- **[Meritous](http://asceai.net/meritous)** - 动作冒险式地牢爬行游戏。 [[source]](https://github.com/Patashu/Meritous)

- **OpenNefia** - 日本 roguelike [Elona](https://en.wikipedia.org/wiki/Elona_(video_game)) 的可 mod 引擎重实现。 [[source]](https://github.com/OpenNefia/OpenNefia)

- **[Shattered Pixel Dungeon](https://shatteredpixel.com)** - 开源传统 roguelike 地牢爬行游戏，关卡与敌人随机生成，数百种道具可收集使用。 [[source]](https://github.com/00-Evan/shattered-pixel-dungeon)

## 角色扮演游戏

- **[Ambermoon.net](https://pyrdacor.itch.io/ambermoon)** - [Ambermoon](https://en.wikipedia.org/wiki/Ambermoon) 的完整 C# 重写。 [[source]](https://github.com/Pyrdacor/Ambermoon.net)

- **[Daggerfall Unity](https://www.dfworkshop.net)** - 用 Unity 引擎对 [Daggerfall](https://en.wikipedia.org/wiki/The_Elder_Scrolls_II:_Daggerfall) 的开源重制。 [[source]](https://github.com/Interkarma/daggerfall-unity)

- **[Exult](https://exult.sourceforge.io)** - 面向现代操作系统重制 [Ultima VII](https://en.wikipedia.org/wiki/Ultima_VII:_The_Black_Gate) 的项目。 [[source]](https://github.com/exult/exult)

- **Fallout Community Edition** - [Fallout](https://en.wikipedia.org/wiki/Fallout_(video_game)) 的完整可用重实现。 [[source]](https://github.com/alexbatalov/fallout1-ce)

- **Fallout 2 Community Edition** - [Fallout 2](https://en.wikipedia.org/wiki/Fallout_2) 的完整可用重实现。 [[source]](https://github.com/alexbatalov/fallout2-ce)

- **[GemRB](https://gemrb.org)** - Bioware [Infinity Engine](https://en.wikipedia.org/wiki/Infinity_Engine) 的可移植开源实现

  **支持的游戏：

  - [Baldur’s Gate](https://en.wikipedia.org/wiki/Baldur%27s_Gate_(video_game))

  - [Baldur's Gate II: Shadows of Amn](https://en.wikipedia.org/wiki/Baldur%27s_Gate_II:_Shadows_of_Amn)

  - [Icewind Dale](https://en.wikipedia.org/wiki/Icewind_Dale)

  - [Icewind Dale II](https://en.wikipedia.org/wiki/Icewind_Dale_II)

  - [Planescape: Torment](https://en.wikipedia.org/wiki/Planescape:_Torment)

- **[Kandria](https://kandria.com)** - 用 Common Lisp 制作的动作 RPG。[[source]](https://codeberg.org/shirakumo/kandria) **引擎：[Trial](https://shirakumo.org/docs/trial/)** [[source]](https://codeberg.org/shirakumo/trial)

- **[Naev](https://naev.org)** - 2D 动作/RPG 太空游戏，融合动作、RPG 与模拟要素。 [[source]](https://codeberg.org/naev/naev)

- **[Oolite](https://www.oolite.space/)** - 开放世界太空歌剧。 [[source]](https://github.com/OoliteProject/oolite)

- **OpenEnroth** - 使用原始数据与代码的 [Might and Magic VI-VIII](https://en.wikipedia.org/wiki/Might_and_Magic) 引擎重制。 [[source]](https://github.com/OpenEnroth/OpenEnroth)

- **[OpenMW](https://openmw.org)** - 免费开源的现代引擎，重实现并扩展 2002 年的 Gamebryo 引擎，用于开放世界 RPG [The Elder Scrolls III: Morrowind](https://en.wikipedia.org/wiki/The_Elder_Scrolls_III:_Morrowind)。 [[source]](https://github.com/OpenMW/openmw)

- **OpenNox** - 开源社区协作项目，扩展 Nox 引擎。 [[source]](https://github.com/noxworld-dev/opennox)

- **reone** - 免费开源游戏引擎，可运行 [Star Wars: Knights of the Old Republic](https://en.wikipedia.org/wiki/Star_Wars:_Knights_of_the_Old_Republic) 及其续作 [The Sith Lords](https://en.wikipedia.org/wiki/Star_Wars_Knights_of_the_Old_Republic_II:_The_Sith_Lords)。 [[source]](https://github.com/seedhartha/reone)

- **[Severed Chains](https://legendofdragoon.org/projects/severed-chains)** - [The Legend of Dragoon](https://en.wikipedia.org/wiki/The_Legend_of_Dragoon) 的反编译、逆向工程并移植到 PC/Mac/Linux/Steam Deck。 [[source]](https://github.com/Legend-of-Dragoon-Modding/Severed-Chains)

- **[Space Station 14](https://spacestation14.io/)** – Open-source remake of [Space Station 13](https://en.wikipedia.org/wiki/Space_Station_13). [[source]](https://github.com/space-wizards/space-station-14)

- **[Ultima VII: Revisited](https://www.u7revisited.com)** - [Ultima VII](https://en.wikipedia.org/wiki/Ultima_VII:_The_Black_Gate) 的替换引擎，把游戏以 3D 呈现，并修复了原作的诸多问题。 [[source]](https://github.com/ViridianGames/U7Revisited)

- **[Veloren](https://www.veloren.net/)** - 用 Rust 编写的多人体素 RPG。 [[source]](https://github.com/veloren/veloren)

### *[Diablo](https://en.wikipedia.org/wiki/Diablo_(series)) 重实现*

- **Abyss Engine** - [Diablo 2](https://en.wikipedia.org/wiki/Diablo_II) 的净室重实现，用 C 编写。 [[source]](https://github.com/AbyssEngine/AbyssEngine)

- **[DevilutionX](https://devilutionx.com/)** - [Diablo](https://en.wikipedia.org/wiki/Diablo_(video_game)) 与 [Hellfire](https://en.wikipedia.org/wiki/Diablo:_Hellfire) 的移植版，力求开箱即玩，同时提供引擎改进、bug 修复与部分可选的体验优化。 [[source]](https://github.com/diasurgical/devilutionX)

- **[Freeablo](https://freeablo.org)** - 仍在开发中的免费开源 [Diablo I](https://en.wikipedia.org/wiki/Diablo_(video_game)) 引擎替代品。 [[source]](https://github.com/wheybags/freeablo)

- **Open Diablo II** - [Diablo 2](https://en.wikipedia.org/wiki/Diablo_II) 的开源重实现。 [[source]](https://github.com/OpenDiablo2/OpenDiablo2)

### *大型多人在线角色扮演游戏*

- **OpenKO** - 老派 [Knight Online](https://en.wikipedia.org/wiki/Knight_Online) MMORPG 的开源版本。 [[source]](https://github.com/Open-KO/KnightOnline)

- **OpenKore** - [Ragnarok Online](https://en.wikipedia.org/wiki/Ragnarok_Online) 的自定义客户端与智能自动助手。 [[source]](https://github.com/OpenKore/openkore)

## 沙盒游戏

- **Minosoft** - 从零用 Kotlin（及 Java）编写的开源 Minecraft 客户端。 [[source]](https://github.com/bixilon/minosoft) [[source]](https://gitlab.bixilon.de/bixilon/minosoft)

## 射击游戏

- **[SDL Sopwith](https://fragglet.github.io/sdl-sopwith)** - 经典双翼机射击游戏 “Sopwith” 的移植版，可在现代电脑与操作系统上运行。 [[source]](https://github.com/fragglet/sdl-sopwith)

- **[Taisei Project](https://taisei-project.org)** - [Tōhō series](https://en.wikipedia.org/wiki/Touhou_Project) 的免费开源同人游戏，用 C 编写，使用 SDL3 与 OpenGL。 [[source]](https://github.com/taisei-project/taisei)

## 体育游戏

- **[Open Golf](https://mgerdes.github.io/minigolf.html)** - 用 C 编写的跨平台迷你高尔夫游戏。 [[source]](https://github.com/mgerdes/Open-Golf)

- **[Pooltool](https://pooltool.readthedocs.io)** - 强调真实物理的沙盒台球游戏。 [[source]](https://github.com/ekiefl/pooltool)

## 第三人称游戏

- **[Command & Conquer Renegade](https://en.wikipedia.org/wiki/Command_%26_Conquer:_Renegade)** - [[source]](https://github.com/electronicarts/CnC_Renegade)

- **CroftEngine** - [Tomb Raider 1](https://en.wikipedia.org/wiki/Tomb_Raider_(1996_video_game)) 的开源引擎重制。 [[source]](https://github.com/stohrendorf/CroftEngine)

- **[Lugaru: The Rabbit's Foot](http://www.wolfire.com/lugaru)** - 跨平台开源 3D 动作游戏。 [[source]](https://github.com/WolfireGames/lugaru)

- **[OpenLara](http://xproger.info/projects/OpenLara)** - 经典《古墓丽影》开源引擎。 [[source]](https://github.com/XProger/OpenLara)

- **[OpenRW](https://openrw.org)** - [Grand Theft Auto III](https://en.wikipedia.org/wiki/Grand_Theft_Auto_III) 的重实现。 [[source]](https://github.com/rwengine/openrw)

- **[Overgrowth](https://overgrowth.wolfire.com)** - Lugaru 的续作。 [[source]](https://github.com/WolfireGames/overgrowth)

- **RE3** - [GTA III](https://en.wikipedia.org/wiki/Grand_Theft_Auto_III) 与 [GTA VC](https://en.wikipedia.org/wiki/Grand_Theft_Auto:_Vice_City) 的完整逆向源码。 [[source]](https://github.com/VideogameSources/gta3-decomp-alt)

- **[Tomb Engine](https://tombengine.com)** - 用于自定义 [Tomb Raider](https://en.wikipedia.org/wiki/Tomb_Raider) 冒险游戏的开源引擎，覆盖 Core Design 时期（1-5 代）。 [[source]](https://github.com/TombEngine/TombEngine)

## 塔防游戏

- **[Server Survival](https://pshenok.github.io/server-survival)** - 教云架构的塔防游戏：建基础设施、扛住流量、学会扩容。 [[source]](https://github.com/pshenok/server-survival)

## 回合制策略游戏

- [Ancient Beast](https://ancientbeast.com) - 在线对战他人的回合制策略独立游戏项目。 [[source]](https://github.com/FreezingMoon/AncientBeast)

- **[Athena Crisis](https://athenacrisis.com)** - 现代复古风的回合制战术策略游戏。 [[source]](https://github.com/nkzw-tech/athena-crisis)

- **[C-evo](http://c-evo.org/)** - 面向 Windows 的免费帝国建造游戏。 [[source]](http://c-evo.org/files/files.php)

- **[fheroes2](https://ihhub.github.io/fheroes2)** - [Heroes of Might and Magic II](https://en.wikipedia.org/wiki/Heroes_of_Might_and_Magic_II) 游戏引擎的重制。 [[source]](https://github.com/ihhub/fheroes2)

- **[FreeCol](https://www.freecol.org/)** - 基于老游戏 [Colonization](https://en.wikipedia.org/wiki/Sid_Meier%27s_Colonization) 的回合制策略游戏，玩法类似 [Civilization](https://en.wikipedia.org/wiki/Civilization_(video_game))。 [[source]](https://github.com/FreeCol/freecol)

- **[Freeciv](http://www.freeciv.org/)** - 免费开源帝国建造策略游戏。 [[source]](https://github.com/freeciv/freeciv)

- **[FreeOrion](https://www.freeorion.org/index.php/Main_Page)** - 免费开源回合制太空帝国与银河征服（4X）游戏。 [[source]](https://github.com/freeorion/freeorion)

- **[Hnefatafl](https://hnefatafl.org/)** - 哥本哈根 Hnefatafl 棋游戏，有点像国际象棋。 [[source]](https://github.com/dcampbell24/hnefatafl)

- **[OpenPanzer](https://www.linuxconsulting.ro/openpanzer)** - [Panzer General II](https://en.wikipedia.org/wiki/Panzer_General_II) 游戏的 JavaScript/HTML5 重写。 [[source]](https://github.com/nicupavel/openpanzer)

- **[OpenXcom](https://openxcom.org/)** - [UFO: Enemy Unknown](https://en.wikipedia.org/wiki/UFO:_Enemy_Unknown) 与 [X-COM: Terror From the Deep](https://en.wikipedia.org/wiki/X-COM:_Terror_from_the_Deep) 两款流行游戏的开源克隆，原作由 [MicroPros](https://en.wikipedia.org/wiki/MicroProse) 出品。 [[source]](https://github.com/OpenXcom/OpenXcom)

- **[The Battle for Wesnoth](https://www.wesnoth.org/)** - 高奇幻题材的回合制策略游戏。 [[source]](https://github.com/wesnoth/wesnoth)

- **[Unciv](https://yairm210.itch.io/unciv)** - [Civilization V](https://en.wikipedia.org/wiki/Civilization_V) 的开源安卓/桌面重制版。 [[source]](https://github.com/yairm210/Unciv)

- **[VCMI Project](https://vcmi.eu)** - [Heroes of Might and Magic III](https://en.wikipedia.org/wiki/Heroes_of_Might_and_Magic_III) 的开源引擎。 [[source]](https://github.com/vcmi/vcmi)

## 其他清单

- **[Awesome Game Remakes](https://github.com/radek-sprta/awesome-game-remakes)**

- **[Awesome Open Source Games](https://github.com/michelpereira/awesome-open-source-games)**

- **[Games on GitHub](https://github.com/leereilly/games)**

- **[Libre Game Wiki](https://libregamewiki.org)**

- **[List of (interesting) FOSS game engine replacement projects](https://forum.openmw.org/viewtopic.php?p=57882)**

- **[List of Open Source Games](https://trilarion.github.io/opensourcegames)**

- **[Mac Source Ports](https://www.macsourceports.com)**

- **[Open Source Game Clones](https://osgameclones.com)**

- **[Wikipedia list open-source video games](https://en.wikipedia.org/wiki/List_of_open-source_video_games)**


---

## 参与贡献

欢迎补充条目、修正链接或改进翻译：

- 条目增删与格式要求见 [CONTRIBUTING.md](CONTRIBUTING.md)。
- 中文翻译问题欢迎直接提 Issue 或 PR。

## 致谢

感谢 [bobeff](https://github.com/bobeff) 维护英文原版清单，以及所有把这些游戏开源出来的开发者。
