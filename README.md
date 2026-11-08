# NeuroSignal: Signal Recovery

An original first-person game for **one to three Windows players**. Protect a fictional neuroscience research archive from drones, clear three waves, and decide what three records support.

## Download and play

1. Open the [latest Windows release](https://github.com/VM934/NeuroSignal-Play/releases/latest). Under Assets, download **NeuroSignal-SignalRecovery-Windows-20261108-042304.zip** for **0.9.0-playtest.1**.
2. Extract the entire ZIP, then double-click **Play NeuroSignal.cmd**.
3. Choose **Deploy solo**, or use **Host co-op** and **Join a squadmate**.

The ZIP includes controls, prerequisites, a source-linked learning guide, and file hashes. The launchers select **1080p, 100% 3D render scale, FXAA, GI quality 1, and a 30 FPS cap**. You can play without an editor, a compiler, or an account.

## Fight for the archive

- **Find another angle.** Approach either violet **Transfer Gate** standing, face it, and press **E / Y**. You cross to its partner with your heading preserved. A blocked exit keeps you in place. Try a gate while a drone is charging or take the marked north **LOW ROUTE** with a sprint-slide.
- **Read the threat.** When **ARCHIVE TARGETED** appears, use the direction cue and time bar to find the charging drone. Land two hits during one charge to interrupt it. When **DRONE LOCK** is on you, solid cover can block the shot.
- **Review the record.** Use the central console between waves. Set an app's permissions, examine a suspect brain recording, and compare a fictional compound with its matched carrier. Read the explanation and choose when you're ready. There is time to think between waves.

## Take the decisions into everyday life

After solving a record, press **Tab / View** to open Field Notes, select Science or Cybersecurity, and press **F / X** to try a Field Drill. You can retry after reading the explanation.

**Science** asks whether a signed record can be trusted after a sensor calibration failure, whether to drive after too little sleep and an energy drink, and what a bystander should do when someone wakes after naloxone in a suspected mixed-drug overdose. **Cybersecurity** practices responding after you approve a suspicious device code, handling an AI document that asks for a private-file upload, and testing that a backup restores without risking your current work. **LEARNING-GUIDE-2026.md** explains the science and links the source material and dated examples.

## Play with friends or edit the game

Everyone needs the **same complete 0.9.0-playtest.1 release**, network protocol **8**. One player hosts. Up to two friends join the host's reachable IPv4 address, normally on **UDP 7777**. The co-op tests use loopback on one laptop. Playing across separate home networks requires a route to the host.

The private team release pairs the same executable with the editable project. Sign in with an invited account, start a personal branch, and use Unreal Engine **5.8.3** and Windows C++ tools to build changes. [Team releases](https://github.com/VM934/NeuroSignal/releases) · [Friends' quick start](https://github.com/VM934/NeuroSignal/blob/main/Distribution/Collaboration/FRIENDS_QUICK_START.md)

## Exact-build verification

On the target ASUS laptop, **6** automated 1080p solo missions averaged **30.00 FPS** across **65.40 seconds** of sampled combat. The 99th-percentile combat frame took **33.79 ms**. The 720p and 1080p rendered checks reviewed **56** captures in total. The three-player and delayed two-player loopback runs checked host and remote gate traversal. The 0.8 build rejection check was headless.

**FINAL-VERIFICATION.json**, the checksum, and the gameplay screenshots are in the release assets. Player ZIP SHA-256 `214DBC4A37156F6AF9D989BD88BE4FD056C2E8E47528E17FC89ECB9B0CD4C97D`. Separate-computer networking, physical controller comfort, and learning outcomes remain to be tested with players.
