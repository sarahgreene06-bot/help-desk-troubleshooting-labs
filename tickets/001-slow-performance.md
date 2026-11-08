# Ticket 001: Slow Windows Performance

## Environment
- Lenovo laptop
- Windows 11
- 4 GB installed RAM

## Reported Issue
Slow performance during everyday use.

## Investigation
1. Opened Task Manager.
2. Sorted running processes by memory usage.
3. Checked Performance > Memory.
4. Observed approximately 3.5 GB in use and
   337 MB available during the investigation.
5. Identified running applications including
   ChatGPT, Discord, and Chrome.

## Action Taken
Closed ChatGPT, Discord, and Chrome.

## Results
| Resource | Before | After |
|---|---:|---:|
| Memory usage | 95% | 75% |
| CPU usage | 44% | 2% |
| Disk activity | 99% | 0% |

Readings are Task Manager snapshots taken at
different points during testing.

## Verification
Opened File Explorer and switched between folders.
Responsiveness improved.

## Assessment
High memory usage likely contributed to the slowdown.
After closing the applications, resource usage
decreased and responsiveness improved.

Because multiple applications were closed, the test
did not identify one application as the sole cause.

## Prevention
Close unused applications and check Task Manager
if slow performance returns.

## Status
Resolved for the tested session.

## Lesson Learned
An application can run in the background even when
its window is closed. Task Manager helps verify
which processes are still running.
