# Verus Anticheat

Get it on our website: https://verus.ac

## Information about this Repository
This project was originally closed source and is now open source. Since we will not be able to commit as much as we used to, we have decided it would be best to open source Verus, allowing the community to help and build off Verus. There will be more documentation on how to develop and improved comments by the end of 2022.

Verus Development reserves all rights for any code residing in this repository. If you are to use any code in this repository, the code must be open sourced on GitHub or GitLab with credits
inside any class used. Otherwise, please message a Verus support member personally to get written consent for other uses.

For contributors to the Verus repository, you retain copyright to the changes you submit, and only the code you submit. Contributing does not grant you as a copyright holder any other parts of the project.
### Improvements
Since verus original owners abandoned this project, i used the verus custom src code to use and improve it(fixing some bypasses/vulnerabilities that have been around for years that the original developers didn't fix).

**Verus, at it's current stage, with the improvements :**
- Fixed the exploit related with BoatDisabler(which allowed to disable all checks) with InvalidSteer3B2 and InvalidSteer3B3
- All the checks / utilities of verus custom package and fully customizable(color, naming, plugin name, commands)
- Improved reach checks with the capabilitie to detect backtrack(you should enable moreTransactions and ignoreLag on the config file)
- Added some autoblock checks to only allow the vanilla sword block and not hit while blocking
- Added hitbox check HitBox6R with the verus custom utils(idk why verus never implement it having all the utils)
- The Fly4A3 is a bit configurable on the config file(you can customize if you want pullbacks and the max ground ticks)
- Improved the hoverAlert adding the check debug(before, this was only for verus devs)
- Added some KillAura heuristics checks and experimental KeepSprint check(Killaura6N2)
- Improved movement checks with Speed10X, Speed10G and Strafe402
- Fixed the SpeedF check , is SwordNoSlow(shitto check)
- If you want to use it, please use it with updated ncp to avoid any movement bypass
- To get the verus build md on dc -> jazened
