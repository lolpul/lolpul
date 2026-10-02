# Link the independent ArduPilot Lua examples

## Intent and changes

The UAV selected-work entry now links the reviewed public Lua examples and explains sensor-event handling, guarded state machines and virtual ownership. The text identifies independent demonstration code and host tests without implying employer source publication or flight validation.

## Verification and publication

The examples are published separately in `lolpul/ardupilot-lua-scripts`. Profile diff review checks the new text/link and all changed documentation before a normal main push. Remote profile README and head are checked after publishing; exact receipts belong to the handoff and technical memory. No unrelated profile entry or account setting is changed.

## Backup and rollback

Pre-change README, memory, local Git config and Obsidian note have timestamped copies and a manifest under ignored `.backups/`. Revert the focused link change with a normal commit if necessary; no force push. No source GitLab, website deployment, network configuration or physical action is included.
