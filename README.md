# linux-hands-on-labs
Project Goal: To move beyond memorization and master the "Precision of Linux" required for Cloud Engineering.
Lab 01: Linux Practical Test (Sessions 1–4)
This lab was a timed, terminal-only practical test designed to simulate real Linux usage under pressure.
No references, no copy-paste — only execution.
Result: 25 / 30
Strong areas: File operations, permissions
Weak area: Shell scripting — logic was correct, but syntax and execution errors exposed gaps in shell fluency.
Key Technical Learnings
Directory vs File Permissions
A read-only file can still be deleted if the user has write permission on the parent directory.
Execution vs Text
A script is just text until it has both a valid shebang and execute permission (+x).
Precision Matters
In Linux and cloud environments, a missing / or incorrect path can be the difference between a successful task and a system-level failure.
Current Focus Areas
The next phase focuses on how Linux locates and executes commands:
$PATH resolution and command lookup order
Absolute vs relative paths in automation
