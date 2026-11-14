# NeuroSignal: Signal Recovery

**[Download the original 3D Windows game](https://github.com/VM934/NeuroSignal-Play/releases/latest).** Extract the entire player ZIP, open **Play NeuroSignal.cmd**, and choose **Deploy solo**. Friends and reviewers use the same player download. No editor, compiler, AI model, subscription or GitHub account is needed to play.

An original first-person cybersecurity and neuroscience co-op mission for one to three players. Protect a fictional research archive through six encounters, recover a trustworthy reference record and investigate what the evidence supports. This is a development playtest with prototype art and animation.

## Current player release: 0.9.5-playtest.1

[Versioned release](https://github.com/VM934/NeuroSignal-Play/releases/tag/v0.9.5-playtest.1) · [Player ZIP](https://github.com/VM934/NeuroSignal-Play/releases/download/v0.9.5-playtest.1/NeuroSignal-SignalRecovery-Windows-0.9.5-playtest.1.zip) · [Final verification](https://github.com/VM934/NeuroSignal-Play/releases/download/v0.9.5-playtest.1/FINAL-VERIFICATION.json) · [Longer performance check](https://github.com/VM934/NeuroSignal-Play/releases/download/v0.9.5-playtest.1/SUSTAINED-PERFORMANCE.json)

The default is **1280×720 fullscreen**, 100% scene scale, FXAA, GI quality 1 and a **90 FPS cap**. Alt+Enter toggles fullscreen; `Play NeuroSignal.cmd /windowed` starts in a window. A separate 30 FPS launcher is included. Keep every extracted file together. The ZIP includes the learning guide, controls, Microsoft runtime prerequisites, credits and file hashes.

This update adds tap-slide continuation, a collision-safe co-op crouch-to-jump fix, clearer slide and recovery instructions, fitted cache-sign backings and more practical feedback on medicine ingredients, overdose emergency response and unexpected sign-in approvals.

## Fight, recover and investigate

Sprint, tap crouch to slide through the Low Route, reload behind cover and use violet Transfer Gates to switch flanks. Jumping or aiming ends a slide. An accepted slide continues after releasing crouch, then stands; holding crouch finishes crouched. Two confirmed hits during a surviving drone's charge interrupt its shot. Hit, defeat, threat and reload feedback distinguish the results of your actions.

Each operation pairs an eastern breach with a western counterattack. In the final operation, inspect three caches: a record can be intact yet lack the required carrier, or match the carrier but fail integrity. Recover the record that passes both checks, deliver a read-only copy and defend 30 seconds of verification against two reinforcement batches. Clear the surviving drones, then review the comparison at the central console.

The three investigations ask what access an app needs, whether an unreliable neural recording establishes a receptor mechanism, and whether a matched-carrier comparison supports a separate compound effect or clinical benefit. Wrong choices give explanatory feedback and allow retry. Everyone marks ready separately after reviewing the result.

## Put the lessons to use

After solving a record, press **F / controller X** or select **Try an Everyday Decision**. Open Field Notes with **Tab / View**. Six optional practice decisions cover:

- Sedating medicines and duplicate active ingredients.
- Caffeine, too little sleep and choosing a rested driver.
- Emergency help after naloxone in a possible mixed-drug overdose.
- Responding after approving an unexpected device sign-in code.
- Verifying a possible family voice-cloning scam through another channel.
- Testing a backup restore without replacing the original files.

Correct Science answers lead to the paired Cybersecurity decision, then back to record review. Progress counts each correct decision once and resets for a new mission; it records choices, not demonstrated learning retention. The study, compound and data are fictional. The included **LEARNING-GUIDE-2026.md** links primary sources and labels dated examples, including a CISA vulnerability snapshot rather than a live feed. The game is general education, not personal medical advice.

## Play with friends and build on it

Everyone in a squad needs **0.9.5-playtest.1 / network protocol 13**. One player hosts; up to two friends join a reachable IPv4 address, normally on UDP 7777. There is no matchmaking or Internet relay. Separate-PC and Internet connectivity require their own tests; loopback tests on one laptop do not establish them.

Invited collaborators can use the [private editable Unreal project](https://github.com/VM934/NeuroSignal) and [matching team release](https://github.com/VM934/NeuroSignal/releases/tag/v0.9.5-playtest.1). The source handoff contains the same player executable, editable source/assets, build scripts, learning context and feedback forms. [Friends' quick start](https://github.com/VM934/NeuroSignal/blob/main/Distribution/Collaboration/FRIENDS_QUICK_START.md) · [Development setup](https://github.com/VM934/NeuroSignal/blob/main/DEVELOPING.md).

## What was verified

The final executable `B7E6C26E9396529EE291CF6C3EA5970E6CF0AFBC317D89A1848AEDA14ED2FD66` was built from source commit `b1e9be7478f19ba8b9b7db49db212e538961209a`. The final ZIP was independently extracted and checked file by file. That extraction completed a rendered solo mission, all six encounters, reference recovery, all three investigations and all six practice decisions, with a natural exit. All 32 required screenshots were individually reviewed. Normal and 100 ms delayed three-process co-op routes also ran from the extracted final ZIP; all peers completed their missions and exited normally. The old-build rejection check verified protocol-11 rejection and protocol-13 solo standby; graphical recovery was not checked.

On November 14, 2026, the ASUS UX581GV test laptop (i9-9980HK, RTX 2060 6 GB, 32 GB RAM) recorded these separate workloads at the default fullscreen profile:

| Workload | Accepted combat | Average | p95 / p99 | Maximum | Frames over 50 ms |
| --- | --- | --- | --- | --- | --- |
| Ordinary controls, nine mostly stationary first-wave attempts | 121.53 s / 10,917 frames | 89.83 FPS | 11.118 / 11.294 ms | 27.301 ms | 0 |
| Automated route, three completed missions | 150.54 s / 13,542 frames | 89.95 FPS | 11.618 / 11.978 ms | 23.594 ms | 0 |

The ordinary CSV excludes its first 15 seconds, menus/outcomes and padded transitions; the selected capture began after startup and recorded zero horizontal speed. The longer route used automated ideal aim, a ten-second warmup and phase exclusions. Its total route distance was 198.73 metres, which does not establish continuous moving-combat duration. All accepted combat frames were focused under the engine's policy, with no observed focus transitions. Startup was 5.61 seconds; shutdown was 2.64 seconds. No build, compression or profiler capture ran during that longer measurement.

These results apply to the recorded workloads on this laptop. They do not establish human control comfort, physical-controller use, multiplayer frame pacing, long-term thermal stability, other hardware performance or learning retention. A frame cap alone is not a result. Small secondary labels at 720p remain a useful accessibility improvement.

Player ZIP: **414,820,365 bytes**. SHA-256: **0306615BDF95F8D65E09F44C488688E6D6B09BE67938212499415067A0C0D21C**. Use the adjacent release checksum to verify it.

## Competition page and earlier browser work

The [existing Handshake project](https://app.joinhandshake.com/ai-showcase/projects/3706502) is being prepared for the account holder's final review and Save with this 3D release. A saved project page does not itself confirm which revision judges will review or whether a Windows download satisfies the mission's browser-delivery requirements; organizer confirmation is requested separately.

[Breach Run in a browser](https://neurosignal-breach-run.vin-mami10.chatgpt.site/) is a historical separate 2D implementation. Its source and measurements do not identify or validate this original Unreal 3D Windows game.

