# NeuroSignal: Signal Recovery

**Windows playtest 0.3.1-playtest.1.** An original first-person educational prototype combining cybersecurity and neuroscience. Defend a research archive through three drone attacks, then investigate access-control flaws, unreliable neural recordings and experimental controls. Built with AI assistance, with prototype geometry and animation.

## Download and play

1. Download the [playable Windows ZIP](https://github.com/VM934/NeuroSignal-Play/releases/download/v0.3.1-playtest.1/NeuroSignal-SignalRecovery-Windows-20261101-213732.zip) (approximately 414 MB). GitHub's automatic **Source code** archives do not contain the game.
2. Extract the complete ZIP to a local folder. Keep its Windows folder and supporting files together.
3. On the target ASUS laptop, double-click **Play NeuroSignal - 30 FPS.cmd** for the measured pacing profile. **Play NeuroSignal.cmd** offers a 60 FPS cap, which current tests did not sustain on that laptop.
4. Choose **Deploy solo**. Unreal Editor and Visual Studio are not required to play. See **READ ME FIRST.txt** for requirements and included prerequisite installers.

This is a native Windows 64-bit download requiring compatible graphics hardware. It does not run in a browser, on phones, or natively on macOS.

## Controls and objective

WASD moves, mouse looks, left click fires, right click aims, R reloads, Shift sprints, Space jumps, C/Ctrl crouches, E interacts or revives, and Escape opens Options. Select evidence answers with 1/2/3 or the mouse. Read each investigation's explanation, then mark ready to continue. Optional field notes provide more context. Survive all three waves and resolve all three investigations to win.

## Co-op

Up to three players can share a mission. Everyone needs this same release. One selects **Host co-op**; others select **Join a squadmate** and enter the host's reachable IPv4 address (default port 7777). The host waits for the squad before deploying. Direct networking requires a network path to the host; matchmaking, relay/NAT traversal and host migration are not implemented. Solo is available immediately. Separate PCs and Internet co-op remain unverified.

## What changed and what was checked

This release fixes repeated menu activation, Ctrl+A address editing, connection-error recovery, redundant reload requests, paused jump/crouch releases and revive eligibility guidance. It improves combat hints and the investigation explanations.

The exact packaged executable passed 62 input checks, 11 evidence checks, a three-process loopback mission with normal exits, full-squad rejection/rejoin and incompatible-build recovery. All 24 captured menu/combat/investigation/outcome screens at 720p and 1080p were inspected. These are bounded implementation and presentation checks; physical controllers, learner comprehension, long sessions and separate-PC networking still need testing. The new out-of-ammunition and revive prompt appearance was not captured in those ordinary-combat screenshots; their underlying behavior has contract checks.

At 1080p with the original graphics, the optional 30 FPS profile completed six automated missions, averaging **30.00 FPS** across **65.39 seconds of aggregate combat**, with p99 frame time **34.36 ms** and no combat frames over 50 ms. It passed its declared 30 FPS/startup/shutdown goals. Current 60 FPS runs measured approximately **40.93–45.50 FPS** and failed their pacing goal. Laptop operating-state variation remains unresolved; these short runs do not establish long-term thermal stability, multiplayer FPS or performance on other PCs. No persistent graphics or system power changes were adopted.

The lessons use synthetic educational examples; this is not a clinical simulator. AI assistants helped review original source, runtime reports, screenshots and an original Boolean-rule lab. The game runs locally without an online AI-model dependency. No third-party game reverse engineering was performed. Commercial shooter feature parity and competition eligibility are not established.

Unreal Engine and Epic template assets are used alongside original game code and educational content. This public repository distributes the playable build and player information. Editable project source and contributor context are maintained separately in the team's private repository.

**ZIP SHA-256:** `8A1FDFC544E8726617615D49BE98068E05DB04DD94C5F14BC3D4032B5660F87C`

[Release notes and checksum metadata](https://github.com/VM934/NeuroSignal-Play/releases/tag/v0.3.1-playtest.1) accompany the game. The release's **cover.png** is an actual screenshot of this packaged executable.
