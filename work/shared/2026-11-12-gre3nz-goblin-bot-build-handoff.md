# GRE3NZ Goblin Bot build handoff

From GoBro / Scraps to Shadow Squad

- Verified the installed BL4 Steam build 26007962 with unrealsdk 3.2.0, pyunrealsdk 1.10.0, and embedded Python 3.14.6. The renamed Genie archive is a legacy reference. The independent preview excludes Discord.
- Independently reran Nash's pinned prototype on Python 3.13.15. All 90 tests and the simulated demo passed. Follow-up tests reproduced two gaps: an old listing could target a new visit after rejoin, and cached authority could allow a simulated removal after authority changed.
- The local patch binds listing entries to exact visits and refreshes authority before preparation and again before the adapter call. Three regression tests cover rejoin, authority loss, and failed authority reads. All 93 tests passed with the simulated adapter.
- Live read-only SDK checks saw three roster entries while hosting, one after both teammates left, and three as a guest. Controller authority was true while solo and hosting, false as guest. The viewport supplied the world. Network mode was unavailable.
- The new roster adapter passed ten simulated checks. Live checks saw one roster entry solo and three while hosting, with exactly one local match in both. The SDK reported zero client connections solo and one while hosting three players. Use the roster for player counts. The guest run of the new network-driver diagnostic is still unverified.
- Packaged the independent GRE3NZGoblinBot.sdkmod 0.1.0 preview with one read-only command, goblin_players. It shows roster count, local/remote labels, and authority without player names or IDs. ZIP integrity, import, single command registration, and healthy and partial roster behavior passed simulated checks.

## Next check

On Green's PC, put GRE3NZGoblinBot.sdkmod in BL4's sdk_mods folder, restart, enable GRE3NZ Goblin Bot, and run goblin_players once in a solo session. Expect one roster entry labeled local player and controller authority yes. The packaged mod has yet to be verified in-game. No live removal or delivery was attempted. Cinder's review and runtime capability report remain pending.

The preview archive, local patch, and diagnostic sources are in GoBro's workspace. The private team repo holds Nash's prototype, the adapter contract, and team review records.
