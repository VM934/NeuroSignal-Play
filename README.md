# NeuroSignal: Signal Recovery

Defend a fictional drug-study archive, then work out what its recovered evidence actually supports. NeuroSignal is an original first-person mission combining cybersecurity, neuroscience and pharmacology. Play solo or with up to two friends using direct-IP Windows co-op.

## Download and play

Open the [0.4.0-playtest.1 Windows release](https://github.com/VM934/NeuroSignal-Play/releases/tag/v0.4.0-playtest.1), then download **NeuroSignal-SignalRecovery-Windows-20261103-092625.zip** under Assets. GitHub's automatic source archives do not contain the game. Extract the entire ZIP and double-click **Play NeuroSignal.cmd**. Keep every file together. Unreal Editor, Visual Studio and an AI subscription are not required to play. The ZIP includes player instructions, Microsoft runtime installers, a learning guide, credits and file hashes.

Both launchers use **1920x1080 output, 100% 3D render scale, FXAA, GI quality 1 and a 30 FPS cap**. On the target ASUS UX581GV laptop (i9-9980HK, RTX 2060 6 GB, 32 GB RAM), the current executable completed 17 automated solo missions over approximately 14 minutes. Across 190.832 seconds of aggregate combat, it averaged **29.990 FPS**, with p95 **34.162 ms**, p99 **34.785 ms** and maximum **64.716 ms**. Two of 5,723 combat frames exceeded 50 ms (0.035%). All declared pacing/startup/shutdown goals passed. Current 60 FPS comparisons failed; other PCs and multiplayer pacing require their own testing.

## What changed in 0.4.0

- The three investigations now follow a fictional neuropharmacology study: secure a record, question a receptor claim from a faulty neural recording and use the right carrier control.
- Larger science/security field notes explain agonists and antagonists, binding versus functional action, target-site exposure, research integrity, privacy, protected audit history and recovery.
- An original sprint-to-crouch slide adds a movement option. Crouch while sprinting on the ground; release crouch to end it. Jumping from a settled crouch now checks overhead clearance and uncrouches before jumping.
- The source-linked learning guide includes everyday definitions and transfer questions. Source review is dated November 2, 2026. All compounds and measurements are fictional; there are no real doses or treatment recommendations.

The released native executable passed **85 distinct input checks and 14 evidence checks**, a host/two-client loopback mission including both remote-client slide checks, 24 selected-profile captured screens at 720p/1080p, and readable incompatible-build recovery. The automated mission and rendered routes exited normally; the compatibility fixture's older idle host was intentionally stopped. The 720p secondary labels remain small, and empty-ammunition/downed-revive appearance was not captured. Still images do not establish motion quality or broad accessibility.

The ZIP is **413,919,416 bytes**. Its SHA-256 is:

```text
477271C45607F247AD1BDD25AAA14172AD1460D576D34129D2C8E37822DC7DB4
```

All **56 payload files**, plus their `FILE-HASHES.csv` manifest, were verified in the final ZIP and extracted copy. The actual extracted launcher reached the versioned 0.4.0 menu without a blocking prompt, with log readback confirming the selected cap, render scale, FXAA and GI settings. It exited normally with code 0 through the displayed Exit to desktop action, with no harness stop. The checked native executable SHA-256 is `4D286CFE2C0C032F5DAD09E182DE8B3DD7CA4C679EB5E1DD0BB5DA5D4C1A911F`. REA 6.8.0 statically inspected this exact executable's PE imports with complete coverage and no parser issues. The inspection concerns our own executable; it does not recover another game's mechanics, establish resolved runtime dependencies or explain frame-rate variation.

## Play together or contribute later

All players need the same complete build. One player selects **Host co-op** and waits for the squad counter; friends select **Join a squadmate** and enter the host's reachable IPv4 address, normally with port 7777. The host then deploys. `127.0.0.1` reaches only the same computer. Version 0.4.0 uses network protocol 3 and cannot join a 0.3.1 session.

Co-op uses direct IP with no matchmaking, relay, NAT traversal or host migration. Sending the ZIP does not make separate homes' networks reachable. Separate-PC and real internet sessions remain unverified. The launchers do not change firewall or router settings.

This public repository distributes runnable playtests. Editable Unreal source and complete team bundles are in the private [team repository](https://github.com/VM934/NeuroSignal) and require an accepted invitation. Development can continue while friends are busy; they can play and contribute later. The [previous 0.3.1 release](https://github.com/VM934/NeuroSignal-Play/releases/tag/v0.3.1-playtest.1) remains available for rollback.

This is a prototype vertical slice with original code and documented Epic assets. Automated ideal aim and correct answers do not establish enjoyment, human difficulty or learning. Physical-controller comfort, broad accessibility, fresh Windows installations, longer sessions and subject-matter/learner validation remain future work. The existing Handshake Showcase page now links to this release, with revised description and an actual current-native combat cover confirmed after a reload. That update does not confirm competition eligibility or late-entry acceptance; this native Windows build does not implement the identified mission's browser and room-code format.
