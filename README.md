# NeuroSignal: Signal Recovery

Protect a fictional neuroscience research archive in an original first-person game for **one to three Windows players**. Clear three drone waves and check three records to win. The mission ends in defeat if the archive reaches 0% or the whole squad goes down.

## Download and play

1. Open the [latest Windows release](https://github.com/VM934/NeuroSignal-Play/releases/latest). Under Assets, choose **NeuroSignal-SignalRecovery-Windows-20261107-024722.zip** for **0.6.0-playtest.1**.
2. Extract the entire ZIP, then double-click **Play NeuroSignal.cmd**.
3. Choose **Deploy solo**, or use **Host co-op** and **Join a squadmate**.

Playing requires no editor, compiler, account or AI subscription. The launchers select **1080p, 100% 3D render scale, FXAA, GI quality 1 and a 30 FPS cap**. The ZIP includes controls, prerequisites, a source-linked learning guide and file hashes.

## Play the mission

- **Fight for the archive.** When **DRONE LOCK** appears, break line of sight with solid cover and stay there until the warning clears. You can also move out of range or destroy the charging drone. Each attack spends about 0.8 seconds winding up against its chosen target. **ARCHIVE TARGETED** signals a separate shot aimed at the objective. **HIT** and **DRONE NEUTRALIZED** confirm your shots.
- **Decide what the records support.** Use the central console after each wave. Block an app's request to edit every record when its job needs read-only access to one. Then investigate a faulty neural recording and check whether a matched-carrier experiment supports a separate compound effect or clinical benefit.
- **Read the result at your pace.** Wrong answers give a hint and retry without damage. There is no answer timer. After a correct choice, Tab or controller View opens field notes. Left/Right or D-pad changes pages. Enter or controller A marks your own review ready. The mission advances when everyone is ready.

Use **WASD** and mouse to move and look, **left/right mouse** to fire and aim, **R** to reload and **E** to use the console or revive a nearby teammate. **Shift** sprints, **Space** jumps, and **C/Ctrl** crouches or slides while sprinting on the ground. **Esc** opens the menu. Xbox-style controller controls are in the ZIP.

## Connect the mission to everyday decisions

The Cybersecurity pages cover unexpected college device-code requests, app permissions, AI tools reading untrusted documents, supported software and testing an assignment backup. Science pages explore a suspicious clinic message, a sleep-app claim and a memory advertisement. Dated examples distinguish device security guidance, one participant's investigational speech brain-computer interface, and a medicine approved for a specific disease.

The source snapshot is **November 4, 2026**. The mission's study and decisions are fictional. The included **LEARNING-GUIDE-2026.md** links the sources. Discussion questions are unscored.

## Play with friends or build on the project

Everyone needs the **same complete 0.6.0-playtest.1 release**. One player hosts, up to two join the host's reachable IPv4 address, then the host deploys. The default port is **UDP 7777**. This is direct-IP co-op for a reachable network. Separate-home internet play remains unverified.

The private team release pairs the same tested native executable with the editable project. Sign in, accept your invitation and work on a personal branch. C++ development uses **Unreal Engine 5.8.3** and Windows C++ tools. [Team repository](https://github.com/VM934/NeuroSignal) · [Team releases](https://github.com/VM934/NeuroSignal/releases) · [Friends' quick start](https://github.com/VM934/NeuroSignal/blob/main/Distribution/Collaboration/FRIENDS_QUICK_START.md)

## Exact-build verification

Two automated solo runs from the extracted player ZIP exited normally. All **36 captures** at 720p and 1080p were reviewed individually, including the live operator warning, hit and defeat feedback, all records and notes, and victory. The archive warning awaits a dedicated image. This is an automated playtest with prototype art. Human playability and learning outcomes require separate evaluation.

Six automated solo missions on the target laptop averaged **29.996 FPS** across 1,962 combat frames and 65.408 seconds of aggregate combat. Combat p99 was **34.548 ms** and the slowest combat frame was **41.618 ms**. No combat or review frame exceeded 50 ms. The run met its frame pacing, startup and shutdown goals and exited normally.

All roles cleared the mission and acknowledged three reviews in a three-player loopback run and a two-player loopback run with **100 ms of outgoing delay per endpoint**. The game reported that the delay setting was active, and all five processes exited normally. Both runs passed **125 input checks, 14 evidence checks and seven drone-lock checks**.

In a separate headless check, **0.6.0-playtest.1** rejected a **0.5.0-playtest.1** host, logged the same-release instruction, returned to standby and exited normally. That check covers network rejection and process recovery. The graphical recovery menu requires a separate check.