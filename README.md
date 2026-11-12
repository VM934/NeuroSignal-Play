# NeuroSignal: Breach Run

[**Play the competition game in your browser**](https://neurosignal-breach-run.vin-mami10.chatgpt.site/)

Create a room, share its six-letter code and play with up to five friends. Clear three waves and a boss, make six practical neuroscience and cybersecurity decisions, then extract together. The menu also offers all six lessons without combat. No game account or installation is required. Friends and Showcase reviewers use this same published browser version.

Invited collaborators can edit the browser source in [the private project](https://github.com/VM934/NeuroSignal/tree/main/Browser) or download its source ZIP from [Private Latest](https://github.com/VM934/NeuroSignal/releases/latest).

## Optional Windows first person playtest

The download below is the separate Signal Recovery Windows edition. The browser link above is the competition entry.

An original first-person cybersecurity and neuroscience game for one to three Windows players. Protect a fictional research archive through six encounters, recover a trustworthy reference record and decide what the evidence supports.

## Download and play

Download [NeuroSignal-SignalRecovery-Windows-0.9.4-playtest.1.zip](https://github.com/VM934/NeuroSignal-Play/releases/download/v0.9.4-playtest.1/NeuroSignal-SignalRecovery-Windows-0.9.4-playtest.1.zip) from the [0.9.4 Windows release](https://github.com/VM934/NeuroSignal-Play/releases/tag/v0.9.4-playtest.1), or check the [Latest Windows release](https://github.com/VM934/NeuroSignal-Play/releases/latest). Extract the entire ZIP and double-click **Play NeuroSignal.cmd**. Choose Deploy solo, Host co-op or Join a squadmate.

The package includes controls, runtime prerequisites, learning sources and file hashes. Playing requires no editor, compiler, AI model, subscription or GitHub account. The standard **Play NeuroSignal.cmd** selects 1280x720 output, 100% scene scale, FXAA, GI quality 1 and a 60 FPS cap; **Play NeuroSignal - 30 FPS.cmd** retains the same graphics with a 30 FPS cap.

## Fight, recover and investigate

Each operation pairs an eastern breach with a western counterattack. Sprint, slide through the north Low Route, use cover and take violet Transfer Gates between flanks. Reloading with rounds left takes 1.15 seconds, versus 1.65 seconds from empty. Two confirmed rifle hits during a surviving drone's charge interrupt its shot.

Version **0.9.4-playtest.1** adds a **100 ms jump buffer** for short taps and presses just before landing. Firing temporarily suppresses ordinary sprint while preserving held or toggled sprint intent; releasing fire resumes eligible sprint, and releasing sprint during fire cancels that resumption. A validated slide can continue while shooting. Crouching and standing blend the cosmetic camera height over **0.16 seconds**. Restrained weapon-only turn and strafe motion, grounded movement bob and timed reload dip and tilt use the existing rifle mesh. A filling reload meter shows the remaining seconds.

In the final encounter, inspect three caches. An intact untreated record lacks the required carrier. Another has matching carrier conditions but fails integrity. Recover the record that passes both checks, deliver the squad's read-only copy and defend 30 seconds of verification against two reinforcement batches. Clear the surviving drones before reviewing the compound comparison.

The three investigations ask what access an app needs, whether a faulty neural recording supports a mechanism claim and whether a matched-carrier comparison supports a drug claim. Wrong choices give feedback and retry. Everyone marks ready after reviewing the result.

## Make the lessons useful

After solving a record, press **F / controller X** or select **Try an Everyday Decision**. Field Notes open with **Tab / View**. Science and Cybersecurity drills practice decisions about sedating medicines, caffeine and fatigue, emergency help after naloxone, possible family voice-cloning scams, suspicious device-code approvals and testing a backup restore.

A correct Science answer now offers **Next: Cyber Decision** for the same record; a correct Cybersecurity answer offers **Return to Record Review**. Wrong answers offer **Retry This Decision**. Field Notes still let you choose either topic directly. Local progress records up to **six correct practice decisions** per mission, counting each once. Notes, menus and record changes preserve it; starting a new mission resets it. Practice is optional, and returning to review leaves each player's readiness unchanged. This counter records choices, not demonstrated learning or retention.

The required recovery task applies matched experimental conditions and recovered-record integrity. The compound, measurements and carrier amounts are fictional. **LEARNING-GUIDE-2026.md** explains the reasoning and links primary sources. [NIH/NCATS assay guidance](https://www.ncbi.nlm.nih.gov/sites/books/NBK92001/) · [NIST recovery guidance](https://www.nccoe.nist.gov/sites/default/files/legacy-files/di-nist-sp1800-11b-final.pdf)

## Play with friends and build on the project

Everyone needs **0.9.4-playtest.1**, network protocol **12**. One player hosts, and up to two friends join a reachable IPv4 address, normally on UDP 7777. Keep the complete extracted Windows folder together.

The private team bundle supplies the playable executable together with editable source, assets, build scripts and feedback forms. Invited collaborators can use Unreal Engine 5.8.3 and Windows C++ tools to make a personal branch and test changes. [Private editable project](https://github.com/VM934/NeuroSignal) · [Team release 0.9.4](https://github.com/VM934/NeuroSignal/releases/tag/v0.9.4-playtest.1) · [Friends' quick start](https://github.com/VM934/NeuroSignal/blob/main/Distribution/Collaboration/FRIENDS_QUICK_START.md)

## Verification for this release

The final native executable (`148FDAB05D22998AFA72BC7C3086B352E2C75E4CB452326C413F529B3057B02C`) passed a rendered solo mission and normal three-process loopback co-op from an extracted player package. The final independently extracted ZIP passed the standard 60 FPS rendered route with a normal exit and all 32 required captures; six selected images were visually inspected. A separate three-process native-package route passed with 100 ms packet lag, with the delay setting read back. All three peers completed the six encounters, three record reviews, reference recovery and six optional practice decisions. The version-mismatch test rejected protocol 11 and returned the protocol 12 client to solo standby with a normal exit; its graphical recovery was not verified.

On the target ASUS UX581GV (i9-9980HK, RTX 2060 6 GB, 32 GB RAM), three automated solo missions sampled **148.97 seconds and 8,938 combat/objective frames** at **59.998 FPS**. Frame times were **16.85 ms p95**, **17.10 ms p99** and **18.12 ms maximum**, with **zero frames over 50 ms**. Startup to the first test tick took **5.10 seconds**, and requested shutdown to process exit took **2.31 seconds**. Measurement validity, normal exit and all declared pacing/startup/shutdown goals passed.

These are automated ideal-aim routes on one laptop. Combat/objective timing aggregates normal encounters across three missions; it is not one continuous fight. The reports do not establish human comfort, difficulty, physical-controller operation, separate-PC/network connectivity, multiplayer frame pacing, long-term thermal stability or learning retention. Other Windows workload and power state were not independently controlled.

The [release verification report](https://github.com/VM934/NeuroSignal-Play/releases/download/v0.9.4-playtest.1/FINAL-VERIFICATION.json) identifies the tested executable and release checks. Use the release's adjacent checksum to verify the complete ZIP.

This is a development playtest with prototype art. Automated routes on one computer do not establish physical-controller comfort, separate-PC/network connectivity or learning retention; those need their own playtests. This download is the **Windows Unreal edition**. The **browser competition edition** has separate source and hosting.

Player ZIP size: **414,810,227 bytes**. SHA-256: **570991A713C3C8B30F58CACA95D8E0B08937AD9B09C8226DECAE730532EFEAA5**.
