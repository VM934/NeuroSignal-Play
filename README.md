# NeuroSignal: Signal Recovery

Defend a fictional drug-study archive, then work out what its recovered evidence actually supports. NeuroSignal is an original first-person mission combining cybersecurity, neuroscience and pharmacology. Play solo or with up to two friends using direct-IP Windows co-op.

## Download and play

Open the [latest Windows playtest](https://github.com/VM934/NeuroSignal-Play/releases/latest), currently **0.4.1-playtest.1**, and download **NeuroSignal-SignalRecovery-Windows-20261103-190508.zip** under Assets. Extract the entire ZIP, then double-click **Play NeuroSignal.cmd**. Keep every file together. Playing needs no GitHub login, Unreal Editor, compiler, AI model or AI subscription. GitHub's automatic source archives are not the playable game.

The ZIP includes controls, Microsoft runtime installers, a source-linked learning guide, credits and file hashes. All co-op players must use the same complete release.

## Larger field notes in 0.4.1

Science and Cybersecurity now have separate full-width pages with larger body text, a visible page counter and keyboard, controller and mouse navigation. After solving an investigation, press Tab / controller View to open Science; use Left/Right or D-pad Left/Right to turn pages. Discussion stays visible on both pages. Enter / controller A marks only your own review ready. Paging preserves answers, evidence progress and readiness.

The three fictional investigations connect record integrity, neural-recording quality and matched carrier controls to the evidence needed for a pharmacological claim. They distinguish agonists and antagonists, binding and functional action, target-site exposure and clinical benefit. Research security topics include phishing-resistant authentication, least privilege, protected audit records, recovery, neural-data privacy and treating untrusted report content as data. Sources retain their November 2, 2026 review date. All compounds and measurements are fictional; no real doses or treatment recommendations are supplied.

## Measured profile and checks

Both launchers select **1920x1080, 100% 3D render scale, FXAA, GI quality 1 and a 30 FPS cap**. On the target ASUS UX581GV (i9-9980HK, RTX 2060 6 GB, 32 GB RAM), this executable completed six automated solo missions in approximately five minutes. Across 65.401 seconds of aggregate combat, it averaged **30.000 FPS**, p95 **33.944 ms**, p99 **34.293 ms**, maximum **34.865 ms**, with **zero of 1,962 combat frames over 50 ms**. Startup, shutdown and all declared pacing goals passed. This is a short solo regression; the previous release's longer benchmark does not validate this executable.

The current build passed **106 distinct input checks and 14 evidence checks**, a host/two-client loopback mission with both remote slide fixtures, and actual extracted-ZIP solo routes at 720p and 1080p. Every role exercised both note pages of every investigation. All **30 captured screens** were individually inspected, with no blocking clipping or overlap. Game processes exited normally. See the release's **FINAL-VERIFICATION.json** and screenshots for exact scope.

The player ZIP is **413,927,286 bytes**, SHA-256:

```text
18DE71A3A8BAFDA7D95DA299D58DCF6FB82AC1AF1CEB44DA338B9B8816DF7118
```

All **56 payload files plus FILE-HASHES.csv** were verified in the actual ZIP and extracted copy. A public download without authentication returned HTTP 200 and exactly the same bytes/hash. All eight initially uploaded release assets also matched GitHub's server SHA-256 digests. Native executable SHA-256: `03E4281334FFA48186C78DF50533B6774B3350B7DBDD84E70436B8983D489664`.

## Play together

One player selects **Host co-op** and waits for the squad counter; friends select **Join a squadmate** and enter the host's reachable IPv4 address, normally port 7777. The host deploys after everyone joins. `127.0.0.1` reaches only the same computer. Use this same release on every PC.

Direct-IP co-op has no matchmaking, relay, automatic NAT traversal or host migration. Sharing the ZIP does not connect separate homes' networks. Start with solo and same-LAN tests; separate-PC internet sessions remain unverified. Launchers do not change firewall or router settings.

## Keep building with the team

Saket and Shiam can play the public download immediately. Editable C++/Unreal assets, the project vision, [friends’ quick start](https://github.com/VM934/NeuroSignal/blob/main/Distribution/Collaboration/FRIENDS_QUICK_START.md), setup instructions, feedback templates and complete team bundles are in the private [team repository](https://github.com/VM934/NeuroSignal). Private access requires signing in and accepting the repository invitation. The quick start explains where to change gameplay, teaching content and interface code.

Playing needs no engine. Editing C++ needs Unreal Engine 5.8.3 and the Windows C++ toolchain, followed by rebuilding and testing. Keep the tested ZIP and main branch as a baseline; make a small personal branch and propose changes through a pull request. Coordinate before editing the same binary asset. Private team bundles are available from the [team releases](https://github.com/VM934/NeuroSignal/releases); check their version rather than assuming an older bundle contains the latest source.

The [0.4.0 release](https://github.com/VM934/NeuroSignal-Play/releases/tag/v0.4.0-playtest.1) remains available for rollback. Its manual launcher, incompatible-build recovery, static REA analysis and longer benchmark are historical checks for that executable.

This is a prototype vertical slice with original code and documented Epic assets. Automated ideal aim and correct answers do not establish enjoyment, human difficulty or learning. Secondary text remains small at 720p. Physical-controller comfort, broad accessibility, fresh Windows PCs, longer sessions and subject-matter/learner validation remain future work. The existing Handshake Showcase uses the durable Latest release URL, which now resolves to 0.4.1. Its retained description and combat cover were recorded for 0.4.0. Showcase publication does not confirm competition eligibility or late-entry acceptance; this native Windows build does not implement the identified mission's browser/room-code format.
