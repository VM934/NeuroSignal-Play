# NeuroSignal: Signal Recovery

Protect a fictional research archive, stop hostile drones and check what its records actually support. This original Windows first-person playtest combines action, cybersecurity, neuroscience and pharmacology for **one to three players**.

## Download and play

Open the [latest Windows release](https://github.com/VM934/NeuroSignal-Play/releases/latest). For **0.5.0-playtest.1**, download **NeuroSignal-SignalRecovery-Windows-20261104-180432.zip** under Assets, extract every file and double-click **Play NeuroSignal.cmd**. Choose **Deploy solo** to start. GitHub's automatic source archives are not the playable game.

Playing needs no editor, compiler, Epic account, GitHub login, AI model or subscription. The ZIP includes controls, runtime installers, learning sources and file hashes. Both launchers select **1080p, 100% 3D scale, FXAA, GI 1 and a 30 FPS cap**.

## Understand the mission

**Win:** clear three drone waves and check all three records. **Lose:** the archive reaches 0% or the whole squad goes down.

Follow **clear drones → central console → decide from evidence → read the result → everyone ready**. The HUD shows your NEXT action and records checked. Wrong answers give hints and retries without damage. Evidence has **no answer timer**; every connected player marks their own review ready.

WASD/mouse moves/looks; left/right mouse fires/aims; R reloads; E uses the console or revives nearby teammates. Shift sprints, Space jumps and C/Ctrl crouches; crouch while sprinting on the ground to slide. Esc opens the menu. Xbox-style mappings are documented in the ZIP.

Local firing sound/tracers are separate from server-confirmed **HIT** and **DRONE NEUTRALIZED** feedback. Dark label panels improve contrast; a tracer alone does not confirm damage.

## Learn through everyday questions

After solving a record, **Tab / controller View** opens larger field notes. **Left/Right / D-pad Left/Right** changes Science/Cybersecurity pages; **Enter / controller A** marks ready. Paging never advances the squad.

**Cybersecurity** discussions practice verifying unexpected college device-code requests, keeping AI-read documents from authorizing private-file uploads, and proving an assignment backup restores. Notes also cover app permissions, phishing-resistant authentication, supported software and known exploitation.

**Science** discussions examine an urgent clinic text, a sleep-app change after a supplement, and a memory advertisement. Labeled real-2026 cases distinguish [FDA device-security guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/cybersecurity-medical-devices-quality-management-system-considerations-and-content-premarket), [one participant's investigational speech BCI](https://www.nih.gov/news-events/nih-research-matters/brain-computer-device-helps-man-speak), and [Zanvastro's specific Alexander-disease approval](https://www.fda.gov/news-events/press-announcements/fda-approves-first-drug-treat-alexander-disease).

Sources/examples were checked **November 4, 2026**. NS-17 and mission data are fictional; no doses or treatment recommendations are supplied. Discussions are unscored and learning outcomes unvalidated. **LEARNING-GUIDE-2026.md** explains the evidence and sources.

## Play together or contribute

Everyone needs the **same complete release**. Choose **Host co-op**, have friends **Join a squadmate** using the host's reachable IPv4 address (normally port 7777), then deploy. `127.0.0.1` reaches only your own PC. Direct IP has no matchmaking, relay, automatic NAT traversal or host migration; separate-home internet play remains unverified.

Editable source, project goals and complete team bundles are in the private [team repository](https://github.com/VM934/NeuroSignal) and [team releases](https://github.com/VM934/NeuroSignal/releases). Accept the invitation, read the [friends' quick start](https://github.com/VM934/NeuroSignal/blob/main/Distribution/Collaboration/FRIENDS_QUICK_START.md), and work on a personal branch. C++ changes need Unreal Engine 5.8.3, Windows C++ tools, rebuilding and testing. Older releases remain available for rollback.

## Exact-build checks and limits

On the target laptop, six automated solo missions took **298.406 seconds**, including **65.401 seconds of aggregate combat** across **1,962 frames**: **30.000 FPS**, p95 **34.000 ms**, p99 **34.413 ms**, maximum **35.484 ms**, with none over 50 ms. Startup **3.439s**, shutdown **2.306s** and all declared combat/startup/shutdown goals passed, with normal exit 0. Review had **one of 6,099 frames over 50 ms**, maximum **105.263 ms**, cause unresolved. This was not globally hitch-free or a long thermal test. External power was reported; desktop apps/light document review continued without concurrent game/build/export/profiler/capture work.

The native passed **125 input checks, 14 evidence checks**, three-process loopback, and separate two-process loopback with **100 ms outgoing delay per endpoint** and verified settings readback. All exited normally. Actual extracted-ZIP solo routes produced **34 individually reviewed images** at 720p/1080p without blocking clipping/overlap. Extraction verified **56 payload files plus manifest**. See **FINAL-VERIFICATION.json** and the release checksum for exact identity and scope. Loopback does not establish real internet or multiplayer FPS.

Logs confirmed older-build rejection and its message, while a Windows permission prompt blocked interactive recovery verification; that check did not pass, and everyone must use **0.5.0-playtest.1**.

Prototype art remains; portal traversal, building systems and commercial-shooter parity are outside this playtest. Secondary labels, accessibility, real-controller comfort, fresh PCs and human enjoyment/learning need further checks. Showcase publication does not confirm competition eligibility.