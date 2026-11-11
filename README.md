# NeuroSignal: Signal Recovery

An original first-person cybersecurity and neuroscience game for one to three Windows players. Protect a fictional research archive through six encounters, recover a trustworthy reference record and decide what the evidence supports.

## Download and play

Open the [Latest Windows release](https://github.com/VM934/NeuroSignal-Play/releases/latest) and download **NeuroSignal-SignalRecovery-Windows-0.9.3-playtest.1.zip**. Extract the entire ZIP and double-click **Play NeuroSignal.cmd**. Choose Deploy solo, Host co-op or Join a squadmate.

The package includes controls, runtime prerequisites, learning sources and file hashes. Playing requires no editor, compiler, AI model, subscription or GitHub account. The launchers use **1280 by 720, full scene scale, FXAA and a 30 FPS cap**.

## Fight, recover and investigate

Each operation pairs an eastern breach with a western counterattack. Sprint, slide through the north Low Route, use cover and take violet Transfer Gates between flanks. Reloading with rounds left takes 1.15 seconds, versus 1.65 seconds from empty. Two confirmed rifle hits during a surviving drone's charge interrupt its shot.

In the final encounter, inspect three caches. An intact untreated record lacks the required carrier. Another has matching carrier conditions but fails integrity. Recover the record that passes both checks, deliver the squad's read-only copy and defend 30 seconds of verification against two reinforcement batches. Clear the surviving drones before reviewing the compound comparison.

The three investigations ask what access an app needs, whether a faulty neural recording supports a mechanism claim and whether a matched-carrier comparison supports a drug claim. Wrong choices give feedback and retry. Everyone marks ready after reviewing the result.

## Make the lessons useful

After solving a record, press **F / controller X** or select **Try an Everyday Decision**. Field Notes open with **Tab / View**. Science and Cybersecurity drills practice decisions about sedating medicines, caffeine and fatigue, emergency help after naloxone, possible family voice-cloning scams, suspicious device-code approvals and testing a backup restore.

The required recovery task applies matched experimental conditions and recovered-record integrity. The compound, measurements and carrier amounts are fictional. **LEARNING-GUIDE-2026.md** explains the reasoning and links primary sources. [NIH/NCATS assay guidance](https://www.ncbi.nlm.nih.gov/sites/books/NBK92001/) · [NIST recovery guidance](https://www.nccoe.nist.gov/sites/default/files/legacy-files/di-nist-sp1800-11b-final.pdf)

## Play with friends and build on the project

Everyone needs **0.9.3-playtest.1**, network protocol **11**. One player hosts, and up to two friends join a reachable IPv4 address, normally on UDP 7777. Co-op was tested with three processes on one laptop.

The private team bundle supplies the same playable executable together with editable source, assets, build scripts and feedback forms. Invited collaborators can use Unreal Engine 5.8.3 and Windows C++ tools to make a personal branch and test changes. [Team releases](https://github.com/VM934/NeuroSignal/releases/latest) · [Friends' quick start](https://github.com/VM934/NeuroSignal/blob/main/Distribution/Collaboration/FRIENDS_QUICK_START.md)

## Verification for this release

The executable passed a rendered solo mission, the independently extracted player ZIP's rendered mission and three-player loopback co-op. Each route completed all six encounters, all three investigations and the reference objective. The render routes provided 31 screenshots each.

On the target ASUS ZenBook, two automated solo missions averaged **30.00 FPS** over **101.03 seconds** of sampled combat and objective time. The 99th-percentile frame took **33.89 ms**, with zero sampled frames over 50 ms. The release includes **FINAL-VERIFICATION.json**, screenshots and the ZIP checksum.

This is a development playtest with prototype art. Separate-network play, physical-controller comfort and learning retention await human playtests. The browser competition game has its own source and hosting.

Player ZIP SHA-256 **A1690618877F8C78E91472829A30A11E0357C5EE1451760057BA5DE5A197434F**.
