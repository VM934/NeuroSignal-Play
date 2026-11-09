# NeuroSignal: Signal Recovery

An original first-person game for **one to three Windows players**. Defend a fictional neuroscience research archive, clear three drone waves, and decide what the recovered records support.

## Download and play

1. Open the [latest Windows release](https://github.com/VM934/NeuroSignal-Play/releases/latest). Under Assets, download **NeuroSignal-SignalRecovery-Windows-20261108-213226.zip** for **0.9.2-playtest.1**.
2. Extract the entire ZIP and double-click **Play NeuroSignal.cmd**.
3. Choose **Deploy solo**, or select **Host co-op** or **Join a squadmate**.

The ZIP includes controls, prerequisites, a source-linked learning guide, and file hashes. The launchers select **1080p, 100% render scale, FXAA, GI quality 1, and a 30 FPS cap**. You can play without an editor, a compiler, or a GitHub account.

## Learn the arena and protect the archive

- **Try a Transfer Gate between waves.** After the first drone wave, look beneath **NEXT** for the shortcut hint before using the console. The bright violet gates have eye-level destination plaques marked **TO NORTH FLANK** or **TO SOUTH FLANK**. Approach either gate standing, face the frame, and press **E / Y** when the prompt appears. You keep your heading. A blocked exit keeps you in place.
- **Use the route under pressure.** Try a gate to reach a charging drone from a different angle, or sprint-slide through the marked north **LOW ROUTE**. **ARCHIVE TARGETED** points toward the incoming threat. Land two hits during a charge to interrupt the shot or move behind solid cover when **DRONE LOCK** is on you.
- **Review the record.** After each wave, use the central console to decide what access an app needs, whether a faulty brain recording supports a claim, and whether a fair comparison supports a fictional drug claim. The first correct decision lets the archive team restore up to eight integrity points from a protected backup. The review shows what you carry into the next wave. Read the explanation and choose when you're ready.

## Take the decisions into everyday life

After solving a record, press **Tab / View** to open Field Notes, choose Science or Cybersecurity, and press **F / X** to try a Field Drill. Read the feedback and retry at your pace.

**Science** asks whether to trust a signed file from a sensor that failed calibration, whether to drive after too little sleep and an energy drink, and what to do when someone wakes after naloxone in a suspected mixed-drug overdose. **Cybersecurity** practices responding to an approved suspicious device code, keeping an AI-read document from authorizing an upload, and testing a backup restore without risking your working files. **LEARNING-GUIDE-2026.md** explains the reasoning and links the sources.

## Play with friends or edit the game

Everyone needs the **same complete 0.9.2-playtest.1 release**, network protocol **10**. One player hosts. Up to two friends join the host's reachable IPv4 address, normally on **UDP 7777**. The co-op tests use loopback on one laptop. Playing across separate home networks requires a route to the host.

The private team release pairs the same executable with the editable project. Sign in with your invited account, start a personal branch, and use Unreal Engine **5.8.3** and Windows C++ tools to build changes. [Team releases](https://github.com/VM934/NeuroSignal/releases) · [Friends' quick start](https://github.com/VM934/NeuroSignal/blob/main/Distribution/Collaboration/FRIENDS_QUICK_START.md)

## Exact-build verification

On the target ASUS laptop, **6** automated 1080p solo missions averaged **30.00 FPS** across **65.40 seconds** of sampled combat. The 99th-percentile combat frame took **33.86 ms**. The rendered runs at 720p and 1080p provided **58** captures for direct review, including the backup recovery result. Host and remote gate traversal were checked in local co-op. The previous 0.9.1 build was used for a headless mismatch check.

The assets include **FINAL-VERIFICATION.json**, the checksum, and gameplay screenshots. Player ZIP SHA-256 `91D38EFE9EF4B240D7A9B99B6E2543CB2BC5C8EAB8F2D257318D410B5618DC9E`. Separate-computer networking, physical controller comfort, and learning outcomes remain to be tested with players.
