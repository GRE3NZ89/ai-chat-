# TTW Arcane Forge test handoff for GoBro

Cinder · 2026-11-17

## Live checks

- **Wealth Forge:** The operator confirmed the button worked. The full 0.6.1-dev log shows five consecutive +1,000 gold increments with immediate readback, for +5,000 total.
- **Vaultworks:** The same solo preview logged eight consecutive +1 backpack SDU upgrades, from 0 to 8. Gold and SDU persistence after reload remain open in the evidence reviewed for this handoff.
- **Loot Forge:** The original preview refused to spawn with an empty queue. The follow-up build in PR #47 claimed a queued item, spawned a weapon and added exactly one backpack entry. The PR reports that the weapon was present in the save and again after restarting and reloading. That test covers the weapon path. Pickup-type results and abnormal stats and sell-value behavior remain open. [Backpack delivery PR #47](https://github.com/GRE3NZ89/GFGbl4editor-site/pull/47), [TTW test record #19](https://github.com/GRE3NZ89/GFGbl4editor-site/issues/19).
- **Level boost:** The rc.3 log confirmed the target-40 helper raised both host and guest to level 40 in an earlier test. PR #45 separately documents guest boost and reload at level 10, refusal of below-level targets, and an rc.4 target selector fix still awaiting in-game verification in that PR. [HUD and guest boost PR #45](https://github.com/GRE3NZ89/GFGbl4editor-site/pull/45).

## Offline checks and next pass

The Arcane Forge preview passed 263 checks across SDK (224), Electron (22), API (10) and parser (7), plus the web and API builds. The browser Item Forge transform was checked separately. The live spawn result establishes game-side queue consumption and backpack delivery for that weapon. An Electron UI-to-game acceptance run remains unverified in the evidence reviewed here.

Start by confirming gold and backpack SDUs survive a save, full restart and reload. Then exercise the Electron Queue button all the way through one manual in-game spawn, record the result, and investigate the pickup path and anomalous item values. PR #56 reports 230 SDK tests for its separate dev/public packaging work and lists both packages as awaiting in-game testing. [Dev and public packages PR #56](https://github.com/GRE3NZ89/GFGbl4editor-site/pull/56).
