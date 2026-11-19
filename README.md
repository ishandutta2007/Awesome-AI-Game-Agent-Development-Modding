# Awesome-AI-Game-Agent-Development-Modding

## Top AI Game Agent Development & Modding Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Autonomous Minecraft/Game AI Agents, Bot Frameworks (Mineflayer), Open Mod Loaders, High-Performance Game Servers & Modding Launchers*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Game Agent Development & Modding**. These tools enable developers, AI researchers, and modders to build embodied LLM game agents, automate multi-agent Minecraft bots, host and distribute game mods, run high-throughput server engines, and manage isolated modded game instances.



**Examples** include Modrinth, CurseForge, Overwolf, Mineflayer Cloud / Altera, Prism Launcher, ATLauncher, FabricMC, PaperMC, SpigotMC, and blendi-remade/agentcraft (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for AI game-playing agents (`AgentCraft`, `Voyager`, `Mindcraft`, `Mineflayer`, `Baritone`), open-source mod loaders and server engines (`FabricMC`, `NeoForge`, `PaperMC`, `Purpur`, `Velocity`), and open-source launchers (`Prism Launcher`, `ATLauncher`, `Modrinth App`) — ideal for AI agent researchers, game modders, server administrators, and creative developers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global AI in gaming and embodied virtual agent market is estimated at approximately $3.5B to $4.2B (projected to reach over $15B by 2030 at a ~25% CAGR). The sector remains **moderately fragmented**: core developer runtimes and NPC tools coexist across specialized generative AI agent startups and traditional game-modding distribution networks, while infrastructure and platform layers are contested by large engine providers and venture-backed platforms.

## SaaS/Hosted Platforms

| Platform | Valuation / Revenue Scale | Pricing (Starting Tier) | Free Tier Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Inworld AI](https://inworld.ai)** | **$500M+ valuation** (~$107M–$150M+ raised) | $25/month (Creator Tier) | **70 mins/mo free TTS**, 400 mins/mo free STT, 2,000 char TTS playground limit, 5 concurrent requests, up to 20 estimated concurrent sessions (On-Demand free plan). | Cloud AI character engine & SDK enabling contextual, memory-backed, voice-capable autonomous NPCs across Unity, Unreal Engine, and web runtimes. |
| **[Overwolf](https://overwolf.com)** | **$250M–$500M valuation** (~$150M raised, $300M+ paid out to creators) | $2.50/month (CurseForge ad-free subscription) | **Full access free forever** to overlay apps, mod management, and mod downloads supported by banner/video ads. | Commercial desktop overlay, game app framework, and mod distribution ecosystem powering the CurseForge app and game telemetry integrations. |
| **[CurseForge](https://curseforge.com)** | **Subsidiary of Overwolf** (Acquired for ~$10M–$15M; ecosystem processes $300M+ creator payouts) | $2.50/month (CurseForge Premium) | **Full mod browsing, auto-installation, and updates free forever** with ad-supported interface in app and web. | Commercial cloud mod repository and modpack distribution platform spanning Minecraft, World of Warcraft, and PC titles. |
| **[Apex Hosting](https://apexminecrafthosting.com)** | **$40M+ annual revenue** (Acquired by Nitrado / marbis GmbH under Flex Capital) | $9.99/month ($7.49 first month for 2 GB basic plan) | **7-day money-back guarantee** (no permanent free tier; paid hosting infrastructure). | Enterprise game server hosting provider offering one-click Fabric, PaperMC, Spigot, and modpack deployments for multi-agent bot environments. |
| **[Convai](https://convai.com)** | **~$6.5M annual revenue** (Venture-backed by Rainfall Ventures & Mountain View Capital) | $29/month ($22/mo billed annually for Indie Dev) | **100 interactions/month**, 60 mins Cloud Rendered Avatar Studio & Convai Sim, and 1 character session concurrency free forever. | Cloud conversational AI and spatial reasoning platform enabling NPCs to perceive 3D environments, navigate scenes, and interact with players. |
| **[Altera / Project Sid](https://altera.al)** | **$11.1M total funding** ($9M Seed led by Patron & First Spark Ventures; ~$40M estimated seed valuation) | Developer / Research API access (waitlist / pilot pricing) | **Free open-source research access** to papers/benchmarks and closed beta companion waitlist access. | Cloud autonomous AI agent civilization platform running multi-agent LLM simulations inside persistent Minecraft worlds with emergent economic behavior. |
| **[Modrinth](https://modrinth.com)** | **$1.2M seed funding** (Acquired by Spark Universe in 2026; Adrinth monetization) | $4.99/month (Modrinth+ ad-free / cosmetic tier; Modrinth server hosting starts at $5/mo) | **Unlimited free downloads, modpack creation, and mod hosting forever** (funded via Adrinth advertisements). | Modern, developer-friendly open platform for hosting, discovering, monetizing, and distributing Minecraft mods and modpacks via REST API. |
| **[exaroton](https://exaroton.com)** | **Bootstrapped / Profitable SME** (Operated by Aternos GmbH) | €0.01 per GB RAM/hour (~€7.20/mo for 1 GB continuous 24/7) | **5 free credits (€0.05 value)** on signup to test servers without a credit card; sister service **Aternos** provides 100% free ad-supported servers (dynamic 2–4 GB RAM, 4 GB storage cap, queue-based startup, auto-sleep). | Pay-per-minute cloud Minecraft server platform with fast sleep/wake automation and custom modpack/bot support. |
| **[MCreator / Pylo](https://mcreator.net)** | **Independent / Bootstrapped SME** (Pylo UG; community-funded) | €10/month (Patreon Supporter Tier for priority builds) | **100% free and open-source software (GPL v3)** with unlimited local mod and datapack generation; optional community cloud showcase. | Visual mod-creation and prototyping IDE enabling developers to build custom entities, behaviors, blocks, and dimensions without deep Java boilerplate. |

## Open-Source GitHub Projects



- **[blendi-remade/agentcraft](https://github.com)**  

  Open-source AI game agent and Minecraft automation framework designed for embodied LLM agents to perceive game state, execute actions, and collaborate inside sandboxed worlds.



- **[Mineflayer (`PrismarineJS/mineflayer`)](https://github.com)**  

  Foundational open-source (`MIT`) JavaScript/TypeScript API for creating programmable Minecraft bots with high-level pathfinding, inventory, combat, crafting, and block-interaction primitives.



- **[Voyager (`MineDojo/Voyager`)](https://github.com)**  

  Landmark open-source (`MIT`) LLM-powered embodied lifelong learning agent in Minecraft that continuously writes, refines, and stores executable Mineflayer JavaScript skills in a curriculum loop.



- **[Mindcraft (`kolbytn/mindcraft`)](https://github.com)**  

  Popular open-source (`MIT`) framework for crafting collaborative LLM-driven Minecraft agents powered by Mineflayer, supporting OpenAI, Anthropic, Gemini, and local Ollama models.



- **[Baritone (`cabaletta/baritone`)](https://github.com)**  

  Ultra-fast open-source (`LGPL-3.0`) automated Minecraft pathfinding and world-traversal bot engine written in Java, widely used as a deterministic navigation backend for game agents.



- **[Prism Launcher (`PrismLauncher/PrismLauncher`)](https://github.com)**  

  Flagship open-source (`GPL-3.0`) custom Minecraft launcher offering isolated instance management, direct Modrinth/CurseForge modpack downloads, and Java runtime management across Linux, Windows, and macOS.



- **[ATLauncher (`ATLauncher/ATLauncher`)](https://github.com)**  

  Established open-source (`GPL-3.0`) multi-platform Minecraft launcher integrating Modrinth, CurseForge, FTB, and Technic modpacks with automated server creation tools.



- **[Modrinth App / Theseus (`modrinth/code`)](https://github.com)**  

  Open-source (`GPL-3.0`) monorepo powering the Modrinth web frontend, Rust-based desktop launcher app, and high-speed Labrinth API backend.



- **[FabricMC (`FabricMC/fabric` & `fabric-loader`)](https://github.com)**  

  Lightweight, modular open-source (`Apache-2.0`) Minecraft modding toolchain and loader prized for rapid snapshot updates, Mixin bytecode injection, and client/server AI instrumentation.



- **[NeoForge (`neoforged/NeoForge`)](https://github.com)**  

  Community-driven open-source (`LGPL-2.1`) fork of Minecraft Forge providing a modernized, high-compatibility modding API and event bus for large-scale content mods.



- **[PaperMC (`PaperMC/Paper`)](https://github.com)**  

  High-performance open-source (`GPL-3.0`) Minecraft server software forked from Spigot featuring asynchronous chunk loading, anti-exploit fixes, and full Bukkit/Spigot/Paper plugin support.



- **[SpigotMC / CraftBukkit (`SpigotMC` / `Bukkit`)](https://spigotmc.org)**  

  Foundational open-source Minecraft server API and patch ecosystem powering thousands of server-side plugins, custom game rules, and AI agent bridge plugins.



- **[Purpur (`PurpurMC/Purpur`) & Folia (`PaperMC/Folia`)](https://github.com)**  

  Drop-in open-source (`MIT` / `GPL-3.0`) forks of PaperMC offering deep gameplay configurability (`Purpur`) and regionized multithreading (`Folia`) for massive multi-agent server simulations.



- **[Velocity (`PaperMC/Velocity`) & BungeeCord (`SpigotMC/BungeeCord`)](https://github.com)**  

  Modern open-source (`GPL-3.0` / `BSD-3-Clause`) high-throughput Minecraft proxy servers for routing players and autonomous agents across distributed server clusters.



- **[MineDojo (`MineDojo/MineDojo`)](https://github.com)**  

  Open-source (`MIT`) embodied AI research suite built on Minecraft featuring thousands of programmatic tasks, multimodal knowledge bases, and `MineCLIP` reward models.



- **[Project Malmo (`microsoft/malmo`)](https://github.com)**  

  Pioneering open-source (`MIT`) AI experimentation and reinforcement-learning platform from Microsoft Research built directly on top of Minecraft.



### Additional Strong Open-Source Options



- **[CraftGPT / Ollama-Minecraft Bridges](https://github.com)** and **[mineflayer-pathfinder (`PrismarineJS/mineflayer-pathfinder`)](https://github.com-pathfinder)** for modular A* pathfinding, combat (`mineflayer-pvp`), and local LLM integration in Node.js bots.

- **[Packwiz (`packwiz/packwiz`)](https://github.com)** and **[Ferium (`gorilla-devs/ferium`)](https://github.com)** for CLI-based declarative modpack version control and automated Modrinth/CurseForge mod updates.

- **[MCProtocolLib (`GeyserMC/MCProtocolLib`)](https://github.com)** and **[Azalea (`azalea-rs/azalea`)](https://github.com)** for low-level Java and high-concurrency Rust headless Minecraft client/bot frameworks.

- **[Godot Engine (`godotengine/godot`)](https://github.com)** and **[Bevy Engine (`bevyengine/bevy`)](https://github.com)** with **[godot-mcp](https://github.com)** for AI-driven modding and scene automation in open-source 2D/3D game engines.

- **[Gymnasium (`Farama-Foundation/Gymnasium`)](https://github.com)** and **[PettingZoo (`Farama-Foundation/PettingZoo`)](https://github.com)** for standardized single-agent and multi-agent reinforcement learning game environments.



**Frameworks for building custom systems**: Combine **blendi-remade/agentcraft** or **Mindcraft + Mineflayer** (agent control) with **PaperMC / Folia** (high-throughput server runtime), **FabricMC** (client/server modding), **Prism Launcher + Packwiz** (reproducible modpacks), and **Ollama** (local LLM inference) for end-to-end open-source AI game agent and modding ecosystems.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.
