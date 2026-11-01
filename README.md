# NeuroSignal: Signal Recovery

Download the playable Windows build from [Releases](https://github.com/VM934/NeuroSignal-Play/releases). Choose the game ZIP under Assets; the automatic source archives on GitHub do not contain the game.

# NeuroSignal: Signal Recovery — Windows playtest

**Version 0.3.0-playtest.1.** A playable first-person educational prototype combining cybersecurity and neuroscience. Defend a research archive through three drone attacks, then investigate evidence between encounters. The investigations teach access-control reasoning, artifacts in neural recordings, and experimental controls. Built with AI assistance, with prototype visuals and further testing planned.

## Download and play

1. Download the [playable Windows ZIP](https://github.com/VM934/NeuroSignal-Play/releases/download/v0.3.0-playtest.1/NeuroSignal-SignalRecovery-Windows-20261031-140655.zip) (approximately 414 MB). Its filename is **NeuroSignal-SignalRecovery-Windows-20261031-140655.zip**. GitHub's automatic **Source code** archives do not contain the playable game.
2. Extract the complete ZIP to a local folder. Keep its Windows folder and all supporting files together.
3. Double-click **Play NeuroSignal.cmd** and choose **Deploy solo**. Unreal Editor and Visual Studio are not required to play.
4. Read **READ ME FIRST.txt** for requirements and the included prerequisite installers if a required runtime is missing.

This is a native Windows 64-bit download requiring compatible graphics hardware. It does not run in a browser, on phones, or natively on macOS.

## Controls and objective

Move with WASD, look with the mouse, fire with left click, aim with right click, and reload with R. Shift sprints, Space jumps, C/Ctrl crouches, E interacts or revives, and Escape opens Options. Select evidence answers with 1/2/3 or the mouse. Optional field notes appear after resolving an investigation. Read the explanation, then mark ready to continue. Survive all three waves and resolve all three investigations to complete the mission.

## Co-op

Up to three players can share a mission. Every player needs the same version. One selects **Host co-op**; the others select **Join co-op** and enter the host's reachable IPv4 address (default port 7777). The host waits for the squad to connect before deploying. This version uses direct networking; matchmaking, relay/NAT traversal and host migration are not implemented. Solo play is available immediately.

## Verification and current limits

The exact packaged executable completed rendered solo routes at 1920x1080 and 1280x720 and a host/two-client co-op test using three processes on one Windows laptop. Separate physical PCs, Internet co-op, physical controllers, stable frame-rate targets and learning outcomes have not been verified. These checks do not establish compatibility with every PC. The release is a playtest, with prototype geometry and animation.

**Known exit-delay observation:** one 1080p test completed the mission but took about 153 seconds from requesting exit to logging that it was exiting, exceeding the test's overall deadline. A repeat using the same executable exited normally in about 1.5 seconds. Closing-time behavior still needs broader testing; this observation is not evidence of a mission crash or a confirmed graphics-driver cause.

The educational examples are synthetic. Optional explanations support learning; this is not a clinical simulator. Unreal Engine and Epic template assets are used alongside original game code and educational content. The public package contains the playable build; editable project source is maintained separately.

**ZIP SHA-256:** `45F3528825985B2A3FA6642D40E1297640D005FEC93D21668B1C8795C9B4E518`

The attached **cover.png** is an actual screenshot of this packaged version. **checksums.json** records the file hashes and verification scope.
